 ### Big Data Analytics | ECCDLO7032 
Department of Electronics & Telecommunciation, 
Don Bosco Institute of Technology, Mumbai.  
Course Coordinator: Mr. Jithin Isaac

### Laboratory Experiment No. 2
 
### Objective  
To learn and explore the Metabase Business Intelligence Tool & Google Big Query 

### Tools used  
- Software: 
  - Metabase https://www.metabase.com/
  - Google Big Query https://cloud.google.com/bigquery
- Cloud: AWS EC2 (Open ports 22, 3306 & 3000)

### Experiment Outcome
- Installation of Metabase in an AWS EC2 instance 
- Exploring the Metabase dashboard
- Importing a database into Metabase and performing data analysis on the same.
- Access the Google Big Query Dashboard
- Running queries on large sample databases included in Big Query
- Plotting data on Google Data Studio (extra)

### Instructions

**Metabase**
- Spin up an AWS EC2 instance
- Install Metabase on the EC2 instance
  - https://jithinsisaac.github.io/posts/aws_metabase/
- For importing new database into Metabase, follow these instructions:
  - In MySQL/MariaDB shell ->
    - CREATE USER 'jithin'@'%' IDENTIFIED BY 'isaac';
    - GRANT ALL PRIVILEGES ON . TO 'jithin'@'%';
    - FLUSH PRIVILEGES;
    - In sudo nano /etc/mysql/mariadb.conf.d/50-server.cnf
      - Change bind address to: 0.0.0.0
    - sudo systemctl restart mariadb.service
- Import .sql database into your EC2 instance
- Link the database with Metabase 

**Google BigQuery**
- We will use Google Bigquery sandbox, which does not need an credit card details
- https://cloud.google.com/bigquery
- https://cloud.google.com/bigquery/docs/sandbox

### Final list of Deliverables for Expt 2
(Please attach necessary screenshots & video clips for the same)

**1. Metabase**  
Screenshots of   
a. Dashboard of Sample Dataset  
b. Dashboard of your own Dataset

**2. Google Big Query**   
a. Screenshots of atleast 3 queries done on the any bigquery-public-data dataset

**3. Google Data Studio (Optional)**  
a. Screenshots of Dashboard of data from Big Query OR Sample data present in GDS

### Procedure 
- **ADD THE PROCEDURE THAT YOU FOLLOWED FOR COMPLETING THE EXPERIMENT HERE**

### Output
- **ADD SCREENSHOTS OF YOUR OUTPUT HERE ALONG WITH VIDEO**  

### Submission Details
- **Submitted on** 11-08-2021
- **Submitted by** Mr/Ms. XYZ
- **Roll No.** 111
