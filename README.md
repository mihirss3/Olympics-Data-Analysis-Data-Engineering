# data-analytics-engineer-pipeline-olympics-data

**The Task**

Dataset: teams, disciplines and athletes taking part in the 2021 Tokyo Olympics 
https://www.kaggle.com/datasets/arjunprasadsarkhel/2021-olympics-in-tokyo

**The pipeline**

![Olympics flow](https://github.com/user-attachments/assets/87f177f6-8cfa-473f-8667-74329bb5d488)


**Step 1: Data Ingestion**

Download the dataset in csv format, ingest it on this github repository and extract the data from the API (raw format) using Azure Data Factory tool, buiding a data flow and loading it into Azure Data Lake storage:

![image](https://github.com/user-attachments/assets/3035960e-0a2c-466e-adc2-01dc051eaab7)


**Step 2: Data transformation**

Write some spark code to read the data from the data lake, apply transformation techniques and load it back to data lake avaliable for analysis.

**Step 3: Data Analysis**

Following, use Synapse Analytics tool to run SQL queries on transformed data and find some insights through visualizations.


1. Which discipline had the most significant difference in the number of entries by gender?

Artistic Swimming, Athletics and Wrestling are in the top 3 in all disciplines.

![image](https://github.com/user-attachments/assets/544a066d-e5fa-4588-a524-6489c7d2414e)



![image](https://github.com/user-attachments/assets/1820af25-7602-41b3-be0c-f5e24b02ebbc)



The visualization the average number of entries by gender for each discipline

![image](https://github.com/user-attachments/assets/50d7c519-dce5-4e9e-9a2d-aa11e619baed)



2. Counting the number of brazilian athletes by discipline

Athletics, Football and Handball had the most significant number of athletes, following Volleyball.

![image](https://github.com/user-attachments/assets/5f711db6-3fe9-436e-832f-01c88930614a)


![image](https://github.com/user-attachments/assets/34535a69-48d6-4ed7-8473-803cbbfea4ea)


3. Analyzing the medals


USA and China secured the highest number of gold medals, 39 and 38 respectively. 
Following by Japan with 27.
Brazil holds the 12º position.

![image](https://github.com/user-attachments/assets/4fd70e16-196f-4ad1-82f8-2bb9d068184c)


![image](https://github.com/user-attachments/assets/5184642c-f64b-4834-af4f-ae31aca7f707)


4. Counting the number of athletes by country

![image](https://github.com/lauranonato/data-analytics-engineer-project-olympics/assets/56266061/8ad2f273-ed80-4bfd-bbb0-141b5b4298c7)



