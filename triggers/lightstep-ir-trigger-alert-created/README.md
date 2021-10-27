# jira-trigger-issue-created

This [Lightstep IR](https://lightstep.com/incident-response/) trigger fires when an Incident Response rule is triggered with the webhook URL configured.

## Setup Instructions

### Create a Relay Automation rule in Lightstep IR

- Navigate to `Automation` in Lightstep IR
- Click `Create New rule`
- Name your automation rule, for example `Trigger Relay Workflow`
- Optionally, specify filter criteria
- Click `Save and Continue`
- On the `Response rule actions` page, click `API / Webhook`
![image info](/media/configure-trigger.png)
- Copy the Webhook URL from your Relay workflow and paste it in the URL field.
- Optionally, click `Test` to test triggering the workflow.
- Click `Save Actions`

Your automation rule now will trigger the Relay workflow.