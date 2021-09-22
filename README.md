# Markdown Blog Dashboard
[Click here to see the project live!]()
# Table of Contents
  - [1.0 Overview](#10-overview)
    - [1.1 Description](#11-description)
    - [1.2 Technologies](#12-technologies)
    - [1.3 Features](#13-features)
  - [2.0 How to Use](#20-how-to-use)
  - [3.0 License](#30-license)
  - [4.0 Notes](#40-notes)
    - [4.1 Learning Objectives](#41-learning-objectives)
    - [4.2 User Stories](#42-user-stories)
## 1.0 Overview
### 1.1 Description
[Back to table of contents](#table-of-contents)
&nbsp;&nbsp;&nbsp;&nbsp;This project is a dashboard meant for librarians to see information related to books, authors, and librarian visitors.
### 1.2 Technologies
[Back to table of contents](#table-of-contents)
&nbsp;&nbsp;&nbsp;&nbsp;This project uses React, Node, Express, Knex, and PostgreSQL.
### 1.3 Features
&nbsp;&nbsp;&nbsp;&nbsp; A user can:
- sign in
- See total amount of books, books currently borrowed, and total number of visitor accounts
- See most popular genres
- See most popular books 
- See most popular authors
- See a list of all books and see information for individual books
- See a list of all visitor accounts and see information for individual visitors
## 2.0 How to Use
[Back to table of contents](#table-of-contents)
1. Fork and clone repo
2. cd to frontend and backend directories and ```npm install``` to install depedencies
3. cd to backend and create a `.env` file
4. Inside the `.env` file, set ```NODE_ENV``` to `development` or `production`.Set ```PORT``` to a port of your choice. Then set ```DATABASE_URL``` to the url of your database
5. Run ```knew migrate:latest``` and ```knex seed:run``` to migrate and seed
6. Run ```npm install`` to run the API locally
## 3.0 License
[Back to table of contents](#table-of-contents)
MIT License

Copyright (c) 2021 by Suncerie Daye

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## 4.0 Notes
### 4.1 Learning Objectives
[Back to table of contents](#table-of-contents)
- Write user stories that easily translate to features
- Plan architecture of project before touching code
- Write documentation that is easy to follow
- develop multi-page applications using react library
- implement a user authentication system
- implement data structures when manipulating or calculating data 

### 4.2 User stories
[Back to table of contents](#table-of-contents)
#### US-1
As a librarian, I want to see the total amount of book, how many books are checked out, and how many visitor accounts are registered so that I can determine whether the library's book to visitor ratio is appropriate and see how many books are currently unavailable.

#### US-2
As a librarian, I wants to see the most common genres so that I may possible expand our book selection in those genres.

#### US-3

As a librarian, I want to see the most popular books so that I may order more copies of those books.

#### US-4
As a librarian, I want to see the most popular authors so that I may expand our books selection from those authors. 

