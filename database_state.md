# NGS2_recsys_1

https://github.com/NGS2Montage/PI_Demo_November2017_DAC/tree/master/site
---

psql -d django db 

\l      # show databases

\d      # show tables 

---

SELECT *  from recsys_author ;

schema : <id, name> ; count 27479

---

SELECT *  from recsys_paper_authors ;

schema : <id, paper_id, author_id> ; count 35832

14773 papers

27104 papers

---

SELECT *  from recsys_paper;

id , doi,titlke,Abstract,pdf_url, pdf,venue,year,cid,fetched,citation_only >

doi: string

fetched : boolean

citation_only : boolean   

Abstract not null or  pdf url not null count : 203785

doi not null count : 14774

---

SELECT *  from recsys_citationobject; 

no data

---

SELECT *  from recsys_citation ;

no data


---
