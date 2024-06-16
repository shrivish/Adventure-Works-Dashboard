# Adventure-Works-Dashboard-Report

## Preview of the Dashboard (Power BI Service)

 ![Screenshot 2024-06-15 161443](https://app.powerbi.com/links/PZAN2VK-ud?ctid=3be611e8-6b6a-448c-8616-8c993bba1879&pbi_source=linkShare)

 ![Screenshot 2024-06-15 164317](https://app.powerbi.com/links/PZAN2VK-ud?ctid=3be611e8-6b6a-448c-8616-8c993bba1879&pbi_source=linkShare&bookmarkGuid=0babc5f4-bc1c-4e09-b755-1896fb489e5c)

 ![Screenshot 2024-06-15 161346](https://app.powerbi.com/links/PZAN2VK-ud?ctid=3be611e8-6b6a-448c-8616-8c993bba1879&pbi_source=linkShare&bookmarkGuid=0e674ba0-4ba2-4b58-a393-fd0ef36b3e65)

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
    ![Screenshot 2024-06-15 162747](https://github.com/Abtg08/Adventure-Works-Dashboard-Report/assets/87989296/efc6969d-bcfa-4ef8-b212-b2c351fd2bbf)


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

    ![Screenshot 2024-06-15 161443](https://github.com/Abtg08/Adventure-Works-Dashboard-Report/assets/87989296/6aea78c0-2c56-4815-a28a-280e120fe854)


- Step 9 : Also built the following custom tooltip to show the KPIs for each category when hovered on Category chart.

    ![Screenshot 2024-06-15 161300](https://github.com/Abtg08/Adventure-Works-Dashboard-Report/assets/87989296/c200ef4b-7eba-4ce2-866f-426ccbbedc34)

- Step 10 : The *Product Detail* page includes visuals like Total Profit, Return Rate etc for a selected product from the product slicer.

    ![Screenshot 2024-06-15 164317](https://github.com/Abtg08/Adventure-Works-Dashboard-Report/assets/87989296/4ae7bcf3-e297-46b3-937c-cbad6af30eeb)

- Step 11 : The *Customer Detail* page shows the total number of unique customers and the statistical relationship between customer purchasing the products on the basis of their *Occupation*, *Income Level* etc.
    
   ![Screenshot 2024-06-15 161346](https://github.com/Abtg08/Adventure-Works-Dashboard-Report/assets/87989296/7b98f5a7-4717-45f3-a33b-bf257efe1115)


- Step 12 : Added a custom filter functionality to the *Executive Dashboard* page that can be toggled on and off:

    ![Screenshot 2024-06-15 161511](https://github.com/Abtg08/Adventure-Works-Dashboard-Report/assets/87989296/12847db6-5ec7-42bf-9c53-272725dbcc09)


- Step 13 : The dashboard was complete with all my target requirements being met. Finally, I linked all the pages using Buttons to facilitate smooth navigation.

- Step 14: Uploaded the entire Dashboard to PowerBI Service.
