# Backend Design

## Overview

This repository contains an example of a simple backend web application using JavaScript and Node.js.

It is a student project within the university course **"Backend Development" (5 ECTS)** offered by Åland University of Applied Sciences.

The purpose of this project was to learn how to design and implement a backend web application in Node.js. This backend is built
around the frontend developed in the previous course, **"Frontend Development" (5 ECTS)**, making this course a natural continuation of earlier
work.

This project stores data in an MS Access database. At the time this course is conducted, we have not yet gained deeper knowledge of
relational database design. We work in a Windows environment, and the finished application is deployed on an IIS web server at the end
of the course.

---

## Project Structure

/config – Configuration files

/data – Data sources in various formats for exercises (JSON, XML, MDB)

/masterframe – Frontend HTML files

/public/css – Stylesheet files

/public/images – Layout images (GIF, JPG, PNG)

/public/photos – Personnel registry images

/public/scripts – Frontend JavaScript files

/public/t-veronica, tyrant, uroboros - Files for object observation

/public/virusphoto - Storage for submitted pictures for each object

/public/text - Text information to be displayed on the application

/routes – Route definitions (JavaScript)

/ – Main application files

---

## Installation

git clone https://github.com/BeltonPelton/duvalia.tricell.local-Backend.git

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

- ejs

- multer

- pdfkit

## Disclaimer

This example is intended for educational purposes only and should not be used in production environments.

Security mechanisms included in this project are deliberately simplified to support learning objectives.

## Author

Arthur Dent, Mickey Mouse, Don Lorenzo

Course: Backend Development (5 ECTS)

IT Students

Åland Islands, Finland

2026
