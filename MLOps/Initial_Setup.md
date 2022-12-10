# MLOps - Initial Setup
## Who are the audience?
- Leaders
- Technical Project Managers
- Experienced ML & DS Engineers
- Medium & Large Enterprises leveraging ML & DS
- Job seekers
## Who are part of this?
- Business Decision Makers - The one defining the business problem.
- Product Owner - The person who has idea on both Business problem & Industrial data.
- Data Scientist/ML Engineer - The one who builds models to generate ROI.

To Solve a specific business problem, each stakeholder, that is, The Business Decision Makers, Product Owners, and ML Engineers should do their job as designated.

Investing in all the above resources is a waste of efforts and money, unless a specific business problem is determined.

![Screenshot from 2022-12-10 00-08-08](https://user-images.githubusercontent.com/19406666/206770087-42f1be67-15b8-41f9-b423-0c69eded3916.png)

## Business Problem
A business problem can be defined as any hurdle, situation, or variation that leads to a difference between the desired objectives and accomplished results. Ex: Identifying Spam, Making Product Recommendations.

## Data Lake
A data lake is a system or repository of data stored in its natural/raw format, usually object blobs or files. 

A data lake can include structured data from relational databases (rows and columns), semi-structured data (CSV, logs, XML, JSON), unstructured data (emails, documents, PDFs) and binary data (images, audio, video).

Examples are Amazon S3, Apache Hadoop, Snowflake.

## Data Problem
Once data is gathered and analysed, business problem is converted into a data problem by product owner and Data Scientist or Machine Learning Engineer.

- For continuous analysis, data needs to be in One Place (Data Lake). Only do this, if you have a clear vision on your business requirement.
- For Initial Analysis, data can be manually gathered/retrieved from multiple places.

While building a model, for example a model which will analyse if the customer churn happens or not, it is important to have different categories of data such as customer details, financial details, product details, transactional details and so on.

All these types of data can be categorised into:
- Must to have data: Required to start exploring the solution to the business problem.
- Good to have data: Will give additional information to solve the problem but is not that critical.
- Data whose relevancy can't be established without exploration.

## Prioritise Business Problems
From the main Business Problem, find out the list of sub business problems and from that list find out top 5-10 sub business problems and work on them to reach the final solution and get the business value.



## Key Terminologies
**Business decision maker**: The person who has the authority to make a decision, for example, sales head, engineer head, and so on, depending on the use case.

**Product owner**: The person who understands the business the the organisation handling and the data that the organisation has.

**Primary data**: The data that the organisation owns.

**Secondary data**: The data, which is available like weather, and so on, as the primary data of some other vendor.

**Third party data**: The data, which is useful but has to be acquired from multiple vendors and aggregated/processed.
