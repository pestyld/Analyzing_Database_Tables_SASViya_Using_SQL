# Analyzing Database Tables in SAS Viya Using SQL

## Description
Discover how to seamlessly connect with databases through SAS/ACCESS engines and SAS Viya Data connectors in this workshop. Gain insights into SAS's execution of code within databases, processing locations, and techniques for optimizing efficiency when working with database tables using SAS.

## Introduction
You will learn how to
- Establish connections to databases using SAS/ACCESS (Compute server).
- Establish connections to databases using SAS Viya Data Connectors (CAS Server).
- Gain insights into processing locations by examining the log.
- Use implicit pass through to allow the database to handle certain operations to optimize performance and reduce data movement between the database and SAS.
- Use explicit pass through to execute native database SQL queries to leverage the full capabilities of the underlying database system.


### Modify the following statement:
The demonstration environment uses the following username and password to the Oracle database. You will had to modify yours accordingly.
*caslib &outputCaslib datasource=(srctype="oracle",
                                 user="STUDENT",
                                 password="Metadata0",
                                 path="//server.demo.sas.com:1521/ORCL",
                                 schema="STUDENT");*

You can also use similar techniques with your data.

## Requirements
- You will need access to SAS Viya.
- You will need access to a database. The HOW uses Oracle