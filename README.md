# Workflow-Chat-Ticket-Alerts
Instructions on how to create Dynatrace Workflow that will retrieve ticket/chat information from the Totango and ingest it to tenant as Bizevents. The Workflow also sends Slack alert messages using the Slack Workflow in Default Workspace and in Sandbox Workspace 

## Configuration steps
- Download the workflow template and upload it to your tenant
- Edit the "variables" task/tile and input the following information:

  | Variable Name      | Description                                                                                   |
  |--------------------|-----------------------------------------------------------------------------------------------|
  | `name`             | Your Name and Surname in the following format: "first_name last_name".                        |
  | `email`            | Your Work Dynatrace Email address.                                                            |
  | `token`            | The Totango [Personal Access Token](https://support.totango.com/hc/en-us/articles/203036939-Personal-Access-Token-and-Service-ID#01GSKRV5MS5573EKJAR6CJHXPR) |
  | `slackWorkflowURL` | The Slack Workflow URL.                                                                       |

- Add the Sandbox and Workflow Integration
