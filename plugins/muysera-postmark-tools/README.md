# Postmark Tools (Muysera)

Runs Postmark's official MCP server, the npm package @activecampaign/postmark-mcp pinned at version 2.1.1, so Claude can work in a Postmark server: list and edit templates, send email, search messages, diagnose delivery, read bounces, manage suppressions and webhooks, and read delivery stats. A safety skill makes Claude ask before sending email or deleting anything.

Setup: set POSTMARK_SERVER_TOKEN (Server API token of the dedicated "Chronicle Staging" Postmark server), DEFAULT_SENDER_EMAIL and DEFAULT_MESSAGE_STREAM as environment variables. Never put the token in this repository. Data goes only to Postmark's API (api.postmarkapp.com).
