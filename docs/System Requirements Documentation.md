## System Requirements Documentation

### 1. Introduction

The PCTO management application allows users to view the companies that collaborate with the school and offers tutors a simplified management, adding, removing or modifying them.
This document will provide instructions for access the site, research and modify companies.

---

### 2. Setup HTTP Server

An internet connection, a web server and a database connection are required to make the application work. You can also use a hosting service to put the site on.
A platform consisting of HTTP server is XAMPP.

1. Download XAMPP
1.1 Go to the website: https://www.apachefriends.org/it/index.html
1.2 Download the correct version

2. Activate XAMPP
2.1 Run xampp-control.exe
2.2 Click on "Start" of Apache and MySQL

---

### 3. Access Application code

Access to the internet and a repository on GitHub used to store the code is required. Login credentials are required.

All the code is stored in the repo on GitHub. The local files, on the other hand, are contained in the "htdocs" folder.

---

### 4. Install on Simulator or Device

#### 4.1 Required Components

A computer with a software that allows to run virtual machines, such as VirtualBox, is required.

There must be a virtual machine that acts as a server (the case of an Ubuntu machine is discussed).

A web server, for example Apache, is needed.

#### 4.2 Save the page

The page must be contained in a folder, preferably in "var/www/PCTO".

---

### 5. System Maintenance

The user interface consists of a table for viewing companies, plus the login screen. Everything is implemented in multiple files, using only HTML and PHP.
There is a file for each "section": one for managing the login, one for checking and directing to the correct page, one for logging in as a student, one for logging in as tutor, one for viewing specific information, one for editing companies and one for managing logout.

On first launch, the application displays the login screen. Once the user is logged in, the view switches to the company table, which is displayed in the center of the screen. There is also a search bar at the top of the page.
The logout button is located on the right and destroys all of the data associated with the current session.

The connection to the database, made at the code level, allows you to view the companies, their information and modify them, also changing the corresponding record.
