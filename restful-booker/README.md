# Student_Rest_API_Newman

## How to run this project

- Clone this project
- Open with Postman / Command Shell
- Run Command:

```console
newman run restful-booker.postman_collection.json -e newshikhi.postman_environment.json
```

- Run Command for Report:

```console
newman run restful-booker.postman_collection.json -e newshikhi.postman_environment.json -r cli,htmlextra
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

- https://documenter.getpostman.com/view/29986135/2s9YR57FFY

## Test case list:

1. ### Create Student

    Create Data Sets Using the Dynamic Random Variables.

2. ### Update Student
    In the test case you need to validate the following field values:
   1.  Token

3. ### Get the Student's Full Details

    In the test case you need to validate the following field values:

   1.  First Name
   2.  Last Name
   3.  Date of Birth
   4.  Total Price
   5.  Depositpaid
   6.  BookingDates
   7.  Additionalneeds
