# Harness Sketch

Describe Juno's role and task: Juno turns a week of Slack threads, tickets, and call notes into a cited feedback digest for the PM, who decides what happens next.

_Rough first pass, Module 3 Lab 1. Not the AI PRD._

## 01 · Context
The week’s customer-facing Slack threads, support tickets, and CRM call notes. It does not see private DMs.

## 02 · Tools
It can read, count, cite, and post a digest to the PM only. It can’t contact customers, edit Jira or the CRM, draft replies, or order roadmap work.

## 03 · Loop
2 passes. If a source is still ambiguous, it marks NEEDS CLARIFICATION and stops.

## 04 · Memory
Last week’s digest, the PM’s corrections. Everything else starts fresh each run.

## 05 · Permissions
Reading sources, counting mentions, and drafting the digest are automatic. Posting anywhere beyond the PM, and anything that touches a customer, Jira, or the CRM, needs PM approval first. If it spots a promise a rep made that engineering hasn’t confirmed, it flags it to me right away and doesn’t count it as customer demand.

## 06 · Verification
Run it on the five Raw Signals and check the results.
