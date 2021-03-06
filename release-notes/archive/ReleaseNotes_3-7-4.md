Release Notes
xTuple ERP
Version 3.7.4
October 11, 2011
----------------------------------

These are the release notes for the 3.7.4 Patch Release. Thanks
to all who contributed to make this release possible.

As always, please review the xTuple Compatibility Matrix before
upgrading: http://www.xtuple.org/compatibility-matrix.

----------------------------------

The following features and bug fixes have been added to the
applications since the 3.7.3 release. Additional detail for
each item listed below may be found on our community
website (www.xtuple.org).

New Features:

N/A

Bug Fixes:

* Rounding error in WO issue [14490]
* Multi-company consolidation doesn't forward update balances
  if there are no transactions [14581]
* Kit problem + Sales Order Cancel Item Problem [15003]
* 'Cancel Item' in S/O Item dialog creates a W/O for the item
  (if item has "Create W/O's linked to S/O's" checked) [15104]
* Add soline reopened changelog (code included) [15113]
* PostProduction for User defined cost elements
  uses CURRENT_DATE [15212]
* $0 AP open items not dropping off open payables [15215]
* forwardUpdateAccount always updates all accounts [15262]
* Issue with deactivating customers via
  the customer workbench [15277]
* Credit card Cash Receipts can't be deleted
  when transaction wasn't finished properly [15331]
* Foreign key error adding new ship-to [15344]
* Get irrelevant dialog entering new quote item [15345]
* Error Message Using Contact Merge [15383]
* AR cash receipts - Taxes charged on
  early payment discount [15387]
* Issues with Copy Sales Order function [15424]
* ForwardUpdateAccount SLOW for
  Revenue and Expense Accounts [15467]
* Next Quote Number when using the Copy quote [15536]
* PO Item UOM Ratio is Zero [15576]
* Adding a new line to a close S/O
  does not reopen the S/O [15585]
* Sales Order Line Item Notes are not added to
  Work Orders for Kit components generated automatically
  from Sales Order [15590]
* MetaSQL statement �salesOrderItems� (list) incorrectly
  calculates �discountfromcust� when the
  IncludeFormatted parameter exists [15639]
* �Sales Representative� filter in Summarized Sales history
  is not functional [15671]
