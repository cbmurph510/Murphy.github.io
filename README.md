## Murphy says "Welcome to GitHub Pages!"
CRM Data Migration Project

Project entailed migrating data from Onyx CRM databases to MS Dynamics CRM databases while doing data manipulation and cleanup. 


You can use the [editor on GitHub](https://github.com/cbmurph510/Murphy.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

(https://github.com/cbmurph510/Murphy_SQL_Portfolio/blob/master/dbo.Contact_table.sql)


### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

USE [OnyxToMSCRM_STAGE]
3	GO
4	
5	SET ANSI_NULLS ON
6	GO
7	
8	SET QUOTED_IDENTIFIER ON
9	GO
10	IF  EXISTS (SELECT * FROM sys.objects WHERE OBJECT_ID = OBJECT_ID(N'dbo.Contact') AND type in (N'U'))
11	BEGIN
12		DROP TABLE dbo.Contact
13	END
14	GO
15	
16	CREATE TABLE [dbo].[Contact]
17	(
18		[ContactId] [uniqueidentifier] NOT NULL DEFAULT(NEWID()),
19		[DefaultPriceLevelId] [uniqueidentifier] NULL,
20		[CustomerSizeCode] [int] NULL,

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/cbmurph510/Murphy.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
