# WERADIATE DATA TEMPLATE Add-on Usage:
This page helps you to get understand how to work with the WeRadiate Google Sheet Add-on.
`Add-ons -> WERADIATE DATA TEMPLATE -> Menus...`

## MANAGE CONNECTIONS
Manage Connections menu helps the user to login to the server to communicate and fetch login.

<img src="https://github.com/mukeshbharath/Add-on-test/blob/master/menu-mang-conn.png" width=75% height=75%>

1. Now click on the first option `Manage Connections`, this will pop-up a `Login` window.
2. In `Login` window, the user needs to provide the credentials for accessing the server (`Server URL`, `Username` & `Password`) from which the data has to be fetched.

<img src="https://github.com/mukeshbharath/Add-on-test/blob/master/mang-conn-login.png" width=40% height=25%>

3. For easy access the credentials have been pre-filled and just need to press `Submit` to establish the connection.
4. This will establish a connection to the server to which we need to communicate.

<img src="https://github.com/mukeshbharath/Add-on-test/blob/master/mang-conn-established.png" width=40% height=25%>

## GET DATA
1. Once you see the `Connection Established` pop-up, move on to the next menu option `Get-Data` in the WeRadiate Add-on.

<img src="https://github.com/mukeshbharath/Add-on-test/blob/master/menu-get-data.png" width=75% height=75%>

2. This menu helps to fetch the data from the server for a desired date range with various aggregations in user convenient templates.
3. `Get-Data` window provides various drop down fields for `Client`, `From Date`, `To Date`, `Select Aggregator`, `Select Template`, `Ref.Line Value (Temp)` that user has to fill with options/values.
  * Date pickers are provided for selecting `From Date` & `To Date`.

<img src="https://github.com/mukeshbharath/Add-on-test/blob/master/get-data-date.png" width=25% height=25%>

  * The Aggreagation for the data per day has to be choosed from `Select Aggregate` dropdown (`Max`/`Min`/`Mean`/`Median`).

<img src="https://github.com/mukeshbharath/Add-on-test/blob/master/get-data-aggr.png" width=25% height=25%>

  * The Template with which the user likes to view the Data has to be selected from the Select Template dropdow (from `DEC Report`/`Model1`/`Model2`/`Model3`)

<img src="https://github.com/mukeshbharath/Add-on-test/blob/master/get-data-template.png" width=25% height=25%>

  * The `Get Data` also offers user to select the `Ref. Line Value (Temp)` to provide Reference Line for Temperature which will be added as threshold in Charts for reference.

<img src="https://github.com/mukeshbharath/Add-on-test/blob/master/get-data-refLine.png" width=25% height=25%>

  * Once all the fields are provided, press `Submit`.
4. You'll see the Add-on Loads the Selected template with Data populating under it.

<img src="https://github.com/mukeshbharath/Add-on-test/blob/master/get-data-loading.png" width=25% height=25%>

## TEMPLATES
The template model details used in this Add-on are as follows:
### DEC Report Template
  * DEC Report - Displays all location (sensor) data in a Sheet.

<img src="https://github.com/mukeshbharath/Add-on-test/blob/master/DEC-Report.png" width=75% height=75%>

  * DEC Chart - Plots a cumulative representation and Displays in another Sheet.

<img src="https://github.com/mukeshbharath/Add-on-test/blob/master/DEC-Report-chart.png" width=75% height=75%>

### Model1 Template
  * Model1 - Each Sheet has location (sensors) data and resp. charts plotted, and N sheets for N number of locations available in the client.

### Model 2 Template
  * Model2 - First Sheet displays all the location (sensor) data and chart representation for each sensor (Site specific) provided in separate sheets and cumulative representation of all sensors in a sheet.

### Model 3 Template
  * Model3 - Displays sensor data and it chart representation in a sheet (Piles specific), N sheets for N Piles available in the Site.
  
<img src="https://github.com/mukeshbharath/Add-on-test/blob/master/model3-template.png" width=75% height=75%>
  
## REFRESH
On clicking `Refresh` menu, all the sheets in current workbook will be deleted and inserts a new active worksheet.

<img src="https://github.com/mukeshbharath/Add-on-test/blob/master/menu-refresh.png" width=75% height=75%>

It is designed to pop up an alert message to save the Workbook before attempting to refresh the sheets.

<img src="https://github.com/mukeshbharath/Add-on-test/blob/master/refresh-alert.png" width=25% height=25%>

## ABOUT
`About` menu displays the Product Name, its Version and Website Information.

<img src="https://github.com/mukeshbharath/Add-on-test/blob/master/about.png" width=25% height=25%>

