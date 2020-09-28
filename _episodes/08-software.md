---
title: "Software"
teaching: 0
exercises: 0
questions:
- "Key question"
objectives:
- "The objective of this lesson is to get learners up to speed on how the FAIR principles apply to software, and to make learners aware of accepted best practices."
keypoints:
- "First key point."
---

# Applying FAIR to software

The FAIR principles have been developed with research data in mind, however they are relevant to all digital objects resulting from the research process - which includes software. The discussion around FAIRification of software - particularly with respect to how the principles can be adapted, reinterpreted, or expanded - is ongoing. This position paper (https://doi.org/10.3233/DS-190026) elaborates on this discussion and provides an overview on how the 15 FAIR Guiding Principles can be applied to software. 

**BTW what do we mean by software here?**
Software can refer to programming scripts and packages such as those for R & Python, as well as programs and webtools/webservices such as ......
For the most part, this lesson focuses on the former.

**Note/Acknowledgements**

This lesson draft, complied during the FAIR lesson sprint @CarpentryCon2020, draws heavily from the Top 10 FAIR Data & Software Things + FAIR Software Guide (see reference list).

## Findable

For software to be findable, 
- **it should be accompanied with sufficiently rich metadata and persistent identifiers.**

1. Software should be well documented to to increase findability and eventually, reusability. This metadata can start with a minimum set of information that includes a short description and meaningful keywords. This documentation be further improved by applying metadata standards such as those from CodeMeta (https://codemeta.github.io/terms/) or DataCite.

2. Software should be registered in a dedicated registry such as Research Software Directory, rOpenSci project, Zenodo. These registries will usually request the previously mentioned metadata descriptors, and they are optimized to show up in search engine results. _question to be resolved: how is a registry different from a repository?_  

3. When attaching identifiers to software, they should be unqiue and persistent. They should point only the one version and location of your software. A software registry usually provides a PID, otherwise you can obtain one from another organization and include it in your metadata yourself. See: Software Hertigage archive.    

4. Your software can also be hosted/deposited in an open and publicly accessible repository, preferably with version control and citation guidelines. Examples: Zenodo or GitHub (see GitHub doc on citing code, but note the issue about attaching identifiers and the 'permanence' of GitHub). _Still have to check the difference between registries and repositories._

## Accessible

For software to be accessible, 
- **software metadata should be in machine and human readable formats.**
- **software and metadata should be deposited in a trusted community-approved repository.**

1. _What does it mean to make metadata machine and human readable? This should be covered in a previous lesson and referred back here..._

2. The (executable) software and metadata should be publicly accessible and downloadable. These downloadable and executable files can be hosted or deposited in a repository / registry, as well as project websites. 

## Interoperable

For softare to be interoperable,
- **community accepted standards and platforms should be used, making it possible for other users to run the software.**

1. Interoperability is increased when there is documentation that outlines functions of the software. This means providing clear and concise descriptions of all the operations available with the software, including input and output functions and the data types associated with them.

2. If community standards are available, input and output formats should adhere to them. This makes it easy to exchange data between software (the data itself will be better linked too).

## Reusable

For software to be reusable,
- **it should have a clear licence and documentation.**

1. Software should be sufficiently documented beyond metadata. This could include instructions, troubleshooting, statements on dependencies, examples or tutorials. 

2. Include a license. This informs potential users on how they may/may not (re)use the software.

3. Include a citation guideline, if you'd like to receive credit or acknowledgement for your work.

4. Combine best practices for software development with FAIR. This would include working out of a repository with version control (which allows for tracking changes and transparency), following code standards, building modual code etc.

5. In addition to 4, you can use a software quality checklist. There are several available and you can select which is most suitable for your software. A good checklist will include items which allow for a granular evaluation of the software, explains the rationale behind the check, and explains how to implement the check. It can cover documentation, testing, standardization of code etc. You quality checklist could be maintained in your README file.  

## References

- position paper: https://doi.org/10.3233/DS-190026
- Top 10 Fair Data & Software Things: https://librarycarpentry.org/Top-10-FAIR//2018/12/01/research-software/
- FAIR Software guide: https://fair-software.eu/
- Netherlands eScience Center FAIR Software lesson outline: https://escience-academy.github.io/2020-09-08-4tu-fair-software/
- CarpentryCon2020 FAIR Software course: https://www.youtube.com/watch?time_continue=321&v=-x81mpkQAWo&feature=emb_logo / Etherpad: https://pad.carpentries.org/cchome-FAIR-software
- FSCI2020 FAIR Data course (session 3 slides): https://osf.io/jx2tp/

---------------------

## Lessons to teach in connection with this section and exercises
[Software Carpentry: Version Control with Git](https://swcarpentry.github.io/git-novice/) or [Library Carpentry: Intro to Git](https://librarycarpentry.github.io/lc-git/)
[Making your Code Citeable](https://guides.github.com/activities/citable-code/)
Does an exercise or lesson exist that we can point to involving Software Heritage?
