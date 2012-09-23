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

##Suggestions

Some suggestions for improving or building on this script:

* Build this into a Moodle or Wordpress plug-in so that tables can be embedded easily into language class exercises or blogs.
* Build an independent database and hosting component around this script and others so that users don't need to save the resulting table.
* Tweak: Change the column and row mouseover so that instead of reversing the display of cells, turns them all on or off (currently, if a cell has been revealed, it will be hidden on header mouseover)
* Tweak: Make the tables display nicely on very small browsers such as phones (most table already display fine on larger tablets)

##Note
The script, uses a hosted version of Jquery, and thus requires an internet connection. You can create an entirely offline version of this script if you modify it to load a local copy of Jquery. 

##Live version:
[http://huginn.net/scripts/table-review] (http://huginn.net/scripts/table-review)

*Example data for a table:*
    Irregular Verbs,Essere,Avere,Stare,Andare,Fare,Bere,Uscire,Giocare
    Io,sono,ho,sto,vado,faccio,bevo,esco,gioco
    Tu,sei,hai,stai,vai,fai,bevi,esci,giochi
    Lui/Lei,è,ha,sta,va,fa,beve,esce,gioca
    Noi,siamo,abbiamo,stiamo,andiamo,facciamo,beviamo,usciamo,giochiamo
    Voi,siete,avete,state,andate,fate,bevete,uscite,giocate
    Loro,sono,hanno,stanno,vanno,fanno,bevono,escono,giocano

(c) [Konrad M. Lawson] (http://muninn.net/). MIT License