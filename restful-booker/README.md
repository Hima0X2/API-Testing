# Student_Rest_API_Newman

## How to run this project

- Clone this project
- Open with Postman / Command Shell
- Run Command:

```console
newman run StudentDetails.postman_collection.json -e StudentDetails.postman_environment.json
```

- Run Command for Report:

```console
newman run StudentDetails.postman_collection.json -e StudentDetails.postman_environment.json -r cli,htmlextra
```

## Technology used:

- Postman
- Newman

## Prerequisite:

- Jdk
- Node Js
- Newman
- Html Report Library

## Newman and Report Installation Process:

- Newman Install Command:

```console
npm install -g newman-reporter-htmlextra
```

- Newman Html Report Install Command:

```console
npm install -g newman-reporter-htmlextra
```

## API Documentation:

- https://documenter.getpostman.com/view/13082503/2s93Xwz4Az

## Test case list:

1. ### Create Student

    Create Data Sets Using the Dynamic Random Variables.

2. ### Verify Crated Student Details

    In the test case you need to validate the following field values:

   1.  First Name
   2.  Middle Name
   3.  Last Name
   4.  Date of Birth

3. ### Update Student
    In the test case you need to validate the following field values:
   1.  Only Message
4. ### Verify Verify Updated Student Details

    In the test case you need to validate the following field values:

   1.  First Name
   2.  Middle Name
   3.  Last Name
   4.  Date of Birth

5. ### Create Technical skills Create Student Address

    In the test case you need to validate the following field values:

   1.  Only Message

6. ### Create a Student Address

    In the test case you need to validate the following field values:

   1.  Only Message

7. ### Get the Student's Full Details

    In the test case you need to validate the following field values:

   1.  First Name
   2.  Middle Name
   3.  Last Name
   4.  Date of Birth
   5.  Language
   6.  Year Of Experience
   7.  Last Used Date
   8.  House Number
   9.  City
   10.  State
   11.  Country
   12.  Std Code
   13.  Home Address
   14.  Mobile

8. ### Delete Specific Student
    In the test case you need to validate the following field values:
   1.  Only Message
