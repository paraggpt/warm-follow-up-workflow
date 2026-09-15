# Human-in-the-Loop Warm Follow-Up Workflow

A lightweight workflow for turning event connections into relevant, manually reviewed follow-up messages.

## Why this exists

After events, I often returned with 80–100 new connections but followed up with only a small number. The repetitive work was easy to postpone:

- Deciding who was worth contacting
- Reviewing profile context
- Writing a relevant first message
- Keeping track of follow-up status

This project focuses on removing that repetitive work without automating the final decision or message sending.

## Workflow

New connections
→ Relevance filter
→ Context gathering
→ Message draft
→ Human review
→ Manual send

## Principles

- No autonomous sending
- Every message is reviewed and edited by a human
- Use only appropriate, publicly available context
- Do not scrape or store unnecessary personal information
- Respect platform rules and contact preferences
- Avoid bulk or misleading outreach

## Example outcome

In one informal implementation for a freelance business, the workflow
helped start approximately 25–30 conversations in the first month.
Three conversations became paying clients, resulting in approximately
₹1.5 lakh of reported work.

This is an individual case study, not a controlled experiment or a
guaranteed result.

## Example

Input:

- Person: Aarav Mehta
- Role: Founder
- Shared context: Startup meetup
- Relevant topic: Customer onboarding

Draft:

> Hi Aarav, enjoyed our conversation at the startup meetup about customer onboarding. Your point about reducing manual setup stood out to me. I’d be interested to hear how Example Labs is approaching that now.

The message must be reviewed and edited before sending.

## Limitations

- The workflow can produce inaccurate or incomplete context.
- A personalized draft does not guarantee a response.
- Results depend on the quality of the connection and follow-up.
- It should not be used for indiscriminate outreach.

## Possible improvements

- Add contact-priority scoring
- Add follow-up reminders
- Track response and conversion rates
- Add prompt evaluation examples
- Add data-retention controls
- Support CSV and JSON input

## License

MIT License

Copyright (c) 2026

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files, to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY.
