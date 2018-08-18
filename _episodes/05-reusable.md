R1. (meta)data have a plurality of accurate and relevant attributes
R1.1 (meta)data are released with a clear and accessible data usage licence
R1.2 (meta)data are associated with their provenance
R1.3 (meta)data meet domain-relevant community standards


## What does it mean to be machine readable vs human readable?

According to the [Open Data Handbook](http://opendatahandbook.org/glossary/en/):

*Human Readable*
"Data in a format that can be conveniently read by a human. Some human-readable formats, such as PDF, are not machine-readable as they are not structured data, i.e. the representation of the data on disk does not represent the actual relationships present in the data."

*Machine Readable*
"Data in a data format that can be automatically read and processed by a computer, such as CSV, JSON, XML, etc. Machine-readable data must be structured data. Compare human-readable.

Non-digital material (for example printed or hand-written documents) is by its non-digital nature not machine-readable. But even digital material need not be machine-readable. For example, consider a PDF document containing tables of data. These are definitely digital but are not machine-readable because a computer would struggle to access the tabular information - even though they are very human readable. The equivalent tables in a format such as a spreadsheet would be machine readable.

As another example scans (photographs) of text are not machine-readable (but are human readable!) but the equivalent text in a format such as a simple ASCII text file can machine readable and processable."


## File naming best practices
Stanford Libraries [guidance on file naming](https://library.stanford.edu/research/data-management-services/data-best-practices/best-practices-file-naming) is a great place to start, but general best practice is to organize files in a consistent manner and clearly describe the content they contain. Avoid including spaces and special characters which can be difficult for computers to read. Use common [special letter case](https://en.wikipedia.org/wiki/Letter_case#Special_case_styles) patterns such as Kebab-case, CamelCase, or Snake_case. Include author name, project name, type of data, type of analysis, date, and file extension. 
Here are some examples [from Dryad](http://datadryad.com/pages/reusabilityBestPractices):

- 1900-2000_sasquatch_migration_coordinates.csv
- Smith-fMRI-neural-response-to-cupcakes-vs-vegetables.nii.gz
- 2015-SimulationOfTropicalFrogEvolution.R

## Directory structures and README files
For others to reuse your research, it is important to include a README file and to organize your files in a logical way. Consider the following file structure examples from Dryad:

![]()

It is also good practice to include README files to describe how the data was collected, processed, and analyzed. In other words, README files help others correctly interpret and reanalyze your data. A README file can include file names/directory structure, glossary/definitions of acronyms/terms, description of the parameters/variables and units of measurement, report precision/accuracy/uncertainty in measurements, standards/calibrations used, environment/experimental conditions, quality assurance/quality control applied, known problems, research date information, description of relationships/dependencies, additional resources/references, methods/software/data used, example records, and other supplemental information. 

Dryad README file example:
https://datadryad.org//resource/doi:10.5061/dryad.j512f21p

Awesome README list (for software):
https://github.com/matiassingers/awesome-readme

