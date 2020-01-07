Standard Project Flow Procedures

== SOP ==
* Establish the development process at a high level (This document)

== Enhancement Queue == 
* Anyone may place bugs and enhancement ideas in the enhancement backlog 
* Agree on How to write a change request
* Grooming the enhancement backlog
** How often: 1 hour a week
** Who:
*** The product owner
*** At least 1 developer
*** At least 1 business person
*** At least 1 QA/Tester
* Process
** Read each item, oldest first
** Does the enhancement make sense?
*** Can it be recreated?
*** Does the Product Owner understand the enhancement?
*** Does it make business sense? (ie: profitable, broad need, or sensitive customer)
*** Does it have a different resolution?
*** If it's lacking info, then work with requester to provide the proper context
** If it makes sense, create a new tracker item. Include
*** Summary of change
*** Description of problem
*** Steps to create / Recreate
*** Office who reported the problem
*** Due date -- if any
** The item will be prioritized, packaged up with a project, or deferred during the Tracker Review

== Product Management (PPT) == 
* Products are initiated, packaged  prioritized by the [Product%20Planning%20Team.doc Product Planning Team].
* The [Project%20Inventory.doc Project inventory] is a list of possible future projects
* Optionally maintain a [Project%20History.doc Project history] to track what was done

== Project Management == 
* Vision
** The Project Vision describes at a high level the set of features for a project. The goal is for everyone involved to share their vision of the end result.
** sample Vision template (Vision%20Template.doc)
* Define the methodology
** This is when you'd decide whether to use agile or waterfall or some other hybrid
** Agile is better for projects where the requirements and scope are uncertain, but the resources and time frame are fixed
** Waterfall is better for projects where the requirements are known and fixed, and the time frame is flexible
** Depending on the size of the project, develop Project Plan
** In agile projects the team also writes a Definition of Done and a Release Plan.
*** DefinitionofDone.docx Definition of Done
*** Release%20Plan.docx Release Plan
* Generating the feature backlog, and backlog grooming
** At the start of the project, the team and stakeholders will create a set of features based on the vision.
** One way to generate these features is through [[User_story_mapping | User story mapping]]
** After the project starts, the Product Owner, Scrum Master, and possibly other stakeholders will meet once a week to groom and align the features as the project evolves.
* Feature Prioritization
** List of uniquely prioritized features
** Set of Release points (minimum viable feature set)
* Feature Estimation
** Development's best estimate for the time required to implement a story or feature
* Specification
** When using a waterfall project methodology, the development team will create the following documents:
*** User requirement Specification (URS). There may be multiple URS documents depending on the number of features. [One-Page%20URS.doc Here is an example]
*** URS may also be developed using the IBM Rational Requisite Pro tool
*** Software Requirements Specification (SRS). This document describes the code changes for the project. [Software%20Requirement%20Specification.doc Here is an example].
*** SRS may also be developed using the IBM Rational Requisite Pro tool
** Agile Stories
*** Sticky Notes
*** Excel Spreadsheet
*** [https://trello.com Trello]
*** [JIRA]
* Development (see below)
* Integration and Build
* QA
** SOP
** Test environments
* Alpha testing
** Retrospective
** In-house review
* Beta testing
** Beta Site Checklist
** Release to beta
* Feature Documentation
** What's New
** User Guide
** Release Notes template
* Release to production
** Release checklists
** Release automated tests
** Dry run
** General release

== Development Process == 
* Team Roles
** Product Owner / System Expert / Analyst
** Project Lead / Scrum Master
** Developer
** QA
* Development Technologies
** Development language(s) - Front end/ back end
** Database repository
* Revision Control
** Repository
** Branching strategy
* Unit testing
** Manually test the changes
** Manually baseline test existing functionality
** Or, optimally, automate unit tests for the changes
* Acceptance Testing
* End-to-end testing
** Testing Guidelines
** Automated regression testing
* Printed Report Design Guidelines
* Agile philosophy
** Scrum
** Local implementation
** Scrum Cheat Sheet
* Waterfall process
**  Some projects, usually maintenance projects due to changes in regulations, may require a waterfall process.   In that case we use this a waterfall method
* Retrospectives
**  Sprint retrospective
**  Project retrospective
**  Interim retrospectives
*** Beta release
*** Dry run release
*** Other ad hoc milestones
** dialogsheets for facilitating retrospectives
