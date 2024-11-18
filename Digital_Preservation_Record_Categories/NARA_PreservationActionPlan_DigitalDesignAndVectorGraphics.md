# Preservation Action Plan for Digital Design and Vector Graphics 
### National Archives and Records Administration (NARA)

Plan Date: 20240322
Template: 202105

#### Digital Design and Vector Graphics
Information that is accessed and updated through software (a designer and viewer) that enables users to design a product. The steps in the design process include creating, modifying, and representing the product in two and three dimensions. Many formats in this category are included under the “Computer Aided Design” category in the [NARA Transfer Guidance (Bulletin 2014-04)](https://www.archives.gov/records-mgmt/bulletins/2014/2014-04.html "NARA Transfer Guidance (Bulletin 2014-04)").


#### Significant Properties of Digital Design and Vector Graphics
As a general rule, appearance properties for this record type are layout, fonts, images, line work, resolution, color and scale. All files need to be internally referenced only.



#### Appearance
| Name  | Definition  | Function Description  |
| ------------ | ------------ | ------------ |
|Layout/Scale  | Ratio of the distance on a plan, elevation, or section to the corresponding distance on the surface the plan represents.  |   |
| Size  | Pixel dimensions  |   |
| Geometry  | Includes angular unit, dimensions, array, and axis tripod (XYZ coordinates used to visualize).  | Required to create plans and visualizations based on the underlying data.  |
| Text  | Font; Orientation: text direction (left to right, angled, vertical, etc.); Color  | These properties may be significant if the text displayed, such as plan legends or display headings, bears meaning through its formatting. The text itself is always significant, but the formatting may also be significant when it is evidence of how the maps were used or displayed by the creator.   |
| Color  | Hue; Saturation; Brightness (Light Source and Light Intensity for shadowing/shading); Contrast | Even if exact colors cannot be made persistent, distinctions between colors may be significant to understand the attributes and overlays displayed as a result of a user query. All of these properties are ways of measuring and making distinctions between colors. The International Color Consortium specifications and Microsoft Windows Image Color Management profiles define standard methods of generating and interpreting numeric values that describe color to ensure color consistency across platforms and devices.  |


#### Structure
| Name  | Definition  | Function Description  |
| ------------ | ------------ | ------------ |
| CAD Structure  | **HEADER** section – General information about the drawing. Each parameter has a variable name and an associated value. <br><br>**CLASSES** section – Holds the information for application-defined classes whose instances appear in the BLOCKS, ENTITIES, and OBJECTS sections of the database. Generally does not provide sufficient information to allow interoperability with other programs. <br><br>**TABLES** section – This section contains definitions of named items.|Manner in which elements are organized, interrelated, and displayed. *Note: not applicable to the whole Digital Design and Vector Graphics category.* |



#### Behavior
| Name  | Definition  | Function Description  |
| ------------ | ------------ | ------------ |
| Manipulation Functionality  | The ability to examine relationships within a table or between tables.   | Once there is a defined schematic, the ability to manipulate exists.   |
|Display Graph or Plot  | Features on one data layer are overlaid onto those of other data layers in order to show areas that have a certain combination of attributes: Single map; Multiple overlays; 3-dimensional display.  | The ability to graph and plot data is significant to the meaning of Digital Design and Vector Graphic records. If there is no value to the display, or no ability to plot, then the records could be handled much like databases.  |
| Display Report  |Report(s) from data tables.   |   |
|Manipulation Functionality   |Includes but not limited to: Draw; Zoom; 	Animate (continuous and/or step-by-step progression); Contour; Pan; and Enhance (smooth, simplify, merge, dissolve, rotate, invert). |Depending on the software toolkit and data elements available to the user, a host of behaviors are possible that may be significant to the meaning or value of the records. Much of the functionality concerns manipulation of the display, whether it be a plotted map or reported data from a query. The data elements that allow this functionality are a function of the data type and transfer format. If the value of the records lies in how the creator manipulated the plan attributes and the utilities they used to do so, these behaviors will have to be identified and articulated at appraisal or transfer.  |



#### Context
| Name  | Definition  | Function Description  |
| ------------ | ------------ | ------------ |
|Series  |A group of related records that are normally used and filed as a unit because they relate to a similar activity/function. The relationship between records and the series of which they are a part must be preserved. |   |
|Descriptive Metadata |May include but is not limited to: Caption; Subject; Date; Event; Creator; and Transaction. |Information contained within the record that refers to the intellectual content of material and aids discovery of such materials. Assumes that all descriptive metadata for a database is contained within the structure and content of the database itself. |


#### Current NARA Transfer Guidance for Computer Aided Design
[Bulletin 2014-04](https://www.archives.gov/records-mgmt/bulletins/2014/2014-04.html "Bulletin 2014-04")

- Preferred:
   - Extensible 3D (X3D)
   - Standard for the Exchange of Product Model Data (STEP) 
   - ASTM E57 3D file format (E57) (Version 1.0)
   - OpenDocument Graphics Format (ODG)

- Acceptable: 
   - Portable Document Format/Engineering (PDF/E)
   - Universal 3D (U3D)
   - Product Representation Compact (PRC)




#### Current NARA Format(s) for Public Access and Reference for Digital Design and Vector Graphics

Formats for Public Access are those made available online through the National Archives Catalog. Formats for Reference are defined as those made available to researchers upon direct requests for digital copies.

Formats Available for Public Access: PDF

Format(s) Available for Reference: When available, records may be delivered to researchers in the formats in which they are preserved.


