Lync Tools - Get Lync Objects and Policies (GUI)
================================================

Find all Lync enabled Objects (Users, Analogue Lines, Common Area Phones, RGS Workflows, Exchange UM Contacts, Trusted Applications and Conferencing Numbers) and the related policies (Dial Plan Policy, Voice Policy, Conference Policy, Client Version Policy, PIN Policy, External Access Policy, Archiving Policy, Location Policy, Mobility Policy) and display them in a table format. This includes: Users, Analogue Lines, Common Area Phones, RGS Workflows, Exchange UM Contacts, Trusted Applications and Conferencing Numbers (both with and without a Line URI assignment).

 Once again there are probably plenty of PowerShell scripts that will do this for you. This however is an application without the need for running PowerShell or Logging in to the Lync servers (provided the core components are installed on the PC the tool is run from). Its a good way to extend basic searching of name and number assignments without the need to run PowerShell scripts manually, or collect information from a saved output file. 

You can also click on the Column title's to sort the data according to what you are looking for. 

Also if you click on the top left hand box (to the left of the Name box) you will be initiating the "select all" function, simply paste this into an Excel spreadsheet and voila!
 

Using GLOP
Simply launch GLOP.exe (Get Lync Objects and Policies).


Click on Query Lync to populate the data display window (Lync Core Components required for this). 


Once Query is complete,  the Lync Objects will be visible in the window. If the Window has no data then the core components may be missing or your account may not have permissions to query Lync. (TIP Scroll to the right to see what the number is assigned to eg. user, Private Line, RGS Workflow etc.)
Use the search box to find any number or user


 

Requirements
Install the Lync core components of the PC that the tool will be run from. We like to nominate a Tool Server to run this on, also other items such as SEFAUtil.

The usual Lync RBAC permissions are required.
Revision History
Version 1.0 - Initial release