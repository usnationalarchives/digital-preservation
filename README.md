# U.S. National Archives and Records Administration Digital Preservation Framework

The National Archives and Records Administration Digital Preservation Framework consists of a Risk Matrix and Preservation Action Plans.

## Background

The National Archives [2022–2026 Strategic Plan](https://www.archives.gov/about/plans-reports/strategic-plan/strategic-plan-2022-2026) embraces the primacy of electronic records. Our vision is to ensure cutting-edge access to extraordinary volumes of government informa­tion and unprecedented engagement to bring greater meaning to the American experience. To do so, NARA must collaborate with other Federal agencies, the private sector, and the public to ensure records and archives thrive in a digital world.

Digital preservation is critical to this work. It has become even more important because of the direction ([M-23-07, Update to Transition to Electronic Records](https://www.archives.gov/files/records-mgmt/policy/m-23-07.pdf)) to Federal agencies to transition business processes and recordkeeping to a fully electronic environment. As of June 30, 2024, the National Archives no longer accepts paper records from Federal agencies, with limited exceptions.


NARA holds over one billion files representing more than 700 file format versions. These files can be categorized into 16 general categories of electronic records. The vast majority of files are email messages, JPEG and TIFF still images, PDFs, HTML, and plain ASCII text.

The NARA Digital Preservation Unit created the Digital Preservation Framework in response to the current and anticipated volume of electronic records in NARA’s holdings. This set of documents describes how NARA identifies risks to digital files and prioritizes them for action, as well as how NARA plans for their long-term preservation. 

The Digital Preservation Framework consists of:
1. The NARA Risk Matrix
2. File Format Preservation Action Plans
3. Record Category Preservation Action Plans

These documents are actively maintained and updated on a quarterly basis, as NARA continues to research formats newly identified or newly accessioned into its holdings.

## The NARA Risk Matrix

NARA uses the [Risk Matrix](https://github.com/usnationalarchives/digital-preservation/tree/master/Digital_Preservation_Risk_Matrix) to measure the preservation risk of digital file formats in our holdings and to assess formats we anticipate receiving in the future. By answering questions related to the ability to preserve and sustain a file format, we identify relative risk levels.

The Risk Matrix is structured as a series of twenty-seven questions about each file format, organized by eight categories relating to risk and sustainability:

1. Disclosure
2. Adoption
3. Transparency
4. Self-Documentation
5. External Hardware Dependencies
6. External Software Dependencies
7. Impact of Patents
8. Technical Protection Mechanisms

The answers to all the questions have been assigned numeric values, which are used to calculate an overall numeric Risk Rating and a general Risk Level which translates to: Low Risk, Moderate Risk, and High Risk.

The final questions in the Risk Matrix represent how NARA prioritizes formats in our holdings for preservation actions. We use Need/Use/Feasibility to determine our preservation priorities. The Risk Rating represents the "Need" for a preservation action. "Use" is represented by evaluating Prevalence: how common the format is in our holdings at the time of assessment, therefore approximating the level of use of the format in the permanent records of the Federal Government. "Feasibility" is measured as the capacity for NARA to process and convert formats. We assess Feasibility based on the general availability of tools for format migration that do not alter the content in unacceptable ways as well as our capacity to perform acceptable migrations.

The Risk Matrix is [described in greater detail here](https://github.com/usnationalarchives/digital-preservation/blob/master/Digital_Preservation_Risk_Matrix/readme.md).

## File Format Preservation Action Plans
NARA publishes File Format Preservation Action Plans for all file formats represented in the Risk Matrix. These Plans identify actions that would enhance long-term preservation for a format type and documents NARA’s practices and preferred tools. However, they are not exhaustive nor universally applicable; actions may differ based on the file formats and variant versions in NARA holdings, the current NARA risk assessment, processing capabilities, and tools in use at NARA. These Plans apply to files once they have been deemed permanent for NARA's holdings; the appraisal guidelines for when a record is permanent is different for Congressional, Federal, and Presidential records.

These plans can be accessed in the [File Format Preservation Action Plan Spreadsheet](https://github.com/usnationalarchives/digital-preservation/tree/master/Digital_Preservation_Plan_Spreadsheet). The spreadsheet covers over 700 variant versions of file formats and identifies:

* Categories of electronic records associated with the format
* Specifications, standards, and documentation where possible; some have no specification or standard available
* Proposed preservation migration actions to be taken by NARA, including no action when appropriate
* Recommended tools for processing and preservation actions

The Preservation Action Plans are also available as [linked open data](https://www.archives.gov/preservation/digital-preservation/linked-data) on archives.gov.

## Record Category Preservation Action Plans

NARA also maintains preservation action plans for categories of electronic records. Each category has its own Plan that contains a list of “Significant Properties,” which identify the properties, or characteristics, of a record (its Appearance, Behavior, Context, and Structure) that should be retained, if possible, in any format migration. These characteristics are important to ensure the highest fidelity format record migrations. The Record Category Preservation Action Plans, and a template for their creation, can be [accessed here](https://github.com/usnationalarchives/digital-preservation/blob/master/Digital_Preservation_Record_Categories/NARA_PreservationActionPlan_Template.docx "accessed here"). 

The 16 categories are:

- [Digital Audio](https://github.com/usnationalarchives/digital-preservation/blob/master/Digital_Preservation_Record_Categories/NARA_PreservationActionPlan_DigitalAudio.md "Digital Audio")
- [Digital Design and Vector Graphics](https://github.com/usnationalarchives/digital-preservation/blob/master/Digital_Preservation_Record_Categories/NARA_PreservationActionPlan_DigitalDesignAndVectorGraphics.md "Digital Design and Vector Graphics")
- [Digital Still Image](https://github.com/usnationalarchives/digital-preservation/blob/master/Digital_Preservation_Record_Categories/NARA_PreservationActionPlan_DigitalStillImage.md "Digital Still Image")
- [Email](https://github.com/usnationalarchives/digital-preservation/blob/master/Digital_Preservation_Record_Categories/NARA_PreservationActionPlan_Email.md "Email")
- [Geospatial](https://github.com/usnationalarchives/digital-preservation/blob/master/Digital_Preservation_Record_Categories/NARA_PreservationActionPlan_Geospatial.md "Geospatial")
- [Moving Image: Digital Cinema](https://github.com/usnationalarchives/digital-preservation/blob/master/Digital_Preservation_Record_Categories/NARA_PreservationActionPlan_DigitalCinema.md "Moving Image: Digital Cinema")
- [Moving Image: Digital Video](https://github.com/usnationalarchives/digital-preservation/blob/master/Digital_Preservation_Record_Categories/NARA_PreservationActionPlan_DigitalVideo.md "Moving Image: Digital Video")
- [Navigational Charts](https://github.com/usnationalarchives/digital-preservation/blob/master/Digital_Preservation_Record_Categories/NARA_PreservationActionPlan_NavigationalCharts.md "Navigational Charts")
- [Presentation and Publishing](https://github.com/usnationalarchives/digital-preservation/blob/master/Digital_Preservation_Record_Categories/NARA_PreservationActionPlan_PresentationAndPublishing.md "Presentation and Publishing")
- [Software and Code](https://github.com/usnationalarchives/digital-preservation/blob/master/Digital_Preservation_Record_Categories/NARA_PreservationActionPlan_SoftwareAndCode.md "Software and Code")
- [Structured Data: Calendars](https://github.com/usnationalarchives/digital-preservation/blob/master/Digital_Preservation_Record_Categories/NARA_PreservationActionPlan_Calendars.md "Calendars")
- [Structured Data: Databases](https://github.com/usnationalarchives/digital-preservation/blob/master/Digital_Preservation_Record_Categories/NARA_PreservationActionPlan_Databases.md "Structured Data: Databases")
- [Structured Data: Generic](https://github.com/usnationalarchives/digital-preservation/blob/master/Digital_Preservation_Record_Categories/NARA_PreservationActionPlan_StructuredData.md "Structured Data: Generic")
- [Structured Data: Spreadsheets](https://github.com/usnationalarchives/digital-preservation/blob/master/Digital_Preservation_Record_Categories/NARA_PreservationActionPlan_Spreadsheets.md "Structured Data: Spreadsheets")
- [Textual And Word Processing](https://github.com/usnationalarchives/digital-preservation/blob/master/Digital_Preservation_Record_Categories/NARA_PreservationActionPlan_TextualAndWordProcessing.md "Textual And Word Processing")
- [Web Records](https://github.com/usnationalarchives/digital-preservation/blob/master/Digital_Preservation_Record_Categories/NARA_PreservationActionPlan_WebRecords.md "Web Records")


## File Format Extensions

NARA also publishes file extensions data from our holdings for potential reuse, such as to identify extensions to be researched further for file format identification. The extensions and counts provided are generated by combining reports from various preservation systems for Federal, Legislative, and Presidential electronic records. More information and the dataset can be [accessed here](https://github.com/usnationalarchives/digital-preservation/tree/master/File_Extensions).

## Related Resources

There are several related resources available from NARA about file formats:

* [Digital Preservation Framework Linked Open Data](https://www.archives.gov/preservation/digital-preservation/linked-data) (File Format Preservation Action Plans as linked data)
* [Transfer Guidance on Preferred and Acceptable File Formats](https://www.archives.gov/records-mgmt/policy/transfer-guidance.html) (file formats that NARA prefers to receive from agencies, but which is not 100% proscriptive)
* [NARA Digitization Products and Service](https://www.archives.gov/preservation/products/) (file formats that NARA produces in its own internal digitization)
* [NARA Digital Preservation Strategy](https://www.archives.gov/preservation/electronic-records/digital-preservation-strategy) (NARA’s approach to Digital Preservation)

## Publications and Presentations
[All Risk is Local: File Format Risk Assessment In Two U.S. Government Contexts](https://ipres2024.pubpub.org/pub/xtwb1guc/). iPres International Digital Preservation Conference, 2024.

[Creating a holdings format profile and format matrix for risk-based digital preservation planning at the National Archives and Records Administration](https://osf.io/ctw3g/). iPres International Digital Preservation Conference, 2018.

## How Can You Participate?

We share these documents to be transparent about our approach to digital preservation and to communicate our current practices to Federal agencies, records managers, archivists, digital preservation professionals, researchers, private industry, allied professionals, and members of the public.


We always welcome feedback on the following topics:
* What revisions can you suggest to the proposed processing and preservation actions for the formats?
  * Are the Significant Properties for each category comprehensive enough for digital preservation?
  * Are the proposed preservation actions for the formats technically appropriate?
* Are there appropriate tools for processing and preservation migrations of specific formats that we have not listed? Are any of the listed tools inappropriate or risky to use for the purposes we have identified?
* Are there other formats we have not yet identified that need plans?

Please use the [issues feature](https://github.com/usnationalarchives/digital-preservation/issues) on this site to leave a specific comment or question or to just start a discussion. You can read more about how to contribute [here](https://github.com/usnationalarchives/digital-preservation/blob/master/CONTRIBUTING.md). NARA staff will respond as quickly as they can.

We update the matrix and plans on an ongoing basis in response to changing risks and new technologies and formats.
