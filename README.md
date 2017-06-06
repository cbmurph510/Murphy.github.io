## SQL Portfolio

### CRM Data Migration Project

Introduction: 
I served as the team lead on a fourteen-month project that entailed migrating data from existing Onyx CRM SQL databases to a new install on premise of MS Dynamics CRM SQL databases. Tasks included data manipulation and cleanup per business analysis.  


**Project Samples:**

| Purpose          | File Link |
| -------------------    | ------------- |
| Staging table creation | [Contact_table.sql](https://github.com/cbmurph510/Data-Migration/blob/master/dbo.Contact_table.sql)  |
| Data Migration log table creation | [DataMigrationLog_RowError.sql](https://github.com/cbmurph510/Data-Migration/blob/master/dbo.DataMigrationLog_RowError.sql)  |
| Stored Procedure to manipulate, cleanse and import data into Contact staging table  | [Contact Stored Procedure.sql](https://github.com/cbmurph510/Data-Migration/blob/master/dbo.Contact.sql)  |
| Post go live Contact record update | [Maximizer Update Stored Procedure.sql](https://github.com/cbmurph510/Data-Migration/blob/master/dbo.Maximizer_Update.sql)  |

<BR/>


### Data Integrity Scripts and Stored Procedures

Introduction: 
The files below are examples of Data Integrity related SQL scripts and stored procedures I have authored and they represent the following:

**Data Integrity Stored Procedure used by SSRS report** - The report "Individuals with Unlinked Comapnies" was used by sales support staff to create lists of Individuals who were not linked to a Company so they could evaluate and perform manual cleanup if necessary.

**Data Integrity Script** –Used to update a staging table with records from the Contacts table that had invalid data in the MTB_PendingAccountName field.  The records in the staging table were then processed by an in-house .net import utility and make the necessary updates. 

**Project Samples:**

| Purpose          | File Link |
| -------------------    | ------------- |
| SSRS report Stored Procedure | [mtb_rpt_IndivUnlinkedCompanies.sql](https://github.com/cbmurph510/DIG/blob/master/dbo.mtb_rpt_IndivUnlinkedCompanies.sql)                 |
| Data Integrity Script |  [Pending Account Cleanup Queries.sql](https://github.com/cbmurph510/DIG/blob/master/Pending%20Acct%20Cleanup%20Queries.sql)               |

<BR/>

### Data Retrieval Script

Introduction: 
This is an example of one of the data retrieval scripts I have authored that returns records that meet specific criteria to send bulk email communications to target audiences. 

| Purpose          | File Link |
| -------------------    | ------------- |
| Product Release Queries | [Release Queries.sql](https://github.com/cbmurph510/DIG/blob/master/Release%20Queries.sql)          

<BR/>

### Data Update Scripts

Introduction: 
This is an example of a few of the data update scripts and stored procedures I have written that make various record updates. 

| Purpose          | File Link |
| -------------------    | ------------- |
| Annual Recurring Opportunities | [AnnualRecurringOpportunities_Import.sql](https://github.com/cbmurph510/Data-Updates/blob/master/AnnualRecurringOpportunities_Import.sql)   
| Update Subscription Status | [mtb_UpdSubscriptionStatusToReady.sql](https://github.com/cbmurph510/Data-Updates/blob/master/mtb_UpdSubscriptionStatusToReady.sql) 
| Free Upgrade SUL   | [FreeUpgradeSUL_Import.sql](https://github.com/cbmurph510/Data-Updates/blob/master/FreeUpgradeSUL_Import.sql)   







### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
