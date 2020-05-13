# Test Plan

### Change History

| Version | Date        | Modifier           | Description of Change |
| ------- | ----------- | ------------------ | --------------------- |
| 0.1     | 14 Apr 2020 | Damiano Ghisellini | Initial draft.        |

## 1. Introduction

This document details the objectives, resources, and processes for a specific test for the PCTO Application. It discovers faults and failures in the software.

## 2. Approach

The overall method of this testing procedure is manual system testing. Each test category corresponds to one or more cases in the [Test Case Specification](test_case_specification.md).
Similar functionality and different types of results will be collected in the same category, but in different cases. Adding new features can sometimes interfere with the functionality of old ones and to ensure project success, all features implemented should function as intended throughout the life of the software.

## 3. Items and Features Tested

The tested features include all the functionalities useful to the user during the research of the companies and during their modification.

- Login page, the ability to access the page using one's own credentials.
In the Test Case Specification: 2.1 - 2.2 - 2.3
- Search bar, the possibility to filter the results by inserting text in the input field.
In the Test Case Specification: 3.1 - 3.2
- Information page, the possibility of obtaining more information about the company by clicking on its name.
In the Test Case Specification: 4.1
- Edit button, the ability to edit company information.
In the Test Case Specification: 5.1 - 5.2 - 5.3

## 4. Item Pass/Fail Criteria

The functions are simple and intuitive, so to consider them functional it will be sufficient that each of them meets expectations. Essential features that cause problems or don't work should be reviewed and corrected before proceeding. The additional non-functional features must be corrected in a short time and only if they do not interfere with the progress of the project.

---

See this document as [PDF](pdf/test_plan.pdf)