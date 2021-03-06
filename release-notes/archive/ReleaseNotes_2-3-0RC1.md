Release Notes
xTuple Applications
OpenMFG - PostBooks
Version 2.3.0RC1
December 14, 2007


This is the first Release Candidate for version 2.3.0 of OpenMFG and
PostBooks. This is primarily a bug fix release, improving on issues 
discovered by the community during testing of 2.3.0Beta2.

We are also including with this release a beta version of our new-look 
application-based help files which feature the following:

Help Files
- New and better navigation (tables of contents, indexes)
- Fixed screenshot resolution problem
- Source content migrated to .XML format (DocBook)
- SourceForge site contains new 'xtupledocs' repository

(PLEASE NOTE: These beta docs cover some but not all of the new 2.3.0 
features. Look for the completed 2.3.0 docs in early 2008.)

	
----------------------------------

The following features and bug fixes have been added to the application 
since the release of version 2.3.0Beta2:


New Features:

* [A/P] Added Vendor Types to Accounting Master Information
* [System] Added default Customer Terms to Sales Configuration 
screen
* [System] Added default Sales Rep option to Sales configuration 
screen

Bug Fixes:

* [All] Fixed issue where some push buttons in the Mac client 
appeared as rectangles instead of having rounded corners
* [A/P] Fixed distortion of the Misc. Check screen in the Mac 
client
* [A/P] Fixed Misc. Check Credit Memo cluster to only show Credit 
Memos for the selected Customer
* [A/R] Modified default Invoice report definition to handle 
multi-currency
* [G/L] Prevented editing of Vouchers in view mode
* [G/L] Modified Chart of Accounts report definition to sort 
Profit Center field correctly
* [Accounting] Fixed issue where Exchange Rate was not being 
applied correctly to freight charges on multi-currency Invoices
* [Accounting] Modified Summarized Taxable Sales screen to use 
base Currency by default
* [CRM] Fixed text overlap problem on CRM Account Search screen
* [CRM] Fixed issue preventing linking of Opportunities to To-Dos 
after the fact
* [Inventory] Fixed problem when printing from right-click menu 
in Transfer Order master list screen
* [Inventory] Removed references to advanced lot/serial tracking 
functionality for RMA, etc. from lot-tracking reports because the 
functionality has not been implemented yet
* [Inventory] Prevented impression that new comments may be added 
before saving a new Transfer Order item
* [Inventory] Fixed date format inconsistency on TO item screen
* [Inventory] Fixed incorrect TAB order on TO item screen
* [Inventory] Fixed issue in copied Transfer Orders where Line 
Item Taxes were not being totaled properly
* [Manufacture] Hid Costing tab on Planned Work Order being 
released from MPS/MRP
* [Manufacture] Fixed blank menu on Work Order screen in Mac 
client
* [Manufacture] Fixed issue with Work Order widget not working 
properly
* [Manufacture] Required Work Orders for Job Items to be closed 
if related Sales Order Line Item is closed or canceled
* [Products] Made BOO and BOM screen behavior consistent when 
viewing inactive Revisions
* [Products] Prevented BOO Revisions from being copied when a BOO 
is copied
* [Purchase] Fixed issue where PO Item edits were not be saved
* [S/O] Fixed Customer widget problem on S/O Credit Memo screen
* [Sales] Fixed issue leading to SQL error when changing the Tax 
Authority for a Billing Selection
* [Sales] Added more QOH information in header of Item 
Reservations screen
* [Sales] Corrected column mis-labeling on List Return 
Authorizations screen
* [Sales] Fixed issue where RA refund was appearing as a charge 
when it should have been a credit on the Customer Information 
Workbench
* [Sales] Fixed Customer Type filter on Allocate Reservations 
screen
* [Sales] Renamed Shipping Terms to Ship Via on Customer 
Workbench
* [Sales] Updated RA Check to show correct RA Number
* [Sales] Fixed the Print Credit Memo check box on the RA 
Workbench
* [Sales] Fixed problem with RECEIVE ALL option on the Return 
Authorization screen causing receipt entries to be made even for 
ship and service dispositions
* [Sales] Fixed error received when selecting CANCEL when posting 
receipts on a new Return
* [Sales] Fixed issue in RA where payment was expected after a 
substitute was specified
* [Sales] Fixed issue where a mixed RA Return was not selectable 
for Receipt
* [Sales] Fixed font sizing problem Customer Characteristics tab
* [Sales] Fixed issue where Warranty Account was not being used 
when posting Warranty-related RA Receipts
* [Sales] Prevented importation of Sales Order Items on R/A for 
service unless they are Job Items
* [Sales] Fixed issue where original Sales Order was being 
disabled prematurely when editing RAs
* [Sales] Prevented credit data from being entered on Return 
Authorizations unless there are some credit or Return Line Items
* [Sales] Fixed Item lookup on RA Service screen to present 
only Job Items
* [Sales] Fixed issue where RA (Replace/Immed/None) was being 
closed Prematurely
* [Sales] Revamped QUERY button methodology on R/A Workbench
* [Sales] Fixed issue where RA Credit Memos were not 
immediately accessible
* [Sales] Fixed issue preventing conversion of Prospects to 
Customers when converting Quotes to Sales Orders
* [Sales] Fixed issue leading to an error when processing a 
Return if no Reason Codes exist
* [Sales] Fixed Pricing schedules to always honor qty. breaks 
even if more qty. does not give lower Price
* [Sales] Fixed issue with Receipts not posting on RA Line 
Items screen
* [Sales] Updated PackingList-Shipment report definition to 
show RA#
* [Sales] Fixed issue where amounts could be entered for RAs 
defined as Immediate - Credit None
* [Sales] Fixed blank menu bar on RA screen in the Mac client
* [System] Made commission information match on 
api.custshipto and Ship-To screen
* [System] Fixed MSXSL.exe error received with importing Yahoo 
Store data 
 

=============
Release Notes
xTuple Applications
OpenMFG - PostBooks
Version 2.3.0Beta2
December 7, 2007


This is the second and final Beta release of version 2.3.0, 
leading up to an expected Release Candidate at the end of next
week. We are in the final stages of the release cycle now, so
beta testers are urged to please send us their feedback as soon 
as possible. This is a bug fix release, and so very few new 
features have been added since Beta 1.

One highlight of this Beta 2 release is the following:

Job Costing
- Added Job Item Type
- Designed for ad-hoc Work Orders
- Operates outside Standard Costs
- WIP posts to COGS on shipment
- Additional Job Cost reporting


----------------------------------

The following features and bug fixes have been added to the 
applications since the release of version 2.3.0Beta1:

New Features:

* [Products] Added Job Costing Item Type and related 
functionality
* [A/R] Added ability to enter negative amount in Misc. Charge 
field on Invoice screen

Bug Fixes:

* [A/R] Added multi-currency logic to A/R Open Items list
* [Accounting] Made Return Authorization Credit Memo information 
visible on the View Check Run screen
* [Accounting] Changed A/R Aging logic to use apply date if no 
Journal exists
* [Accounting] Fixed issue preventing voiding of posted Checks
* [Accounting] Fixed issue where Tax on Select For Billing 
screen was incorrect because selling UOM was not being factored
* [Accounting] Added missing A/P menu options to Purchase menu 
in Neo menu
* [Community] Updated links in Community Menu
* [Inventory] Fixed issue with post function on Inventory 
distribution screen not handling default Location properly
* [Inventory] Fixed issue preventing partial shipment of MLC 
Items having Sales Reservation quantity
* [Inventory] Fixed issue resulting in SQL Error at Issue Stock 
to Shipping
* [Inventory] Enabled printing of Transfer Orders before a 
Shipment # has been assigned
* [Inventory] Forced Transfer Orders to close when all Line 
Items are closed
* [Inventory] Updated Inventory Availability logic to include 
SO Line Items using alternate UOMs
* [Inventory] Modified Inventory | Receiving | Return menu to 
specify use for Purchase Order Returns
* [Inventory] Fixed Cost Categories master list report to 
include TO Liability Clearing information
* [Products] Fixed issue where revision history was being 
included when copying a BOO
* [Products] Fixed issue in 221 to 23alpha1 Conversion where 
BOM/BOO links not preserved
* [Reports] Added UOM column to Pick List report definition
* [S/O] Prevented Shipping Asset Account from using wrong values 
if Costs are changed while Order is at Shipping but not yet 
shipped
* [S/O] Fixed Windows-only issue preventing use of S/O Credit 
Memo screen in the case where override numbers were allowed and 
the cursor was on the C/M Number by default
* [Sales] Fixed problem in client that was causing 
cobmisc_invcdate on Select Order For Billing screen to be unset
* [Sales] Updated Quote report definition to include UOM, 
multi-currency, and correct related totaling
* [Sales] Added UOM column to Uninvoiced Shipments screen
* [Sales] Improved wording on insufficient inventory error 
message at Sales Order entry
* [Sales] Fixed loophole leading to dead end when Return 
Authorization Item is closed
* [Sales] Fixed issue where unauthorized Return Authorization 
Lines were showing as eligible for receipt
* [Sales] Fixed issue preventing Checks from being processed 
to pay Return Authorization Credit Memos
* [Sales] Added Currency information to Return Authorization 
Workbench
* [Sales] Updated "0 Value� message on Unposted Invoices screen 
to check for Misc. and Freight charges before giving warning
* [Sales] Fixed issue preventing issuing of non-reserved qty. 
on Sales Orders having reserved qty.
* [Sales] Fixed issue where sufficient inventory function was 
subtracting reserved qty. twice
* [Sales] Fixed issue preventing Sales Reservations for 
complete unreserved qty.
* [Sales] Added missing privileges to update script to enable 
Sales Reservations
* [Sales] Fixed typo on Sales Config | Returns tab
* [Sales] Automatically Update option on List Open Sales Orders 
screen does not remember its setting
* [Sales] Removed word �Material� when referring to Return 
Authorizations
* [Sales] Fixed issue preventing Returns if no Reason Code 
exists
* [Sales] Fixed tab sequence on Return Authorization Line Item 
screen
* [Sales] Added Print S/A Special Calendar Form option to Neo 
menu
* [Sales] Added UOM detail to Sales Order Status report 
definition
* [Sales] Fixed error received when posting a Replace Upon 
Receipt Return Authorization
* [Sales] Fixed issue where Return Authorization payment 
status was not being updated properly when payment complete
* [Sales] Added additional filtering for closed S/O Line Items 
to Inventory Availability by Customer Type screen
* [Sales] Updated Return Authorization Workbench to identify 
Credit Memos created from RAs which have pending payments
* [Sales] Fixed issue where Return Authorization pricing was 
not honoring S/O Item UOM
* [Schedule] Fixed error received when attempting to view 
Running Availability for Purchased Items from Planned Orders 
by Planner Code screen
* [Schedule] Updated error message to more clearly explain 
why Work Centers cannot be deleted
* [System] Improves server maintenance utility to add reindex 
after VACUUM FULL ANALYZE
* [System] Successfully imported XML files are given unique 
names when renaming them instead of trying to overwrite 
previously-imported files with the same name 
* [System] Fixed commission mismatch between api.custshipto 
and Ship-To Screen
* [System] Fixed issue generating error when importing Yahoo 
Store data using MSXSL.exe
* [W/O] Prevented creation of Work Orders for inactive Items
* [Manufacture] Required Work Order Components to use the 
parent WIP Account when scrapping from a Work Order
* [Manufacture] Fixed Running Availability screen to correctly 
calculate Sales Order Item UOM qty.
* [Manufacture] Required Work Order Components to use the 
parent WIP Account when returning stock from a Work Order
* [Manufacture] Updated Return W/O Material Item screen to 
handle UOM conversions
* [Manufacture] Fixed issue causing error message when 
scrapping W/O Components


=============
Release Notes
xTuple Applications
OpenMFG - PostBooks
Version 2.3.0Beta1
November 20, 2007

This is the first Beta release of version 2.3.0, marking the end of 
new feature development for this release cycle. We move now into 
refining, testing, and bug fixing mode leading up to the final release.

Highlights of this Beta release include the following:

Sales Order Reservations
- Added Sales Order configuration metric to "Enable Reservations" 
- Added Sales Order Item function to "Reserve" and "Unreserve" all or 
part of an order qty based on a set of reservation netting rules
- Altered the Issue Stock to Shipping screen to disallow users from 
issuing more material than is available based on reservation netting
- Added reports that show Sales Order Availability by Customer/Customer 
Type

Return Authorizations
- Enabled processing of Returns
- Ship, Issue Credits for Returns
- Import historical Sales Orders
- Return Authorization Workbench

Characteristic Templates
- User-defined templates make loading Characteristics easier


----------------------------------

The following features and bug fixes have been added to the applications 
since the release of version 2.3.0Alpha1:

New Features:

* [Accounting] Moved the "Maintain Vouchers" privilege from the 
Purchasing function to the Accounting function
* [CRM] Added ability to create user-defined templates for 
Characteristics  
* [CRM] Add search capability to both List CRM Accounts and List Contacts
* [Manufacture] Added option to release only firmed orders from the 
Planned Orders by Planner Code window.
* [Manufacture] Moved UOM field next to Total Qty Required field on 
Issue W/O Material Item screen
* [Manufacture] Added ability to create Work Orders without a BOM
* [P/O] Added default dates to P/Rs by Planner Code screen
* [Sales] Modified Customer Information Workbench to show Invoices for 
both $0 and non-$0 amounts on Invoices tab 
* [Sales] Added check box to Open Sales Orders screen to enable automatic 
update
* [System] Modified database Updater tool so updates will now be rolled 
back when an error is encountered
* [System] Changed SoCommentsChanged Event to SoOrderNotesChanged Event
* [System] Reorganized Preferences screen 
* [W/O] Added SUBMIT button to Work Order Operation Buffer Status By Work 
Center screen


Bug Fixes:

* [A/P] Fixed SQL error encountered when preparing Check Run
* [A/R] Fixed Sales Credit Memos to calculate properly when amounts are 
more precise than two decimal places
* [Accounting] Fixed SQL error encountered when correcting Receiving
* [Accounting] Fixed financial reports to only show zero amounts when 
specified
* [Inventory] Enabled Maximum Desired Cost above $999.00 on Item master
* [Inventory] Fixed issue preventing posting of PO Receipts tied to 
Expense Categories
* [Inventory] Fixed Qty. field sizing issue in Mac client on Inventory 
Adjustment screen
* [Inventory] Enabled shipping of Orders with only ShipOrders privilege
 [Inventory] Fixed Sales Order screen to accurately reflect Qty. at 
Shipping after recalling Orders
* [Manufacture] Fixed error received when scrapping components from a 
Work Order
* [Products] Fixed blank output when printing Costed Indented BOM report
* [Products] Fixed issue where Revision Number was not visible on BOM if 
accessed from BOM button on Item master
* [Products] Fixed issue with Revision control malfunction on copied BOMs
* [Products] Fixed issue where Product Revisions were enabled despite 
Revision Control not being selected
* [Products] Fixed 221 to 23alpha1 conversion script to preserve BOM / 
BOO link
* [Purchase] Fixed field sizing issues on PO Line Item screen
* [Purchase] Fixed issued where recv_vend_item_number and 
recv_vend_item_descrip fields in recv table were not being populated 
correctly when Receiving
* [Purchase] Fixed issue where Correct Receiving action was deleting 
current Receiving Notes and not appending new Notes
* [S/O] Enabled Customer Discount% functionality on SO Line Item screen 
in Mac client
* [Sales] Enabled Promise Date field on Sales Order Item screen
* [Sales] Fixed issue preventing removal of Work Orders created from
Sales Orders
* [Sales] Fixed Locale date inconsistency in Promise Date field on Sales 
Order Item screen
* [Sales] Fixed issue where Tax override at Sales Order Item entry was not 
carrying through to invoicing
* [Sales] Fixed issue preventing Shipping Notes from being entered on the 
Quote and Sales Order screens
* [Sales] Fixed issue with api.customer view saving wrong decimal 
precision for commissions



================
Release Notes
xTuple Applications
OpenMFG - PostBooks
Version 2.3.0Alpha1
November 2, 2007

This is the first Alpha release of version 2.3.0. We are especially
interested in feedback from alpha testers on the following new areas
of functionality:

UOM Enhancements
- Extensive changes to normalize Unit of Measure handling/conversions
- New Selling UOM
- New UOM for Bill of Materials
- See issue #4963 in our xTuple.org issue tracker for a detailed spec

BOM/BOO Revisions
- Encompases Part III of Return Material Authorization (RMA) effort
- New Bill of Materials/Operations revision-tracking
- See issue #5771 for a detailed spec

Return Authorizations (Preview)
- Initial preview of Return Authorizations functionality
- Encompasses Part I of RMA effort
- See issue #4832 for a detailed spec

XML Data Import (Preview)
- Initial preview of XML import utility
- Uses XSLT mapping to transform XML for import into xTuple databases
- See issue #5886 for more information

Added UI configuration memory to
- Grid layouts
- Window Size/Position
- Checkboxes when enabled and where applicable

(NOTE: Checkboxes that remember their state are being temporarily 
indicated by a small '?' symbol when checkbox memory is enabled in 
user preferences. We would like additional feedback on windows where 
this behavior should/shouldn't be included.)
	
----------------------------------

The following features and bug fixes have been added to the applications 
since the release of version 2.2.1:

New Features:

* [System] Memory for checkboxes
* [System] Hide menus that are disabled
* [A/P] GUI Memory
* [A/P] Can A/P (or A/R) 'As-Of' Reports be created?
* [A/R] Need open balance snapshot capability
* [CRM] Characteristics Template 
* [CRM] Add ability to search both List CRM Accounts and List Contacts
* [G/L] Add Journal Entry to api schema 
* [P/D] BOM uses Inventory UOM rather than Capacity UOM 
* [P/O] P/R by Planner Code Default Dates
* [S/O] Copy billing address to credit card
* [W/O] Submit button on dspWoOperationBufrStsByWorkCenter 

Bug Fixes:

* [All] CPU usage higher than expected
* [All] Minimize/Maximize window lost of displayed info
* [Inventory] cannot ship with only ship order privilege
* [Inventory] Qty at Shipping is not correct after recalling orders
* [Inventory] Can't Apply Maximum Desired Cost Over $999.00
* [Inventory] Qty field strangely oversized on Inv. Adjustment window 
on Mac.
* [Inventory] Message popped up on issue stock to shipping screen
* [I/M] TO - Unable to Edit TO Head Comment
* [Manufacture] Cut off date field scrunched up on Mac on Release W/O 
by Planner Code window
* [P/O] Contact w/no name gives error
* [Sales] tax override at sales order item entry does not carry through 
to invoicing
* [Sales] Can not remove work order from sales order
* [Sales] Changed Customer Layout
* [Sales] Provide a way to enable the promise date capability in SO
* [System] setting the neo menus, and show menus/toolbars
* [System] Change SoCommentsChanged Event to SoOrderNotesChanged Event
* [System] Saving in Product Configuration turns on Routings in PostBooks