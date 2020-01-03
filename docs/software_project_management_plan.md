# Software Project Management Plan
# Chat Protocol
<data>

#### Team Members
+ Sartori Riccardo
+ Ghisellini Damiano
+ Mafficini Andrea
+ Bianchini Davide

#### Document Control
| Revision | Change Date | Description of Changes |
| -------- | ----------- | ---------------------- |
| V1.0 | 03/01/2020 | Initial Release |

#### Document Storage
This document, along with the rest of the documentation for the project, is stored at https://2020-5bi-team4-sartori.readthedocs.io/en/latest/

## 1 Overview

### 1.1 Purpose and Scope
This project is about creating a chat capable of sending and receiving messages, and that will require a server and a client. The two actors will communicate using a custom protocol defining the type of messages they send to each other. This application will be developed so students can understand a possible application of network-level development and how to do it.

The application will most likely never be used outside the classroom it was developed in, as it is merely an exercise to understand how this part of programming works. No type of help will be provided to the end user, since it's implied they are familiar with the protocol and with how an average client/server application implementing it looks like.

### 1.2 Goals and Objectives

#### 1.2.1 Project Goals
1. Teach students how to program low-level applications.
2. Help students understand how packets are sent or received and which protocols work best in which situations.

#### 1.2.2 Project Objectives
1. Create a server capable of handling multiple requests at the same time using threads.
2. Create a client software that can make use all of the protocol's functionalities.

### 1.3 Project Deliverables

| Date | Deliverable |
| ---- | ----------- |
| 29/10/2019 | Source code for either the client or the server portion |

### 1.4 Assumptions and Constraints

#### 1.4.1 Assumptions
1. All machines have Python 3.7 or higher installed

#### 1.4.2 Constraints
1. The application will use the protocol given to us
2. The application will be written in Python 3.7 or higher
3. The application will be ready by 29/10/2019

### 1.5 Schedule and Budget Summary

![Schedule](img/gantt-1.png)

### 1.6 Success Criteria

Either:
+ A server capable of receiving and handling multiple requests from multiple hosts
+ A client capable of connecting and communicating with a server, interpreting the responses it sends.
All parts of the protocol must be correctly implemented.

### 1.7 Definitions

+ **Student:** A person developing the project, not necessarily part of our team.

### 1.8 Evolution of the Project Plan

As the project is relatively simple, there is only one phase to the plan, meaning that there can be no evolution.

## 2 Startup Plan

### 2.1 Team Organization

+ **Project Manager:** Must coordinate the team and take orders from the higher-ups.
	+ Sartori Riccardo
+ **Programmers:** Responsible for developing and testing the application. They must partecipate in team meetings and report to the Project Manager.
	+ Ghisellini Damiano
	+ Mafficini Andrea
	+ Bianchini Davide

### 2.2 Project Communications

The team communicates informally through team meetings and informal gatherings. Team members are free to ask each other information whenever they need it.

### 2.3 Technical Process

The project is small enough to only have one phase, which begins with the start of the app's development and ends when it's finished.

### 2.4 Tools

+ **Programming Language:** Python 3.7 or higher
+ **Version Control:** Source code will be stored in a git repo.
+ **Development Tools:** PyCharm