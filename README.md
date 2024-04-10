# DB Dialogue

<div align="center">
  <img src="Images/Chat With SQL Conversation 1.png" width="800" height="600" alt="Chatbot Interface">
  <br>
  <p>Chatbot Interface</p>
</div>

## Table of Contents
1. [Introduction/Overview](#1-introductionoverview)
2. [Features](#2-features)
3. [Architecture Overview](#3-architecture-overview)
4. [Installation/Requirements](#4-installationrequirements)
5. [File Descriptions](#5-file-descriptions)
6. [Conclusion](#6-conclusion)
7. [License](#7-license)

## 1. Introduction/Overview
This project introduces a conversational chatbot capable of interpreting natural language queries, generating SQL queries accordingly, and fetching results from a SQL database. Leveraging OpenAI's GPT-4 for natural language processing and featuring a Streamlit-based GUI, it offers an intuitive and user-friendly interface for complex database interactions.

## 2. Features
- **Natural Language Processing**: Employs GPT-4 to understand and process user queries in natural language.
- **SQL Query Generation**: Dynamically constructs SQL queries based on natural language inputs.
- **Database Interaction**: Seamlessly connects with SQL databases to retrieve accurate query results.
- **Streamlit GUI**: Provides a simple and engaging user interface, making it accessible for individuals of all skill levels.

## 3. Architecture Overview
The chatbot architecture integrates GPT-4 for processing and understanding natural language inputs. It translates these inputs into SQL queries which are then executed against a SQL database to fetch results. The frontend is built using Streamlit, offering a clean and interactive interface for users. This setup demonstrates a practical application of combining AI with web technologies for database management.

<div align="center">
  <img src="https://github.com/ManideepTelukuntla/Natural-Language-to-SQL-Chatbot/blob/main/Images/Architecture.png" width="800" height="254" alt="Chatbot Architecture">
  <br>
  <p>Chatbot Architecture Overview</p>
</div>

## 4. Installation/Requirements
- **Python & GPT-4**: Essential for the chatbot’s core functionalities.
- **Streamlit**: Utilized for creating the web-based user interface.
- **SQL Database**: A compatible SQL database is required for query execution. In this project MySQL database has been utilized.

Refer to `requirements.txt` in the project directory for specific versions of the frameworks and libraries used.

## 5. File Descriptions
- **`Chat-With-SQL-Database-App.py`**: The main Python script that integrates GPT-4 for NLP, connects and runs the SQL query against MySQL database and handles the Streamlit GUI.
- **`chinook.db`**: This is the datbase utilized in this project, containing Digital Media Store data.
- - **`ChinookMySQL.sql`**: SQL file to create the chinook database.
- **`requirements.txt`**: Lists all the dependencies necessary for the project.
- **`Images`**: Contains images related to the project for documentation and UI design.

## 6. Conclusion
The Natural Language to SQL Chatbot represents a significant step forward in making database interactions more intuitive and accessible. By leveraging cutting-edge NLP technology and user-friendly GUI designs, it simplifies complex database queries, making it a valuable tool for users ranging from database administrators to those with minimal SQL expertise.

## 7. License
Licensed under [MIT License](https://github.com/ManideepTelukuntla/DB-Dialogue/blob/master/LICENSE)
