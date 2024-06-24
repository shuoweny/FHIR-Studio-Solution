# FHIR-Studio
This team project work aim to provide an innovative solution for the client to simulate health data through configuration.
## Table of Contents:

* <a href="#Description">Project Description</a><br>
* <a href="#TeamMember">Team structure</a><br>
* <a href="#Struct">Repository Structure</a><br>
* <a href="#ChangeLog">Changelog</a><br>

<h2 id="Description">Project Description:</h2>
FHIR Studio is a web-based platform for simulating patient data in the Fast Health Interoperability Resource (FHIR) standard, which will eventually contribute to developing the Validitron Sandbox. This project devised, prototyped, implemented and tested a UI-driven workflow ‘data scaper’ for engineering realistic simulated time series data for clinical measurements. The simulated data can be staged, configured, and then pushed to a receiving clinical system. The data may be used for testing and validating the developing digital health software so that the developer avoids collecting real patient data, which is expensive and time-consuming.

This repository contains the deliverables of each sprint and is accessible to the client. It stores the history of the development process and enables the client to monitor the progress easily.

<h2 id="TeamMember">Team structure:</h2>

1. Shuowen Yu&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; &emsp;&emsp;&emsp;Team Member&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;shuoweny@student.unimelb.edu.au
2. Yuchen Cao&nbsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; &emsp;&emsp;&emsp;Team Member&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;yuccao@student.unimelb.edu.au
3. Yanbo Lu&nbsp;&nbsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; &emsp;&emsp;&emsp;Team Member&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;yanbol3@student.unimelb.edu.au
4. Jie Zhou&nbsp;&nbsp;&nbsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; &emsp;&emsp;&emsp;&emsp;Team Member&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;jiezhou5@student.unimelb.edu.au
5. Yulong Huang&emsp;&nbsp;&emsp;&emsp;&emsp;&emsp; &emsp;&emsp;&emsp;Team Member&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;yulongh@student.unimelb.edu.au
6. Naveed Ali&nbsp;&nbsp;&nbsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; &emsp;&emsp;&emsp;Supervisor&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;naveed.ali@unimelb.edu.au
7. Dr. Kit Huckvale&nbsp;&nbsp;&emsp;&emsp;&emsp; &emsp;&emsp;&emsp;&emsp;Client&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&nbsp;&nbsp;&nbsp;kit.huckvale@unimelb.edu.au


<h2 id="Struct">Repository Structure</h2>

├── [docs/](https://github.com/SWEN90009-2023/FH-Koala/tree/main/docs)&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; &emsp;&emsp;&emsp;# Documentation files for organize the requirements and meeting minutes

  - [Project Background](https://github.com/SWEN90009-2023/FH-Koala/blob/main/docs/Project%20Background.pdf)
  - [FH presentation](https://github.com/SWEN90009-2023/FH-Koala/blob/main/docs/FH%20presentation.pptx)
  
  - [user requirements/](https://github.com/SWEN90009-2023/FH-Koala/tree/main/docs/user%20requirements)&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&nbsp; # The subfolder of "docs" which contains the user requirement related files
  
    - [Requirements Elicitation](https://github.com/SWEN90009-2023/FH-Koala/blob/main/docs/user%20requirements/Requirements%20Elicitation.pdf)
        
    - [Who-Do-Be-Feel](https://github.com/SWEN90009-2023/FH-Koala/blob/main/docs/user%20requirements/Who-Do-Be-Feel.pdf)
    
    - [Goal Model](https://github.com/SWEN90009-2023/FH-Koala/blob/main/docs/user%20requirements/Goal%20Mode.pdf)
    
    - [Personas](https://github.com/SWEN90009-2023/FH-Koala/blob/main/docs/user%20requirements/Personas.pdf)
    - [User Stories](https://github.com/SWEN90009-2023/FH-Koala/blob/main/docs/user%20requirements/User%20Stories.pdf)
    - [User Story Map](https://github.com/SWEN90009-2023/FH-Koala/blob/main/docs/user%20requirements/User%20Story%20Map.pdf)
    


    
├── [tests/](https://github.com/SWEN90009-2023/FH-Koala/tree/main/tests)&nbsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;# User/system tests

  - [Acceptance Criteria](https://github.com/SWEN90009-2023/FH-Koala/blob/main/tests/Acceptance%20Criteria.pdf)
  - [Acceptance Test](https://github.com/SWEN90009-2023/FH-Koala/blob/main/tests/Acceptance%20Test.pdf)
  - [Traceability Matrix](https://github.com/SWEN90009-2023/FH-Koala/blob/main/tests/Traceability%20Matrix.pdf)
  - [Usability Tests](https://github.com/SWEN90009-2023/FH-Koala/blob/main/tests/Usability%20Tests.pdf)

├── [prototypes/low fidelity/](https://github.com/SWEN90009-2023/FH-Koala/tree/main/prototypes/low%20fidelity)&nbsp;&emsp;&emsp;&emsp;&emsp;&emsp;# Contain the Confluence page of low fidelity file and the figma link

  
  - [Low Fidelity Prototype](https://github.com/SWEN90009-2023/FH-Koala/blob/main/prototypes/low%20fidelity/Low%20Fidelity%20Prototype.pdf)
  - [Low Fidelity Prototype Link](https://github.com/SWEN90009-2023/FH-Koala/blob/main/prototypes/low%20fidelity/Low%20Fidelity%20Prototype%20Link.txt)

├── [prototypes/high fidelity/](https://github.com/SWEN90009-2023/FH-Koala/tree/main/prototypes/high%20fidelity)&nbsp;&nbsp;&nbsp;&emsp;&emsp;&emsp;&emsp;# High fidelity files

  - [High Fidelity Prototype](https://github.com/SWEN90009-2023/FH-Koala/blob/main/prototypes/high%20fidelity/High%20Fidelity%20Prototype.pdf)
  - [Figma-high-fidelity](https://github.com/SWEN90009-2023/FH-Koala/blob/main/prototypes/high%20fidelity/Figma-high-fidelity.pdf)
  - [High Fidelity Prototype Link](https://github.com/SWEN90009-2023/FH-Koala/blob/main/prototypes/high%20fidelity/High%20Fidelity%20Prototype%20Link.txt)

├── [prototypes/MoodBoard](https://github.com/SWEN90009-2023/FH-Koala/blob/main/prototypes/MoodBoard.pdf)

├── [ui/](https://github.com/SWEN90009-2023/FH-Koala/tree/main/ui)&nbsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;# All the images created for the prototypes

  - [IT](https://github.com/SWEN90009-2023/FH-Koala/blob/main/ui/IT.jpg)
  - [Validitron Brand - Style Guide](https://github.com/SWEN90009-2023/FH-Koala/blob/main/ui/Validitron%20Brand%20-%20Style%20Guide.pdf)
  - [Validitron Brand - Web and Mobile Elements](https://github.com/SWEN90009-2023/FH-Koala/blob/main/ui/Validitron%20Brand%20-%20Web%20and%20Mobile%20Elements.pdf)
  - [patient_doctor](https://github.com/SWEN90009-2023/FH-Koala/blob/main/ui/patient_doctor.jpg)
  - [researcher](https://github.com/SWEN90009-2023/FH-Koala/blob/main/ui/researcher.jpg)
  - [tada](https://github.com/SWEN90009-2023/FH-Koala/blob/main/ui/tada.jpg)

├── [data samples/](https://github.com/SWEN90009-2023/FH-Koala/tree/main/data%20samples)&nbsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;# Documents of data which would used to simulate/demonstrate the prototype

  - [Data Sample On Confluence](https://github.com/SWEN90009-2023/FH-Koala/blob/main/data%20samples/Data%20Sample%20On%20Confluence.pdf)
  - [data_output](https://github.com/SWEN90009-2023/FH-Koala/blob/main/data%20samples/data_output.xlsx)
  - [data_sample](https://github.com/SWEN90009-2023/FH-Koala/blob/main/data%20samples/data_sample.ipynb)
  - [oxygen_saturation](https://github.com/SWEN90009-2023/FH-Koala/blob/main/data%20samples/oxygen_saturation.csv)

└── README.md

<h2 id="ChangeLog">Changelog:</h2>

**Sprint 1**:

Tag: SWEN90009_2023_FH_Koala_BL_SPRINT1

- Add Project Background
- Add Requirements Elicitation
- Github setup

**Sprint 2**:

Tag: SWEN90009_2023_FH_Koala_BL_SPRINT2
- Add Who-do-be-feel table
- Add Motivational/goal model
- Add Personas
- Move Requirements Elicitation to user requirements

**Sprint 3**:

Tag: SWEN90009_2023_FH_Koala_BL_SPRINT3
- Add User Stories
- Add User Story Map
- Add Low Fidelity Prototype and the figma link

**Sprint 4**:

Tag: SWEN90009_2023_FH_Koala_BL_SPRINT4
- Add Acceptance Criteria
- Add Acceptance Test
- Add Traceability Matrix
- Add Usability Tests
- Add High Fidelity Prototype and figma link
- Add high fidelity from figma
- Add Data Sample On Confluence and the corresponding data sample documents
- Add MoodBoard
- Add image and prototype style pdf to the ui folder

**Sprint 5**:

Tag: SWEN90009_2023_FH_Koala_BL_SPRINT5
- Add presentation slide
