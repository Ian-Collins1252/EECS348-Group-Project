# EECS348-Group-Project 
by David Donaldson, Noah O'grady, Hamzeh Al-Tamari, Ian Collins, Ky Jost

Project Description:

This project purpose is to create a functional calculator that can perform the order of operations on a inputted expression while recognizing any errors that may occur
within the program. We are using c++ for our back-end and HTML/javascript for the front-end I/O. This site is intended to run locally for now however, as we do not have 
a domain to host the site. We worked on this project all semester as a term project to demonstrate the software engineering process and how team development works within
the field. 

Our Team:

Our project manager is David who set up the Teams, GitHub and was our liaison to our professor as well as working on the order of operations code. Ky worked on the error
handling portion of the code as well as keeping notes at all of our meetings throughout the semester. Noah created the front-end I/O for the project including the HTML and
JavaScript to connect the front end to the back-end while. Ian worked on the error handling portion of the code and does quality assurance for the documention and source code.
Hamzeh worked on the order of operations code while also being in charge of the configuration of the softwear. Every member of the group participated in the development of 
this project from documentation to implemtation. 

Installation:

Based upon the OS of your system, download either the Windows or Linux Calculator folder from the GitHub. In order of run the project, your device must have Node.js installed.
Once both of those are downloaded and installed, navigate to the Calculator folder in the terminal and run 'npm install'. After that has finished, run 'node.server.js' and
while holding 'crtl', click on the link that appear in the terminal. The HTML form should open from there, and the project is now running on your device.

User Iteractions with Project:

This software runs using a website to pass an arithemtic expression to our code which returns either the result of the expression or error(s) of the given expression. 
Possible errors are syntax and arithemetic errors ranging from mismatched parantheses, invalid characters, invalid operators, divide by zero, or taking the power of a 
negative number. The user guild to the program is relatively straight forward:

  1. Enter a possibly valid arithmetic expression
  2. Press the 'Solve' button
  3. Recieve either the result or error(s)
