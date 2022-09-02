# Using spreadsheet applications

## Overview
Spreadsheets are divided into cells and each cell contains one piece of data that can be used to calculate, compare or filter information. Each column of a spreadsheet is labelled with a letter, A-B-C-D-etc, while each row is labelled with a number, 1-2-3-4-etc. This means the first row and first column is cell A1, while the cell in the fifth column and tenth row is E10. The data in each cell can be a variety of things such as numbers, currency, dates, words and formulas and can be the result of calculations based on data in other cells. This can make spreadsheets very powerful programs that can be used for many different purposes and adapted to your needs. The most common spreadsheet programs are: 
-	Microsoft Excel  
-	Google Sheets, a web-based program 
-	Numbers for Mac computers.  

## Basic 
### Formulas 
A cell can contain a formula that will display the answer to a calculation. If part of the calculation is a value in another cell and you change the value in that cell the answer will change. Formulas always start with an = (equals sign) and use other mathematical symbols such as
-	plus: +
-	minus: -
-	multiply: * 
-	divide: /
-	less than: <
-	greater than: >

Formulars can also include instructional words such as SUM, AVERAGE and COUNT. The spreadsheet will display the answer to the formula in the cell. If a cell is highlighted the formula will be visible and editable in the formula bar above the cells. Examples of common formulas:
| Formula          | Explanation                                                                            |
|------------------|----------------------------------------------------------------------------------------|
| =A2+A3           | Adds the values in cells A2 and A3                                                     |
| =A2-A3           | Subtracts the value in cell A3 from the value in cell A2                               |
| =A2*A3           | Multiplies the two values in cells A2 and A3                                           |
| =A2/A3           | Divides the value in A2 by the value in A3                                             |
| =SUM(C2:C32)     | Adds all the values in cells C2 through to C32                                         |
| =AVERAGE(C2:C32) | Calculates the average of all the values in cells C2 through to C32                    |
| =COUNT(A1:A10)   | Displays the number of cells from A1 through to A10 that have numerical values in them |

### Freeze rows or columns
If you have a large amount of data that you need to scroll through to see you may want to “freeze” the top row or first column so that it remains visible when you scroll down or across. This will let you see the headings or labels next to your data. In Google sheets do this by clicking the View menu then Freeze then select if you want to freeze rows, columns or both. 

In the Numbers program the header for columns and rows are ‘frozen’ by default. Adjust this in the Table menu.

### Autofill
Autofill is a function in spreadsheets that allows you to automatically fill in data rather than typing it. If you want to enter 30 into many cells write 30 in the first cell. Then click the cell so it is highlighted – there will be a small square in the bottom-right of the cell. Click and hold this square with the mouse pointer then drag the mouse down or across into the cells where you want the same data to appear. This is slightly different in the Numbers program where you will drag the circle from the middle of the cell.
Autofill can also be used to enter data in patterns. If you enter 1,2,3 into successive cells then highlight those three cells and drag the small square into other cells the software will continue counting up for you. This will work for many different types of patterns, including:
-	Uniform jumps in numbers: 5,10,15…
-	Dates
-	Days of the week
-	Times 
-	Data that contains text: Test1,Test2 – autofill will continue with Test3,Test4…

If the cell has a formula in it the autofill function will adjust the cell value in the formula. For example, if you add together two numbers with the formula =B2+C2 then use autofill to drag this formula down the cell below will be =B3+C3 so that you can add together both values from all the rows.   

In some cases you may not want the autofill function to adjust the cell value in your formula. In this case use the $ symbol to indicate that the cell value should remain the same when you use autofill. For example, if you want to multiply a column of values, in column B with a constant number in cell D2 you could use this formula: =B2*$D$2 – the autofill function would increase the first number e.g. B3,B4,B5 but always multiply by the constant in cell D2.   

### Charts
Information in spreadsheets can be represented visually in charts or graphs. How you do this will depend on which spreadsheet program you are using. In Google Sheets you would highlight the data that you want to represent in a chart then click the Insert Chart button that is a square box with three vertical lines in the toolbar. This will create a chart and also open the Chart editor at the right of the screen. This will give you option to change the type of chart (line, bar, column, pie etc.) and change other settings. If you click outside the chart the Chart editor will disappear – edit the chart again by clicking the chart, then the menu (three small dots) in the top right of the chart.    

## Proficient
### Conditional Formatting
Conditional formatting allows you to format particular cells if they meet certain conditions. There are many different options for the formatting but the most common is to give the cell a background colour. For example, you may choose to make cells green if they show an improvement on numbers from the previous year and red if they show a decline. You can also choose to format cells if they:
-	are above or below a certain threshold
-	have text that contains, or starts with, certain letters 
-	before or after a certain date
-	many other rules

In the Numbers program this is called conditional highlighting and is available from the Format sidebar.

### IF Function
Using IF at the start of a formula allows you to display a value in a cell if a certain condition is met and another value if that condition is not met. For example you could display Pass or Fail in the column next to a percentage to indicate whether someone has passed a test. If the grade was in cell D14 and the pass mark was 50 the formula would look like this: 
-	=IF(D14>49,"Pass","Fail")    
-	This is a written explanation of this formular: if the value in cell D14 is greater than 49 display Pass otherwise display Fail.

### COUNTIF Function
The COUNTIF function will allow you to count the number of cells that meet whatever criteria you would like. If you had a list of “Pass” or “Fail” next to students you could count the number of students that passed. If the list containing Pass or Fail was in column E and between rows 5 and 26 the formula would look like this: =COUNTIF(E5:E26,"Pass") 


## Advanced
### Data validation
Data validation is a way for you to ensure that the information entered into your spreadsheet is consistent. You can create a drop-down list with values to select from or create other rules that must be met. This can be useful if there is more than one person working on the same spreadsheet. For example if people have to enter grades as a percentage you could ensure that only numbers from 0 to 100 could be entered. You could also set up rules to ensure that people enter information consistently. If you are asking people a yes/no question people may enter different values: Yes, yes, Y, y, yep. This can be problematic if you are trying to calculate the number of affirmative responses. Data validation can help with this. In Google Sheets, highlight the cells you would like to make rules for, then select Data > Data validation to define the rules for data that can be entered into those cells.    

All the data validation options are not available in Numbers but it is possible to create a “Pop-Up Menu” with the cell formatting options. This will allow only options defined in the list to be entered. 




