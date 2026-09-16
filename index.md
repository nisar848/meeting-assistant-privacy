# Privacy Policy for Meeting Summarizer GPT

**Effective Date: September 16, 2026**

Meeting Summarizer GPT is designed to help users process meeting transcripts, create meeting minutes, identify action items, track task updates, and manage tasks. This Privacy Policy explains how information may be handled when users use Meeting Summarizer GPT or connect it to supported third-party services such as Trello.

## Information We Access

Meeting Summarizer GPT may process information that users voluntarily provide, including:

- Meeting transcripts
- Meeting notes
- Action items and task information
- Project names
- Due dates
- Task statuses
- Supporting documents
- Other information submitted by the user

When a user connects a third-party service such as Trello, the integration may access information necessary to perform the requested task, including:

- Trello boards
- Trello lists
- Trello cards
- Card titles and descriptions
- Due dates
- Card status and location
- Other Trello information necessary to perform an authorized task

The integration accesses a user's Trello account only after the user authorizes the connection through Trello's authentication process.

## How Information Is Used

Information is used to provide functionality requested by the user, such as:

- Creating meeting minutes
- Identifying confirmed action items
- Reviewing existing tasks
- Comparing meeting tasks with Trello cards
- Checking for potential duplicate tasks
- Creating Trello cards
- Updating Trello cards
- Moving or completing tasks when requested
- Archiving cards when requested
- Reporting task and status changes

Meeting Summarizer GPT is designed not to create or modify Trello tasks merely because a meeting transcript was processed. Trello changes require an authorized user request or synchronization request.

## Authentication and Connected Accounts

Users connecting Trello may be asked to sign in and authorize access through Atlassian / Trello's authentication system.

Users should never enter passwords, API keys, OAuth tokens, client secrets, or other private authentication credentials directly into a ChatGPT conversation.

The Trello integration uses an OAuth authentication process. Cloudflare Workers is used as a secure intermediary between ChatGPT and Trello.

During authentication, temporary information such as OAuth state, authorization handoff information, and authentication tokens may be processed or temporarily stored as necessary to complete the connection.

Temporary OAuth records used by the integration are configured to expire after a short period and are not intended to serve as permanent storage for a user's Trello data.

## Cloudflare Infrastructure

The Trello integration uses Cloudflare Workers to securely communicate between Meeting Summarizer GPT and Trello.

Cloudflare KV may temporarily store information required to complete an OAuth authentication flow, including short-lived authorization state and token handoff information.

This temporary storage is used to authenticate the user and securely connect the user's Trello account. It is not intended to maintain a permanent database of meeting transcripts or Trello cards.

## Third-Party Services

Meeting Summarizer GPT may interact with services including:

- OpenAI / ChatGPT
- Atlassian / Trello
- Cloudflare Workers and Cloudflare KV
- GitHub Pages

GitHub Pages is used to host this Privacy Policy.

Information processed through third-party services may also be subject to those providers' respective privacy policies, security practices, and terms of service.

## Data Sharing

Personal information is not sold to advertisers.

Information may be transmitted to third-party services when necessary to perform functionality requested or authorized by the user, operate the integration, protect the service, or comply with applicable legal requirements.

## Data Retention

Meeting Summarizer GPT's Trello integration is designed to minimize persistent storage of user information.

Temporary OAuth information may be retained for a short period while authentication is being completed and may expire automatically after the authentication window.

Meeting transcripts and other information submitted through ChatGPT may be handled according to OpenAI's applicable policies and account settings.

Trello, Cloudflare, GitHub, and other third-party providers may maintain their own records according to their respective retention policies.

## User Control

Users choose whether to connect Trello.

Users may use Meeting Summarizer GPT for meeting analysis without connecting an external task-management service.

Users may revoke Trello access through the applicable Trello or Atlassian account settings.

Users may also choose not to authorize a requested Trello action.

Meeting Summarizer GPT is designed to distinguish between reading Trello information and modifying Trello information. Actions such as creating, moving, updating, completing, or archiving cards are performed only when authorized through the user's request.

## Security

Reasonable technical measures are used to protect authentication information and communications with connected services.

Sensitive application credentials are stored using protected environment-secret mechanisms rather than being included in public source code or GPT instructions.

Temporary OAuth information is stored only as necessary to complete authentication and is configured with short expiration periods.

However, no internet-based service can guarantee absolute security.

Users should never submit passwords, private API keys, OAuth tokens, client secrets, or other sensitive credentials directly into a ChatGPT conversation.

## Changes to This Privacy Policy

This Privacy Policy may be updated as Meeting Summarizer GPT adds, removes, or changes integrations, infrastructure, or functionality.

The effective date at the top of this page will be updated when significant changes are made.

## Contact

Questions or concerns about this Privacy Policy may be submitted through the GitHub repository:

https://github.com/nisar848/meeting-assistant-privacy/issues
