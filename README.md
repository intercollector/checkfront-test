# checkfront-excercise-1
Checkfront Assignment for Dev Team Lead role

Two excercises were given, this is the first excercise.

Log Viewer 
----------
LogViewer.html
The Log Viewer exercise goal was to display an HTML table with data from a json file. While the source of the file is not specificied, in this answer I simply embedded the data into the html file. If the source of the file is on a server, a simple AJAX request could be used to read the file.

The table is rendered using the DataTables library here:
https://datatables.net/
This library provides very common functions such as sorting, pagination and search to html tables, as well as a large amount of interactivity through callbacks. It's only dependency is JQuery.

To test, simply load the html file into a web browser (internet connectivity needed in order to load libraries from their CDNs).


