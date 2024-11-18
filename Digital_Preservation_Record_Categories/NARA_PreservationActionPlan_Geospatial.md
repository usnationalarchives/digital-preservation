# Preservation Action Plan for Geospatial
### National Archives and Records Administration (NARA)

Plan Date: 20240322
Template: 202105

#### Geospatial
A geographic information system (GIS) is a system for creating, storing, analyzing, and managing spatial data and associated attributes. In the strictest sense, it is a computer system capable of integrating, storing, editing, analyzing, sharing, and displaying geographically-referenced information. In a more generic sense, GIS is a tool that allows users to create interactive queries (user created searches), analyze the spatial information, and edit data.


#### Significant Properties of Geospatial
GIS map overlays integrate spatial data with attribute data about map features. The overlays combine information from one map layer with another map layer to derive or infer an attribute for one of the layers. All layers must match up correctly to be able to draw them on top of each other or combine them to see relationships. For layers to match up, they must be in the same map projection and coordinate system, which allows one to specify a unique and definite position for every location on a map. Some appearance properties are covered in the Behavior Properties section, since a GIS’s value is often in the many ways data can be manipulated and displayed. 

Appearance/Layout properties are essential to preserve the accuracy and meaning of GIS map layers. The geographic information in a GIS digital map provides the position and shape of each feature. The information describes how the map is to be displayed or plotted. Common display information includes feature colors, line widths, and line types.


#### Appearance
| Name  | Definition  | Function Description  |
| ------------ | ------------ | ------------ |
| Layout/Scale  | Ratio of the distance on a map to the corresponding distance on the surface the map represents. | |
|Layout/Orientation |Absolute geographic coordinate position: specified using a universal coordinate system such as latitude/longitude or Universal Transverse Mercator coordinates; Relative coordinate position: specified using the location of other variables or phenomena. ||
|Layout/Projection |Translates the locations on the globe onto the flat surface of a map. | |
|Text|Font; Orientation: text direction (left to right, angled, vertical, etc.); Color |These properties may be significant if the text displayed in GIS records, such as map legends or display headings, bears meaning through its formatting. The text itself is always essential, but the formatting may also be essential when it is evidence of how the maps were used or displayed by the creator.  |
|Color |Hue; Saturation; Brightness (Light Source and Light Intensity for shadowing/shading); Contrast|Even if exact colors cannot be made persistent, distinctions between colors may be essential to understand the attributes and overlays displayed as a result of a user query. All of these properties are ways of measuring and making distinctions between colors. The International Color Consortium specifications and Microsoft Windows Image Color Management profiles define standard methods of generating and interpreting numeric values that describe color to ensure color consistency across platforms and devices. |



#### Structure
| Name  | Definition  | Function Description  |
| ------------ | ------------ | ------------ |
| Layout/Linkage(s) | Links to related geographic, attribute, and display data (internal or external to the record). | |



#### Behavior
| Name  | Definition  | Function Description  |
| ------------ | ------------ | ------------ |
| Query | Queries may be graphics-driven, spatial-based (point and query) searches for objects that retrieve the associated attribute data.  They may also be data-driven, using data values to display the matching spatial features or the use of attribute values to determine the shading pattern of the relevant spatial elements. | |
|Display Graph or Plot |Features on one data layer are overlaid onto those of other data layers in order to show areas that have a certain combination of attributes: Single map; Multiple overlays; 3-dimensional display. |The ability to graph and plot data is essential to the meaning of GIS map records. If there is no value to the map display, or no ability to plot, then the records could be handled much like databases. |
|Display Report |Report(s) from data tables. | |
|Manipulation Functionality| Includes but not limited to: Draw; Zoom; 	Animate (continuous and/or step-by-step progression); Contour; Pan; 	Enhance (smooth, simplify, merge, dissolve, rotate, invert).|Depending on the software toolkit and data elements available to the user, a host of behaviors are possible that may be essential to the meaning or value of the records. Much GIS functionality concerns manipulation of the display, whether it be a plotted map or reported data from a query. The data elements that allow this functionality are a function of the data type and transfer format. If the records’ value lies in how the creator manipulated the map attributes and the utilities they used to do so, these behaviors will have to be identified and articulated at appraisal or transfer. |


#### Context
| Name  | Definition  | Function Description  |
| ------------ | ------------ | ------------ |
| Descriptive Metadata |Geospatial records could contain, or link to, metadata that describe any attribute that can be displayed on a map, such as the Federal Geographic Data Committee’s Content Standard for Digital Geospatial Metadata. The records may also be described by more specialized metadata profiles, such as the Metadata Standard for Shoreline Data. | All of the descriptive metadata employed by the record creator are presumed essential to the value of GIS records, because they are what make the records unique and meaningful.|


#### Current NARA Transfer Guidance for Email
[Bulletin 2014-04](https://www.archives.gov/records-mgmt/bulletins/2014/2014-04.html "Bulletin 2014-04")

- Preferred:
  - Geospatial Tagged Image File Format
  - Geographic Markup Language
  - Topologically Integrated Geographic Encoding and Referencing Files
  - Keyhole Markup Language
  - Geopackage Encoding Standard

- Acceptable: 
  - Vector Product Format
  - ESRI ARC/INFO Interchange File Format
  - TerraGo Geospatial PDF
  - ESRI Shapefile (Compound)
 
- Acceptable for Imminent Transfer:
  - Spatial Data Transfer Standard (SDTS)

#### Current NARA Format(s) for Public Access and Reference for Geospatial

Formats for Public Access are those made available online through the National Archives Catalog. Formats for Reference are defined as those made available to researchers upon direct requests for digital copies.

Formats Available for Public Access: Shapefile, PDF

Format(s) Available for Reference: When available, records may be delivered to researchers in the formats in which they are preserved.
