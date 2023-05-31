# Retail-Store-Data-Modeling-using-DataStage

## Project Overview:

This project focuses on building a data warehouse for a fictional retail store and using IBM InfoSphere DataStage for efficient data extraction, transformation, and loading (ETL) processes. The goal is to store and analyze the retail store's data in a way that enables easy analysis while preserving all changes in the dimensions.

By implementing a star-schema data warehousing approach, the project organizes the data in a simple and intuitive manner. This structure simplifies complex queries and facilitates meaningful data analysis for the retail store.

The ETL pipelines created with IBM InfoSphere DataStage play a crucial role in this project. They extract data from different sources, transform it to fit the star-schema model's requirements, and load it into the appropriate data marts. This streamlined process ensures that the retail store can analyze the data effectively and gain valuable insights.

A key aspect of the project is capturing and preserving changes in the dimensions. This means that any updates or modifications in the retail store's data are accurately recorded in the data warehouse. By doing so, the project allows for historical trend analysis and provides a comprehensive view of the retail store's performance over time.

## Problem Statment:

A fictitious national department store made the strategic decision to construct a sales analysis data warehouse utilizing a star-schema approach. The data warehouse comprises dimensions such as customer, store, and product. As the operation progresses, it is anticipated that attributes within these dimensions will undergo modifications.

To ensure the delivery of precise results when querying previous versions of dimension attributes, it is imperative to maintain a comprehensive record of all changes made to the star-schema data warehouse. By preserving versions of these changes, the data warehouse can effectively facilitate accurate analysis and provide relevant insights into historical data. This proactive measure enables users to access and query prior versions of dimension attributes, enabling a thorough examination of historical trends and patterns within the department store's sales data.

## Building star schema :
![dstage](https://github.com/islamyounis/Retail-Store-Data-Modeling-using-DataStage/assets/83661639/a30bee30-e1e0-4cdc-b9a0-5f7ce4da43d1)


## DataStage Jobs:

![arch1](https://github.com/islamyounis/Retail-Store-Data-Modeling-using-DataStage/assets/83661639/8e4d50f8-e49f-44f9-b62c-012a9ad4a04c)


![arch2](https://github.com/islamyounis/Retail-Store-Data-Modeling-using-DataStage/assets/83661639/cdaffe40-6d74-44f4-ac74-7157a7780e90)
