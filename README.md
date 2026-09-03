UiPath Business Process Automation

An end-to-end RPA project built with UiPath Studio to automate processing of work items from a web-based business system.

Overview

The automation retrieves work items from the ACME Test web application, extracts the relevant business data, processes and validates it, generates the required hash value, and updates the work item automatically.

The project demonstrates practical experience with business process automation, structured data handling, web automation, transaction processing, exception handling, and UiPath Orchestrator.

Main Features

Automated login and navigation in a web application

Extracted work-item data into a DataTable

Processed multiple records using reusable workflows

Opened individual work items and extracted:

Client ID

Client Name

Client Country

Built the required input string and generated a SHA-1 hash

Updated work items automatically with the calculated result

Implemented pagination to process records across multiple pages

Added validation and exception handling

Used UiPath Orchestrator for execution and monitoring

Structured the automation into Dispatcher / Transaction Processing flows

Technologies

UiPath Studio

UiPath Orchestrator

DataTables

Web Automation

Selectors

Workflow Automation

Transaction Processing

Exception Handling

Automation Flow

Open the ACME Test application

Log in to the system

Extract the work-items table

Filter and iterate through relevant transactions

Open each work item

Extract the required client information

Generate the required SHA-1 value

Update the work item with the generated result

Return to the work-items page

Continue through all available pages

Log execution results in UiPath Orchestrator

Project Structure

UiPath-Business-Process-Automation/
├── Main.xaml
├── project.json
├── Dispatcher/
├── Process/
└── README.md

The exact folder structure may vary depending on the exported UiPath project.

Skills Demonstrated

This project demonstrates hands-on experience with:

End-to-end business process automation

Web-system integration

Structured data processing

Business-rule implementation

Automated transaction handling

Debugging and troubleshooting

Workflow design

UiPath Orchestrator

Reliable automation of repetitive business processes

Screenshots / Demo

Add screenshots or a short demo video here to show the automation running.

Example:

docs/
├── workflow-overview.png
├── orchestrator-run.png
└── demo.mp4

Notes

This repository is intended as a portfolio project demonstrating RPA and automation capabilities.
No credentials, passwords, or sensitive production data are included.

Author

Noa Zucker
B.Sc. Computer Science
Software Engineer | Automation | Integration | Full-Stack Development
