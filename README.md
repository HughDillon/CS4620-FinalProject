# CS4620-FinalProject
Database-Application Android malware database We will be creating a database that has all of the different types of android malware viruses that are running rampant along with their family types

Motivation

● You should find our project interesting because it has application to the computer science field and the database can be used as a tool for cybersecurity purposes ● The project interests us because it’s interesting to see the many types of malware that exist today, along with their variations. We both (Hugh and I) work in the IT Field where we often have to remove malware from infected machines and it’s interesting to know how to classify them.

Dataset

● We will be using data from CCCS-CIC-AndMal-2020 (Canadian Institute for Cybersecurity (CIC) project in collaboration with Canadian Centre for Cyber Security (CCCS) : https://www.unb.ca/cic/datasets/andmal2020.html ● (Note) We may not utilize all available datasets in this database as it is quite large and could cause performance issues on some machines

Methodology

● We will be using C++ to complete this project ● We plan on using other tools such as extensions, libraries, etc throughout the project as well ● We will be using Wt, a 3rd party web GUI library, juce, and boost libraries. ● Basic list of query types we will be using: (1) Finding the malware with the most occurrences across the dataset, (2) comparing different types of malware and how prevalent they are. (3) Comparing the total amount of malware samples found between the different types of malware. (4)Searching for specific malware family names

Milestones, Schedule, and Deliverables

● Week 1: Learn and get used to how the database is layed out, convert files to .db if necessary. Create the database. ● Week 2: Begin writing base program and several basic features(Searching, comparing, etc). Create dynamically based query based on user input. Develop a reasonable input method for users. ● Week 3: Create console based UI that makes the program easy to understand for basic users. ● Week 4: Add any other features that we think would make the project better/ more user friendly, add SQL injection protection ● Week 5: Freshen up UI if possible and smooth out any bugs we find.

Team Members and Responsibilities

● Anthony Dade & Hugh Dillon ● Split the majority of work, but if one of us knows how to create certain features more efficiently, that person will be the one decided to work on the feature. ● Hugh: Backend UI Development, Implement injection security features/ other vulnerabilities, implement queries 1 and 2. General application development ● Anthony: (Frontend) Develop UI, Implement reasonable DB input method and dynamic input method, queries #3, and #
