# 🏷️ Priority Labels and Categories

This file lists the priority labels and email categories used in the Email Triage Assistant workflow.

## Gmail Priority Labels

| Label | Purpose |
|---|---|
| Priority/High | Emails that may need urgent attention |
| Priority/Medium | Emails that may need review but are not urgent |
| Priority/Low | Emails that are general updates, newsletters, promotions, or non-urgent messages |

## Priority Values

The AI assistant returns one of these priority values:

```text
High
Medium
Low
```

## Notes

* The workflow applies Gmail labels based on priority.
* Categories are logged in Google Sheets for tracking.
* Each email gets one priority value and one category value.