# Welcome to MySQL Workbench Data Dictionary Plugin Generator!

This a plugin for MySQL Workbench Community Edition 6.x. This plugin allows you to generate an HTML data dictionary from the database schema selected in the application.

## Installation 

1. git pull the following repository
2. Open MySQL Workbench.
3. Select the option **Scripting → Install Plugin/Module**.
4. Browse to the repo directory and select the file datadict_script.py.
5. After the success message, click on **OK** and restart Mysql Workbench.

## Usage

1.  Open a database model file or create a new one (File → New Model).
2.  Go to  **Tools → Catalog → Generate HTML Data Dictionary** .

> Note that if your Model file has several schemas, you'll have to
> select the schema for which you want to generate the data dictionary
> first. To do this:

1.  Click on the  **MySQL Model**  tab.
2.  In the  **Physical Schemas**  section, click on the tab of a schema.
3.  Generate the data dictionary.

> After this, an HTML data dictionary will be generated and displayed in
> your Web browser.
