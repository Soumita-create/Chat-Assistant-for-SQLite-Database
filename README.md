# Chat-Assistant-for-SQLite-Database

## Overview
The SQLite Chat Assistant is a Python-based chatbot that interacts with an SQLite database to answer user queries about employees and departments. It processes natural language input, converts it into SQL queries, and retrieves relevant information from the database.
## How It Works
1. The assistant initializes an SQLite database (your_database_name.db) with two tables:
 Employees: Stores employee details (ID, Name, Department, Salary, Hire Date),
 Departments: Stores department details (ID, Name, Manager).

2. The chatbot processes user queries using regex-based pattern matching.

3. Queries are translated into SQL statements and executed against the database.

4. Results are retrieved and presented in a user-friendly format.

5. The chatbot runs in a command-line interface where users can input queries and receive responses.

## How to Run the Project Locally
### Steps
1. Clone the repository: git clone https://github.com/your-repo/sqlite-chat-assistant.gitcdsqlite-chat-assistant
2. Run the script: python sqlite_chatbot.py
3. Interact with the chatbot by typing queries like:
   "Show me all employees in the sales department."
   "Who is the manager of the engineering department?"
   "List of all the employees hired after 2021-01-01."
   "What is the total salary expense for the marketing department?"
4. Exit the chatbot by typing exit.
