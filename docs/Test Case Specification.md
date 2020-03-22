# Test Case Specification

## 1. Introduction

This document provides the test cases to be carried out for the PCTO Application.  Each part to be tested is represented by an individual test case.  Each case details the input and expected outputs.

## 2. Test Cases: Login

### Test ID: 2.1

| Field         |Description|
|--|--|
|**Title**|Correct login as student|
|**Feature**|Login to use the application as student.|
|**Objective**|Confirm that proper user and password yields access to the website as expected.|
|**Setup**|A web server must be running.|
#### Test Data

Login information:

+ User: *Username existing on Spaggiari*
+ Password: *Password associated with that user*

#### Test Actions

1. Access the login page
2. Select the "student" type
3. Enter login information

#### Expected Results

You access a page that offers the possibility to search for companies in the database, also by applying filters, or to log out.

---

### Test ID: 2.2

|Field|Description|
|--|--|
|**Title**|Correct login as tutor|
|**Feature**|Login to use the application as tutor.|
|**Objective**|Confirm that proper user and password yields access to the website as expected.|
|**Setup**|A web server must be running.|
#### Test Data

Login information:

+ User: *Username existing on Spaggiari*
+ Password: *Password associated with that user*

#### Test Actions

1. Access the login page
2. Select the "tutor" type
3. Enter login information

#### Expected Results

You access a page that offers the possibility to search for companies in the database, also by applying filters, to change them or to log out.

---

### Test ID: 2.3

| Field         |Description|
|--|--|
|**Title**|Incorrect password|
|**Feature**|Login to use the application.|
|**Objective**|Confirm that valid user with an invalid password denies access to the website without leaving the user stranded.|
|**Setup**|A web server must be running.|
#### Test Data

Login information:

+ User: *Username existing on Spaggiari*
+ Password: password1234

#### Test Actions

1. Access the login page
2. Select a user type
3. Enter invalid login information

#### Expected Results

You remain on the login page and you are informed that your login credentials are incorrect.

## 3. Test Cases: Filtering of companies

### Test ID: 3.1

| Field          |Description|
|--|--|
|**Title:**|Adding correct filters|
|**Feature:**|Add filters to search for specific companies.|
|**Objective:**|Confirm that the use of filters reduces the number of companies displayed.|
|**Setup:**|A web server must be running and there must be a connection with the database.|
#### Test Data

Filters applied:

+ Province: Verona
+ District: San Giovanni Lupatoto

#### Test Actions

1. Add the filters in the space provided

#### Expected Results

All the companies present in Verona, in the municipality of San Giovanni Lupatoto, should be displayed.

---

### Test ID: 3.2

| Field         |Description|
|--|--|
|**Title**|Adding inexistent filters|
|**Feature**|Add filters to search for specific companies.|
|**Objective**|Confirm that using inexistent filters does not return any results.|
|**Setup**|A web server must be running and there must be a connection with the database.|
#### Test Data

Filters applied:

+ Province: Zevio

#### Test Actions

1. Add the filters in the space provided

#### Expected Results

No company should be displayed.

## 4. Test Cases: Company information

### Test ID: 4.1

| Field         |Description|
|--|--|
|**Title**|View company information|
|**Feature**|View more information about a particular company.|
|**Objective**|Confirm that clicking on a company displays additional information about it.|
|**Setup**|A web server must be running and there must be a connection with the database.|
#### Test Data

N/A

#### Test Actions

1. Click on a company

#### Expected Results

A page containing more information on the chosen company should be displayed.

## 5. Test Cases: Modify companies

### Test ID: 5.1

| Field         |Description|
|--|--|
|**Title**|Adding companies|
|**Feature**|Add a company to the database.|
|**Objective**|Confirm that by entering the data of a new company, it appears in the list|
|**Setup**|A web server must be running, there must be a connection with the database and the"tutor mode" is required.|
#### Test Data

Company information:

+ Type: Azienda
+ Name: Prova SRL
+ Province: Verona
+ District: San Giovanni Lupatoto
+ Nation: Italia
+ Address: Via Prova, 1
+ CAP: 37057

#### Test Actions

1. Select the "add" option
2. Enter the data
3. Save changes

#### Expected Results

The company should appear on the list.

---

### Test ID: 5.2

| Field         |Description|
|--|--|
|**Title**|Removing companies|
|**Feature**|Remove a company from the database.|
|**Objective**|Confirm that by deleting a company, it doesn't appear in the list anymore.|
|**Setup**|A web server must be running, there must be a connection with the database and the "tutor mode" is required.|
#### Test Data

N/A

#### Test Actions

1. Select the "remove" option
2. Select the company
3. Save changes

#### Expected Results

The company shouldn't appear on the list anymore.

---

### Test ID: 5.3

| Field         |Description|
|--|--|
|**Title**|Modifying companies|
|**Feature**|Modify a company in the database.|
|**Objective**|Confirm that by modifying a company, changes appear in the list.|
|**Setup**|A web server must be running, there must be a connection with the database and the "tutor mode" is required.|
#### Test Data

+ Province: Firenze

#### Test Actions

1. Select the "modify" option
2. Select the company
3. Enter the new data
4. Save changes

#### Expected Results

The changes should appear on the list.