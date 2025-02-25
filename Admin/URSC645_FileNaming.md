# General Filename Plan for Reproducible Worklow

This filename plan provides basic guidelines to help with reproducible research. 
An ideal filename provides information about the author, the contents, and when the file was made. 
Consistent filenames make finding files easy. 
The need for a clear file naming plan is important for a large research project that produces a large number of files. 
This document outlines the four main parts of a filename. 
These include the provenance or origin of the file, 
the contents of the file, 
the file version, and 
the file type. 
This naming plan can be applied to survey instruments, data files, and programs such as Jupyter Notebooks.
The following sections provide more details about the filename parts.

## Filename Part 1 – Highlight Provenance

To highlight the project a filename that starts with a mnemonic, a short string of letters, will help future users of the file recognize its provenance or origin. 
For example, TAMU, is an acronym and a mnemonic for the Texas A&amp;M University. 
TAMU has many departments and centers. 
HRRC is the mnemonic for the Hazard Reduction and Recovery Center. 
LAUP is the mnemonic for the Department of Landscape Architecture and Urban Planning.
TAMU, HRRC, and LAUP are all recognizable mnemonics.

Notice that all filenames in the URSC645 project have a recognizable mnemonic that uniquely identifies the provenance of the files.

## Filename Part 2 – Describe the Contents or Function

In this example the project mnemonic is followed by the descriptive text that highlights the file contents or function. 
For example, a file that archives the form used in a field study for a food retail survey, could include the text &quot;Food Retail Form&quot;.
To avoid issues sometimes caused by included spaces in filenames each word is separated by an underscore &quot;\_&quot; or a mix of upper case and lower-case letters.

HRRC\_FoodRetailForm\_2018-01-26

The goal of descriptive name is to reduce a future user&#39;s need to click on the file and open it. Hopefully the contents are described enough to help identify what is inside the file.

## Filename Part 3 - Version Control

The example above includes the third part of the filename, the date. 
The date in the format year, month, date (YYYY-MM-DD) follows an international standard (ISO 8601). 
Typing the date in this format means that files will appear in chronological order in file directory. 
Also, by including the date of the file, a future user of the file will be able to easily confirm the version. 
If the date does not provide enough information to identify the version a zero padded version number might be appropriate. 
For example, adding v03 would allow for up-to 99 different versions of a file to be tracked.

## Filename Part 4 – File Type Extension

After the filename, each file includes a file type extension (.xlsx, .csv, .pdf etc.). 
The file type extension provides a way to differentiate files that may have the same name. 
For example:

- HRRC_FoodRetailForm_2018-01-26.docx
- HRRC_FoodRetailForm_2018-01-26.pdf

The two files have the same name but one file is a Word Document and the second file is a PDF. 
The two files have the same contents but provide future users with a file format that can be edited (the Word Document) and 
a file format that preserves the original formatting (the PDF).

# Use of Special Characters and Filename Length

Names best tolerated by the widest variety of systems use a combination of letters (A-Z, a-z), numbers (0-9), underscores (\_), and hyphens (-). 
The filename plan presented above uses an underscore &quot;\_&quot; to separate the parts of the naming plan and dashes within the date format YYYY-MM-DD.

Filenames longer than 255 characters may not be readable by some operating systems, such as LINUX.
Therefore, filenames must be less than 255 characters. Additionally, since the filenames are designed to be viewed on a screen with limited width, 
filenames longer than 80 characters will be cutoff, requiring the user to scroll to see the full name. 
Therefore, it is recommended that file names not exceed 80 characters.

# Summary

A good naming plan needs to be easy to understand and should be consistent. 
The filename plan presented is designed to reinforce the project goals, 
project management, and to help future users easily navigate files shared publicly.

# References

Cornell University Research Data Management Service Group. (n.d.). _File Management._ Retrieved from [https://data.research.cornell.edu/content/file-management](https://data.research.cornell.edu/content/file-management)

Hodge, A. (2015). _File Naming Best Practices_. Stanford Data Management Services. Retrieved from [https://library.stanford.edu/research/data-management-services/data-best-practices/best-practices-file-naming](https://library.stanford.edu/research/data-management-services/data-best-practices/best-practices-file-naming)

ISO. (n.d.). _Popular Standards: ISO 8601 DATE AND TIME FORMAT_. [https://www.iso.org/iso-8601-date-and-time-format.html](https://www.iso.org/iso-8601-date-and-time-format.html)

Long, J. S. (2016, August). _Reproducible Results and the Workflow of Data Analysis_. Indiana University Workshop in Methods. [http://hdl.handle.net/2022/20969](http://hdl.handle.net/2022/20969)

NIST Weights and Measures. (2016). _Electronic File Organization Tips_. Retrieved from. [https://www.nist.gov/system/files/documents/pml/wmd/labmetrology/ElectronicFileOrganizationTips-2016-03.pdf](https://www.nist.gov/system/files/documents/pml/wmd/labmetrology/ElectronicFileOrganizationTips-2016-03.pdf)

University of Illinois Research Data Service. (2017). _Organize Your Data_. Retrieved from [https://www.library.illinois.edu/rds/organize/](https://www.library.illinois.edu/rds/organize/)

Wikipedia. (2019). ISO 8601. [https://en.wikipedia.org/wiki/ISO\_8601](https://en.wikipedia.org/wiki/ISO_8601)
