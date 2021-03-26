# Tableau-and-R-for-Analytics-

Laura's Tableau Public Profile: https://public.tableau.com/profile/laura.cline#!/?newProfile=&activeTab=0 

Connect Tableau to RStudio:

1. Install the Rserve package on RStudio
2. On Tableau Desktop, select "Help" > "Settings and Performance" > "Manage Analytics Extension Connection"
3. In the "Select Analytics Extension" drop-down list, select "Rserve" 
4. Enter your credentials

Port 6311 is the default port for plaintext Rserve servers.
Port 4912 is the default port for SSL-encrypted Rserve servers.
If the server requires credentials, enter a Username and Password.
If the server uses SSL encryption, select the Require SSL check box, then click the Custom configuration file link to specify a certificate for the connection.
