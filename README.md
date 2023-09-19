Sales Data Mart SSAS Project Documentation
This documentation provides an overview and instructions for the Sales Data Mart SSAS (SQL Server Analysis Services) project. The project involves creating a cube for analyzing sales data from the AdventureWorks database.

**Table of Contents**
- Overview
- Prerequisites
-  Project Structure
- Creating the SSAS Cube
- Deploying the SSAS Cube
- Processing the SSAS Cube
- Accessing and Analyzing the SSAS Cube
- Contributing
- License

- 
Cube  

  -  ![Cube Schema overview](https://github.com/Abdullah28-gheyad/AdventurWorks-Sales-Cubit/blob/master/cube.png)
1. Overview
The Sales Data Mart SSAS project involves creating an SSAS cube to analyze sales data from the AdventureWorks database. The cube provides a multidimensional view of sales data, allowing for in-depth analysis and insights to support business decisions.

2. Prerequisites
Ensure you have the following prerequisites in place:

SQL Server Analysis Services (SSAS) installed and configured
AdventureWorks database or a suitable dataset with sales-related data
SQL Server Data Tools (SSDT) or SQL Server Management Studio (SSMS) for creating and managing SSAS projects
3. Project Structure
The SSAS project is structured as follows:

Data Source: Connection to the AdventureWorks database or your dataset.
Data Source View (DSV): A logical view of the data source.
Dimensions: Dimension tables such as DimProduct, DimCustomer, DimDate, and DimTerritory.
Measures: Fact table (Sales) and related measures.
Cube: Multidimensional cube to organize and present the data for analysis.
4. Creating the SSAS Cube
- 
Cube  Browser

  -  ![Cube Schema overview](https://github.com/Abdullah28-gheyad/AdventurWorks-Sales-Cubit/blob/master/cube%20browser.png)
Follow these steps to create the SSAS cube:

Open the SSAS Project: Open the SSAS project in SQL Server Data Tools or SQL Server Management Studio.

Create Dimensions: Define dimensions using dimension tables, specifying attributes and hierarchies.

Define Measures: Define measures based on the fact table (Sales), aggregating data appropriately (e.g., sum, count).

Build the Cube Structure: Build the structure of the cube, defining relationships between dimensions and measures.

Configure Cube Properties: Configure cube properties such as storage, partitions, and aggregations for optimization.

Deploy the Cube: Deploy the SSAS cube to the SSAS server.

5. Deploying the SSAS Cube
To deploy the SSAS cube, follow these steps:

Right-click on the SSAS project and select "Deploy."

Verify deployment success in the Output window.

6. Processing the SSAS Cube
To process the SSAS cube and load data into it, follow these steps:

Right-click on the deployed cube in SSAS and select "Process."

Choose the processing options (e.g., Process Full, Process Data, Process Update).

Execute the processing to load data into the cube.

7. Accessing and Analyzing the SSAS Cube
To access and analyze the SSAS cube, use tools like SQL Server Management Studio, SQL Server Data Tools, or other compatible reporting and analysis tools.

Connect to the SSAS server using your preferred tool.

Navigate to the cube and use the tool's interface to explore and analyze the sales data.

8. Contributing
We welcome contributions! If you'd like to contribute to this SSAS project, follow the Contributing Guidelines.

9. License
This project is licensed under the MIT License.
