# Lesson 3.8: Final Project -- Build a Complete Intake System

## Learning Outcomes

By the end of this lesson, you should be able to:

- Design and build a comprehensive intake worksheet using multiple element types
- Configure automation rules linking client creation to worksheet delivery
- Set up a multi-touch reminder sequence with appropriate timing
- Test the complete intake workflow end-to-end
- Evaluate your intake system against a defined rubric

---

## Project Overview

For the final project of Module 3, you will build a **complete digital intake system** using CoachSheets. This is not just a single worksheet. It is an automated workflow that begins the moment a new client joins your practice and delivers a structured intake experience without manual intervention.

A well-designed intake system sets the tone for the entire coaching relationship. It is the client's first experience of your digital coaching practice. A good intake system feels welcoming, organized, and professionally guided. A poor intake system feels confusing, overwhelming, or impersonal.

Your intake system must include four components:

1. **An intake worksheet** with at least 5 question types
2. **An automation rule** that delivers the worksheet when a new client is created
3. **A reminder sequence** with at least 3 reminders spaced at least 2 days apart
4. **A test run** with a dummy client to verify the system works

---

## Requirements

### Component 1: Intake Worksheet (40 points)

Build an intake worksheet that meets these requirements:

| Requirement | Points | Description |
|---|---|---|
| Minimum 8 questions | 5 | The worksheet must contain at least 8 questions |
| Minimum 5 element types | 10 | Use at least 5 different element types from the available library |
| Progressive disclosure | 5 | Questions must be ordered from easy/approachable to deep/vulnerable |
| Clear instructions | 5 | Every question must have a clear label and help text |
| Mobile-friendly | 5 | All elements must be usable on a mobile screen |
| Worksheet title and description | 5 | A professional title and context-setting description |
| Required toggle appropriate | 5 | Required/optional toggles must be justified per question |

**Required element types:** You must include at least one of each of these categories:
- A **visual assessment** element (Wheel of Life, Progress Rings, Energy Map, etc.)
- A **sorting/ranking** element (Cards, Values Card Sort, Priority Matrix, etc.)
- A **scalar** element (Scale, Slider, Confidence Ladder, Percentage Slider, etc.)
- A **reflection** element (Textarea, Thought Record, Future Self Chat, etc.)
- A **structured framework** element (Decision Matrix, Eisenhower Matrix, SWOT, Cognitive Distortions, etc.)

### Component 2: Automation Rule (20 points)

| Requirement | Points | Description |
|---|---|---|
| Correct trigger | 5 | Automation must trigger on new client creation |
| Worksheet attached | 5 | The intake worksheet must be selected as the automated assignment |
| Due offset set | 5 | A reasonable due date must be configured (recommended: 3-7 days) |
| Rule is active | 5 | The automation rule must be marked as active |

### Component 3: Reminder Sequence (25 points)

| Requirement | Points | Description |
|---|---|---|
| Minimum 3 reminders | 5 | At least three reminder touches for the intake worksheet |
| Appropriate spacing | 5 | Reminders must be spaced at least 2 days apart (e.g., Day -4, Day -2, Day +1) |
| Varied timing types | 5 | Use a mix of pre-due and post-due reminders |
| Professional tone | 5 | Reminder messages must follow the encouraging (not nagging) principles |
| Configuration matches strategy | 5 | The reminder timing must match the three-phase strategy (preview, nudge, support) |

### Component 4: Test Run (15 points)

| Requirement | Points | Description |
|---|---|---|
| Create a dummy client | 3 | Create a test client in CoachSheets |
| Trigger the automation | 3 | The intake worksheet must be automatically assigned |
| Complete the worksheet | 3 | Fill out all questions as a test client would |
| Verify reminders | 3 | Confirm that reminder timings are correctly configured |
| Screenshot evidence | 3 | Take screenshots of the completed workflow |

---

## Step-by-Step Guide

### Step 1: Plan Your Intake Worksheet

Before opening the builder, plan your worksheet on paper or a document. Decide:

- **Your coaching niche:** What type of coaching do you offer? The intake questions should match.
- **The worksheet flow:** Map the progressive disclosure arc from first question to last.
- **Element types:** Which 5+ types will you use, and where?

**Example plan for a life coach:**

1. Energy check-in (Scale, 1-10) -- Easy start
2. Life satisfaction overview (Wheel of Life) -- Visual, holistic
3. Top values identification (Cards / Card Sort) -- Interactive, reveals priorities
4. Goal clarity (Textarea) -- Reflection, builds on the previous questions
5. Obstacle exploration (Thought Record) -- Structured, surfaces beliefs
6. Decision about focus area (Decision Matrix) -- Action-oriented
7. Readiness for change (Confidence Ladder) -- Scalar, quantifiable
8. Open reflection (Textarea, optional) -- Gentle closing

This plan uses 7 element types across 8 questions with clear progressive disclosure.

### Step 2: Build the Worksheet

Open the CoachSheets Builder (Quick Tweak or Canvas) and build your worksheet following the plan. Refer to Lesson 3.3 for detailed builder instructions if needed.

For each question, ensure:
- The label is a clear, complete question
- The help text provides guidance and sets expectations
- The element type is appropriate for the coaching objective
- Required/optional is correctly set

### Step 3: Configure the Automation Rule

Navigate to Automations and create a new rule:

1. **Name:** "New Client Intake Delivery"
2. **Trigger:** "When a client is created"
3. **Worksheet:** Select your intake worksheet
4. **Due offset:** Set to 5 days (recommended for intake)
5. **Status:** Active

### Step 4: Configure the Reminder Sequence

Create additional automation rules for each reminder. You will need three rules in total:

| Rule | Name | Trigger | Timing Offset | Tone |
|---|---|---|---|---|
| 1 | "Intake Preview" | Client created | +1440 min (1 day after creation) | Preview: "Your intake worksheet is ready..." |
| 2 | "Intake Gentle Nudge" | Client created | +4320 min (3 days after creation) | Nudge: "If you have not started yet..." |
| 3 | "Intake Support Check" | Client created | +7200 min (5 days after creation, or Day +1 past due) | Support: "No pressure, would an extension help?" |

Each rule attaches the same worksheet but with different timing offsets. Remember: timing offset is relative to the trigger (client creation), not relative to each other.

### Step 5: Test the System

1. Create a dummy client with a test email address you can access.
2. Verify that the intake worksheet is automatically assigned.
3. Open the worksheet link (as the client would see it).
4. Complete all questions on a mobile-sized browser window.
5. Submit the worksheet.
6. Verify that the reminder sequence is scheduled correctly in the automation logs.
7. Take screenshots at each stage for your submission.

### Step 6: Document and Submit

Prepare a submission document that includes:

- **Worksheet name and description**
- **Question list** (number, element type, label, required/optional)
- **Progressive disclosure justification** (explain your question order)
- **Automation rule configuration** (screenshot or description)
- **Reminder sequence** (three rules with timing and message text)
- **Test results** (screenshots of assigned worksheet, completed worksheet, and any delivery confirmations)
- **Reflection** (300 words on what you learned and what you would improve)

---

## Rubric (Auto-Verifiable Criteria)

The following criteria can be verified by reviewing your CoachSheets account or submission document:

| Criterion | How to Verify |
|---|---|
| Worksheet exists in account | Check Worksheets list in CoachSheets |
| 8+ questions | Count questions in the worksheet |
| 5+ element types | List element types used |
| Wheel of Life or similar visual assessment | Confirm one visual element is present |
| Card sort or ranking element | Confirm one ranking element is present |
| Scale or slider element | Confirm one scalar element is present |
| Textarea or reflection element | Confirm one open-ended element is present |
| Structured framework element | Confirm one framework element (Decision Matrix, etc.) is present |
| Progressive disclosure order | Review question order for easy-to-deep progression |
| Automation rule exists | Check Automations for a new-client-triggered rule |
| Automation rule is active | Confirm status is "Active" |
| 3 reminder rules configured | Check that three rules exist with different timing offsets |
| Reminder spacing >= 2 days | Calculate gaps between reminder timings |
| Pre-due and post-due reminders present | Confirm at least one reminder before and one after due date |
| Test client exists | Check Clients list for a test/dummy client |
| Worksheet assigned to test client | Confirm the assignment is visible in Assignments |
| Worksheet completed by test client | Confirm submission exists in Submissions |

## Passing Threshold

To pass the final project, you must meet at least 14 of the 18 criteria above. If you do not pass, review the feedback on your submission, revise your intake system, and resubmit.

---

## Stretch Goals (Optional)

If you want to go further, add these enhancements:

- **Add a second worksheet** to the sequence (e.g., a coaching agreement worksheet released 2 days after the intake).
- **Create a program** that includes your intake worksheet as Week 1 of a structured program (see Lesson 3.4).
- **Configure AI summary generation** for the intake worksheet (requires client consent setup per Lesson 3.6).
- **Design a group intake** using the Groups feature for cohort-based coaching programs.
- **Set up Zapier integration** to add the client to your email marketing list when the intake worksheet is completed.

---

## Submission Checklist

- [ ] Intake worksheet created with 8+ questions and 5+ element types
- [ ] Progressive disclosure verified
- [ ] Automation rule configured and active
- [ ] 3 reminder rules with 2-day spacing
- [ ] Pre-due and post-due reminders included
- [ ] Test client created
- [ ] Worksheet assigned and completed by test client
- [ ] Screenshots captured
- [ ] Reflection written (300 words)
- [ ] 14 of 18 rubric criteria met

---

## Assignment

Complete the intake system project following the requirements and rubric above. Submit your documentation and screenshots to the course assignment portal by the deadline. Peer reviews will follow in the course discussion forum.

---

## Knowledge Check

- What are the four components of a complete intake system?
- List the five element type categories that must be represented in your worksheet.
- How many reminder rules are required, and what is the minimum spacing between them?
- What is the recommended due offset for an intake worksheet (in days)?
- What trigger should your automation rule use for new client intake?
- How many of the 18 rubric criteria must you meet to pass the project?
- Why is it important to test with a dummy client rather than assuming the system works?
- What documentation should you include in your project submission?
