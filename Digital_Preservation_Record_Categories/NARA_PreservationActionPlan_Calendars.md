# Preservation Action Plan for Structured Data/Calendars
### National Archives and Records Administration (NARA)

Plan Date: 202503

Template: 202105

#### Structured Data/Calendars
A calendar contains structured information necessary to capture and exchange information normally stored within a calendaring, scheduling, or to-do list application, whether a Personal Information Manager (PIM) or a Group Scheduling product. Calendars support operations such as requesting, replying to, modifying, and canceling meetings or appointments, to-dos or tasks, reminders and journal entries, and potentially support other calendaring and scheduling operations such as requesting for and replying with free/busy time data. Calendar objects are extensions of the text/directory MIME type.

#### Significant Properties of Structured Data/Calendars
Structure is generally the most important property to preserve in calendars. 

#### Appearance
| Name  | Definition  | Function Description  |
| ------------ | ------------ | ------------ |
| Character Encoding  | The default encoding for calendar entries in current implementations is UTF-8.  |The sequence of characters (letters, numbers, punctuation, and certain symbols) or coding that translate human readable or natural language characters to a specialized format for efficient transmission or storage.  
Character encoding needs to be identified in order to open in a compatible format or to transform to another format, such as ASCII.|
|Text Properties  | Properties such as font, text size, or color.   |  These have never been considered primary properties in the past. If at some point in time they are important to understanding the record, then they should be reconsidered as significant for calendars. |
#### Structure
| Name  | Definition  | Function Description  |
| ------------ | ------------ | ------------ |
| Entry Property  | Properties of the calendar or to-do entry, e.g., ID, Event, Summary, Date, Duration, Period of Time, Location, RSVP Expectation, Recurrence, Alarm Trigger Relationship, Free/Busy Time, Sent By, Language, Time Zone Identifier, etc.  | Individual calendar or to-do entry properties.  |
| User Property  | Properties which define users, user roles, and relationships between a calendar entry or to-do entry and users, including ID, Common Name, Calendar User Type, Calendar User Address, Delegator, Delagatee, Group Membership, Directory Entry Reference, etc.  | Descriptions of the calendar user and relationships between entries or to-do items and other users.  |
| Action Property  | Properties which define associated actions, including Needs Action, Participation Status, Participation Role, etc.  | Actions associated with entries or to-do items, such as task delegation, participation/RSVP status, or completion status.  |
| Property Parameters  | A property can have attributes with which it is associated. These "property parameters" contain meta-information about the property or the property value. Property parameters are provided to specify such information as the location of an alternate text representation for a property value, the language of a text property value, the value type of the property value, and other attributes.  |   |
| Technical Metadata  | Metadata describing the markup specification, software, software version, etc. This is generally declared at the beginning of the file and embedded in the file header.  | Supports the ability to potentially recreate interactions with the calendar entries. |
| Attachments  |Binary content associated with a calendar entry.    |  Binary content that is referenced using a URI, or in applications which support or require that a calendar object be expressed as a single entity, inline binary content which is encoded into text using the "BASE64" encoding method. |

#### Behavior
| Name  | Definition  | Function Description  |
| ------------ | ------------ | ------------ |
|  See Structure Properties | The properties set for a calendar entry or to-do item can include triggers for behavior in the calendar system, such as marking time as free or busy, sending event alarms/reminders to users, etc.   | The encoding of the behaviors is system-neutral, while implementation of the behaviors are specific to the system.  |

#### Context
| Name  | Definition  | Function Description  |
| ------------ | ------------ | ------------ |
| Relationship Parameter  | A parameter that specified a reference to another related calendar.  |   |
| URI  |  A pointer to external content which is linked from a calendar entry or to-do item. |   |

#### Current NARA Transfer Guidance for Structured Data/Calendars
[Bulletin 2014-04](https://www.archives.gov/records-mgmt/bulletins/2014/2014-04.html "Bulletin 2014-04")

- Preferred:
 - iCalendar / iCal (ICS)

- Acceptable: 
 - None specified 


#### Current NARA Format(s) for Public Access and Reference for Calendars
Formats for Public Access are those made available online through the National Archives Catalog. Formats for Reference are defined as those made available to researchers upon direct requests for digital copies.

Formats Available for Public Access: Content created or delivered for public access in the Catalog is delivered primarily in the following file formats: PDF (Textual and Image), JPEG (Textual and Image), MP3 (Audio), and MP4 (Audio/Video) and ASCII (Datasets). Other file formats may be present depending on when they were added to the Catalog. 

Format(s) Available for Reference: When available, records may be delivered to researchers in the formats in which they are preserved.

#### Comments and Notes
In general, NARA accessions calendar and scheduling records in formats defined in 36 CFR 1235 and NARA Bulletin 2014-04. NARA appraises the contents of calendar and scheduling files, and not the functionality.


