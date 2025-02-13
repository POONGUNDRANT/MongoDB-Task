# MongoDB Task - Zen Class Programme

This project involves designing a database for the Zen Class Programme using MongoDB. The database contains collections for users, codekata, attendance, topics, tasks, company drives, and mentors. Below are the tasks to be performed on the designed database.

## Collections
The following collections are used in the database:

- **users**: Contains information about users enrolled in the programme.
- **codekata**: Tracks the CodeKata problems solved by users.
- **attendance**: Logs the attendance of students for each session.
- **topics**: Lists the topics covered in each class.
- **tasks**: Contains tasks assigned to students.
- **company_drives**: Information about the company drives held for placement.
- **mentors**: Details about mentors guiding the students.

## Database Queries

### 1. Find all the topics and tasks which were taught in the month of October
Query to retrieve all topics and tasks that were taught during the month of October.

### 2. Find all the company drives which occurred between 15th October 2020 and 31st October 2020
Query to find all company drives that were held between 15th October 2020 and 31st October 2020.

### 3. Find all the company drives and students who appeared for the placement
Query to list all company drives and the students who participated in each placement.

### 4. Find the number of problems solved by each user in CodeKata
Query to retrieve the number of problems solved by each user in the CodeKata system.

### 5. Find all the mentors who have more than 15 mentees
Query to find mentors who are supervising more than 15 mentees.

### 6. Find the number of users who were absent and did not submit tasks between 15th October 2020 and 31st October 2020
Query to count the number of users who were absent and did not submit their tasks during this period.

## Setup Instructions

To set up this MongoDB database, follow the steps below:

### Prerequisites
- Install MongoDB on your machine (or use a cloud-based solution like MongoDB Atlas).
- A MongoDB client (such as MongoDB Compass or Robo 3T) for querying the database.

### Steps
1. Clone this repository to your local machine.
2. Set up your MongoDB instance or connect to your cloud-based MongoDB service.
3. Import the collections data into the database (if the data is provided in a file, use `mongoimport` or manually input data).
4. Execute the queries listed above to retrieve the desired data.

## Conclusion
This MongoDB database design helps in tracking various aspects of the Zen Class Programme, from attendance and topics to tasks, CodeKata performance, and placements. The queries can be modified to suit additional requirements if needed.
