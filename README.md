# CMPG-323-Project4-38148900
**Purpose**: Develop and evaluate an AI-powered automation solution for cloud-hosted database testing. Specifically, the solution will test the functionality of CRUD operations (create, read, update, and delete).

**System Overview**: The system architecture is depicted in the diagram below. The user initiates the testing process, which then performs the following steps:

1. Authenticates to the database using saved credentials.
2. Executes customer CRUD operations.
3. Executes product CRUD operations.
4. Executes order CRUD operations.
5. Executes order detail CRUD operations.
6. Logs out of the database.
   
**Error Handling**: If the system encounters an error during login, the user must stop the process and restart it.
