# Data Engineering 

Welcome to my Data Engineering GitHub Repository! This repository showcases a variety of data engineering projects focused on data extraction, transformation, and storage. Each project demonstrates practical solutions to common challenges, such as web scraping, API integration, and database management, while leveraging modern tools and technologies. Designed with scalability and automation in mind, these projects highlight efficient data workflows and offer a resource for solving diverse data engineering problems.

## 🛠️ Key Skills and Tools

- **Languages:** Python, SQL
- **Cloud Platforms:** Azure 
- **Databases:** MySQL, PostgreSQL, MongoDB  
- **DevOps Tools:** Docker
- **Data Processing:** ETL/ELT pipelines, Batch and Streaming Data

## 📂 Projects

### 1. **Comprehensive Data Extraction and Processing** 🔄

**Overview:**  
The goal was to automate web scraping and data processing using a simple, serverless approach. Instead of building a complex pipeline, we aimed to efficiently scrape and store web data.

**Solution:**  
Azure Functions were used to automate the workflow. The process begins with an HTTP-triggered function that receives a request and scrapes the necessary web pages. Additional Azure Functions are triggered to handle tasks such as processing URLs, extracting detailed information, and saving the data into a database. This serverless solution ensures that each step runs independently, allowing for scalability and flexibility.

**Technologies Used:**  
- *Azure Functions (HTTP and Queue Triggers)*
- *Azure Storage Queue*
- *Azure SQL Database*

**Outcome:**  
The solution successfully scrapes data from webpages, processes it in stages, and stores structured information in a database. The system runs efficiently without the need for a complex pipeline, providing a scalable and serverless approach to handling data extraction and storage.


### 2. **Video Insight Extractor** 🎥

**Overview:**   
The project aims to automate the extraction of insights from video files stored in Google Drive. By leveraging cloud services, we will retrieve video content, process it for insights, and store the results efficiently.

**Solution:**  
The workflow begins by retrieving video files from Google Drive, get content of file and uploading them to blob storage. Once stored, the Video Indexer processes the files to generate valuable insights, returning the results in JSON format. Finally, this JSON data is uploaded back to Google Drive for easy access and management.

**WorkFlow Diagram:**
![image](https://github.com/user-attachments/assets/e7d83a3a-5715-4305-ace3-aacc1462de16)

**Technologies Used:**  
- *Google Drive API*
- *Azure Blob Storage*
- *Azure Video Indexer*

**Outcome:**  
The project successfully automates the process of extracting insights from video files, allowing for efficient storage and retrieval of valuable data. The insights are readily accessible in JSON format on Google Drive, facilitating further analysis and use.

### 3. **Data Extraction from APIs Using Power BI Queries**  📈

**Overview:**  
The project focuses on utilizing Power BI to extract and analyze data from Advanced Hunting and Secure Score APIs. The goal is to structure this data effectively for further analysis and reporting

**Solution:**  
The solution involves using Power BI queries to connect to the Advanced Hunting and Secure Score APIs. Data is extracted, transformed, and structured to meet analytical needs before being saved in an Azure database. This structured data can then be easily accessed for reporting and visualization.

Video_processing_image.PNG

**Technologies Used:**  
- *Power BI*
- *Advanced Hunting API*
- *Secure Score API*
- *Azure SQL Database*

**Outcome:**  
The project successfully extracts and structures data from multiple APIs, storing it in an Azure database. This enables efficient data analysis and reporting, allowing stakeholders to gain insights from the collected data and improve decision-making processes.



