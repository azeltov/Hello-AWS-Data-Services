# Lake Formation

## What is it?

AWS Lake Formation is a service that makes it easy to set up a secure data lake in days. 
- A data lake is a centralized, curated, and secured repository that stores all your data, both in its original form and prepared for analysis. 
- A data lake enables you to break down data silos and combine different types of analytics to gain insights and guide better business decisions. 

To create a data lake with AWS Lake Formation...
- define where your data resides and what data access 
- define what security policies you want to apply. 
- Lake Formation then collects and catalogs data from databases and object storage, moves the data into your new Amazon S3 data lake
- it then cleans and classifies data using machine learning algorithms, and secures access to your sensitive data
- Your users can then access a centralized catalog of data which describes available data sets and their appropriate usage
- Your users then leverage these data sets with their choice of analytics and machine learning services, like Amazon EMR for Apache Spark, Amazon Redshift Spectrum, and Amazon Athena. 

## Newly Released Features

AWS Lake Formation transactions, row-level security, and acceleration are now available for preview. These capabilities are available via new, open, and public update and access APIs for data lakes. These APIs extend AWS Lake Formation’s governance capabilities with row-level security. In addition, with this preview, we introduce governed tables - a new Amazon S3 table type that supports atomic, consistent, isolated, and durable (ACID) transactions. AWS Lake Formation transactions simplify ETL script and workflow development, and allow multiple users to concurrently and reliably insert, delete, and modify rows across multiple governed tables. AWS Lake Formation automatically compacts and optimizes storage of governed tables in the background to improve query performance. 

By integrating Amazon EMR with AWS Lake Formation, you can enhance data access control on multi-tenant EMR clusters by managing Amazon S3 data access at the level of databases, tables, and columns. This feature also enables SAML-based single sign-on (SSO) to EMR Notebooks and Apache Zeppelin, and simplifies the authentication for organizations using Active Directory Federation Services (ADFS). With this integration, you have a single place to manage data access for Amazon EMR along with other AWS analytics services including Amazon Redshift Spectrum, Amazon Glue, and Amazon Athena.  

Amazon EMR now allows you to leverage AWS Lake Formation for defining and enforcing fine-grained access control policies for Apache Spark applications. Previously, this feature was in beta.  

---

- More info - https://aws.amazon.com/lake-formation    
- FAQ - https://aws.amazon.com/lake-formation/faqs/

<img src="https://github.com/lynnlangit/Hello-AWS-Data-Services/blob/master/images/lake-formation.png" width=800>
