# Eddie DataTable Generator


**Step 1** - Create Google Spreadsheet:
                    There are several caveats to creating this spreadsheet: please name all the column heads 'col1', 'col2' and so on. This is so that Eddie Can Parse the column Data. Future versions will lift column titles directly.


**Step 2** - Publish Google Spreadsheet to Web:
                    Make sure the viewer permissions are public. [A Demonstration Sheet can be found here](https://docs.google.com/spreadsheet/pub?key=0AkTBIga8sxWGdG52NkFGM3hEdUVlSFh5ekhmLVRFZEE&output=html)

**Step 3** - Open up the Eddie Homepage, and follow the directions from there. You will add the title, link and the number of columns from your spreadsheet that you wish to display.


**Step 4** - Eddie the overeager computer generates and overeager data table that can quickly be sorted and searched.


**Issues** : 
--The columns are simply named "Column 1" and so forth. Parsing of the Column Data names from the google spreadsheet API and the existing tabletop.js library proved difficult

--There is currently not a way to republish and Eddie table to a third party platform. Issues with creating a fully functioning server and generating unique pages for individual use could not be completed in time for submission.

