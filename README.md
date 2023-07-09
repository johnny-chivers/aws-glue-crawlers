# Gue Cralwers

## Table of contents

- [What's included](#whats-included)
- [Main Tutorial](#main-tutorial)
- [Useful Links](#useful-link)
- [Creators](#creators)

## What's included

The repo is to supplement the [youtube video](https://youtu.be/yb7dAQl1Di8) on AWS Glue. 

You will need an AWS User that has permissions to access S3 and Glue. I am using my Admin account to carry out the tutorial. 

## Data
Below is the schema for the customer table which is created in the Glue Data Catalog by the crawler. The schema also contains some sample data. 

**Customers**
| Customerid      | Firstname | Lastname| Fullname |
| ----------- | ----------- |-----------|-----------|
|  293 | Catherine                | Abel                   | Catherine Abel                 |
|  295 | Kim                      | Abercrombie            | Kim Abercrombie                |
|  297 | Humberto                 | Acevedo                | Humberto Acevedo               |


## Main Tutorial
1. Create S3 bucket 
![image](/img/1.create-bucket.png)

2. Upload customers folder with data stored in csv. 
![image](img/2.upload-data.png)

3. Create A cralwer 
![image](img/3.create-crawler.png)

4. Name Cralwer 
![image](img/4.name-crawler.png)

5. Add data source
![image](img/5.add-datasource.png)

6. Data Source configuration. 
![image](img/6.datasource-config.png)

7. Create new IAM role 
![image](img/7.create-new-iam-role.png)

8. Select database
![image](img/8.select-database.png)

## Creators

**Johnny Chivers**

- <https://github.com/johnny-chivers/>

## Useful Links

- [youtube video](https://youtu.be/yb7dAQl1Di8) 
- [website](https://www.johnnychivers.co.uk)
- [buy me a coffee](https://www.buymeacoffee.com/johnnychivers)


Enjoy :metal:
