# UipathSmartSheetPackageActivities
1. get_SheetObject :>> 
  This Uipath workflow helps in getting a Sheet Object of any Smartsheets. 
  Input: SheetID (String), API Token (String), int_PageSize (Integer, Default - 100 records)
  Output: Sheet Object (Sheet)
  
2. get_ColumnID_By_ColumnName :>> 
  This Uipath Workflow helps in returning the Column ID for each Column Names of a Smartsheet. 
  Input: Sheet Object (Sheet), Array of Column Names (String array)
  Output: Dictionary with Column Ids & Column Names (Dictionary)

3. get_ColumnIndex_By_ColumnName :>> 
  This Uipath Workflow helps in returning the Column Index for each Column Names of a Smartsheet. 
  Input: Sheet Object (Sheet), Array of Column Names (String array)
  Output: Dictionary with Column Index & Column Names (Dictionary)

