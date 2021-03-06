Release Notes
xTuple ERP
PostBooks, Standard, and Manufacturing Editions
Version 3.2.0Beta2
December 8, 2008
----------------------------------

This is the second Beta release of version 3.2.0. It is primarily
a bug fix release--and it is the last expected release before the
official 3.2.0 Release Candidate. Thanks to all in the community
who have contributed valuable testing, patches, and other
feedback so far. Please keep up your efforts during this Beta2
round. We want to hear from as many of you as possible!
----------------------------------

The following features and bug fixes have been added to the
applications since the release of version 3.2.0Beta. Additional
detail for each item listed below may be found on our community
website (www.xtuple.org). Simply go to the Issue Tracker and
select the Changelog option.

New Features:

* [CRM] Added graphical calendar for managing To-Do list to CRM
* [Manufacture] Added the ability to process disassembly Work
Orders
* [Manufacture] Added Work Order line notes
* [Products] Added Bill Of Materials line notes
* [Reports] Added Description, Notes and Reference Designator
columns to all usage variance reports
* [Sales] Added size/position memory for dialog screens
* [Sales] Enhanced Sales Credit Memo screen
* [Sales] Added baseline Sales Order acknowledgment form
* [System] Exposed XtreeWidget menu so it can be populated by
scripting


Bug Fixes:

* [Accounting] Fixed issue where ACH file had blank first line
if bank account is set to use default immediate origi
* [Accounting] Fixed bytea/int problem in ACH when printing
checks
* [Accounting] Fixed issue where declined Credit Card amount
was being posted to AR Invoice
* [Accounting] Fixed client crash when navigating windows
* [Accounting] Fixed issue preventing save of vendor record
with ACH check printing enabled
* [Accounting] Fixed Mac-only field sizing issue in Select
Payment screen
* [Accounting] Fixed issue in AP Aging where checks distributed
in the future were not being handled properly
* [Accounting] Fixed printing issue in A/R Aging report
* [Accounting] Fixed issue preventing creation of new EDI
Profile
* [Accounting] Fixed non-functional free-form sub accounts
option
* [Accounting] Hiding currency columns instead of balance
columns in single-currency environments
* [Accounting] Fixed issue leading to error when selecting
Vendor types in A/P Aging
* [Accounting] Fixed issue where PO Items marked "as Paid"
cannot have new Voucher Items posted for them
* [Accounting] Prevented creation of duplicate Voucher numbers
* [Accounting] Prevented duplicates in AP select table
* [Accounting] Made Vendor Type drop down list visible on
Select Payments screen
* [Accounting] Improved performance on Invoice selection
reprint screen
* [Accounting] Fixed issue where the ship goods function was
relieving Shipping Asset using average cost of inventory ATM,
not avg. cost of inventory + goods at shipping
* [Accounting] Added code to convert Cash Receipt amounts to
specified Bank Account's currency
* [Accounting] Tightened up handling of accounting period
dates
* [Accounting] Fix problem where manually supplied Contact
number was not being accepted Contact API view
* [Accounting] Fixed issue preventing the entering of foreign
currency credit limits when setting up foreign Customers
* [Batch Manager] Fixed issue where the Batch Manager was
showing completed jobs across all databases
* [Batch Manager] Changed default of "Reschedule every" option
to be OFF when users are rescheduling Batch Manager jobs
* [CRM] Fixed issue leading to error when changing a contact
which is already in use
* [CRM] Fixed issue leading to error when adding a Contact and
Address
* [CRM] Fixed screen display problems encountered when choosing
the "Workbench" option from Customer drop-down button on CRM
Account screen
* [CRM] Added search on contact cluster to prevent duplicates
when searching
* [CRM] Fixed Address check boxes so they remember selected
preferences
* [CRM] Removed duplicate menu icon for CRM Calendar
* [CRM] Fixed issue where Contact search was getting confused
* [CRM] Fixed broken link between CRM Account and Customer
Workbench
* [Inventory] Fixed issue where TOs could be closed before they
were received in full
* [Inventory] Fixes issue where canceled TO items were showing
up in Receiving screen
* [Inventory] Fixed result inconsistencies depending on where you
printed the Packing List from
* [Inventory] Fixed issue where transform transaction was creating
separate itemloc records for MLC items when there should only be
one
* [Inventory] Fixed issue with transformed quantity after being
displayed incorrectly
* [Inventory] Fixed issue with inventory not being thawed
completely
* [Inventory] Added back in report Time Phased Statistics by Item,
which shows data both numerically and graphically
* [Inventory] Fixed scheduled date display inconsistency when
copying TOs
* [Inventory] Allowed deactivation of Item Site having canceled
Sales Order items
* [Inventory] Fixed issue leading to error when printing the
Packing List Batch
* [Inventory] Fixed issue leading to error when posting Count
Tags
* [Manufacture] Fixed issue leading to error when selecting Work
Order characteristics
* [Manufacture] Fixed standard cost error when creating a PO for
an Item with multiple Item Sources for a single Vendor
* [Manufacture] Fixed Purge Closed Work Orders utility so it
functions properly
* [Products] Removed BOO button from Item master for Kit Items
* [Products] Fixed issue leading to error when removing/replacing
BOM Items
* [Products] Fixed issue with auto-generated Lot/Serial
registration numbers incrementing incorrectly
* [Products] Prevented creation of empty user-defined costing
element records
* [Products] Fixed issue where Costed Indented BOM was not
considering non-fractional quantities
* [Products] Fixed issue leading to error when querying Costed
Single Level BOM
* [Purchase] Fixed issue where PO status was showing as open when
more quantity was received than purchased
* [Sales] Fixed inconsistent field labeling on Price update
utility
* [Sales] Fixed issue leading to error when selecting "Use
Reservation Netting" option
* [Sales] Fixed issue preventing deletion of  Pricing Schedule
item for a freight class type
* [Sales] Fixed issue leading to error when creating Credit
Memos
* [Sales] Fixed issue where freight tax was not being added to
SO total tax
* [Sales] Fixed issue preventing deletion of freight lines from
Pricing Schedule
* [Sales] Fixed issue where editing a Pricing Schedule item for
freight reset the price to 0
* [Sales] Fixed issue preventing entry of fractional SO item
quantity if global UOM was also fractional
* [Sales] Fixed handling of Sales Order commissions after SO is
edited
* [Sales] Fixed missing descriptions in RMA Items list
* [Sales] Fixed issue with failed import on API view
customertypechar
* [Sales] Fixed issue preventing creation of replacement RMA
* [Sales] Fixed issue with zero Invoice items linking to
incorrect documents on AR History Tab on Customer Information
Workbench
* [Schedule] Fixed issue with Site Calendar Exceptions not
saving
* [Schedule] Fixed issue leading to error when creating a new
Production Plan
* [Schedule] Fixed display problems View W/O screen
* [System] Fixed issue preventing custom commands argument
setup within custom screen
* [System] Removed email option references in PostBooks client
* [System] Fixed issue leading to error when unchecking "Reserve
by location" option
* [System] Fixed issue leading to error when saving Exchange Rate
* [System] Fixed crash problem when creating a new Locale
* [System] Fixed issue leading to error when using CSVimp on
api.itemchar API view
* [System] Prevented creation of TO having source and destination
as same Site

----------------------------------
Release Notes
xTuple ERP
PostBooks, Standard, and Manufacturing Editions
Version 3.2.0Beta
November 24, 2008
----------------------------------

This is the Beta release of version 3.2.0. Thanks to all in the
community who have contributed valuable testing, patches and other
feedback during the Alpha cycle! Please keep up the effort on
this Beta. We are eager to hear from as many of you as possible.

Users may be especially interested to know about the following
new features introduced for the first time in this Beta:

* Accounts Payable Workbench
* Vendor Information Workbench
* Disassemly Work Orders
* CRM Alarms
* Send Email for Events
* Optional Report Query Storage in Database
* One-to-Many Item Sources per Item
* Support for Item Source Manufacturer Data

----------------------------------

The following features and bug fixes have been added to the
applications since the release of version 3.2.0Alpha. Additional
detail for each item listed below may be found on our community
website (www.xtuple.org). Simply go to the Issue Tracker and
select the Changelog option.

New Features:

* [Accounting] Created API views for A/R misc. Debit Memo and
misc. Credit Memo
* [Accounting] Cleaned up summarized G/L transactions display
* [Accounting] Enhanced Cash Receipt Edit List
* [Accounting] Added "amount" column to List Unposted Invoices
* [Accounting] Added G/L transaction date support to AR Aging
* [Accounting] Created Accounts Payable Workbench
* [CRM] Linked outgoing emails to Incidents
* [CRM] Added timed events for To-Do Assignees to the existing
event system
* [CRM] Added alarms for CRM To-Do with option to E-mail
* [CRM] Enhanced Project Tasks
* [Inventory] Added better support for activate/deactive of
Items
* [Inventory] Added PO Item balance at receiving
* [Inventory] Added in contributed code that can infer UPS
shipment number from order number
* [Manufacture] Added the ability to process disassembly Work
Orders
* [Manufacture] Streamlined post operations screen
* [Manufacture] Added Reference designator field on BOM
* [Manufacture] Added Work Order Line Item Notes
* [Products] Added Line Notes on Bill Of Materials
* [Products] Increased precision for Costing to six decimals
* [Purchase] Created Vendor Information Workbench
* [Purchase] Added the ability to include one to many Item
Sources per Vendor and Item
* [System] Added in new executeDbQuery(group, name, params)
script function to the script toolbox to load and execute report
queries from the database
* [System] Added user preference to have email sent when events
occur; only visible when Batch Manager enabled
* [System] Added Prev/Next button to Comment


Bug Fixes:

* [Accounting] Fixed issue where shipping goods was relieving
shipping asset account at standard cost for average cost Items
* [Accounting] Fixed issue where AR credit memos and Sales
credit memos could get mixed up
* [Accounting] Fixed issue where declined Credit Card amounts
were being posted to AR Invoice
* [Accounting] Added trigger to automatically reset initial
Accounting Period if new initial period is added or otherwise
changed
* [Accounting] Fixed issue with date conflicts on saved Bank
Reconciliations
* [Accounting] Made button labels on Item master more
intuitive
* [Accounting] Corrected calculation of receipt value of
average cost Items at vouchering
* [Accounting] Added total information to Cash Receipts
display
* [Accounting] Now using invoice cluster on schedule e-mail
delivery of invoices instead of list
* [CRM] Fixed issue where unused Addresses were not printing
when Address master list was printed
* [CRM] Fixed error received with checking "Show incidents"
option on To-Do List
* [CRM] Fixed error received when opening To-Do List
* [Inventory] Fixed issue where RECEIVE ALL function was
receiving closed PO items
* [Inventory] Fixed PostBooks error received when viewing or
editing Item Site records
* [Inventory] Fixed error received when selecting to edit
Sales Order related to backlog item
* [Inventory] Fixed issue where scheduled date was being
displayed under ordered date on Transfer Order
* [Inventory] Fixed issue with "Order by Pack date" report
printing empty from Summarized Backlog by Site screen
* [Inventory] Fixed issue where "View Order Item" option on
List Receipts screen not working for Return Authorizations
* [Inventory] Fixed issue with "Show Reorder Exceptions"
option printing empty from Inventory Availability by Item
screen
* [Inventory] Fixed issue with Loc/Lot/Serial information
not showing in Item History in Item Workbench
* [Inventory] Fixed issue preventing receipt of RA items
* [Inventory] Fixed issue preventing save of new Site
Locations
* [Inventory] Fixed issue preventing receipt of Transfer
Order Items
* [Manufacture] Fixed issue where Phantom Items themselves
were being added as Material Requirements
* [Manufacture] Fixed issue where Running Availability report
was not including Job Type Items in printed output
* [Manufacture] Fixed issue where changing a Work Order item
qty. to zero created an error for material usage variance
* [Manufacture] Added P/O and P/R menu options Inventory
Availability by Work Order screen
* [Manufacture] Fixed issue with qty. ordered not showing on
Post Production screen
* [Products] Fixed Linux crash when adding new Characteristic
to Item master
* [Products] Fixed scale of file browse button size on Item
master screen
* [Products] Fixed issue leading to error when querying
Capacity UOMs screen
* [Products] Fixed issue leading to error when deleting new
Items
* [Products] Fixed issue where Site drop down list was disabled
in BOMs without component Item Site
* [Products] Fixed issue where creating a new BOM revision led
to loss of image links in previous revision
* [Products] Changed Item Site to use control method = None for
Reference Items
* [Purchase] Fixed issue leading to error at receiving for
Purchase Orders having alphanumeric PO Numbers
* [Purchase] Fixed issue leading to error when copying a Purchase
Order
* [Purchase] Fixed issue requiring encryption key when saving
Vendor records
* [Purchase] Added clearer UOM information to Purchase Order and
Purchase Order Item screens
* [Purchase] Revised Purchase Order status to display as
"Received" if qty. is over-received
* [Purchase] Fixed Receipts by Vendor report to display data
* [Purchase] Added email html option to deliver P/O by email
screen
* [Sales] Fixed the AR History tab on the Customer Information
Workbench, which was not totaling correctly
* [Sales] Fixed issue where Alternate COGS information was not
being transferred to new Sales Order Line Items
* [Sales] Fixed issue where selecting to view a Prospect from a
search result screen displayed empty page
* [Sales] Fixed issue leading to error when printing the
Summarized Backlog by Site report
* [Sales] Removed -1 default for Ship-to Zones in custshipto view
* [Schedule] Fixed crash received when selecting "View Demand"
option on Time Phased Demand by Planner Code screen


----------------------------------
Release Notes
xTuple ERP
PostBooks, Standard, and Manufacturing Editions
Version 3.2.0Alpha
November 10, 2008
----------------------------------

This is the Alpha release of version 3.2.0. We are especially eager
to hear feedback from alpha testers on the following new areas of
functionality:

Freight Pricing
  * Full spec: http://wiki.xtuple.org/FreightPricing

CRM Enhancements
  * Graphical calendar view for To-Do list
  * Document Ownership
  * To-Do alarms
  * E-mail notice for Incident
  * Document links for Account and Incident

Reference Designators on BOM
  * Full spec: http://www.xtuple.org/mantis/view.php?id=7258

EDI for Checks
  * Full spec: http://www.xtuple.org/mantis/view.php?id=6909

New OpenRPT Features
  * Added crosstab object
  * Ability to print images from files on disk
  * Added zooming functionality
  * Drag selection of multiple items
  * Added group alignment tools

----------------------------------

The following features and bug fixes have been added to the applications
since the release of version 3.1.0. Additional detail for each item
listed below may be found on our community website (www.xtuple.org).
Simply go to the Issue Tracker and select the Changelog option.


New Features:

* [All] Added api.itemcost Scripts
* [Accounting] Added detail information to g/l transactions
* [Accounting] Created capability to generate ACH check files
* [Accounting] Added search capability to A/R Workbench
* [Accounting] Added running totals to G/L transaction report
* [Accounting] Added grand total to A/P Check Run Edit List
* [Accounting] Added Printed column to Unposted POs
* [Accounting] Added sort by due date to Select Payment screen
* [Accounting] Reformatted Work order operation window
* [Accounting] Added timestamp to detailed inv hist lot/serial report
* [Community] Added Link to xTuple Wiki on "Community" tab
* [CRM] Show total count on To-Do list based on selection criteria
* [CRM] Added the functionality to associate documents to an Account
* [CRM] Added File/URL links to Incident Window
* [CRM] Added Owner information to CRM that defaults to creator
* [CRM] Added priority to To-Do
* [CRM] Enabled navigation to Customer via CRM from To-Do list
* [Inventory] Added ability to review reorder point calculations before
committing updates
* [Inventory] Added "Ship Via" Column to Print Packing List Batch
* [Products] Added item sources tab to item window
* [Purchase] Added PR # to PR displays
* [Sales] Added contact to Sales Order
* [Sales] Added "Firm" status to Sales Order Lines:
* [Sales] Added api.creditmemo and creditmemoitem views
* [Sales] Added ability to define shipping and receiving warehouse on
Return header
* [Sales] Added toggle button to Sales Order screen to allow for simpler
presentation
* [Sales] Included baseline sales order acknowledgment form
* [Sales] Added Cust. info to S/A displays/reports
* [Sales] Updated customer screen
* [Sales] Added Advanced freight calculation functionality extension to
xTuple ERP
* [Sales] Added the ability to mass update prices by amount
* [Schedule] Made firm Planned Orders different color
* [Schedule] Added API view for Planned Order
* [Schedule] Created API view for Purchase Orders
* [Schedule] Added check box option on Item Site screen next to Lead
Time that allows you to "Use on first grouping"
* [System] Converted all embedded mql files to use new database driven
metasql queries
* [System] Converted XMainWindows and XDialog Windows to XWidget


Bug Fixes:

* [All] Fixed compile errors on OpenSolaris
* [All] Fixed startOfTime() and endOfTime() stored procedures which
weren't working with some PostgreSQL datestyle settings
* [Accounting] Fixed blank description column on To-Do/Incident
* [Accounting] Fixed issue with Cash Receipts report ignoring selection
criteria
* [Accounting] Fixed refresh on AR workbench
* [Accounting] Fixed api.invoice insert error where CASE types text
and integer could not be matche
* [Accounting] Fixed issue with run time reporting to G/L regardless
of selection in BOO
* [Accounting] Disallowed single voucher from appearing on multiple
checks
* [Accounting] Fixed mixed mode problem when jumping to CRM account
from Tax Authority Window
* [CRM] Fixed empty window found when selecting to edit the �Uses of
the Contact� in contact screen
* [CRM] Fixed issue preventing selection of open windows when opened
through To Do List
* [Inventory] Fixed issue where Now and Today's date were not treated
the same on Where Used display
* [Inventory] Fixed issue preventing relocation of stock when a
Location is non-netable
* [Inventory] Fixed issue where non-netable location remained netable
if checked after stock received into it
* [Inventory] Reinstated version of report that shows graph
* [Inventory] Fixed itemsite api view to allow update of inactive
Item Sites
* [Inventory] Fixed issue where external shipping maintenance screen
opened behind desktop
* [Products] Made detailed item costs display revision-aware
* [Purchase] Fixed crash behavior on Post PO by Agent screen
* [Reports] Fixed Invoice report, which was printing blank total detail
* [Reports] Clarified wording of html email label
* [Sales] Fixed non-functional bill-to phone number on S/O
* [Sales] Fixed non-functional pattern in RA Workbench
* [Sales] Fixed blank type column on Invoice Information screen
* [Sales] Ensured City, State, and Zip information are displayed when
adding new Ship-To address
* [Sales] Required List Unposted Credit Memos screen include C/M's with
no line items
* [Sales] Removed closed Invoices from displaying on Customer
Information Workbench
* [System] Fixed problem with numeric sort order not working as expected
* [System] Removed superfluous user preferences
