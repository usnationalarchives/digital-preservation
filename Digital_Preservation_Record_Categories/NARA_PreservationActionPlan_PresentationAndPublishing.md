# Preservation Action Plan for Presentation and Publishing
### National Archives and Records Administration (NARA)

Plan Date: 20231205
Template: 20210525

#### Presentation and Publishing
Presentation and publishing formats include a variety of files related to desktop publishing software used to create graphically rich documents, slide shows, magazines, books, brochures, newspapers and other more sophisticated texts. Besides formats associated with presentation and publishing files themselves, this category includes file formats associated with rendering files, such as printer control language and page description language files. 



#### Significant Properties of Presentation and Publishing
The variety of agency usage and types of presentation and publishing formats limit NARA’s ability to fully define consistent properties, especially structure. Built-in tools such as macros, reports, or externally linked files are related to other record categories which have their own significant properties.  

Some appearance properties are discussed in the Structure Properties section, since the appearance of a publication or presentation can be partially based on technical structure that allows the record to be manipulated and displayed in a different manner. If the appearance is fixed, as for official publication, then the dimensions must be maintained. If the appearance is determined by user preference or is otherwise mutable, then the dimensions may not be as significant.

Questions which must be considered:
- Would a change in the record's appearance alter its meaning?
- Does changing the record's appearance diminish its value?  For example, if the records have been appraised as permanent for their informational value, and not evidential, then appearance properties may not need to be preserved.
- Would a change in the record's technical structure alter its appearance?
- Would a change in the record's technical structure affect its possible behaviors?
- Would a change in how people interact with the information affect its value?



#### Appearance
| Name  | Definition  | Function Description  |
| ------------ | ------------ | ------------ |
|Language |A language identifier specifying the natural language(s) used in the document. | |
|Fonts |A list of fonts used in the document, and an indication of whether or not a font is embedded in a document. <br><br> <ul><li>Typeface (Arial, Times New Roman, etc.)<li>Size (10 pt, 18 pt, etc.)<li>Pitch<li>Spacing<li>Emphasis (bold, italic, strikethrough, underline, etc.)|Stores the names of all fonts (embedded and non-embedded) used in a document to assist in rendering the content and identifying the documents with potential long-term preservation risks. There will always be a font in order to have text, however, there are other variables that determine whether a distinct font is a core property. For example, where appearance is fixed, such as in a publication, then font is core. |
|Size |Document “page” size(s), e.g., Letter, Legal, A4. | Physical or virtual dimensions. These properties are conditional. If the appearance is important, such as a publication, then this must be maintained. However, if only the content (“words absent their formatting”) of the document is important, such as meeting minutes, then these dimensional properties are not core.|
|Layout Orientation |Orientation of the “pages,” e.g., portrait versus landscape. |Needed for understanding content and context of record. |
|Text Orientation |Orientation of the text, e.g., horizontal, vertical, custom axes. |Needed for understanding content and context of record. |
|Color |Identification of the use of color in text and layout elements, e.g. borders, boxes.<br><br><ul><li>Hue: color family or name <li>Saturation: purity or sharpness<li>Brightness: shade or tint<li>Contrast: range of optical density or tone | Color is essential if it bears meaning and/or value, or if the appearance is fixed.|
|Pagination or Slide Order |Pagination and content sequence in the document. | If present, then needed for contextual understanding of the record.|
|Forms |Form elements embedded in the document. | |
|Annotations |Annotations included in the document. | |
|Tables |Includes content structured in a table feature, such as a dynamically generated table of contents. |A table is an arrangement of data in rows and columns, or possibly in a more complex structure.  |
|Graphics |Images embedded in the document, or graphics created using a word processing graphics feature. |Used to point readers and viewers to particular information. They are also used to supplement text in an effort to aid readers in their understanding of a particular concept or make the concept more clear or interesting. |
|Audio and Video |Audio or video files embedded in the document. |Audio and video files may be included in the document or package, or referenced to as external resources.  |
|Outline |Includes content in an outline structure. |An outline, also called a hierarchical outline, is a list arranged to show hierarchical relationships and is a type of tree structure. An outline is used to present the main points or topics of a given subject. Each item in an outline may be divided into additional sub-items. |
|Transparency |The use of transparency features for graphics or text in the document. | |
|Layers |The presence of layered graphic elements in the document.  | |


#### Structure
| Name  | Definition  | Function Description  |
| ------------ | ------------ | ------------ |
|Schema |Many presentation and publishing file formats are generated using multiple components that are specified via a set of structured data relationships, which may include:<br><br> <ul><li>Lists<li>Arrays<li>Models<li>Trees<li>Tables<li>Linkage: connection between or within records.  If connections exist, then they are core. <li>Template. Although there is a generally agreed upon composition that exists for written textual records (business and government standards) such as with a letter, the placement of addresses, date, salutation, signature, content, enclosure, carbon copies, if there is the existence of a template needed to generate a textual record, then the template is core. | |
|Character Encoding |Encoding schema, e.g., US-ASCII, EBCDIC, UTF-8.  |Required for the proper parsing and rendering of the record content. |
|Slide Notes |Slide annotation, generally included for the presenter. |If the notes contain information not otherwise contained in the slides, they may be important to retain. |
|Word Count |Total number of words in the document. |Valuable for evaluating the completeness of the content after transformations, but can be highly variable between tools. |
|Character Count |Total number of characters in the document. |Valuable for evaluating the completeness of the content after transformations, but can be highly variable between tools. |
|Line Count |Total number of lines in the document. |Valuable for evaluating the completeness of the content after transformations, but can be highly variable between tools. |
|Paragraph Count |Total number of paragraphs in the document. |Valuable for evaluating the completeness of the content after transformations, but can be highly variable between tools. |
| Table Count|Total number of tables in the document. |Valuable for evaluating the completeness of the content after transformations, but can be highly variable between tools. |
|Graphics Count |Total number of graphics in the document. |Valuable for evaluating the completeness of the content after transformations, but can be highly variable between tools. |


#### Behavior
| Name  | Definition  | Function Description  |
| ------------ | ------------ | ------------ |
|Macros and Linkages | |Significant properties are currently dependent on the export format. |
|Animations and Transitions |The use of effects to animate objects or transition between slides.  |Likely not important to retain, but the content of the record should be evaluated to ensure that it is complete and legible without animations and transitions.  |


#### Context
| Name  | Definition  | Function Description  |
| ------------ | ------------ | ------------ |
|Series |Identification of the document’s inclusion in a series, and enumeration if present. | |
|Descriptive Metadata |Descriptive metadata embedded in the record file header. |Information contained within the record (intrinsic) that refers to the intellectual content of material and aids discovery of such materials, for example, Caption/Subject/Date/Event/ Transaction can all add value to the record.  |


#### Current NARA Transfer Guidance for Presentation and Publishing
[Bulletin 2014-04](https://www.archives.gov/records-mgmt/bulletins/2014/2014-04.html "Bulletin 2014-04")

- Preferred:
 - OpenDocument Presentation Format (ODP)
 - Portable Document Format/Archival (PDF/A-1)

- Acceptable: 
 - Microsoft Powerpoint 1997-2007 Binary Format (PPT)
 - Microsoft Powerpoint Open XML Format (PPTX)
 - PDF/A-2


#### Current NARA Format(s) for Public Access and Reference for Presentation and Publishing

Formats for Public Access are those made available online through the National Archives Catalog. Formats for Reference are defined as those made available to researchers upon direct requests for digital copies.

Formats Available for Public Access: PDF, TIFF, JP2, PPTX, ODP 

Format(s) Available for Reference: When available, records may be delivered to researchers in the formats in which they are preserved.



