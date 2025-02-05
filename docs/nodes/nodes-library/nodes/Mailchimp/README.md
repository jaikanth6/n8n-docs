---
permalink: /nodes/n8n-nodes-base.mailchimp
description: Learn how to use the Mailchimp node in n8n
---

# Mailchimp

[Mailchimp](https://mailchimp.com/) is an integrated marketing platform that allows business owners to automate their email campaigns and track user engagement.

::: tip 🔑 Credentials
You can find authentication information for this node [here](../../../credentials/Mailchimp/README.md).
:::

## Basic Operations

<Resource node="n8n-nodes-base.mailchimp" />

## Example Usage

This workflow allows you to add a new member to a list in Mailchimp. You can also find the [workflow](https://n8n.io/workflows/413) on this website. This example usage workflow uses the following two nodes.

- [Start](../../core-nodes/Start)
- [Mailchimp]()

The final workflow should look like the following image.

![A workflow with the Mailchimp node](./workflow.png)

### 1. Start node

The start node exists by default when you create a new workflow.

### 2. Mailchimp node

1. First of all, you'll have to enter credentials for the Mailchimp node. You can find out how to do that [here](../../../credentials/Mailchimp/README.md).
4. Select the Mailchimp list from the *List* dropdown list.
5. Enter the email address in the *Email* field.
6. Select the status from the *Status* dropdown list.
8. Click on *Execute Node* to run the workflow.
