# Pytickdo

Pytickdo is a project of a ticket manager (like Jira of Trello). 
This ticket manager project want to create a communautary ticket manager, handable by a Web App GUI like by Python CLI, abble to interact with a forum, Git, Github, README.md, JetBrain IDE, Visual Studio Code IDE, Slack...
A Python CLI, a Python Back End and React front GUI will allow to create and manage project's ticket in a agile way or in any project way. 

Created and modified ticket will allow to directly follow ticket ongoing on project's README.md (and will be potentially push on GitHub, GitLab...). 

This project is dedicace for open source project, little structure or solo developer, to help them to drive their projects and allow community to openly follow the advancment and participate by coding, comment, vote... 

## Pytickdo CLI
The pytickdo CLI are abble to create ticket and manage it (state of tickects, link with project, branch...) with CLI commant. This ticket will be store in database and created in Markdown on the shape of Mardown/HTML/Javascript badge. 
This CLI act in coordination of TODO IDE list and git commit. TODO list can be link to a ticket or from a TODO we should be abble to create a ticket. With ticket number indicated in the commit, the commit will be automatically link to the ticket. 
This ticket will be store in database and created in Markdown on the shape of Mardown/HTML/Javascript badge which can be dispaly and updated on a README.md and markdown organized in directories. 

## Pytickdo Web App

API to deal with CLI and stock tickets information in a database. The API expose the usage of CLI functionnality on a web application for GUI with a React frontend. 
A forum is also avaible to discuss about a project, about some ticket, to discuss about a ticket vote for prioritisation, and the database will support this forum and ticket vote. 

## Pytickdo stack

+ CLI: Python abble to right Markdown/HTLM/JavaScript
+ Database: PostgreSQL
+ BackEnd: FastAPI
+ FrontEnd: React 

## Tickets for Putickdo

1. Allow Python CLI to write a Mardown/HTML/Javascript badge template in the README.md
2. Database conception.
3. Improve the writing badge in Mardown readmes hierachised in different directories and Mardown file, write all links from different Markdown in the main README.md
4. BackEnd and API interation with the CLI. Allow to set the Python CLI with a secific URL and with token. 
5. More dynamic CLI with ticket advancement, link with projects, vote, like...
6. FrontEnd
7. Implement a system of vote for ticket prioritisation for authorized people, from front GUI of from badge. 
8. Implementation of a forum on the Web App. Interaction of ticket management with the forum 
9. Interaction with Git commit
10. Interaction with JetBrain Todo (plugin? and/or read the code files to find the TODO in code comment)
11. Interaction with Visual Studio Todo (plugin? and/or read the code files to find the TODO in code comment)
12. Interaction with Slack
 