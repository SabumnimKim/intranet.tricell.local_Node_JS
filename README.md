# Backend Design

## Overview
This repository contains an example of a simple backend web application using JavaScript and Node.js.

It is a student project within the university course **"Backend Development" (5 ECTS)** offered by Åland University of Applied Sciences.

The purpose is to teach first-year university students how to design and implement a backend web application in Node.js. This backend is built around the frontend developed in the previous course, **"Frontend Development" (5 ECTS)**, making this course a natural continuation of earlier work.

This project stores data in an MS Access database. At the time this course is conducted, students have not yet gained deeper knowledge of relational database design. The students work in a Windows environment, and the finished application is deployed on an IIS web server at the end of the course.

For instructional purposes, the project uses the MD5 hashing algorithm for passwords. This intentionally weak algorithm is used to demonstrate security vulnerabilities and to provide practical understanding of why stronger algorithms such as bcrypt or Argon2 are recommended.

---

## Project Structure

/config           – Configuration files  
/data             – Data sources in various formats for exercises (JSON, XML, MDB)  
/masterframe      – Frontend HTML files  
/public/css       – Stylesheet files  
/public/images    – Layout images (GIF, JPG, PNG)  
/public/photos    – Personnel registry images  
/public/scripts   – Frontend JavaScript files  
/routes           – Route definitions (JavaScript)  
/                 – Main application files  

---

## Installation

git clone https://github.com/SabumnimKim/intranet.tricell.local_NodeJS.git
npm install


## Dependencies

- body-parser
- config
- cookie-parser
- express
- express-session
- formidable 2.0.1 (important, version must be correct)
- node-adodb
- nodemon
- pug
- xml2js


## Disclaimer

This example is intended for educational purposes only and should not be used in production environments.
Security mechanisms included in this project are deliberately simplified to support learning objectives.


## Author

Kim Gylling, M.Eng, B.Sc
Higher Education IT Program
Course: Backend Development (5 ECTS)
IT Lecturer and Programme Manager
Åland Islands, Finland
kim.gylling@ha.ax
2022

