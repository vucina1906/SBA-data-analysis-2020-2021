- This project represents the analysis of SBA (U.S. Small Business Administration) data for 2020 and 2021. Data are downloaded from link https://data.sba.gov/dataset/ppp-foia. This link includes PPP (payment and protection program) dictionary and all public avalable SBA data from 2020 and 2021. On link https://www.sba.gov/document/support-table-size-standards you can find PDF file that represents size standards that SBA using prior to classifing businesses as a small business. Purpose of SBA is to promote the economy by assisting the country’s small businesses,
as an independent agency of the United States government, that protects the interests of small businesses and ensures that they receive a fair share of government contracts.

- By using different tools for extraction,transformation and loading huge amount of data (SSIS), analysis (Microsoft SQL Server) and visualization (Tableau) I am gaining much more insights from data and create some valuable conclusions about economy and its different sectors. 

- In the first part of the project I imported all csv files to SSMS using Foreach Loop Container. Folder processed_files was created just to catch processed file one by one so I can easily track ETL process. Standards and Data dictionary were also loaded to SSMS. All SSIS packages shared in repository. 

- In the next part I analysed data in SSMS using SQL. Queries with explanations are updated and loaded in repository. At the end of analysis I created a view, where I stored data of interest, after which I loaded from view from SSMS to flat file using SSIS. This flat file is later used for visualization in Tableau. 

- Last part of the project includes data analysis and visual presentation using Tableau Desktop version. 