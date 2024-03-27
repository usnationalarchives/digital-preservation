# U.S. National Archives and Records Administration Digital Preservation Framework
The National Archives and Records Administration Digital Preservation Framework consists of a Risk and Prioritization Matrix and File Format Preservation Action Plans.

## Background
The National Archives 2022–2026 Strategic Plan embraces the primacy of electronic records. Our vision is to ensure cutting-edge access to extraordinary volumes of government informa­tion and unprecedented engagement to bring greater meaning to the American experience. To do so, NARA must collaborate with other Federal agencies, the private sector, and the public to ensure records and archives thrive in a digital world.

Digital preservation is critical to this work. It becomes even more important because of the direction [(M-23-07, Update to Transition to Electronic Records)](https://www.whitehouse.gov/wp-content/uploads/2022/12/M_23_07-M-Memo-Electronic-Records_final.pdf) to Federal agencies to transition business processes and recordkeeping to a fully electronic environment and to end the National Archives’ acceptance of paper records by June 30, 2024.

Our digital preservation subject matter experts, led by Director of Digital Preservation Leslie Johnston, have been hard at work to prepare the National Archives for this change. They have formalized a set of documents that describe how we identify risks to digital files and prioritize them for action, and created specific plans for the preservation of these many file formats.

NARA holds several billion files representing more than 700 file format versions. These files can be categorized into 16 general categories of electronic records. The vast majority of files are email messages, followed by JPEG and TIFF still images and plain ASCII text.

## The NARA Risk and Prioritization Matrix
NARA uses the [Risk and Prioritization Matrix](https://github.com/usnationalarchives/digital-preservation/tree/master/Digital_Preservation_Risk_Matrix) to measure the preservation risk of digital file formats in our holdings and to assess formats we anticipate receiving in the future. By answering questions related to the ability to preserve and sustain a file format, we identify relative risk levels.

The sustainability factors each have a different level of impact (positive or negative) on a format’s risk level, with several high-impact factors having the greatest effect on the calculations.

High Impact Factors:
* Positive:
  * A high level of adoption; the availability of format documentation; the ability for a file to document itself; a lack of software dependencies; and no requirement for technical protections (such as encryption) provide the most positive impact.
* Negative:
  * Format age and required hardware and/or software dependencies have the most negative impact.

The answers to all the questions have been assigned numeric values, which are used to calculate an overall Risk Rating and a general risk level which translates to: Low Risk, Moderate Risk, and High Risk.

Additionally, NARA prioritizes formats in our holdings for preservation actions. The Prioritization assessment is modeled on the traditional preservation model of Value/Use/Need. For our purposes, we use Need/Use/Feasibility to determine our preservation priorities. The Risk Rating represents the “Need” for a preservation action. “Use” is represented by evaluating Prevalence: how common the format is in our holdings at the time of assessment, therefore approximating the level of use of the format in the permanent records of the Federal Government. There is no way to map the “Value” of the holdings to individual file formats because record sets/series typically contain multiple file formats. Instead, we have replaced Value with “Feasibility,” or the capacity for NARA to process and convert formats. We assess Feasibility based on the general availability of tools for format migration that do not alter the content in unacceptable ways as well as our capacity to perform acceptable migrations.

For both the assessment of Risk and Prioritization, the lower the NARA Total number, the greater the risk or need. It is possible for numbers to be negative integers.

We are sharing our current completed matrix as a template for its use or adaptation by any interested organizations.

For a more technical discussion of the development and use of the Risk and Prioritization Matrix, a conference paper presented at the 2018 iPRES International Digital Preservation meeting is available at: https://osf.io/ctw3g/. Note that this discusses an earlier iteration than what is current.

## File Format Preservation Action Plans
We are also sharing our File Format Preservation Action Plans. These Plans are not exhaustive nor universally applicable proposed actions and recommended or endorsed tools: these represent file formats and variant versions in NARA holdings, the current NARA risk assessment, processing capabilities, and tools in use at NARA. These Plans apply to files once they have been deemed permanent for NARA's holdings; the appraisal guidelines for when a record is permanent is different for Congressional, Federal, and Presidential records.

These plans consist of two types of documentation. The first is documentation for multiple categories of electronic records. The 16 categories are:
* [Digital Audio](https://github.com/usnationalarchives/digital-preservation/tree/master/Digital_Audio_Formats)
* [Digital Design and Vector Graphics](https://github.com/usnationalarchives/digital-preservation/tree/master/Digital_Design_Formats)
* [Digital Still Image](https://github.com/usnationalarchives/digital-preservation/tree/master/Still_Image_Formats)
* [Email](https://github.com/usnationalarchives/digital-preservation/tree/master/Email_Formats)
* [Geospatial](https://github.com/usnationalarchives/digital-preservation/tree/master/Geospatial_Formats)
* [Moving Image: Digital Cinema](https://github.com/usnationalarchives/digital-preservation/tree/master/Moving_Image_Formats)
* [Moving Image: Digital Video](https://github.com/usnationalarchives/digital-preservation/tree/master/Moving_Image_Formats)
* [Navigational Charts](https://github.com/usnationalarchives/digital-preservation/tree/master/Navigational_Chart_Formats)
* [Presentation and Publishing](https://github.com/usnationalarchives/digital-preservation/tree/master/Presentation_and_Publishing_Formats)
* [Software and Code](https://github.com/usnationalarchives/digital-preservation/tree/master/Software_Formats)
* [Structured Data: Calendars](https://github.com/usnationalarchives/digital-preservation/tree/master/Structured_Data_Formats)
* [Structured Data: Databases](https://github.com/usnationalarchives/digital-preservation/tree/master/Structured_Data_Formats)
* [Structured Data: Generic](https://github.com/usnationalarchives/digital-preservation/tree/master/Structured_Data_Formats)
* [Structured Data: Spreadsheets](https://github.com/usnationalarchives/digital-preservation/tree/master/Structured_Data_Formats)
* [Textual and Word Processing](https://github.com/usnationalarchives/digital-preservation/tree/master/Textual_and_Word_Processing_Formats)
* [Web Records](https://github.com/usnationalarchives/digital-preservation/tree/master/Web_Formats)

Each category has its own Plan that contains a list of “Significant Properties,” which identify the properties, or characteristics, of a record (its Appearance, Behavior, Context, and Structure) that should be retained, if possible, in any format migration. These characteristics are important to ensure the highest fidelity format record migrations.

The second resource is the [File Format Preservation Action Plan Spreadsheet](https://github.com/usnationalarchives/digital-preservation/tree/master/Digital_Preservation_Plan_Spreadsheet). The spreadsheet covers over 700 variant versions of file formats and identifies:
* Categories of electronic records associated with the format
* Specifications, standards, and documentation where possible; some have no specification or standard available
* Proposed preservation migration actions to be taken by NARA, including no action when appropriate
* Recommended tools for processing and preservation actions

## Related Resources
There are several related resources available from NARA about file formats:
* [Digital Preservation Framework Linked Open Data](https://www.archives.gov/preservation/digital-preservation/linked-data) (File Format Preservation Action Plans as linked data)
* [Transfer Guidance on Preferred and Acceptable File Formats](https://www.archives.gov/records-mgmt/policy/transfer-guidance.html) (file formats that NARA prefers to receive from agencies, but which is not 100% proscriptive)
* [NARA Digitization Products and Service](https://www.archives.gov/preservation/products/) (file formats that NARA produces in its own internal digitization)
* [NARA Digital Preservation Strategy](https://www.archives.gov/preservation/electronic-records/digital-preservation-strategy) (NARA’s approach to Digital Preservation)

## How Can You Participate?
We are sharing these documents to be transparent about our approach to digital preservation and to share our current practices with Federal agencies, records managers, archivists, digital preservation professionals, researchers, private industry, other stakeholders and allied professionals, and members of the public to help us identify ways we can improve them.

We always welcome feedback on the following topics:
* What revisions can you suggest to the proposed processing and preservation actions for the formats?
  * Are the Significant Properties for each category comprehensive enough for digital preservation?
  * Are the proposed preservation actions for the formats technically appropriate?
* Are there appropriate tools for processing and preservation migrations of specific formats that we do not have listed?
* Are there other formats we haven’t identified that need plans?

Please use the [issues feature](https://github.com/usnationalarchives/digital-preservation/issues) on this site to leave a specific comment or question or to just start a discussion. You can read more about how to contribute [here](https://github.com/usnationalarchives/digital-preservation/blob/master/CONTRIBUTING.md). NARA staff will respond as quickly as they can.

We update the matrix and plans on an ongoing basis in response to changing risks and new technologies and formats.
