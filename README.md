# Parking System

<p align="center">
  <img src=https://user-images.githubusercontent.com/95872501/226944324-cadab981-62de-49b8-9c3b-4e5815154b09.png>
</p>


A command line app for managing the parking system. 
This app uses Java to run and stores the data in Mysql DB.

# Prerequisites

- Java 1.8
- Maven 3.6.2
- Mysql 8.0.17

# Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Installing

A step by step series of examples that tell you how to get a development env running:
1. Install [Java](https://docs.oracle.com/javase/8/docs/technotes/guides/install/install_overview.html)
2. Install [Maven](https://maven.apache.org/install.html)
3. Install [MySql](https://dev.mysql.com/downloads/mysql/)

After downloading the mysql 8 installer and installing it, you will be asked to configure the password for the default `root` account.
This code uses the default root account to connect and the password can be set as `rootroot`. If you add another user/credentials make sure to change the same in the code base.

### Running App

Post installation of MySQL, Java and Maven, you will have to set up the tables and data in the data base.
For this, please run the sql commands present in the `Data.sql` file under the `resources` folder in the code base.

Finally, you will be ready to import the code into an IDE of your choice and run the App.java to launch the application.

# Goal

As part of this project, I achieved the following objectives :
1. Fork this [project](https://github.com/OpenClassrooms-Student-Center/parkingsystem) applying `Getting Started`
2. Correct calculation method
3. Implement new features :
    - Free parking within 30 minutes
    - 5% Loyalty discount
4. Write unit tests
5. Write integration tests

# Class Diagram

<p align="center">
  <img src=https://user-images.githubusercontent.com/95872501/226944917-e851a93c-e867-4b29-a2ff-2d9fb3729ec0.png>
</p>

# SureFire Report

<p align="center">
  <img src=https://user-images.githubusercontent.com/95872501/226964555-ff864ad5-f3e1-4638-b56f-4e66da5834df.png>
</p>

# FailSafe Report

<p align="center">
  <img src=https://user-images.githubusercontent.com/95872501/226964019-dd93708e-eee5-45fd-82a3-37fea48089d3.png>
</p>

# Jacoco Unit Tests Coverage

<p align="center">
  <img src=https://user-images.githubusercontent.com/95872501/226964509-c4d5d4bd-f13d-4f5d-8c09-e4fb1d303ceb.png>
</p>

# Jacoco Integration Tests Coverage

<p align="center">
  <img src=https://user-images.githubusercontent.com/95872501/226964488-581091ea-fea6-45e7-a845-2abce2829d59.png>
</p>

# SpotBug Report

<p align="center">
  <img src=https://user-images.githubusercontent.com/95872501/226964146-455ccfe0-7c55-4b51-b4a9-9d5fbb798625.png>
</p>

