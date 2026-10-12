# Security policy

## Reporting a vulnerability

If you find a security issue in this plugin or in the AnimatedWebs MCP server at `https://mcp.animatedwebs.com`, please report it privately through [animatedwebs.com/contact](https://animatedwebs.com/contact) and choose **Security** as the topic. Do not open a public issue.

Please include:

- a description of the issue and its impact,
- steps to reproduce, and
- the plugin version and MCP client you used.

We will acknowledge your report, keep you informed while we investigate, and credit you once a fix ships if you would like.

## Scope

- The plugin files in this repository (skills, commands and manifests).
- The AnimatedWebs MCP server and its OAuth sign-in.

## How the plugin handles access

- Sign-in uses OAuth in your browser. The plugin stores no passwords or API keys.
- Read-only tools are annotated as read-only so your client can run them without extra prompts.
- The server never reads your project files.
