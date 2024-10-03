# NARA Digital Preservation Risk Matrix

NARA uses the Risk Matrix to measure the preservation risk of digital file formats in our holdings and to assess formats we anticipate receiving in the future. By answering questions related to the ability to preserve and sustain a file format, we identify relative risk levels.

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

The final questions in the Risk Matrix represent how NARA prioritizes formats in our holdings for preservation actions. We use Need/Use/Feasibility to determine our preservation priorities. The Risk Rating represents the “Need” for a preservation action. “Use” is represented by evaluating Prevalence: how common the format is in our holdings at the time of assessment, therefore approximating the level of use of the format in the permanent records of the Federal Government. “Feasibility” is measured as the capacity for NARA to process and convert formats. We assess Feasibility based on the general availability of tools for format migration that do not alter the content in unacceptable ways as well as our capacity to perform acceptable migrations.

## Viewing and Using the Risk Matrix

The Risk Matrix can be downloaded from GitHub. It is published in two “views,” which contain the same information in two different formats:

1. Labeled: In this view, you can see the human-readable answer to each question (i.e. Yes, No, N/A, Unknown).
2. Numbered: In this view, you can see the numeric score assigned to each answer.

If you download the Excel file, you will see both views in the file’s two sheets. They are also available separately as CSV files.

## “Unspecified version”

A number of files in NARA's holdings have only been identified by their extensions. File formats in the Risk Matrix that have “unspecified version” in their name currently serve as catch-alls for these files, until they can be identified more precisely.

In the Risk Matrix, you will see that the entries for unspecified versions are largely blank, except for the risk rating, risk level, and prioritization questions. Many of the questions are impossible to answer for a format if you do not know the specific version, because the answers may vary depending on the version. These unspecified versions are instead assigned the same overall risk rating as the lowest-scoring format with that extension, assuming the highest level of risk.

Unspecified versions still have information in the Risk Matrix about prioritization (prevalence and feasibility) because it is possible for NARA to determine how many files of this type are in our holdings and our ability to render or convert that file into an acceptable format for preservation.

## Risk Matrix Questions

For the numeric values assigned to each of these questions and sections, see [Risk Matrix Weights](https://github.com/usnationalarchives/digital-preservation/tree/master/Supporting_Documentation/Risk_Matrix_Weights).

### Section 1: Disclosure
**1.1: Is the format proprietary?**

Proprietary formats are formats for which the legal/licensing rights are exclusively owned by a company, entity, or individual. Often, use of these formats is restricted through patents or trade secrets. These formats can be prone to long-term preservation challenges such as obsolescence or backward-compatibility. 

**1.2: Does the format have a published open specification?**

A published open specification details how a format and its metadata are structured, which enables validation of a file against its specification. It also may enable the reverse engineering of software and tools to render or execute a file format, if the original software no longer exists. Furthermore, it can be difficult to assess the other sustainability factors of a file format without a published open specification. Both non-proprietary and proprietary formats may have published open specifications.

**1.3: If there is a published specification, has it been approved and published by an internationally recognized standards organization?**

Specifications that have been approved and published by an internationally recognized standards organization have undergone a controlled process for creation and publication, and there is a relatively stable mechanism for maintaining the specification.

**1.4: When was the format specification for this version last updated (or, if the last updated date is not available, when was it created)?**

As formats age, the potential risk increases because they may be superseded by newer formats and software and tool support may decrease. 

### Section 2: Adoption

**2.1: Has the file format commonly been used to create or maintain permanent records within the federal government at any point in time?**

Widespread adoption of the format in the federal government is important for NARA because it increases the likelihood that tools will be available for rendering and/or the expertise to manage the files over time will exist in the federal government. If the format has not been somewhat prevalent in the federal government at any point in time, there is a risk that it was not adopted in line with NARA guidance and that NARA may not have the expertise to manage that format over time.

For the Risk Matrix, we use the number of files in our holdings as a proxy for the prevalence of a file format in the federal government. If there are over 2,000 files of a given format identified in our holdings, we can say that it has been commonly used to create or maintain permanent records in the federal government at some point in time. If there are fewer than 2,000 files of a given format identified in our holdings, the answer to this question is “Unknown” because there is a chance this format is commonly used in the federal government but has not yet been transferred to NARA or ingested into preservation storage.	

**2.2: Is the format, or format family, actively maintained and updated by an organization or community?**

A format that is actively maintained and updated by an organization or community (rather than an individual) is likely to be more stable and have continued options for access over time, such as software backwards compatibility. For the Risk Matrix, if there has been active maintenance and updates to the format family in the past five years, we will give a positive score to older versions of the format family.

**2.3: Have the archives or library communities identified the format as one to avoid for creation and transfer of permanent materials?**

NARA should note if other institutions have identified a format as one to avoid for creation or transfer due to a number of potential risk factors (e.g., lack of support/tools for rendering, legal issues). 

### Section 3: Transparency

**3.1: Is the format character-based, rather than binary?**

Character-based formats are platform-independent files based in a specific character encoding system, such as ASCII, UTF-8, etc. These formats are human-readable and enable transfer of information between computing systems, often enhancing our ability to preserve these formats over time. Binary formats are referred to as “raw data” and comprise the most basic form of computer code. Character-based formats are more “transparent” than binary formats and may not have as complex dependencies for rendering.

**3.2: Is there an internal signature in an authoritative format registry that can be used to identify a file in this format?**

Internal signatures enhance the ability to identify a particular file’s format type and version. 

**3.3: Does the format require the use of compression?**	

While compressed formats are often useful for data transmission and storage, some compression methods result in data loss or degradation of data quality within the file format due to their algorithmic approach to data reconstruction. 

**3.4: If the format requires the use of compression, can it be lossy?**

Lossy compression permanently removes data from files, therefore degrading the original quality of the data. 

**3.5: Does this format support declared or hidden embedded data?**

Formats that can contain declared or hidden embedded data (e.g., attached files in PDF Portfolios, hidden values in spreadsheets that are used for formulas) are more likely to present challenges during the file characterization process, which may not be able to identify and/or extract this embedded data. If NARA is not fully aware of the embedded data inside of a file, it is more difficult to plan and execute preservation actions.

**3.6: If the format supports declared or hidden embedded data, does the format list or provide standard information about embedded data?**

If the format provides standard information about the embedded data, NARA can more easily develop processes and/or tools to find and extract this embedded data.

### Section 4: Self-Documentation
**4.1: Does the format natively include metadata that documents the file and the technical environment used to create (and/or modify) it?**

Formats that natively include technical metadata about their creation will likely be easier to sustain and provide access to over time. For example, knowing the software that was used to create a file can help us determine how to render the file in a context similar to the one in which it was created. This technical metadata may also provide important provenance information that can help to maintain the authenticity and integrity of records.

**4.2: Does the format support adding embedded descriptive and administrative metadata through manual or automated processes?**

Formats that natively support adding embedded descriptive and administrative metadata are more likely to contain information about the context of their creation and the chain of custody, both of which are important for providing meaningful access to records over time.

### Section 5: External Hardware Dependencies

**5.1: Does the format require a specific hardware environment, such as a specific graphics card, chipset, or memory requirements, to process or interact with it?**

NARA will be less likely to be able to migrate and preserve a format that requires a specific hardware environment to process or interact with it, especially as support for the hardware decreases and it is rendered obsolete by newer hardware.

**5.2: Does the format require specific playback hardware (e.g., Blu-Ray, Audio CD, etc) to transfer the format to the NARA environment?**

NARA will be less likely to be able to migrate and preserve a format that requires a specific playback hardware to transfer into the NARA environment. While NARA does maintain an inventory of readers for a range of legacy media, over time it becomes more challenging to procure and maintain these readers.

### Section 6: External Software Dependencies

**6.1: Are renderers available?**

If renderers are not available for a format, it is unlikely that NARA will be able to validate files in that format or provide meaningful long-term access to them.

**6.2: If renderers are available, is at least one of them open source?**

If only proprietary renderers are available for a format, there is a risk of those renderers becoming unavailable from their vendors, or those renderers ceasing support for older versions of a format. Open source renderers help mitigate this risk through open availability and the ability to make changes to the code if needed.

**6.3: Does the format rely on plug-ins and/or scripts, etc. to render or execute files?**

Reliance on plug-ins and/or scripts for rendering poses a risk because of the dependency on these plug-ins or scripts being maintained and available over time, potentially in addition to the core software.

**6.4: Can the format be rendered or executed in more than one computing operating system?**

Formats that cannot be rendered in more than one computing operating system are typically representative of data that is difficult to transfer between computing systems. When formats cannot easily be rendered or transferred between systems, their dependencies and risk of obsolescence increases. 

**6.5: Is there software supported by current computing environments that can create the format?**

If the software used to create the format is currently supported, this enhances NARA’s current ability to accession and process files in this format in the near-term, as it will be easier to troubleshoot any errors that arise during rendering or validation using current tools and/or documentation.

### Section 7: Impact of Patents

**7.1: Is the format subject to patent claims that may impede the development of open source tools for opening and managing the files?**

Formats that are subject to patent claims typically have a higher preservation risk because the ability to open and manage the files is restricted to specific software and licensing applications. 

**7.2: Does the format have open source license terms?**

Open source licenses allow content to be used, modified, or shared. File formats that explicitly have open source license terms around their usage likely carry a low risk for litigation related to the usage of the file format and the creation of tools for processing and access.

### Section 8: Technical Protection Mechanisms

**8.1: Does the format require the use of encryption?**

Encryption restricts access and management of files because the file data is converted into ciphertext. When data is encrypted, a cipherkey is needed to access the file and the original information within, posing a challenge to long-term preservation unless the cipherkey is documented and known. 

**8.2: If the format requires the use of encryption, is it robust (cryptographically secure)?**

Robust (cryptographically secure) encryption provides an extremely high level of restriction to file access. Robust encryption can likely not be broken during archival processing, increasing the need to document and retain the cipherkey. Formats that require the use of robust encryption will be much more difficult to process and provide access to.

**8.3: Does the format natively allow the use of technical protection measures (e.g. digital rights management)?**

Technical protection measures, such as DRM, control access to copyrighted material. Files may require authentication to decrypt their contents, or there may be limitations on the number of devices used to access the contents of the file. Similar to other types of encryption, technical protection measures may prevent NARA from rendering the file for validation and processing, and they also inhibit long-term access to the content.

### Prioritization 

These questions do not count towards the Risk/Sustainability Factor. They are used to calculate the NARA Total, factoring in both risk and prioritization.

**Prevalence: Format Adoption Level**

Prevalence is measured by the proportion of a file format identified in NARA’s preservation systems across Federal, Presidential, and Legislative holdings. As discussed in Question 2.1, we use the number of files identified in our holdings as a proxy in the Risk Matrix for the prevalence of a file format in the government. NARA prioritizes addressing the preservation concerns and needs of a format that is more prevalent, whereas a format that is relatively less prevalent is a lower priority.

**Feasibility: Ability to Convert**

If no acceptable tools exist in the marketplace to convert this format to an acceptable format for preservation, it is a higher priority for NARA to address this format. On the other end of the spectrum, if transformation is already performed at NARA using acceptable tools or if the format has been identified as Preferred/Acceptable in the NARA Transfer Guidance, it is a lower priority for NARA to address this format. The answer to this question comes either from the applied experiences of processing archivists at NARA or research by the Digital Preservation Unit.
