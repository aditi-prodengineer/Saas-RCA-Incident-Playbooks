# SaaS RCA Incident Playbooks

A small collection of root cause analysis (RCA) write-ups, triage queries and API checks for common problems in B2B SaaS integrations.

> **All scenarios here are fictional.** They are written for practice and as a portfolio. They contain no real customer data, no employer data and no internal details from any company.

## Why this repo exists

When an integration breaks, the useful questions are always the same: what changed, who is affected, what does the evidence say, and how do we stop it happening again. These playbooks show how I work through that, from the first symptom to the follow-up actions.

## What is inside

| Folder | Contents |
|---|---|
| `templates/` | A reusable RCA template |
| `playbooks/` | Three sample RCAs: webhook delivery failures, OAuth 401 errors, and 429 rate limits during a bulk sync |
| `sql/` | Example triage queries for a fictional incident database |
| `postman/` | A Postman collection that checks HTTP status handling against the public httpbin.org service |

## How to use it

1. Start with `templates/rca-template.md` for the structure of an incident write-up.
2. Read one playbook in `playbooks/` to see the template applied.
3. Import `postman/http-status-triage.postman_collection.json` into Postman to try the status checks yourself.
4. Adapt the queries in `sql/triage-queries.sql` to your own schema.

## Topics

`rca` `incident-management` `rest-api` `postman` `webhooks` `sql` `troubleshooting` `saas`

## About me

I am a technical engineer with 4+ years of experience, working on a cloud-based B2B SaaS product. See my profile at [github.com/aditi-prodengineer](https://github.com/aditi-prodengineer).
