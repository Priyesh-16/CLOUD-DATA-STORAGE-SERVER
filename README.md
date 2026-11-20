# CLOUD-DATA-STORAGE-SERVER
CLOUD DATA STORAGE SERVER
## Aim

To create and configure an Amazon Relational Database Service (Amazon RDS) instance as a cloud data storage server, configure the required security settings, connect it to a web application, and perform database operations using the application.

## Algorithm / Steps

1. Create a Security Group for the RDS database.
2. Add an inbound rule to allow MySQL (Port 3306) access from the Web Security Group.
3. Create a DB Subnet Group using two Availability Zones.
4. Launch an Amazon RDS MySQL database instance.
5. Configure the database with the required identifier, username, password, storage, and instance class.
6. Associate the database with the created Security Group and Subnet Group.
7. Wait until the database status becomes **Available**.
8. Copy the RDS endpoint.
9. Open the web application using the provided Web Server IP address.
10. Enter the RDS endpoint, database name, username, and password.
11. Connect the application to the database.
12. Verify the connection by adding, editing, and deleting records in the Address Book application.

## Output
<img width="1920" height="1200" alt="Screenshot (240)" src="https://github.com/user-attachments/assets/e15523df-b7a9-4bd7-82b4-ca0fbbfdc5a3" />
<img width="1920" height="1200" alt="Screenshot (241)" src="https://github.com/user-attachments/assets/474993c5-1aba-48bb-b26e-93cafc2c13da" />
<img width="1920" height="1200" alt="Screenshot (242)" src="https://github.com/user-attachments/assets/57736a52-5462-47e9-9c42-f2e5e558bb7a" />
<img width="1920" height="1200" alt="Screenshot (243)" src="https://github.com/user-attachments/assets/af22e936-2b0a-4487-803f-49ca1d1be9b7" />
<img width="1920" height="1200" alt="Screenshot (244)" src="https://github.com/user-attachments/assets/48ec53ef-9b67-4d78-a910-64a69bb7bb05" />
<img width="1920" height="1200" alt="Screenshot (245)" src="https://github.com/user-attachments/assets/4661d08e-ba62-4bef-9bd6-9f1d9f732afa" />
<img width="1920" height="1200" alt="Screenshot (246)" src="https://github.com/user-attachments/assets/f79e8771-0277-45d6-8e6c-2757feb0ff64" />





## Result

Thus, an Amazon RDS database instance was successfully created and configured as a cloud data storage server. The database was securely connected to a web application, and data operations such as inserting, updating, and deleting records were successfully performed through the application.
