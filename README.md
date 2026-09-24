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

The workflow components were tested individually during development.

- The HTTP webhook trigger was configured and successfully received a generated test event.
- The LinkedIn post creation action was tested successfully in Pipedream's test environment.
- Pipedream returned the result: `Successfully created a new Post as User`.

The complete trigger-to-LinkedIn flow was not re-tested after the final webhook event to avoid creating duplicate public LinkedIn posts.

## Project Status

The workflow was developed and tested in Pipedream.

Production deployment was not enabled because deployment requires a plan that is not available under the current account.

## Screenshots

### Workflow

![Workflow](screenshots/workflow.jpeg)

### Successful LinkedIn Post Creation

![Successful LinkedIn Post Creation](screenshots/successful-execution.jpeg)

## Learning Outcomes

Through this project, I learned about:

- Webhook-based workflow triggers
- Workflow automation
- Connecting external services
- LinkedIn integrations
- Testing automation workflows
- Event-driven workflows
