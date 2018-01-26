# NGS2_recsys_1

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

citation_only : boolean   (Todo : Get context/Meaning ). I see abstract missing in these cases. 

Abstract not null or  pdf url not null count : 203785

doi not null count : 14774

---

SELECT *  from recsys_citationobject; 

no data

---

SELECT *  from recsys_citation ;

no data


---
