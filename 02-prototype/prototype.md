# Prototype · Juno

> Module 2 · Prototype. The working build that tests your idea, made with your build tool of choice.

## Prototype link

`02-prototype/slack-digest.html` — open in any browser. No server needed.
Or open: [https://vibesharing.app/view/d168a400-ef33-4b67-803c-3746f224eeef](https://vibesharing.app/view/d168a400-ef33-4b67-803c-3746f224eeef)

_____

## What it demonstrates

A PM opens Slack on Monday morning and sees Juno PM's weekly digest in #product-feedback. The message gives a one-sentence headline, three ranked theme blocks with customer quotes and source IDs, a LOW SIGNAL badge on the weakest signal, and an open-questions list with a NEEDS CLARIFICATION flag — everything a PM needs to forward to leadership without editing.

_____

## Debrief

- **What worked:** The format is easy to scan: a headline first, then ranked themes with a mention count, impact, a customer quote, a source link, and one next step. Low-volume items are flagged, and the footer makes clear the PM decides, so it reads like a real Slack message a PM could forward to leadership.
- **What broke / felt like a toy:** Some wording is jargon leaders won't know ("IdP", "callback URL"). Mention counts don't match the sources shown (17 mentions, only 3 tickets cited), and the data is hardcoded, so it proves the format, not that Juno works on real, messy input.
- **What I'd change next pass:** Use plain language, keep next steps to suggestions, and link one source per counted mention.
