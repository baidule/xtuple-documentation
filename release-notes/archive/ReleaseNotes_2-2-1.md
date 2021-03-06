Release Notes
xTuple Applications
OpenMFG - PostBooks
Version 2.2.1
September 21, 2007
----------------------------------

The 2.2.1 release is a bug-fix release incorporating feedback from 
the xTuple community.

	
----------------------------------

The following features and bug fixes have been added to the applications 
since the release of version 2.2.0:

New Features:

* [System] Moved API views to separate schema

Bug Fixes:

* [P/D] Fixed Single Level BOM Report detail which was empty if showing 
future components 
* [Products] Fixed issue preventing copy of BOMs for Planning Items
* [Products] Fixed loophole allowing access to cost information via Item 
Availability Workbench without proper privileges 
* [Products] Fixed inability to delete Items in PostBooks database
* [Inventory] Enabled default Ship Via for Transit Warehouses to 
populate Transfer Order header
* [Inventory] Fixed issue with time stamp not writing properly to recv 
table
* [Inventory] Made Cost Categories a requirement for Transit Warehouses
* [Inventory] Fixed issue with default Transit Warehouse not being set 
properly in demo.backup
* [Inventory] Fixed issue with Order fields not being cleared properly 
when toggling between Order types on the Issue Stock to Shipping screen
* [Inventory] Fixed inability to delete Item Sites in PostBooks database
* [Inventory] Fixed issue with ITEM SITE button on Item master not passing 
Item Id properly if Item Site wasn't created on initial save
* [Inventory] Fixed problem leading to error message when printing the 
Packing List Batch
* [M/S] Fixed issue with Ordered and Received columns printing blank in 
Running Availability report
* [Schedule] Fixed cause of error received when attempting to view W/O 
Detail for a planned W/O from Running Availability screen
* [Purchase] Fixed Mac-Panther-only issue where permissions to view 
Purchase Requests were being lost after printing a report
* [Purchase] Fixed Copy Purchase Order window which was calculating UOM 
conversion incorrectly in the display
* [W/O] Fixed issue with "View W/O Material Requirements" option not 
working from right-click menu on Open Work Orders with Parent Sales Orders 
screen
* [Manufacture] Enabled Post Production screen to remain open after POST 
button is selected
* [Manufacture] Added missing sort parameters to Work Order Schedule by 
Work Center report in Neo menu
* [Manufacture] Fixed issue preventing manual entry of W/O numbers in the 
Production Time Clock by Work Order report
* [Sales] Re-enabled entry of negative values in the Sales Order header's 
Misc. Distribution field
* [Sales] Enabled api.customer to allow the updating of Customer numbers
* [Sales] Fixed inappropriate error message related to CRM Account number 
conflicts when closing the Customer master
* [Sales] Added error checking to api.customer to prevent deletion of 
Customers if Ship-To Address exists
* [Sales] Enabled api.customer to use default currency on insert
* [Sales] Changed field alias "default" on api.custshipto because term is 
reserved
* [Sales] Fixed erroneous display of 100% Discount on Sales Order item 
screen
* [Sales] Made Characteristic search not case-sensitive
* [Sales] Added better error-checking when converting Quotes having line 
items with no Item Site
* [Sales] Fixed issue where Quotes having line items with no Item Site 
were not appearing on the Quotes master list
* [Sales] Prevented deletion of Customers having existing Quotes
* [Sales] Broke link between MaintainCustomerMasters privilege and ability 
to post Invoices
* [Sales] Fixed errors received when attempting to view Sales Orders
* [Sales] Recast text fields on Customer-related views as varchar
* [Sales] Fixed error received when "Add to Packing List Batch" option 
selected on Backlog By Customer display
* [A/P] Fixed Check Register to handle voided Check amounts properly
* [A/R] Prevented deletion of Customers having existing Invoices
* [G/L] Re-enabled entry of negative values in the Bank Reconciliation 
screen
* [System] Removed redundant metric functions getMetric and 
getMetricBoolean

PLEASE NOTE: The application-based help files for 2.2 will be 
available shortly.


