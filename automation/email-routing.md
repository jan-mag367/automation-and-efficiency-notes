# Email routing automation (draft)

## Problem
Shared inboxes require manual sorting and forwarding.

## Proposed solution
Use Power Automate to:
- Monitor a shared mailbox
- Identify emails by subject or keywords
- Route messages to the correct mailbox or Teams channel

## Flow outline
1. Trigger: New email in shared mailbox
2. Condition: Check subject or sender
3. Action:
   - Forward email
   - OR post message to Teams
4. Log basic metadata to SharePoint list
