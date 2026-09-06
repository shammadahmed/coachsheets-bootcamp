# Lesson 3.4: Automated Programs and Drip Sequences

## Learning Outcomes

By the end of this lesson, you should be able to:

- Distinguish between one-off assignments and multi-worksheet programs
- Configure drip sequences using fixed_offset and fixed_weekly cadences
- Design a structured multi-week coaching program with clear objectives per phase
- Set up program enrollments and manage client progress through a sequence
- Troubleshoot common program delivery issues

---

## One-Off Assignments vs. Programs

In CoachSheets, every worksheet you send falls into one of two categories:

**One-off assignments** are individual worksheets sent at a specific time. They are ideal for check-ins, session preparation, follow-up reflections, or any situation where a single worksheet meets the need. You set a send date and time, the client receives it, completes it, and the assignment is done.

**Programs** are sequences of worksheets delivered automatically over time. A program might contain 4, 8, or 12 worksheets, each released according to a schedule you define. Programs are ideal for structured coaching journeys: onboarding, goal achievement frameworks, habit-building sequences, or any multi-session process.

| Factor | One-Off Assignment | Program |
|---|---|---|
| Use case | Single reflection, session prep, ad-hoc check-in | Multi-week journey, structured curriculum |
| Scheduling | Manual per worksheet | Automatic, pre-defined sequence |
| Client experience | One worksheet at a time | Curated flow, progressive learning |
| Coach effort | Higher (send each time) | Lower (set and forget) |
| Best for | Ongoing coaching, responsive needs | Onboarding, courses, structured programs |

Programs reduce the coach's administrative load while delivering a consistent, progressive client experience. Once designed and activated, a program runs itself.

## Drip Sequences: Fixed Offset vs. Fixed Weekly

The heart of any program is its **drip sequence** -- the schedule that determines when each worksheet is released to the client. CoachSheets supports two cadence types:

### Fixed Offset Cadence

Each worksheet is released a specific number of days after the previous one. For example:

- Worksheet 1: Day 0 (immediately upon enrollment)
- Worksheet 2: Day 3 (3 days after Worksheet 1)
- Worksheet 3: Day 7 (7 days after Worksheet 2)
- Worksheet 4: Day 14 (14 days after Worksheet 3)

Fixed offset is ideal when worksheets build on each other and the timing depends on completion of the previous step. It is also useful when the gap between worksheets should vary (short gap for momentum, longer gap for integration).

### Fixed Weekly Cadence

Worksheets are released on specific days of the week, regardless of when the previous worksheet was completed. For example:

- Worksheet 1: Release on Monday (Day 0)
- Worksheet 2: Release the following Monday (Day 7)
- Worksheet 3: Release the Monday after that (Day 14)

Fixed weekly is ideal for programs that align with a regular session schedule (e.g., weekly coaching sessions every Tuesday). The pattern is predictable for both coach and client.

| Cadence Type | When to Use |
|---|---|
| Fixed offset | Variable gaps, completion-dependent sequencing, momentum-based design |
| Fixed weekly | Regular session schedule, predictable rhythm, group programs |

Both cadences support a **due offset** -- the number of days after release that the worksheet becomes overdue. A common pattern is to release a worksheet 48 hours before a session (fixed weekly, Monday release for Wednesday session) with a due offset of 2 days.

## Designing a 4-Week Onboarding Program

Let us design a practical 4-week onboarding program. This structure works for life coaching, career coaching, health coaching, and most coaching niches.

### Week 1: Intake and Foundation

**Objective:** Gather baseline data, establish the coaching relationship, and set initial direction.

- **Worksheet 1.1:** Life Overview Intake (Wheel of Life + goals textarea + values card sort)
- **Worksheet 1.2:** Coaching Agreement and Session Logistics (collect availability, set expectations)
- **Release:** Immediately upon enrollment (fixed offset Day 0)
- **Due:** Before session 1

### Week 2: Deep Assessment

**Objective:** Explore specific domains identified in the intake and surface limiting beliefs.

- **Worksheet 2.1:** Domain Deep Dive (focused on the lowest-scoring areas from the Wheel of Life)
- **Worksheet 2.2:** Thought Record (identify recurring negative patterns)
- **Release:** Day 7 after enrollment (fixed offset) or next Monday (fixed weekly)
- **Due:** Before session 2

### Week 3: Action Planning

**Objective:** Translate insights into concrete actions and build accountability.

- **Worksheet 3.1:** Decision Matrix (evaluate options for the top coaching goal)
- **Worksheet 3.2:** Weekly Action Plan (specific, measurable steps for the coming week)
- **Worksheet 3.3:** Confidence Ladder (rate confidence for each action step)
- **Release:** Day 14 after enrollment
- **Due:** Before session 3

### Week 4: Reflection and Forward Path

**Objective:** Review progress, integrate learning, and plan the next phase.

- **Worksheet 4.1:** Progress Review (re-rate Wheel of Life, compare to Week 1)
- **Worksheet 4.2:** Future Self Letter (write a letter from their future self who has achieved the goal)
- **Release:** Day 21 after enrollment
- **Due:** Before session 4

This 4-week structure works because it follows a natural coaching arc: **assess, explore, act, integrate**. Each phase builds on the previous one. By Week 4, the client can see measurable progress because they have baseline data from Week 1.

## How to Set Up a Program in CoachSheets

Follow these steps to create your onboarding program:

1. Navigate to **Programs** in the sidebar and click **"New Program"**.
2. Name your program (e.g., "4-Week Life Coaching Onboarding").
3. Add a description that sets client expectations: "This program guides you through your first four weeks of coaching. You will receive a new worksheet every week to complete before your session."
4. Add worksheets in order using the **"Add Step"** button. For each step:
   - Select the worksheet from your library
   - Choose **fixed_offset** or **fixed_weekly** cadence
   - Set the offset in days (e.g., 7 for one week between steps)
   - Set the due offset (e.g., 2 for due 2 days after release)
5. Optionally set an end date for the program if it is time-bound.
6. Save and mark as active.

To enroll a client, navigate to the program, click **"Enroll Client"**, select the client, and set the start date. The program will automatically deliver worksheets according to the schedule.

## Advanced Program Patterns

### Branching Programs

For more advanced use cases, you can create branching paths. For example, a client who scores below 4 on the readiness scale could receive a different Week 2 worksheet than a client who scores above 7. This is achieved by creating separate programs and enrolling based on worksheet results.

### Drip + Session Alignment

Many coaches align their program drip with their session schedule. If you meet a client every Tuesday at 10:00 AM, set worksheets to release on Sunday at 9:00 AM (47 hours before the session) with a due offset of 2 days. The client has Sunday and Monday to complete the worksheet, and you have Monday evening to review it before Tuesday's session.

### Group Programs

You can enroll multiple clients in the same program. Each client's drip schedule is independent and based on their individual enrollment date. This is perfect for group coaching programs where clients start on different dates.

## Troubleshooting Common Issues

- **Worksheet not delivered:** Check that the program is marked active and the client is enrolled with a correct start date.
- **Wrong cadence:** Verify step-level cadence settings. Each step can have its own cadence override.
- **Client not completing:** Review the due offset. If it is too short, clients may feel rushed. If too long, they may lose momentum.
- **Overlapping worksheets:** If a client receives two worksheets on the same day, check that step offsets do not overlap. Buffer of 24 hours is recommended.

The documentation for CoachSheets program features can be found within the app help center, and broader program design principles are discussed at https://www.coachingfederation.org/resources/coaching-competencies.

---

## Assignment

1. Design a 4-week coaching program outline for a specific niche (career transition, health and wellness, leadership, or your own niche). Document:
   - Program name and description
   - The coaching objective for each week
   - The worksheets for each week (titles and element types)
   - The cadence (fixed_offset or fixed_weekly) with specific timing

2. In CoachSheets, create a simplified 2-week version of your program with at least one worksheet per week. Enroll a test client (or create a dummy client) and verify that the first worksheet is delivered.

3. Reflect (200 words): How does structuring coaching into a program change the client experience? What are the potential drawbacks of programs compared to one-off assignments?

---

## Knowledge Check

- What is the difference between a one-off assignment and a program?
- Describe the difference between fixed_offset and fixed_weekly cadences.
- When would you choose a fixed offset cadence over fixed weekly?
- What is a "due offset" and how does it affect the client experience?
- List the four phases of the onboarding program structure described in this lesson.
- How does aligning worksheet release timing with session timing improve the coaching workflow?
- What should you check if a client reports that a program worksheet was not delivered?
- Can multiple clients be enrolled in the same program with different start dates?
