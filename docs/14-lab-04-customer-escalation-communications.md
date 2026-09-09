---
layout: default
title: "Lab 04 — Customer escalation communications"
---

# Lab 04 — Customer escalation communications

| Level | Duration | Primary apps | Sample files |
| --- | --- | --- | --- |
| 200 | 35 minutes | Microsoft Outlook, Microsoft 365 Copilot | `06_CS_Knowledge_FAQ`, `10_Support_Tickets`, `07_Standup_Notes` |

## Department and industry focus

Customer Service handling a Financial Services escalation, where tone, commitments, and privacy matter a great deal.

## Scenario

A cluster of high-priority billing complaints has hit Contoso Financial. You must communicate crisply to very different audiences — the support team, affected business owners, and executives — without leaking customer data or overcommitting. The same Outlook habits carry into an ordinary day, so this lab also covers the daily rhythm: triaging what arrived overnight, tracking the replies you still owe, and checking tone, commitments, and privacy before anything is sent.

## Learning objectives

- Summarize a noisy escalation into decisions, risks, and actions.
- Draft tiered communications (support team, business owner, executive).
- Turn a thread into a follow-up action tracker with owners.
- Validate tone, commitments, and privacy before sending.
- Run a daily inbox triage and follow-up prompt in Outlook, so the same summarising, drafting, and validation habits apply on an ordinary day and not only during an escalation.

## Exercise 1 — Summarize the escalation

- [ ] Build the mock thread first: open `10_Mock_Customer_Support_Tickets.xlsx`, copy five or six high-priority billing rows for Contoso Financial, paste them into a new Outlook email addressed to yourself with the subject **Billing escalation - Contoso Financial**, add two short replies so it reads as a thread, and send it. Never use a real customer thread for this lab.

```text
Summarize this escalation for the customer service manager.
Include: current status, confirmed impact, likely cause, decisions made,
open questions, risks/blockers, and action items with owner and due date if
stated. Flag anything unverified as 'unconfirmed'. Do not include any real
or invented customer personal or payment data.
```

## Exercise 2 — Tiered stakeholder updates

```text
Draft three updates, each labelled clearly:
1. Support team update: precise, current workstream status.
2. Business owner update: impact and expected resolution, no jargon,
   no blame, under 120 words.
3. Executive update: 4 sentences - impact, status, ETA, decision needed.
All must state this is mock training data and avoid unconfirmed commitments.
```

## Exercise 3 — Daily inbox triage

- [ ] Escalations are occasional; the inbox is daily. Run this prompt in Copilot in Outlook at the start of a working day against your own mock mailbox.

```text
Summarise the mail I received in the last twenty-four hours. Group it as:
- needs a reply from me today
- needs a reply this week
- waiting on someone else
- read only
For each item give the sender, the ask in one line, and a suggested next step.
List separately every commitment or deadline I have made, and flag anything
that reads like an escalation. Use only messages from the last twenty-four
hours, and do not quote customer personal or payment data in the summary.
```

> ✅ **Validation:** This prompt reads your live mailbox, so check the triage before you act on it. Open two or three messages from each group and confirm the sender, the ask, and the suggested next step match what the mail actually says. Verify that every commitment and deadline listed is one you really made, and that nothing older than twenty-four hours has been pulled in. Confirm no customer personal or payment data appears in the summary, and delete or re-run the output if it does. Copilot may miss a message it could not access, so treat the triage as a starting point rather than a complete inbox.

## Exercise 4 — Follow-up action tracker

```text
From this thread, create an action tracker table: Action | Owner or role |
Due date if stated | Priority | Dependency | Recommended follow-up message.
```

> ⚠️ **Quality check:** Before sending, verify recipients, facts, dates, and commitments. Never send mock content to real customers, and never include customer PII or payment detail in an email.
