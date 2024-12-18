Q1A_Formulas_Not_Calculating_Questions  
Questions to isolate the problem
1. Make sure that there is no space before the = sign.
2. Make sure that the cell is not formatted as Text. If it is, set the number format to General, then press F2 and press Enter without changing anything.
3. Make sure that the Show Formulas button in the Formula Auditing group of the Formulas tab of the button is not highlighted.
4. If you use comma as decimal separator, you should use semicolons instead of commas in the formula: =IF(AB7>3;"Success";"Fail")
