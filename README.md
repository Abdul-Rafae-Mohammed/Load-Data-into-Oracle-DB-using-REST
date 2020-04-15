
# Load JSON Data into Oracle DB using REST

Last Updated:<br>March 01, 2019 
</td>
<td class="td-banner">
# Load JSON Data into Oracle DB using REST
</td></tr><table>

Project to load tweet data into Oracle Database deployed on Oracle Cloud Infrastructure (OCI) using REST.


## Introduction

These instructions will get you a copy of the project up and running on your local or any machine/system for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

## Prerequisites

What things you need to install the software and how to install them


- A pre-provisioned Oracle Database.


## Package Contents

* import-export
  * pythonapp.py
    * Connect to Oracle Database
    * Insert data into Oracle DB using the REST Service.
* source
  * JSON Data 

## Components
* Data Source&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;: Publicly available twitter datasets
* Data Collection and Processing     &nbsp; &nbsp; : Python
* Data Storage                       &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; : Oracle Database on Oracle Cloud Infrastructure


## Steps to Deploy

- Open terminal
- Move to the folder where you want to download the application.
- Create a directory for the application

  ```
  mkdir /pythonApp
  ```
- Move to that directory

  ```
  cd /pythonApp
  ```
- Clone the Github Repository

  ```
  git clone https://github.com/Abdul-Rafae-Mohammed/Load-Data-into-Oracle-DB-using-REST.git
  ```
- Go inside the downloaded repository

  ```
  cd <repo name>/
  ```
  
- Copy a JSON dataset to the current directory or you can use json dataset provided in the repository you downloaded. Alternatively, you can choose from any publicly available datasets as well.

- Run python app

  ```
  python jsonapp.py <REST Endpoint URL> <JSON FILE Name>
  ```

- The output should be as mentioned below.

```
Total Tweets Loaded : xxx
```



## Authors

**Abdul Rafae Mohammed (abdul.rafae@outlook.com)**


