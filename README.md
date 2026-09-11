# ConnectMachine for Cursor

Connect Cursor to [ConnectMachine](https://connectmachine.ai), the digital
business-card and contact platform. Manage contacts, events, networks, and
your digital cards in natural language.

[![Add ConnectMachine to Cursor](https://cursor.com/deeplink/mcp-install-dark.svg)](https://cursor.com/install-mcp?name=connectmachine&config=eyJ1cmwiOiJodHRwczovL21jcC5jb25uZWN0bWFjaGluZS5haS9tY3AifQ%3D%3D)

## What you can do

- Contacts: create, find, update, and search across name, company, job title,
  email, phone, notes, location, and the event where you met. When two
  contacts share a name, the server asks which one you mean instead of
  guessing.
- Events: track which event you met a contact at.
- Networks: organize contacts into networks (labels).
- Digital cards: create and edit your cards, including websites and socials.
- Housekeeping: merge duplicates, bulk-import leads, export to CSV (Premium).

## Setup

1. Click **Add to Cursor** above, or install the plugin. Either way the
   server is added as `connectmachine`. If you add it by URL instead, Cursor
   names it `server`; rename it to `connectmachine` in the install dialog.
2. On first use, Cursor opens the ConnectMachine sign-in page. Sign in with
   your account email (one-time code) or Google and approve.

Prefer a static key instead of OAuth? Sign in at
https://licenses.connectmachine.ai/mcp/auth to get your personal MCP key,
then add an `Authorization: Bearer <key>` header to the server entry in
`mcp.json`. Keys do not expire.

Requires a ConnectMachine account with onboarding completed in the app.

## Docs and support

- Documentation: https://www.connectmachine.ai/docs/mcp/
- Terms: https://www.connectmachine.ai/en/legal/terms-of-service
- Privacy: https://www.connectmachine.ai/en/legal/privacy
