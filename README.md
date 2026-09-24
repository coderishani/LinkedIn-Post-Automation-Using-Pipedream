# LinkedIn Post Automation Using Pipedream

A Pipedream workflow designed to automate LinkedIn post creation using a webhook trigger and LinkedIn integration.

## Project Overview

This project demonstrates how workflow automation can be used to trigger and create LinkedIn posts programmatically.

The workflow consists of:

- An HTTP webhook trigger
- A LinkedIn post creation action
- Configured post text
- An article/image URL
- Successful execution testing

## Workflow

Webhook Trigger
↓
LinkedIn Create Post
↓
Post Text + Article/Image URL
↓
LinkedIn Post Creation

## Tools & Technologies

- Pipedream
- LinkedIn
- Webhooks
- Workflow Automation

## How It Works

1. An HTTP request is received by the Pipedream webhook.
2. The webhook provides event data to the workflow.
3. The LinkedIn action uses the configured LinkedIn account.
4. Post text and an article/image URL are supplied.
5. Pipedream sends the post creation request to LinkedIn.

## Testing

The workflow components were tested during development.

- The webhook trigger was tested using a generated HTTP request.
- The LinkedIn post creation action was tested successfully.
- Pipedream returned a successful execution result for the LinkedIn action.

Example result:

`Successfully created a new Post as User`

## Project Status

The workflow was developed and tested in Pipedream.

Production deployment was not enabled because deployment requires a plan that is not available under the current account.

## Screenshots

### Workflow

![Pipedream Workflow](screenshots/workflow.png)

### Successful LinkedIn Post Creation

![Successful Execution](screenshots/successful-execution.png)

## Learning Outcomes

Through this project, I learned about:

- Webhook-based workflow triggers
- Workflow automation
- Connecting external services
- LinkedIn integrations
- Testing automation workflows
- Event-driven workflows
