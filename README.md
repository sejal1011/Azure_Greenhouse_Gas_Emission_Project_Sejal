# 🌍 Azure End to End Data Engineering Project on Greenhouse Gas Emission 🏭

## Abstract 📜
🔍 This repository hosts a comprehensive analysis of greenhouse gas emissions from 15 countries over a decade (2007-2016). The goal is to unearth patterns and trends that could shed light on the role these emissions play in climate change and global warming. An interactive dashboard using PowerBI is a key feature of this study.

## Dataset 📊
🌐 The dataset is sourced from the World Development Indicators DataBank: [World Development Indicators – DataBank](https://databank.worldbank.org/source/world-development-indicators). It includes data on CO2 emissions, methane emissions, nitrous oxide emissions, and more.

## Azure Project Steps 🚀
### Initial Setup
- Created Azure Free Subscription account.
- Established a Resource Group 'greenhouse-gas-emission-data'.
- Set up an Azure Data Lake Storage Gen2 account for data storage.
- Created containers for raw and transformed data.

### Data Ingestion using Azure Data Factory
- Built a data integration pipeline to transfer data from source to Azure.
- Configured HTTP source for data ingestion from the World Bank's dataset.

### Data Transformation using Azure Databricks
- Utilized Azure Databricks for heavy-lifting data transformations.
- Mounted ADLS Gen2 to Databricks for efficient data processing.
- Transformed raw data to derive insightful metrics.

### Analysis with Azure Synapse Analytics
- Set up Azure Synapse Analytics workspace.
- Created a database and tables from the transformed data.
- Performed detailed analytics using SQL scripts and integrated with Power BI for visualization.

## Methodology 🧪
- Data was initially processed in Excel for preliminary cleaning.
- Further transformations and analyses were done using Azure Databricks and Synapse Analytics.
- Power BI was used to develop an interactive dashboard showcasing various insights.

## Results 📈
- Interactive Power BI dashboard highlights key metrics like CO2 emission trends, total greenhouse gases emission by country, and more.
- Insights on the leading CO2 emitting countries over the observed period.

## Conclusion 🎯
- The study provides a clear view of greenhouse gas emissions trends globally.
- Significant insights into countries contributing most to global emissions.
- Data-driven approach offers a pathway to understand and combat climate change effects.

## How to Use This Repository 📘
- Clone the repository to get started.
- Explore the 'Data' folder for raw and transformed datasets.
- Check out the 'Notebooks' for detailed data processing and analysis steps.
- Dashboards can be viewed under the 'PowerBI' directory.

## Contributions and Feedback 💬
- Feel free to fork, modify, and use the data and code for your research or projects.
- Suggestions and contributions to enhance this study are always welcome!
