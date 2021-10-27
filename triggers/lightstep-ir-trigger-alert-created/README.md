# jira-trigger-issue-created

This [Lightstep IR](https://lightstep.com/incident-response/) trigger fires when an Incident Response rule is triggered with the webhook URL configured.

## Setup Instructions

#TODO replace by appropriate Lightstep IR instructions / screenshots

**NOTE: Configuring webhooks requires Jira administrator privileges**

### Step 1: Create new webhook
- Navigate to your System Settings in your Jira console 
- Select "Webhooks" from the Advanced Section. 
- Click "Create a Webhook" 

### Step 2: Configure the webhook 
- Name your trigger (e.g. "relay")
- Copy the Webhook URL from your Relay workflow and paste it in the URL field.
- Toggle the box for "Issue: Created" to configure the webhook to trigger when issues are created.