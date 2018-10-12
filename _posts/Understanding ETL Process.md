---
layout:     post   				   
title:      Understanding ETL Process
subtitle:   
date:       2018-10-12
author:     James Cao
header-img: img/post-bg-2015.jpg 	
catalog: true 					
tags:								
    - ETL
---

## Study Note
> <strong>Data warehouse</strong> versus <strong>Database</strong>

Simple Definition: Data warehouse is one kind of database or a large database. Data warehouse is formed using multiple databases.

1. Database is used for Online Transactional Processing (OLTP) & Data warehouse is used for Online Analytical Processing (OLAP).
2. Database tables are always in a normalized structure & Data Warehouse tables are always in a de-normalized structure.
3.

Note:
OLTP is a decentralized system normally used in Internet websites, banks, airlines, to avoid single points of failure and to spread the volume between multiple servers. This system is good to control and run fundamental business tasks.
OLAP is centralized system to help with planning, problem solving, and decision support. Queries are often very complex and relatively used for low volume of transaction.


>  ETL: Extraction, Transformation and Loading

- Extraction: This is the first step of the ETL process. It extracts the data from various forms of data including Excel, csv files, flat files and many web data forms.
- Transformation: This step requires some certain collected data to be processed and transformed. The ways are many not limited to data type conversion, data merge/join, splitting format, currency format etc.
- Loading: It is the final step of the process. This can be accomplished by SQL insert commands and/or bulk insert.


A real-life example with Microsoft SSIS:

TBD

http://www.learnmsbitutorials.net/etl-process-ssis-example.php
