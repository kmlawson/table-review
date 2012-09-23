# Table Review Script

## Introduction
This script helps you review a table of information. It is useful for studying grammar rules when learning a new language or reviewing other reference tables of information that contain closely related materials. Rather than reviewing each component fact in a separate flashcard, table review allows you to see facts in relation to others they are related to. 

##Creating a Review Table
Load the script and enter your table into the "Table Contents" field, along with an optional title for the table. Separate the columns of the table with a delimiter, which by default is a comma. For example:
    first column, second column, third column

The options for the table script include:

* Column delimiter - The default is a comma, but if you have data which already uses a comma, you may wish to use another character to indicate the separation of columns.
* First row is a header - When checked, the first row is assumed to be a header, displayed at all times and not part of the information to be reviewed.
* Leave first column visible - When checked, the first column is assumed to be a header, displayed at all times and not part of the information to be reviewed.
* Reveal column or row when over header - When checked, moving the mouse over (or tapping on a mobile device) on the header row or header column will reveal the targeted row or column.
* Only reveal on click - By default, moving the mouse over a cell will reveal the contents of that cell. When this is checked, only clicking (or tapping) on a cell will reveal the contents of the cell

##Reviewing and Saving a Table
After creating a table for review, all information in the table will be hidden unless the mouse is moved over a cell (unless "only reveal on click" has been checked), when the contents is revealed. Clicking, or tapping on a cell will leave the contents visible. A button below the table allows you to reveal all cells or hide all cells. 

If you click "Version to Save" the HTML and Javascript associated with the newly created table will be loaded in a way that allows you to File->Save the table as an HTML file which you can load whenever you wish to review the table again. You can also incorporate the resulting HTML file into your own website. 

##Note
The script, uses a hosted version of Jquery, and thus requires an internet connection. You can create an entirely offline version of this script if you modify it to load a local copy of Jquery. 

##Live version:
[http://huginn.net/scripts/table-review] (http://huginn.net/scripts/table-review)

(c) [Konrad M. Lawson] (http://muninn.net/). MIT License