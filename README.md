![Clean Data](C:\Users\user\Pictures)

# Excel-data-cleaning-project
 This Project is a step by step process on the data cleaning techniques used to turn dirty data into clean data
## Project Aim
The aim of this project is to clean and organize the data using Microsoft Excel so it’s ready for analysis.

## Objectives
The main objective is to apply all cleaning techniques learnt to make data ready for analysis. I plan to achieve this by using functions, trimming spaces, filtering, and sorting.

## Key Tasks
1. Autofit Columns and Rows.
2. Identify and Remove Duplicates.
3. Trim Extra Spaces.
4. Eliminate Blank Cells.
5. Convert Data into Table.
6. Use Find and Replace to correct errors.
7. Validate data to be sure it is thoroughly clean.

## AUTOFIT COLUMNS AND ROWS
Autofitting is done by highlighting entire table using Ctrl + A, placing cursor on the format pane in the home tab and hovering over to Autofit Row height and autofit column width.

## REMOVE DUPLICATES
Three Duplicates were found in the dataset and it was removed.

## TRIM EXTRA SPACES
Extra spaces were found in the name column and it had to be removed . I removed the extra spaces using the TRIM() function. To trim extra spaces, create a new column and enter the function TRIM() into an empty cell Eg =TRIM(C2), Afterwards, Flash fill or drag cursor to the Last cell to replicate the formula In all cells.

After trimming, the new column would be saved using Paste >>>> Values. You can do this by clicking the column to be saved and then right clicking to paste values.

## ELIMINATING BLANK CELLS
To Eliminate blank cells, I replaced the empty spaces with texts ‘N/A’.
I proceeded to Splitting the date column into Date/time, Date and time to separate each entity into columns.
 
## CONVERT DATA INTO TABLE
In the home tab, move cursor to format as table icon and click on it, you choose from the dropdown containing different table styles and a menu would pop up. Select my table has headers alongside the table range and click okay.

## USING FIND AND REPLACE TO CORRECT ERRORS
To do this, go to the home tab and hover around Find and Select icon and click. A menu would appear and in the find bar type ‘inf’ and replace with ‘0’, I chose ‘0’ because that column contains values. 
Also, the same was done for the rating column replacing ‘Excelent’ with ‘Excellent’ to correct the misspelt word. 
          
## DATA VALIDATION


 



