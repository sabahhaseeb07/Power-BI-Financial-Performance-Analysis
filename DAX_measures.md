1. Growth Indicator = IF(\[Sales Growth 2013 Vs 2014] >= 0,

"🔺",

"🔻")

\&

FORMAT(\[Sales Growth 2013 Vs 2014],"0.0%")



2\. previous year profit = CALCULATE(

&#x20;   \[Total Profit],

&#x20;   SAMEPERIODLASTYEAR('Date'\[Date])

)



3.Previous Year Sales = 

CALCULATE(

&#x20;   \[Total Sales],

&#x20;   SAMEPERIODLASTYEAR('Date'\[Date])

)



4.Profit Margin = \[Total Profit]/\[Total Sales]



5.PY profit margin = Divide(\[previous year profit],\[Previous Year Sales])



6.sales 2013 = CALCULATE(\[Total Sales],'Date'\[year]=2013)



7.Total Sales = SUM(financials\[Sales])



8.YoY Growth % = 

DIVIDE(

&#x20;   \[Total Sales] - \[Previous Year Sales],

&#x20;   \[Previous Year Sales]

)





