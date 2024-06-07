# Employee-Tracker

## Table Of Content
- [General Info](#general-info)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Demo](#Demo)
- [License](#license)
- [Github](#Github)

## General Info
Manage employee data using this command line Content Management System (CMS) built with Node.js, Inquirer, and MySQL. Options include: view all departments, view all roles, view all employees, add a department, add a role, add an employee, and update an employee role.

## Technologies
<div style="display: inline_block"><br>
  <img height="40" alt="Aliyus-Js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <img height="40" alt="Aliyus-Node" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg">
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <img height="40" alt="Aliyus-MySQL" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original.svg">
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</div>
</br>

## Installation

1. **Check Node.js Installation:**  
   Check if you have Node.js installed by typing `node -v` in your command line. If node is not installed, visit the [Node.js website](https://nodejs.org/) to install.

2. **Clone Repository:**  
   Next, clone this project repository to your computer.

3. **Install Dependencies:**  
   Use the command `npm install` to install dependencies.

4. **Create .env File:**  
   Create a file in the root directory titled `.env` and type `PASSWORD='[YOUR PASSWORD HERE]'`.

5. **MySQL Setup:**  
   - Type `mysql -u root -p` in the terminal and enter your personal MySQL password.
   - Next, type `source schema.sql` and `source seeds.sql`. These commands will create the `employee_db` database and seed the database with mock data.

## Usage

1. **Start Application:**
   - Open terminal in the directory containing `index.js`.
   - Run the command `npm start`.

2. **Select Task:**
   - After starting the application, select a desired task from the menu provided.
   - Follow the prompts given by Inquirer.

3. **Repeat or Exit:**
   - After completing a task, you can choose to select another task or exit the application.
   - To exit the application, choose "EXIT" from the task prompt list.

4. **Video Demonstration:**
   - Reference the video demonstration above as needed.

## Demo

[![Demo Video](./video/Screenshot%202024-06-07%20024716.png)](./video/2024-06-07%2002-44-56.mp4)

## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
<br>
This repository is licensed under the MIT license.

## Github
[<img src="./video/25231.png" alt="Github Logo" width="75" height="75">](https://github.com/AliyusUnderwood/Employee-Tracker)