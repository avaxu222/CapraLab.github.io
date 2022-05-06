#Style guide for Fraser Lab website.
#Written by Robbie Diaz - 2020.
#Updated 07/19/21

#Style Guide: Publications
##All sections
  #Indent with two spaces
  #Use double quotes for all string entries

#Authors
#Bold lab member names using the following format: **Last FM**.
#Use one pair of double asterisks for multiple lab members that appear sequentially: **Young ID, Diaz RE, Liu LL**.
#Use &#42; to add an asterisk denoting co-first/corresponding author. Otherwise, bolding of names using **Surname FM** will break.
#For readability of code, start a new line at 140 characters.

#Images and PDFs
#the pub md entry and asscoiated images and PDFs should be named using the following convention: yyyy-mm-dd_FALN_journal.md/pdf/png

#Leave PMID and PMCID blank until an ID is assigned.
#Do not include additional subsections that are not relevant to a publication (PDB, data, Zenodo, etc).

#Example Publication
---
title: "Title of article."
authors: "**FA**, .., .., LA&#42;"
journal: "Journal Name"
pub_date: "YYYY-MM-DD" #Date of journal publication, NOT BIORXIV UPLOAD
image: "/static/img/pub/YYYY_SurnameFirstAuthor.png" #Minimum dimensions of
pmid: "########"
pmcid: "PMC#######"
biorxiv: "YYYY.MM.DD.######"
pdf: "http://cdn.fraserlab.com/publications/YYYY_SurnameFirstAuthor.pdf"

github:
  - description: "qPTxM"
    url: "fraser-lab/qptm"
links:
  - name: ""
    url: ""

[comment]: <> (  - name: "")

[comment]: <> (    url: "")
    
---
