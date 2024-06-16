# Adventure-Works-Dashboard-Report

## Preview of the Dashboard (Power BI Service)

![WhatsApp Image 2024-06-16 at 17 28 46_98ca0550](https://github.com/shrivish/Adventure-Works-Dashboard/assets/86420582/d585b62b-931e-429d-a3dc-d67d6bcec79a)

![WhatsApp Image 2024-06-16 at 17 27 38_2e41b04c](https://github.com/shrivish/Adventure-Works-Dashboard/assets/86420582/141cd665-6c15-4ba1-b521-b0e33fc72aaf)

![WhatsApp Image 2024-06-16 at 17 28 16_a0be3508](https://github.com/shrivish/Adventure-Works-Dashboard/assets/86420582/dd53935f-8f74-43f8-9046-9fcba5359bbd)

![WhatsApp Image 2024-06-16 at 17 26 55_058836ed](https://github.com/shrivish/Adventure-Works-Dashboard/assets/86420582/b1ad9431-6f20-47bf-879f-ec7dd8441fb8)

### Dashboard Link : https://app.powerbi.com/links/2j_7lX3Gfz?ctid=3be611e8-6b6a-448c-8616-8c993bba1879&pbi_source=linkShare
## Problem Statement

AdventureWorks requires a sophisticated dashboard to overcome the current limitations in data analysis and performance tracking. The dashboard must achieve the following expanded goals:

- Track KPIs: It should enable continuous monitoring and evaluation of key performance indicators, such as sales growth, customer acquisition rates, and operational efficiency. This will allow for immediate identification of trends and potential issues, facilitating swift corrective actions.

- Compare Regional Performance: The dashboard must compare and contrast the performance metrics of different geographical regions where AdventureWorks operates. This comparison should highlight best practices, areas needing improvement, and potential for market expansion.

- Analyze Product-Level Trends: Detailed analysis tools are needed to dissect product sales data, providing insights into customer preferences, seasonal demand fluctuations, and product lifecycle stages. This will guide inventory decisions and marketing strategies.

- Identify High-Value Customers: The dashboard should incorporate advanced analytics to detect and profile high-value customers based on their purchasing patterns, engagement levels, and profitability. This information is crucial for tailoring marketing efforts and enhancing customer service.
By addressing these goals, the dashboard will serve as a pivotal tool for AdventureWorks to streamline its operations, bolster its market position, and drive sustainable growth.

## Steps Followed 

- Step 1 : Load the dataset onto Power Query Editor.

- Step 2 : Data transformation based on the requirements. Included steps like creating tables like Date, Measures and other metrices.

- Step 3: Created two calcuated tables named Sales Data and Returns Data to depict the statistics of sales made by various company products and the status of returns across all products respectively.

- Step 4 : Created the following measures to extract key statistics from dataset:

    ![Screenshot 2024-06-15 162435](https://github.com/Abtg08/Adventure-Works-Dashboard-Report/assets/87989296/5f1d82d3-7ce1-47c2-bbd0-9d938d72207c)


- Step 5 : Rectified the Relational Model by linking Primary keys, foreign keys and updating table cardinalities.
    ![image](https://github.com/shrivish/Adventure-Works-Dashboard/assets/86420582/2cc12ff4-a5ab-4fe6-b0fb-070eed5caf19)


- Step 6 : Visualized the dashboard structure based on three key questions:
       
        Q1. What type of data is being dealt here?
         Ans. Time series data, categorical, geospatial and hierarchical.

        Q2. What am I trying to communicate here?
         Ans. Comparison between categories over time, depicting compositions.

        Q3. Who is the end-user?
         Ans. The Managers          


- Step 7 : Created three pages to provide different insights to the viewer:
    
    - #### Executive Dashboard
    - #### Product detail
    - #### Customer Deatil
    


- Step 8 : The *Executive Dashboard* page depicts the following details:

        Total Revenue, Total Profit, Total Orders, Return Rate, Orders by Category, Monthly Revenue chart etc.

    ![WhatsApp Image 2024-06-16 at 17 28 46_db9d766b](https://github.com/shrivish/Adventure-Works-Dashboard/assets/86420582/08b4fa86-b987-4184-8887-fc4b1efe1969)



- Step 9 : Also built the following custom tooltip to show the KPIs for each category when hovered on Category chart.

    ![image](https://github.com/shrivish/Adventure-Works-Dashboard/assets/86420582/368e30f9-2727-47e9-b83d-ab9e46bd3d31)


- Step 10 : The *Product Detail* page includes visuals like Total Profit, Return Rate etc for a selected product from the product slicer.

    ![WhatsApp Image 2024-06-16 at 17 28 16_df99bd79](https://github.com/shrivish/Adventure-Works-Dashboard/assets/86420582/dd21f34f-17c5-4d1c-897f-b841e9f0f0e5)


- Step 11 : The *Customer Detail* page shows the total number of unique customers and the statistical relationship between customer purchasing the products on the basis of their *Occupation*, *Income Level* etc.
    
   ![WhatsApp Image 2024-06-16 at 17 27 38_dbabf469](https://github.com/shrivish/Adventure-Works-Dashboard/assets/86420582/8b6ccd73-0f10-4dd6-88e0-68fc44dcc844)



- Step 12 : Added a custom filter functionality to the *Executive Dashboard* page that can be toggled on and off:

    ![Screenshot 2024-06-15 161511](https://github.com/Abtg08/Adventure-Works-Dashboard-Report/assets/87989296/12847db6-5ec7-42bf-9c53-272725dbcc09)


- Step 13 : The dashboard was complete with all my target requirements being met. Finally, I linked all the pages using Buttons to facilitate smooth navigation.

- Step 14: Uploaded the entire Dashboard to PowerBI Service.
