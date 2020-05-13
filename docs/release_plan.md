# Relase plan
### Change History

| Version | Date        | Modifier         | Description of Change |
| ------- | ----------- | ---------------- | --------------------- |
| 0.1     | 01 Apr 2020 | Andrea Mafficini | Initial draft.        |

## Relase Summary

### Initiation

+ **Interview (01/2020):** Request to the tutor what he needs

### Elaboration
+ **Documentation (02/2020):** Documentation about the progress of the project
+ **Database (02/2020):** Design the database with its tables
+ **ETL (02/2020):** Data extraction from CSV to database
+ **Login (02/2020):** Study how Classeviva's login works

### Construction

+ **Login (04/2020):** Build a login page or find a template
+ **Request (04/2020):** Process the login parameters
+ **User page (04/2020):** Build a read-only page
+ **Tutor page (04/2020):** Build an editable page for the tutor
+ **Information page (04/2020):** Build a page with specific information about a company

### Conclusion
+ **Connection (04/2020):** Correct links to the common user and login tutor page

## Effort
### Initiation
| Activities | Actual Effort |
|--|--|
| The project begins with interviews with the PCTO tutor for the required features | 3 hrs |

### Elaboration
| Activities | Actual Effort |
|--|--|
| Creation of documentation regarding a summary of the tutor's requests and to have an ideal overview of the pages that will be made on the site | 8 hrs |
| Designing of tables in the database for data models with PhpMyAdmin | 2 hrs |
| Creation in Python of the code for the ETL process, which allows you to take the data from a CSV file and export it correctly to the database | 10 hrs |
| After being given the PHP snippet of the Classeviva login, study it to modify it for our application | 1 hr |

### Construction
| Activities | Actual Effort |
|--|--|
| Construction of the login page from scratch through forms or through an online search for ready-made templates, modifying them with the link to the Classeviva request | 3 hrs |
| Check the login credentials through a request that compares the data provided by the user with the Classeviva database, with all accounts | 1 hr |
| Construction of the user page with the possibility of displaying the companies through a filtered table, with an extra page with all the information of a company once you select it | 10 hrs |
| Construction of the tutor page with the possibility to modify, create and delete the parameters of a row with an editable table | 10 hrs |
| Construction of a company information page through a parameter passed from the user page, where each company will have a link that leads precisely to this page | 5 hrs |

### Conclusion
| Activities | Actual Effort |
|--|--|
| Have a user control system to understand if it is a common user who wants to log in or a tutor. The modified code will be that of the request which, through an array, will check whether it is a student or a teacher | 30 mnt |

---

See this document as [PDF](pdf/release_plan.pdf)
