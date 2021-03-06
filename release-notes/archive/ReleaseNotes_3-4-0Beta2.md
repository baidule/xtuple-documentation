Release Notes
xTuple ERP
PostBooks, Standard, and Manufacturing Editions
Version 3.4.0Beta2
November 18, 2009
----------------------------------

This is the second Beta release in the 3.4.0 cycle. Thanks
to all for your feedback on the first Beta. This release builds
on the testing results from the first Beta and also includes
a number of other bug fixes.

Relatively few new features have been included. However, of special
note is the new "Enforce Valid Country Names" option we've added
to the CRM configuration screen. When selected, this option requires
all country names in the database to conform to standard ISO naming
conventions. While this feature is optional, we are also issuing
a free packaged utility called "fixCountry.gz" to help users clean
up any non-conforming country names in their data. Like any other
package, the fixCountry.gz utility can be loaded using the Updater.
If you are interested in this new functionality, please test it out
in this second Beta--and send us any feedback you may have.

NOTE: If you are upgrading your database to version 3.4.0Beta2, 
you must use the new Updater, version 2.2.0Beta. As always, please 
do not use beta software in a production environment. If you're a 
subscriber to our XTN service (www.xtuple.com/xtn), we would be 
happy to help you set up a "sandbox" copy of your database to 
test.

----------------------------------

The following features and bug fixes have been added to the
applications since the first 3.4.0 Beta. Additional detail for each
item listed below may be found on our community website
(www.xtuple.org). Simply go to the Issue Tracker and select the
"Changelog" option.


New Features:

* [Architectural] Make free-floating mode the default for Windows,
Linux, and Mac
* [Manufacture] Add ability to backdate production posting
* [Sales] State and country entry and validation
* [Sales] Add a status column or bar that shows the status of the
sales order
* [System] Standardized state abbreviations in drop-down lists
* [System] Add a hide capability to system scripts

Bug Fixes:

* [Accounting] The Invoice Register total is always displayed
zero
* [Accounting] Tax amount in the Recurring Invoices is double the
amount in original invoice
* [Accounting] Can't edit posted invoice (for recurring invoices)
* [Accounting] Single Level BOM print out displays the wrong UOM
* [Accounting] Selecting to create a Sales order in Standard
edition displays error
* [Accounting] Error posting $0 invoice when accounting config
enabled
* [Accounting] PO Status on Voucher screen is Open when received
qty > ord qty
* [Accounting] Invoice posting error column _r.item_id does not
exist
* [Accounting] Journal series in List unposted G/L series do not
disappear on post
* [Accounting] Unreleased transaction lock in group.cpp can lead
to loss of data
* [Accounting] SQL error written to database log but not shown to
user after saving first non-base currency
* [Accounting] Tax code rates window saves percentages as 0 when
creating and when editing
* [Accounting] Failed stored procedure when posting cash receipt
* [Accounting] Error applying ar credit memo
* [Accounting] Expense Category master list report breaks for some
Chart of Accounts schemes
* [Accounting] Deleting Invoice does not reopen Sales Order
* [All] Indented items on XTreeWidget's not reselected after
refresh
* [Architectural] State list not populating correctly on address
cluster
* [Architectural] Group packages display not complete
* [CRM] Country combo box should not be write-able
* [CRM] Selecting to view a saved Alarm doesn't populate the
details
* [CRM] Incidents with closed To-do lists do not print
* [CRM] Priority list not initialized on To-Do page
* [CRM] Assigned-to field not filtering inactive users
* [CRM] Prospect can share number with customer
* [CRM] CRM search window performance slow
* [Inventory] Disable RETURN STOCK button if not available
* [Inventory] Selecting to print the list of TO, prints the closed
orders
* [Inventory] Selecting to ship sales order displays an error
message
* [Inventory] Unable to post Transformations for lot/serial/
location controlled items
* [Inventory] Selecting to update item controls generates DB log
error
* [Inventory] Selecting to delete an Item Site displays an error
message
* [Inventory] createLotSerial::sAssign() SQL SELECT statement
error
* [Inventory] Item WB shows an error when calling a reference
type item
* [Inventory] Item site save blocked in PostBooks
* [Inventory] Can not view P/O through Running Availability
* [Inventory] Typo in function "invhisttrig"
* [Manufacture] WO: Post Production gives "Set is not defined"
 error => Cannot close work order
* [Manufacture] Unable to �clock in� to Work Order
* [Manufacture] Post Misc. production is not functional
* [Manufacture] Print report of Work Order Operations generates
DB log error
* [Manufacture] Unable to view Job Costing for work order
* [Manufacture] Print report of Breeder Distribution Variance
generates DB log error
* [Manufacture] dspWoBufferStatusByParameterList.ui: Print
generates error
* [Manufacture] dspWoOperationBufrStsByWorkCenter.ui: Querying
displays error
* [Manufacture] Viewing of material requirements for Work
Order generates a DB log error
* [Manufacture] Rescheduling Work Order is not functional
* [Manufacture] Closing Work Order is not functional
* [Manufacture] Selecting to implode a work order displays a
error message
* [Manufacture] dspWoEffortByUser.ui console error message
* [Manufacture] laborRates.ui: button problems
* [Manufacture] plannedSchedules.ui: print and edit button
problems
* [Manufacture] dspWoEffortByWorkOrder.ui: button problems
* [Manufacture] printWoRouting.ui Printing results in DB log
error
* [Manufacture] Attempting to add operation to item results
in DB log
* [Manufacture] Post Misc Production does not use
Materialssue conversion
* [Manufacture] Work order can be created for phantom item
types
* [Manufacture] Error on create WO, set due date
* [Products] No "Bill of Operations" observed
* [Products] Ref item allowed on w/o mat'ls but not bom
* [Products] Can create a BOO for a kit and phantom type
item
* [Products] View Costing Detail displays an error message
* [Products] Print report of Breeder Bill Of Materials
generates a DB log error
* [Products] Update Actual Cost by Class Code results in
error
* [Products] Shiporder.cpp at 198 Nothing to do as the
value to post to G/L is 0
* [Products] The "Indented Where Used" form has reversed
logic for the "show expired" check box
* [Products] Can not create new BOO item
* [Products] Transform into a phantom is allowed
* [Products] Creating a new bom item fails with not-null
constraint violation
* [Purchase] Voucher screen does not show vendor name
* [Purchase] Close/delete button next to purchase order
line items list deletes the line item without warning
* [Purchase] It is possible to post an unbalanced voucher
* [Purchase] Printing a PO without MaintainPurchaseOrder
Privilege Give Error
* [Purchase] Problem with right-click and view voucher on
vendors WB
* [Purchase] Tab to next field skips unit price
* [Purchase] Exiting voucher screen without saving
generates orphan lines
* [Reports] Issue with the stock Packing List Form in
relation to using it with Transfer Orders
* [Reports] Varying print quality when printing an invoice
* [Sales] View privileges allow user to upload new documents/
files in Sales Order
* [Sales] Delete SO gives an error, when customer is
associated with a default tax zone
* [Sales] Selecting to create a Sales Order with Kit item
type gives error
* [Sales] Selecting to edit a sales order generates a DB
log error
* [Sales] Canceled line items on SO still taken in to
reflect scheduled date on List Open Sales Order screen
* [Sales] Post receipts button on Return Authorization-Line
Item tab doesn't work
* [Sales] Cannot view history of in-active item
* [Sales] Default ship to does not populate on credit memo
screen
* [Sales] Performance Loss Issue: The Customer Workbench
takes 14 to 15 Seconds to open
* [Sales] Ship-to info does not populate by entering
Ship-to # in S/O header screen
* [Schedule] dspPlannedRevenuExpensesbyPlannerCode.UI:
Closing the Planned Revenue screen displays a blank screen
* [Schedule] Unable to save production plan of Cumulative
MPS schedule type
* [Schedule] dspMPSdetail.ui: Item Sites are not displayed
with the selection of a particular warehouse
* [Schedule] dspTimePhasedLoadByWorkCenter.ui:Querying
displays error
* [System] The application edition doesn't change upon
loading the package
* [System] RA "Automatic,Use RA #'s, Allow Override" number
generation display an error message
* [System] Selecting to view serial columns display an
error message
* [System] Cannot enter warehouse in invoiceline view
* [System] Horiz Space gets save as Vertical Space in
embedded designe
* [System] Screen builder misrepresents horizontal spacers

----------------------------------
Release Notes
xTuple ERP
PostBooks, Standard, and Manufacturing Editions
Version 3.4.0Beta
October 27, 2009
----------------------------------

This is the Beta release of version 3.4.0--and also the first
release in this shortened release cycle. Implementing the
Manufacturing Edition as a package is the major focus of this
release. And because of that we are especially eager to hear
feedback from beta testers running the Manufacturing Edition.
Here's an overview of new features in this release:

Manufacturing Edition functionality as scripted Package
  * Full spec: http://www.xtuple.org/issuetracker/view.php?id=8333

Script Debugger
  * Full spec: http://www.xtuple.org/issuetracker/view.php?id=8189

CRM
  * Multiple enhancements to Opportunities

NOTE: If you are upgrading your database to version 3.4.0Beta, you
must use the new Updater, version 2.2.0Beta.

----------------------------------

The following features and bug fixes have been added to the
applications since the release of 3.3.1. Additional detail for each
item listed below may be found on our community website
(www.xtuple.org). Simply go to the Issue Tracker and select the
"Changelog" option.


New Features:

* [All] Convert xTuple Manufacturing Edition into a package
* [Architectural] Add a boolean property to the screen widget that
designates document locking
* [CRM] Link Quotes and Sales Orders to Opportunities
* [CRM] Tracking Changes in Opportunities
* [CRM] Need to be able to search Opportunities by Name and CRM
Account
* [CRM] Inactive Opportunities
* [CRM] Additional filters on Opportunities
* [Sales] Add documents widget to Sales Order and Quote
* [System] Script debugger
* [System] Create views for budget and budget entry
* [System] Expose ability to communicate with web services to
scripting
* [System] Add Q_INVOKABLE functions to vendorsgroup widget


Bug Fixes:

* [Accounting] Rescan does not correctly update scripted menu
items
* [Accounting] Misc. Check doesn't clear CM amount
* [Accounting] Deleting a multi-job sales order only deletes
the first job item
* [Accounting] Changing quantities of materials on work orders
does not honor the fractional flag of the materia
* [Accounting] When typing JE on the G/L series screen user
only can jump to next field with tab key
* [Accounting] Item Allocations display uses work order due
date when it should use material requirement due date
* [Accounting] indented BOM list description only shows
item_descrip1 column
* [Accounting] It is possible to change currency on bank
account
* [Accounting] Transaction pairs separated on gl trans printed
report
* [Accounting] Tax not reversed when voiding vouche
* [Accounting] Voiding voucher does not undo misc. tax
distribution
* [Accounting] Incomplete vohead record precludes subsequent
processing of voucher
* [Accounting] Can not load more than one UI into a screen
with scripting
* [Architectural] Scripts can not access the user name in the
username cluster
* [Architectural] Flip Files and Images button on Documents
Widget
* [Architectural] Screens should specify "Grade" instead of
"Order" and use grade logic
* [Architectural] XComboBox updates mapper model after
newID(int) signal
* [CRM] Auto Populate CRM Acct in To-Do created through an
Oppty
* [Inventory] Cannot edit item site when created with utility
* [Inventory] Releasing TO from Line Item closes lin
* [Inventory] Running availability is much slower in version
3.3.0RC2 than 3.2.2
* [Inventory] Year End/Inventory count posting dates
* [Inventory] Site window does not let you set up tax zone;
still uses tax authority
* [Inventory] Receiving TO line items with not enough stock
in transit site gives an error
* [Manufacture] Enter does not save on Work Order screen
* [Manufacture] Comment types on Close Work Order not
filtered
* [Manufacture] Error While querying Production Time Clock
by Work Order report
* [Products] Viewing cost detail fails with error "rev" does
not exist
* [Purchase] Open/close PO line items do not show on "by
vendor" report
* [Purchase] Rescheduling purchase order accepts blank dates
* [Purchase] Item Source screen: Vendor ellipsis pulls up a
list and not a search window
* [Purchase] Print Purchase Orders By Agent screen not
working
* [Reports] Quote Template total calculation omits Misc.
Charges
* [Reports] PO rounding problem
* [Sales] Incorrect data fetched in soheadtrigger
* [Sales] 3.3 Sales analysis report issues
* [Sales] Credit memo line item UOM changes back to default
when editing CM line
* [Sales] Create invoice is much slower than previous version
* [Sales] Voided Check to Customer creates incorrect AR
document
* [Schedule] MRP not creating order for demand because of
existing PRs
* [Schedule] Selecting to release Planned orders generates
db log error
* [System] Privs problem for custom menu items
* [System] XCheckBox memory doesn't work in screen builder
environment
* [System] Vendor Cluster id() function stops script
* [System] Problem importing an invoice with no Order Number
* [System] lupdate gives errors when processing scripts that
use #include
* [System] Work order explosion ignores config option
