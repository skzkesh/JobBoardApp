# Quick Cash

Project Demo Link: 

## Overview

This repository contains the source code for **Quick Cash**, a Java-based mobile application developed as part of a group project for **CS3130: Introduction to Software Engineering**. The application was built using **Android Studio** with Java and follows key software engineering practices such as **Agile methodology**, **Test-Driven Development (TDD)**, and **Extreme Programming (XP)**.

**Quick Cash** serves as a platform where **employers can post jobs** and **users (employees) can browse and apply for jobs**. The app features a **smart filtering system** that enables users to search for jobs based on their **current location**, **keywords**, and **job category**.

For payment, the app integrates **PayPal** to simulate transactions between employers and employees. Additionally, **Google Firebase** is used to manage authentication, job data, and user information.

The development process was conducted over **three iterations**, each lasting 3–4 weeks. At the beginning of each iteration, the client provided a **story card** outlining the feature requirements. Our team then translated those into **user acceptance tests** and **engineering tasks**, with a strong focus on delivering functional solutions at every stage.

Using **TDD**, we wrote unit and UI tests before implementing new features to ensure code reliability. The project also adopted **CI/CD pipelines via GitLab**, where every code push had to pass build and test processes before being merged. On average, we committed code **2.5 times daily**, enabling rapid and continuous development. Furthermore, the application design follows **SOLID principles** and utilizes appropriate **design patterns** to enhance code maintainability.

---

## Features

- **User Authentication**: Sign up and log in as an employer or employee. Credentials are securely managed via Firebase Authentication.
- **Job Posting**: Employers can create job posts including title, category, salary, description, and location. New job listings appear on the main dashboard.
- **Job Application**: Employees can apply to one or multiple job posts. Once accepted, the job status changes to "To-Do" until marked as completed by the employee.
- **Applicant Management**: Employers can view a list of applicants for each job and accept suitable candidates.
- **Payment Integration**: Once a job is completed, the employer is directed to PayPal to process the payment. Upon completion, the job status is updated to "Completed."
- **Advanced Filtering**: Users can filter job listings based on location, keywords, or job category for a more targeted search.

---

## Installation

### Prerequisites

- Android Studio
- Firebase (Authentication & Realtime Database)
- Google Location API
- PayPal SDK (for simulated payment integration)

---

- All UI and unit tests is accessable through "androidTest/java/com/example/template"
- Code files is accessable through 

## Disclaimer

The full project is not yet publicly available to be pulled due to security considerations. However, this repository includes the complete codebase for each page and its corresponding layout. We hope this serves as a useful reference for developing clean, well-structured Java applications in Android.
