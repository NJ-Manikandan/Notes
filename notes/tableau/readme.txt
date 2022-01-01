Tableau

Tableau is a data visualization tool. 
It helps people to see and understand data much quickly and easily. 

Tableau 		(Full Licensed Version) 
Tableau Public 	(Completely free but won't allow you to create any sort of local copy like extract and to save files)

Dimensions are independent variable and measures are dependent variables. Normally in tableau measures will always get aggregated and dimensions specifies the level of granularity of worksheet.

A valid reason to use a data extract over a live connection to the dataset in Tableau is your data is constantly being updated and you want to work with a static file when building your visual (you will later return to the live connection when the visual is ready)

Interactive Action - There are two types of it
* Filtering - Recreates the chart with only the mapped data based on the current selection
* Highlighting - Just highlights the mapped data based on the current selection with keeping all the data in background

Data blending is a smart left join which can happen on fly. It is used majorly in the following cases
* when the level of granularity of two data sets or tables is different.
* tableau won't allow you to perform join when the data sets or tables are from different type of data source ie. excel, csv,..
By default, tableau blend the two datasource with common field name on fly.