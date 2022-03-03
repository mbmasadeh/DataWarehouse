## Create a data warehouse from scratch

In this topic, we will learn how to create a data warehouse from scratch with live demo.

# understanding the business and the diagram
The live demo is to create a data warehouse thats collection a data from several system in a university.
These system are oracle database. Thus, we need to create 4 server as following:

The first server is "Staging", we need to move the required data to this server without any updates or transformation. the aim of moving the data to a staging server not directly to the warehouse, is to make all the "Transformation, Normalaization, Load headeche on the staging servers away of the operational system.
The staging server can accept all data resourses.

The second server is data warehouse which is the core of our project
#Prerequisites
We will create data warehouse using microsoft tools

A visual studio 2019 (Developer edition) can be run for free, but there is no techniqual support.
Before installating V.S 2019, make sure to check the option (Data storage and processing).
If you already installed V.S 2019, you can modify your installation with (Data storage and processing) option.
Click download then install and wait till finished.

Sfter V.S 2019 installation is finished, now lets install SQL server
The required version is 2019, developer edition.


Go to this Url "https://docs.microsoft.com/en-us/sql/ssdt/download-sql-server-data-tools-ssdt?view=sql-server-ver15"

You can use the [editor on GitHub](https://github.com/mbmasadeh/DataWarehouse/edit/main/docs/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

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

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/mbmasadeh/DataWarehouse/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
