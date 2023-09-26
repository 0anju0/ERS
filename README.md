# Employee-Review-System
A full stack app used for reviewing employee. Hoisted Link : https://vivacious-beanie-elk.cyclic.app

## Description
A full stack Project, in which the admin can assign the work to employees and  review each other on the basic of there work. 
The admin has special power to make any other employee as the new admin. 
Admin can also make the new employee admin and they can also assing the reviewer and revieweee. 
The admin can see the current employee, and according to the review, the admin can remove the employee. The review given to the employee, is always going to be store in the database.

## Tech Stack
Node , Express, Mongodb , EJS , javaScript , html, css

## How to setup the project on local system
1.Clone this project
2.Start by installing npm if you don't have it already.
3.Navigate to Project Directory.
4.After reaching the project directory you have to run the following the command.

     npm install 
     npm start || nodemon index.js
If you want to make an employee as admin then use the secret key : happy.
## Features
You can review the employees. The admin has the special power to assing, the task to employee, remove the employee, add new admin, and also employee;

## HomePage / Admin View
![image](https://github.com/0anju0/ERS/assets/123807748/39c548b4-8639-4e25-839e-0c3c8c50120f)

## Home page / Employee view
![image](https://github.com/0anju0/ERS/assets/123807748/fb5fdcf2-686f-4291-8d03-2626c967b1d4)

## Sign-Up
![image](https://github.com/0anju0/ERS/assets/123807748/238275e3-f49c-4298-9a07-be3706f2811e)

## Sign-In
![image](https://github.com/0anju0/ERS/assets/123807748/38e1d669-4b20-47a2-bcd5-ee25879957c5)

## Forget Password
![image](https://github.com/0anju0/ERS/assets/123807748/8e9e8004-d78e-41d7-bb07-4a84c086704b)

## Assign Task
![image](https://github.com/0anju0/ERS/assets/123807748/cb4ddce1-252d-4ea0-93c5-62fc4dbf0f11)

## Employee List
![image](https://github.com/0anju0/ERS/assets/123807748/24d95410-2ede-4ab4-8bbc-c583321111f7)

### Folder Structure

Employee Review System
    |
    |               |--->css
    |--->assets---->|--->images
    |                      
    |
    |               |--->flashMiddleware.js
    |--->config---->|--->mongoose.js
    |               |--->passport-local-Stradegy.js
    |
    |                  |-->admin_controller.js
    |--->controllers-->|-->home_controller.js
    |                  |-->review_controller.js
    |                  |-->user_controller.js
    |
    |               |-->review.js
    |--->models---->|
    |               |-->user.js
    |
    |              
    |               |-->admin.js
    |--->routes---->|-->index.js
    |               |-->review.js
    |               |-->user.js
    |
    |              |--->_header.ejs
    |              |---> addEmployee.ejs
    |              |---> admin.ejs
    |              |---> employe.ejs
    |--->views---->|--->forget_password.ejs
    |              |--->home.ejs
    |              |--->layout.ejs
    |              |--->sign_in.ejs
    |              |--->sign_up.ejs
    |
    |-->node_modules
    |-->.gitignore
    |--> index.js
    |--> package-lock.json
    |-->package.json
    
    ````
