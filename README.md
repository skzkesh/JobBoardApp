# Quick Cash #
## Overview
This repository contains the code files for java mobil application developed for a group project from CS3130 Introduction to Software Engineering. This mobile application is developed using Android Studio with Java as the language. Quick Cash is a mobile application that is use for employer to post jobs and for user to find a job. The application is complement with filter system that allows user to find a specific job according to their current location, keywords, and category. For payment, the app is connected to PayPal to simulates payment. Additionally, this app is connected to the Google Firebase as a database to store user information according to their job posts or applications information.

The project was build as an implementation of the best coding practices. The project was developed in a group with Agile Methodolies, means that the work is done iteratively over 3 iterations, where each iteration consist of 3 or 4 weeks long. The focus of the project is to deliver a working solution continuously. We also developed it according to the CI/CD which means that every code push to the repository, will need to go through assemble and debug tests to prevent pushing failing code. We also take an extreme programming approach where we successfully ensure fast and continuous development by pushing on average 2.5 commits daily. Apart from the practical implementation (?), we are also focusing implementing SOLID principles, appropriate design pattern.

## Features
- **User Authentication**: Sign up and log in as an employer or employee. The login credentials will be saved in a Firebase
- **Job Posting**: An employer can create a new job posts which includes the job description (title, category, salary, description, and location). The new job post will appear in the dashboard along with all other job posts
- **Job Application**: An employee that is interested can apply for one or many job posts that are available. When the employer accept them, the job status will change to 'to-do' until the employee report that they are finish with the job.
- **Job Applicants List**: The list of applicants of a job will be displayed for the employer to 'accept' them.
- **Payment Feature**: This app is integrated with PayPal payment system. Once an employee finish their work, they need to change click a done button to change the job status. The status will also be updated to the employer so that they are directed to the PayPal to complete their payment. Once done, the job status will be 'completed'
- **Filter System**: The user can filter their job findings according to the keywords, location, or preferred category.

## Installation
### Prerequisites
- Android Studio
- Firebase
- Google Location API
  
The project also uses the following libraries:
- `axios` - for making HTTP requests
- `@react-native-async-storage/async-storage` - for local data storage
- `expo` - for developing and testing
