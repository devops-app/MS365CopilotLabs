# Lab 05 - Prepare, recap, and follow up from meetings with Copilot in Teams

| Item | Detail |
| --- | --- |
| Level | 100 |
| Duration | 15 minutes |
| Apps | Microsoft Teams, Microsoft 365 Copilot |
| Sample files | 04_Mock_Meeting_Notes_Operations_Performance.docx, 01_Mock_Project_Charter_Energy_Data_Platform.docx |

## Scenario

You have been invited to an operational performance review meeting for the mock Energy Data Platform initiative. Before the meeting, you need to understand the project status and prepare discussion topics. After the meeting, you will create a recap, identify actions, and draft stakeholder follow-up communications.

> **Note:** Optional live meeting path: This lab can be completed using the provided mock meeting notes, or extended with an optional live Teams meeting. The live option requires a Teams meeting to be scheduled and run, transcription or Copilot meeting features to be available, and a facilitator to speak continuously for at least 5 minutes so Copilot has enough meeting content to summarize.

> **Note:** Audio quality note: Participants may skip the optional live meeting exercise if the environment is noisy or if multiple people may speak at the same time. This activity works best in a quiet place where the microphone can clearly capture only the facilitator’s voice; background noise and overlapping speech can reduce transcript quality and affect the accuracy of Copilot meeting recap.

## Learning objectives

Use Copilot to prepare for upcoming meetings.

Generate concise meeting summaries and recaps.

Extract decisions, action items, and owners.

Create professional follow-up communications.

Validate meeting outputs before sharing with stakeholders.

## Exercise 1 - Prepare for a meeting

```
I am attending a project performance review meeting.

Using /01_Mock_Project_Charter_Energy_Data_Platform.docx, prepare me for the discussion.

Include:
- Project objectives
- Current priorities
- Major risks
- Questions I should ask
- Decisions that may require management attention

Return the response as a meeting preparation briefing.
```

## Optional Exercise - Run a live Teams meeting for facilitator practice

- [ ] Schedule or start a short Teams meeting for the class or a small practice group.

- [ ] Enable transcription or the meeting features required for Copilot meeting recap, based on the tenant configuration.

- [ ] After joining the meeting, the facilitator should open the meeting controls, select More actions, then start transcription or enable the Copilot meeting feature if it is available in the tenant.

- [ ] Assign one facilitator to speak continuously for at least 5 minutes using the sample speech below.

- [ ] After the meeting, use Copilot in Teams to generate the recap, action items, risks, and follow-up message.

Facilitator sample speech: Welcome everyone to this mock operational performance review for the Energy Data Platform initiative. The purpose of this meeting is to review current progress, identify risks, confirm decisions, and agree on follow-up actions. The project is focused on improving reporting consistency across operations, procurement, HSSE, and project control teams. Based on the mock project charter, the team wants better KPI visibility, clearer ownership of reporting outputs, and a more reliable leadership briefing process. Current priorities include confirming the source files, validating key metrics, and preparing a concise update for senior leaders. One risk is that different teams may interpret KPI definitions differently, so we need a clear owner for data standards. Another risk is that procurement and HSSE updates may be prepared separately, which can make the leadership story fragmented. My suggested decision for today is to confirm which team owns the weekly reporting pack and which manager approves changes to KPI definitions. For follow-up actions, the project lead should prepare a one-page summary, the procurement analyst should review supplier spend trends, and the HSSE coordinator should validate incident and near-miss indicators. Please capture these as action items with owners and due dates where possible. Before we close, we should also agree that all outputs are based on mock training data only and should not be treated as official policy, operational instruction, or real company data.

> **Note:** Fallback option: If a live Teams meeting, transcription, or Copilot meeting recap is unavailable, skip the optional live exercise and continue with Exercise 2 using 04_Mock_Meeting_Notes_Operations_Performance.docx.

## Exercise 2 - Generate a meeting recap

```
Use /04_Mock_Meeting_Notes_Operations_Performance.docx to generate the meeting recap.

Include:
- Meeting purpose
- Main discussion points
- Decisions made
- Risks or blockers
- Open questions
- Recommended next actions

Use an executive meeting recap format.
```

## Exercise 3 - Extract actions and owners

```
Create an action tracker from this meeting.

Use the columns:
- Action
- Owner or accountable role
- Due date if available
- Priority
- Dependency
- Risk if not completed

Return the result as a table.
```

## Exercise 4 - Draft a stakeholder follow-up message

```
Draft a follow-up communication after the meeting.

Audience: Project stakeholders.

Requirements:
- Summarize key decisions
- Highlight important actions
- Mention unresolved issues
- Request updates where appropriate
- Use professional business language

Keep the message under 250 words.
```

## Exercise 5 - Identify risks and escalation items

```
Review the meeting notes and identify items that should be escalated to leadership.

For each item provide:
- Risk description
- Potential impact
- Urgency
- Recommended escalation action

Return the result as a table.
```

> **Note:** Additional prompt library: For more Teams and meeting prompt examples to try after this lab, open https://copilotlabs.dsigncodehub.com/reference/microsoft-365-copilot-prompt-library.html and explore prompts for meeting preparation, recaps, action extraction, open questions, and stakeholder follow-up.

> **Note:** Validation: Before sharing any recap or action tracker, verify that actions, owners, deadlines, and decisions accurately reflect the meeting discussion. Copilot-generated content should always be reviewed by a meeting participant before distribution.
