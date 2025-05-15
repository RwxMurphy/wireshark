# **Wireshark Profiles**


## What is a Wireshark profile?
A wireshark profile is a collection of predefined settings. The current profile in
use can be found in the *bottom right corner*.


## How to create a custom profile.
Right click the profile section in the bottom right corner and enter the name of 
the new profile.


## How to add new columns.
In the main menu go to edit => columns 
select the add new column button give it a name and select the info to display. Note
that you can drag the new column to position it where you would like.


## Adjusting the time display format.
You can display time in different levels accuracy such as nanoseconds miliseconds 
etc. 
To adjust go to View => time display format

*Alternative method* 
You can also add columns for the packet details view window by
right clicking on the desired info and selecting apply as column option. Note that
this method will only display the info for the specific protocol you selected.

*Applying info to other protocols* 
To apply the info to other fields you will need to get the field name. To get the
field name select the packet go the details view and select the field you want, the 
name will be displayed at the bottom of the window. Now right click on the column
and select edit column and add name to the filed textbox use an 'or' statement
to display values for multiple protocols.

EXAMPLE:
udp.srcport or tcp.srcport
