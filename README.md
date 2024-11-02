# Cryptocurrency Trading and News Analysis Platform

This project is a cryptocurrency trading and news dashboard that allows users to filter information by time range, enhancing decision-making for investors by providing both historical and real-time market data. The platform integrates trading data from CoinMarketCap and news from CryptoNews, using an automated ETL pipeline and dual-database storage.

## Live Demo
- **Interactive Dashboard**: Filter cryptocurrency prices and news by customizable date ranges.
- **Database Integration**: MongoDB and PostgreSQL for optimized storage and query capabilities.

## Features
- **ETL Pipeline**: Automated data extraction, transformation, and loading, processing over 1GB of real-time data using Spark.
- **Interactive Dashboard**: Built with Flask to enable data filtering by date range.
- **Data Sources**:
  - **CoinMarketCap API**: For trading data
  - **CryptoNews API**: For news data with sentiment analysis

## Data Workflow
### ETL Process
- **Extraction**: Data pulled from CoinMarketCap and CryptoNews APIs
- **Transformation**: Data cleaned and structured for analysis, with outliers removed
- **Loading**: Data loaded into MongoDB and PostgreSQL for seamless access

### Key Technologies
- **Python & Spark**: ETL automation and large-scale data processing
- **PostgreSQL & MongoDB**: Dual-database setup for structured and unstructured data
- **Flask**: Interactive web application framework

## Figures
- **Figure 1**: ETL Workflow Diagram (Data Extraction, Transformation, and Loading)
![ETL Workflow Diagram](https://github.com/LinZhou606/Cryptocurrency-Trading-and-News-Analysis-Platform/blob/main/ETL_Workflow_Diagram.png)
- **Figure 2**: Dashboard Interface Displaying Query Results for Search
![Dashboard Overview](https://github.com/LinZhou606/Cryptocurrency-Trading-and-News-Analysis-Platform/blob/main/dashboard_screenshots.png)  

## Future Enhancements
- **AWS Integration**: Scale data storage with AWS RDS for PostgreSQL and MongoDB Atlas
- **Elasticsearch**: Implement for enhanced news search functionality
- **Data Monitoring**: Establish alerts for data integrity and uptime
