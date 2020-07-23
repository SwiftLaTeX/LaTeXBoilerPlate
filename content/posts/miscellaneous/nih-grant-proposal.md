---
title: NIH Grant Proposal
date: 2020-07-23T10:53:29+0000
img: pkctf_NIHGrant.png
tags:
- miscellaneous
---
```
NIH Grant Proposal

Description:
The National Institutes of Health (NIH) provides grants to researchers wishing to fund their research projects. The lengthy application requires a great deal of information regarding the proposed research and this template is meant to make the process easier by creating the document structure required for the application and providing examples of typical content. The template is primarily meant for the Specific Aims, Research Plan and Bibliography sections of the grant application but other parts (e.g., Budget Justification) can be created as additions to this template or subsequently created in a word processor. The author recommends making the Aims, Research Plan, and Bibliography all in one document and then splitting it up using your preferred method. The entire grant must have a shared, unified Bibliography and the components are submitted separately, generating the grant in one document ensures consistency in formatting and citations. Of course, you are responsible for making sure that you have all the required documents for your grant submission and this template is to facilitate formatting the Aims, Research Plan, and Bibliography in a consistent manner.
Use this template at your own risk. It conforms to the guidelines (as of 2013 when the template was created) but uses larger fonts for section headings and linespace than minimally required; you can squeeze more content into other formats, but the author believes this is a good balance of white space and text density for a 12 page proposal.
Some notes on the bibliobraphy: the original template the current template was adapted from did not use BibTeX; but instead used the \begin{thebibliography} environment; and then entered the bibliography in this file which can be distracting and overly complex. Instead, this template uses a BibTeX file and the nihunsrt.bst bibliography style written by Elana J Fertig. If you currently have your reference library in Endnote only, you can use Endnote to export it as a BibTeX file. In order to include the PMC and PubMed ID (which the nihunsrt.bst recognizes as PMC = field); you need to change the output style of BibTeX Export file in your Endnote library. With BibTeX Export style selected, go to Edit->Export Styles->Edit “BibTeX Export” …. under Templates, go to “Journal Articles,” add this entry:   — |   `PMC = `{PMCID},   …..  Then export  — existing Endnote library to a BibTeX file that you can use. Unfortunately, you will have to manually enter the Key that defines each entry (e.g., Tatro2013). In the future, if you download the citation files from PubMed as BibTeX exports, it will contain the field. But if you need to migrate from a massive Endnote library, this process is necessary. Note also that Endnote exports “government documents” as @misc on the BibTeX file; and the nihunsrt.bst doesn’t handle this well; fix this by changing the article type to @article and for the Author field, put the Department, Agency (e.g., Department of Health and Human Services, Centers for Disease Control and Prevention) which authored the report.
Original Author:
This template was originally created by Erick Tatro adapted from J. Hrabe but has been extensively modified for this website by Vel.
```
[Open this template in SwiftLaTeX](https://www.swiftlatex.com/project.html?import=https://swiftlatex.github.io/LaTeXBoilerPlate/zips/qudfz_NIHGrant.zip&import_name=NIH%20Grant%20Proposal)
