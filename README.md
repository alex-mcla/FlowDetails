# FlowDetails

This is a Power Automate Flow to produce Markdown content with details of Flows.

The flow is manually run with two parameters:

- The maximum number of flows to be included in the output
- A string to match the users' email address who created the flows - use your domain.com for all flows in the environment create by your organisation's users

The final step in the flow is a Compose that will contain the Markdown content that can be copied and pasted into an Azure Wiki page.
