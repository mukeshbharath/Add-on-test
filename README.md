# WERADIATE DATA TEMPLATE USAGE:
## MANAGE CONNECTIONS
Manage Connections menu helps the user to login to the server to communicate and fetch login.
<img src="https://github.com/mukeshbharath/Add-on-test/blob/master/menu-mang-conn.png" width=75% height=75%>
1. Now click on the first option "Manage Connections", this will pop-up a "Login" window.
2. In "Login" window, the user needs to provide the credentials for accessing the server from which the data has to be fetched.
<img src="https://github.com/mukeshbharath/Add-on-test/blob/master/mang-conn-login.png" width=75% height=75%>
3. For easy access the credentials have been pre-filled and just need to press "Submit" to establish the connection.
4. This will establish a connection to the server to which we need to communicate.
<img src="https://github.com/mukeshbharath/Add-on-test/blob/master/mang-conn-established.png" width=75% height=75%>
5. Once you see the "Connection Established" pop-up, move on to the next menu option "Get-Data" in the WeRadiate Add-on.
6. This menu helps to fetch the data from the server for a desired date range with various aggregations in user convenient templates.
7. Select the drop down fields of "Get-Data" window with the option/values of your choice, and press "Submit"
8. You'll see the appropriate Data populating under the selected template.
9. The template model details are as follows:
	(i) DEC report - Displays all location (sensor) data in a Sheet and Plots a cumulative representation in another Sheet
	(ii) Model1 - Each Sheet has location (sensors) data and resp. charts plotted, and N sheets for N number of locations available in the client.
	(iii) Model2 - First Sheet displays all the location (sensor) data and chart representation for each sensor (Site specific) provided in separate sheets and cumulative representation of all sensors in a sheet.
	(iv) Model3 - Displays sensor data and it chart representation in a sheet (Piles specific), N sheets for N Piles available in the Site
10. On clicking "Refresh" menu, all the sheets in current workbook will be deleted and inserts a new active worksheet.
11. It is designed to pop up an alert message to save the Workbook before attempting to delete the sheets.
