# hospital_DBMS
Implementation of a NoSQL database for a generic hospital management system.

1) Look in the dataset directory for the README file to generate the dataset:
* [LINK](https://github.com/CoffeeAddict93/hospital_DBMS/tree/main/dataset)

2) Create a MongoDB account and login with your credentials.
* Create NoSQL database to fit personal needs, i.e. creating "collections" for reimbursement purposes, provider info, etc.

3) Access MongoDB Atlas for cloud services and fire up a cluster (M0) for secure access and deployment.
* Many functions are equivalent to SQL databases (see below), yet many are unique to NoSQL/MongoDB.
* Atlas allows for real-time data analysis directly connected to database, usually faster than traditional databases (see below).



## Features

### Cloud Deployment
https://user-images.githubusercontent.com/77714442/144142222-1d07d4b0-554b-4752-944c-93247657ddd9.mp4
* Accessing and firing up a cloud cluster and settings.
* Performing real-time analysis and creating a LIVE dashboard.

### SELECT
https://user-images.githubusercontent.com/77714442/144142412-bfbd0646-3322-4fcd-a81c-304ce0e37080.mp4
* SQL SELECT statement is equivalent to MongoDB's $MATCH function

### JOIN 
https://user-images.githubusercontent.com/77714442/144142466-3249d80a-b914-4b6b-890d-35fc350a5b8f.mp4
* SQL JOIN statement is equivalent to MongoDB's $LOOKUP function
