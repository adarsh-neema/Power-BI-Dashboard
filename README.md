Power-bi-dashboard-for-Electronic Company:
This bi dashboard will help the an organization to analyse the sales of their electronic devices in different countries and make insightful decision to grow their revenue and recognize the area where the performance is not up-to-the-mark.

**datasource:mysql

The data is loaded, transformed(with power query editor), and visualized with the help of Power BI.

This is a multiple-page report which is more than 25 mb, so I could not upload the iriginal file. However, I uploaded some screenshot of showing what I put into together to analyse the business data.

***This is a home page which is the main page and it can take you to othere pages with the 
![image](https://github.com/adarsh-neema/Power-BI-Dashboard/assets/71634174/711f5dd6-01af-4609-8b8a-1b4fa7d99fc8)


Data modeling where dimensions tables are the outer ones and the main transaction table is fact_actual_estimates where all the important attributes are listed. Key measure are on the left most which has all the measures for the calculations created using DAX.

![image](https://github.com/adarsh-neema/Power-BI-Dashboard/assets/71634174/638fdd82-5cda-4f22-98ac-f0bc95a8d564)


Finance view : Profit and loss statement, Net sales performance over the time, Top and bottom products and customers net sales
![image](https://github.com/adarsh-neema/Power-BI-Dashboard/assets/71634174/abcffb02-dbd2-4ea0-a032-81a355b6207a)


Sales view : Customer performance like net sales, gross margin and gross margin % is shown using matrix and scatter chart. Which product perform best is also displayed using a matrix throgh net sales, gross margin and gross margin %. two donut charts are used for unit economics. Donut charts are used to show the distribution of net sales, total post invoice deduction and total pre invoice deduction. Second donut chart is used to show cost of goods sold and gross margin.

![image](https://github.com/adarsh-neema/Power-BI-Dashboard/assets/71634174/0301638a-35cb-4405-9b8a-5e19f7a3794f)


Marketing view : drill down is used to show the performance of different products and regions using a matrix. Waterfall chart is used to show the increase or decrease in gross margin, net profit and operational expense.
![image](https://github.com/adarsh-neema/Power-BI-Dashboard/assets/71634174/d2b560c4-9596-47b5-8db5-febf799020e1)

Supply chain view : Customer and product performance is shown on the basis of forecast accuracy %, forecast accuracy LY %, net error and net error % is displayed in a matrix. Accuracy and net error's trend is shown over the period using a line and stacked column chart.

![image](https://github.com/adarsh-neema/Power-BI-Dashboard/assets/71634174/4fc5e5f7-8682-4968-9c16-12928eab5226)
