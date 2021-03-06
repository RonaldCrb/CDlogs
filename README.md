# CDlogs REST API!
## UNDER CONSTRUCTION

## Installation

clone repository

```
git clone git@bitbucket.org:RonaldCrb/cdlogs-middleman.git
```

npm install

```
npm install
```

run docker-compose

```
docker-compose up
```
## Usage

this setup compiles and hot reloads code for local development, it is intended to be completely portable. soon i will create a frontend for it.

## Available Endpoints

As the main goal of the project is to organize Dive Records in a programatic fashion, you can start using the it right now ... i will create a user interface with propper authentication and Multi-Tenancy soon and start building functionalities around more powerful documental control services such as Equipment testing and auditing as per DESIGN, FMEA & FMECA, and general Audit and Assurance following international best practices (IMCA, ADCI)

1. GET => http://localhost:3001/api/v1/smartlogs/:id (get Smartlog by ID)
2. GET => http://localhost:3001/api/v1/smartlogs (List of all existing Smartlogs)
3. POST => http://localhost:3001/api/v1/smartlogs (Create a new Smartlog)
4. PUT => http://localhost:3001/api/v1/smartlogs/:id (Update an existing Smartlog)
5. DELETE => http://localhost:3001/api/v1/smartlogs/:id (Delete an existing Smartlog)

# Commercial Diving and the history behind this project

## Background:
I come from the Commercial Diving industry, retired about 2 years ago to become a developer and this is my pet project that ive done multiple times using different frameworks. This time, using Typescript and Express Framework. 

## What are Dive Records?
Commercial Diving dive records, logsheets or "logbooks" as we call them in the industry, are very tedious paperback records of every dive one does in a professional context. these logs are Legal documents and contain all information about the dive including:

1. Safety considerations
2. Diving procedures
3. Weather Conditions
4. Professional Context (contractors and client company names, location, deployment platforms)
5. Equipment testing data
6. Relevant personnel Data

i hope that in the future this web service can help my former colleagues to increase their documental control capabilities as i believe these are the cornerstone of Safety procedures in the offshore industry. everytime i hear about one of my former colleagues having a diving accident, i feel more motivated to push this project forward and i hope i can finish it soon.

## Glossary of terms

1. IMCA (International Marine Contractors Association): formerly known as AODC is the most recognized and reputable organization in the Commercial Diving industry, its guidelines and recommendations are internationally recognized to be the standard for most Diving operations around the world.

2. ADCI (Association of Diving Contractors International): Another key player in the Diving industry, they provide the ADCI Consensus Standards which serves as guidelines and recomendations for diving operations around the world. recently they have come to a mutual recognition agreement with IMCA wich was a very anticipated event by the Diving community.

3. DESIGN (Diving Equipment System Inspection Guidelines Note): based on IMCA documents D-023 and D-024 is the standard for inspection and testing of life support equipment and facilities for surface oriented commercial diving and Saturation diving. CDlogs is an organization intended to adhere to these very guidelines as a way to provide relevant documental control services for life support equipment during offshore Diving operations.

4. FMEA/FMECA (Failure Modes and Effect Criticality Analisys): Begun in the 1940s by the U.S. military, failure modes and effects analysis (FMEA) is a step-by-step approach for identifying all possible failures in a design, a manufacturing or assembly process, or a product or service. It is a common process analysis tool used by Diving Safety Specialists to assess the ways in which a diving system or sub-system can fail and how it affects other systems and sub-systems... in the current situation this is a very complicated process that dramatically increases the operational costs of diving projects and indirectly impacts on the costs associated with project insurance policies https://www.imca-int.com/publications/179/guidance-on-failure-modes-and-effects-analysis-fmea/

## License
[MPL-2.0](https://choosealicense.com/licenses/mpl-2.0/)
