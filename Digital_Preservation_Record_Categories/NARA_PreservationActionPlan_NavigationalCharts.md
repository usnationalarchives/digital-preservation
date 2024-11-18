# Preservation Action Plan for Navigational Charts
### National Archives and Records Administration (NARA)

Plan Date: 20240322
Template: 202105

#### Navigational Charts
Navigational charts support marine navigation and may be used by commercial vessels, recreational boaters, equipment manufacturers, and more. Charts are issued by an individual country’s government hydrographic offices or other institutions, and comply with specifications developed by the International Hydrographic Organization (IHO). Due to the requirements necessary to comply with these specifications and maintain significant properties, records will likely be preserved in the format in which they are transferred.

The international specifications for the formats are available at:

- IHO Special Publication S-61 (Raster): https://iho.int/uploads/user/pubs/standards/s-61/S61E.pdf
- IHO Special Publication S-57 (Electronic/Vector): (https://iho.int/uploads/user/pubs/standards/s-57/31Main.pdf
 - Several component documents and appendices for IHO S-57 are available at: https://iho.int/en/standards-and-specifications 

Additional recommendations that accompany the specifications for portrayal:
- IHO Publication S-52: https://iho.int/uploads/user/pubs/standards/s-52/S-52%20Edition%206.1.1%20-%20June%202015.pdf 
 - Several component documents and appendices for IHO S-52 are available at: https://iho.int/en/s-52-portrayal-bulletins 


#### Significant Properties of Navigational Charts
Navigational charts integrate spatial data with descriptive properties to model real world entities. The significant properties for raster and electronic (vector) navigational charts are described separately in this plan.

Raster navigational charts (RNC) are digital facsimiles of paper nautical charts, presented as image files with accompanying metadata. Information is stored as raster data of color pixels. Appearance properties and georeferencing metadata in Behavior and Context properties are generally the most important to preserve for RNCs.

The electronic navigational charts (ENC) standard supports the exchange of digital hydrographic data to be displayed in an Electronic Chart Display and Information System (ECDIS). Information is stored as vector data (pairs of coordinates) that may be rendered in real-time. Structure properties and georeferencing metadata in Behavior and Context properties are generally the most important to preserve for ENCs.


#### Appearance: Raster Navigational Charts
| Name  | Definition  | Function Description  |
| ------------ | ------------ | ------------ |
| Scale  | The scale at which the chart is displayed should be included in the metadata. | |
|Resolution |Pixels-per-inch |The resolution of the digital image and any compression applied to the image file must clearly display all information that was contained on the paper chart. |
|Features |Represented by symbols |Symbology for RNCs may vary based on the producing country. All features are displayed at all times. |
|Orientation|Indicates orientation of North | |
|Color |Contrast; Color Palette|The chart should have the maximum contrast of displayed information. The color palette for daytime viewing should be the same as the paper version; these colors may vary based on the producing country. Nighttime and dusk palettes should follow those specified in IHO Special Publication S-52, Appendix 2.|



#### Behavior: Raster Navigational Charts
| Name  | Definition  | Function Description  |
| ------------ | ------------ | ------------ |
| Georeferences | Each pixel georeferences a particular latitude and longitude. |Ability to determine the correct geographic coordinates of an individual pixel when the image file is used together with the metadata. |
|Updates |A published change to an RNC is issued as a Notice to Mariners (NtM). The Notices are produced by or distributed under the authority of a government authorized hydrographic office. Version history is included in the metadata. | |

#### Context: Raster Navigational Charts
| Name  | Definition  | Function Description  |
| ------------ | ------------ | ------------ |
| Metadata  | RNCs contain metadata such as update history, identifiers, scale, depth, and height.  |Specified in IHO Special Publication S-61, Section 3.4.   |

#### Structure: Raster Navigational Charts
| Name  | Definition  | Function Description  |
| ------------ | ------------ | ------------ |
|Relationships |Multi-part charts are related to one another through metadata. | As specified in IHO Special Publication S-61, Section 3, arrangement of the image data and metadata into one or more files should be determined by the national hydrographic office originating the RNC.|

#### Appearance: Electronic Navigational Charts
| Name  | Definition  | Function Description  |
| ------------ | ------------ | ------------ |
| Presentation|Must contain the structural data information to support presentation and rendering in an external tool.|Presentation is independent of storage as per the specification. Must be capable of being rendered in an ECDIS system; rendering in a non-ECDIS system may alter the meaning or lose data. See IHO Special Publication S-57, Part 2, Section 3. |
|Scale | Scale at which the chart is displayed. Information about the scale, coordinate system, units of height and depth measurement, should be included in the metadata. | The Data Set Geographic Reference is used to exchange details about the coordinate system. See Metadata properties.|
|Features |Represented by symbols |ECDIS navigational systems use internationally standardized symbology. Non-ECDIS systems may use other symbology. |
|Color |Contrast; Color Palette |Colors for ENCs are consistent internationally. |

#### Behavior: Electronic Navigational Charts
| Name  | Definition  | Function Description  |
| ------------ | ------------ | ------------ |
|Query |Through user interaction to scale the chart and/or select specific features, the display of features can be turned on or off. | |
| Encoding| Encoding of character sets drives the interpretation necessary for rendering the ENC. The ENC must include the exchange set requirements; there are both ASCII and binary implementations. There are 3 levels of encoding.| Specified in IHO Special Publication S-57, Part 3, Section 2.|
| Georeferences|Pairs of latitude and longitude coordinates define the position and shapes of specific points, lines, and features. | |
|Updates |The data structure allows for updates to previously exchanged data without reissuing a complete new data set. Version history is included in the metadata. |Specified in IHO Special Publication S-57, Part 3, Section 8. |

#### Context: Electronic Navigational Charts
| Name  | Definition  | Function Description  |
| ------------ | ------------ | ------------ |
|Metadata |Metadata can be encoded at 3 different levels. ENCs contain metadata such as update history, identifiers, and coordinate system information. ENCs must contain a data set general information record, data set geographic reference record, data set history record, data set accuracy record, and catalog dictionary record. |Specified in IHO Special Publication S-57, Part 3, Section 3. |

#### Structure: Electronic Navigational Charts
| Name  | Definition  | Function Description  |
| ------------ | ------------ | ------------ |
|Spatial object |Object which contains locational information about real world entities. There are 3 types of spatial objects: vector, raster, and matrix. Each spatial object must be referenced by a feature object. Spatial objects are implemented as spatial records. |Specified in IHO Special Publication S-57, Part 2, Section 2. |
|Spatial object/Vector |Vector objects can have zero, one, or two dimensions. Vector objects are implemented as vector records. |Specified in IHO Special Publication S-57, Part 2, Section 2. |
|Spatial record |Encoding of a spatial object in the data structure. Spatial records contain locational data. | Specified in IHO Special Publication S-57, Part 3, Section 5. Raster and matrix record coding conventions are not currently defined.|
|Spatial record/Vector |Vector records contain coordinate geometry information related to the feature records, such as topology. Vector record types are: node, edge, and face. |Specified in IHO Special Publication S-57, Part 3, Section 5. |
|Feature object |Object which contains non-locational information about real world entities. The IHO Object Catalog identifies 4 categories of feature object classes: meta, cartographic, geo, and collection. Feature objects can exist without referencing spatial objects. Feature objects are implemented as feature records. |Specified in IHO Special Publication S-57, Part 3, Section 4. The IHO Object Catalogue, Appendix A, defines allowed attributes for object classes. |
|Feature record |Encoding of a feature object in the data structure. Feature records contain non-locational real-world data. | Specified in IHO Special Publication S-57, Part 3, Section 4.|
|Relationships |Relationships between records can be encoded in 3 ways: catalogue cross reference record, collection feature record, or by defining a master feature record. Relationships are implemented as pointers in the data structure. | Specified in IHO Special Publication S-57, Part 3, Section 6.|
|Structure implementation|Comprised of feature and spatial properties to constitute the object. |Specified in IHO Special Publication S-57, Part 3, Section 7. Includes requirements for implementing as ISO/IEC 8211 data records.|

#### Current NARA Transfer Guidance for Navigational Charts
[Bulletin 2014-04](https://www.archives.gov/records-mgmt/bulletins/2014/2014-04.html "Bulletin 2014-04")

- Preferred:
  - Electronic Navigational Chart (S/57)
  - Raster Navigational Chart (BSB)

- Acceptable: 
  - None specified


#### Current NARA Format(s) for Public Access and Reference for Navigational Charts

Formats for Public Access are those made available online through the National Archives Catalog. Formats for Reference are defined as those made available to researchers upon direct requests for digital copies.

Formats Available for Public Access: Content created or delivered for public access in the Catalog is delivered primarily in the following file formats: PDF (Textual and Image), JPEG (Textual and Image), MP3 (Audio), and MP4 (Audio/Video) and ASCII (Datasets). Other file formats may be present depending on when they were added to the Catalog.

Format(s) Available for Reference: When available, records may be delivered to researchers in the formats in which they are preserved.


