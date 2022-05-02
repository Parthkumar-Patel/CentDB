<div id="top"></div>

<br />
<div align="center">
  
<h3 align="center">Simple Centralized Database Management System (CentDB)</h3>

  <p align="center">
    Building a simple centralized database, DBMS, and analytics systems in Core Java.
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
		<li><a href="#features">Features</a></li>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

In this project, we build a simple centralized database management system (CentDB). Our team have explored and implemented data structure concepts for creating the databases, its management system, and security. In addition, our team have builded an analytics engine to perform basic data analytics. The database management system layer will provide a command-line interface, and perform various functionalities of database management system.
	
### Features

* DB Design
	- Linear Data Structure for query, and data processing
	- Data is processed and stored in a custom file format
	- Maintain data dictionary or meta data file
* Query Implementation : Validate and execute the following operations
	-Create database
	- Use database
	- Create table
	- Insert into table 
	- Select from table with single where condition (AND || OR || NOT are not required) 
	- Update one column with single where condition (AND not required)
	- Delete a row with single where condition
	- Drop table
* Transaction Processing
* Log Management : 3 Logs – JSON format
	- General Logs: query execution time, state of the database (e.g. how many tables are there with number of records at a given time)
	- Event Logs: changes in database, concurrent transactions, crash reports, etc.
	- Query Logs: capture user queries and timestamp of query submission
* Data Modelling – Reverse Engineering
	- Generate an ERD based on current database state
* Export Structure & Value in SQL Format
	- like SQL dump (structure+value) created by MySQL Export
* Analytics
* User Interface & Login Security

### Built With

* [Java](https://www.java.com/)

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- GETTING STARTED -->
## Getting Started

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/Parthp1810/Heart-Condition-Recognition-ML.git
   ```
2. Change directory to the folder
   ```sh
   cd Heart-Condition-Recognition-ML
   ```
3. then open Project
4. Run and Enjoy
   
<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Contributors Names

* Parthkumar Patel
* Dhruv Hiteshkumar Soni
* Hirva Patel
* Sidharth Mahant
* Vikram Babu Rajendran

<p align="right">(<a href="#top">back to top</a>)</p>

