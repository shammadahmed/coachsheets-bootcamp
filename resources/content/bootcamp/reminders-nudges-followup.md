# Lesson 3.5: Reminders, Nudges, and Follow-Up

## Learning Outcomes

By the end of this lesson, you should be able to:

- Apply the BJ Fogg Behavior Model to design effective client reminders
- Choose appropriate timing for reminder delivery relative to worksheet due dates
- Craft reminder messages with encouraging (not nagging) tone
- Determine optimal reminder frequency based on client engagement patterns
- Set up automated reminder sequences in CoachSheets

---

## The Behavioral Science of Reminders

Reminders are not just administrative tools. They are behavioral interventions. Every time you send a client a reminder to complete a worksheet, you are asking them to overcome inertia, competing priorities, and sometimes emotional resistance. Understanding the science behind behavior change makes your reminders more effective and more supportive of the coaching relationship.

### The BJ Fogg Behavior Model

Stanford researcher BJ Fogg developed a simple but powerful model: **B = MAP**. Behavior happens when Motivation, Ability, and a Prompt converge at the same moment.

- **Motivation** -- Does the client want to complete the worksheet?
- **Ability** -- Can the client easily complete the worksheet right now?
- **Prompt** -- Is there a trigger asking them to do it?

If a worksheet is not completed, one of these three elements is missing. Most coaches focus only on motivation ("I should remind them why coaching matters!") but the bottleneck is often ability or the prompt itself.

**Example:** A client who values coaching highly (high motivation) might still not complete a worksheet because they cannot find the link (low ability), or because the reminder email arrived during their busiest work hour (weak prompt).

The Fogg Behavior Model is explained in detail at the official site: https://www.behaviormodel.org/. A practical guide to applying the model in digital products is at https://www.interaction-design.org/literature/topics/fogg-behavior-model.

### Applying B=MAP to Worksheet Reminders

**Boost Motivation:**
- Frame the worksheet as a meaningful step toward their goal, not an obligation.
- Connect each worksheet to the client's stated coaching objective (specific, not generic).
- Use positive reinforcement language: "You are building momentum. Keep going!"

**Increase Ability:**
- Ensure the worksheet link is one tap away (single URL, no login required).
- Optimize worksheets for mobile (as covered in Lesson 3.2).
- Make first question the easiest one (reducing the barrier to starting).

**Design the Prompt:**
- Send reminders at times when the client is likely to have capacity (evenings, weekends, or based on their stated preferences).
- Use the client's preferred channel (email, SMS, or in-app notification).
- Space prompts appropriately (not too many, not too few).

## Timing: When to Send Reminders

The timing of reminders relative to the due date significantly affects completion rates. Research on digital engagement suggests a three-phase reminder strategy:

### Phase 1: The Preview (2-3 days before due date)

Send a preview message when the worksheet is first released. This is not a reminder to complete it yet -- it is a heads-up: "Your new worksheet is ready. It takes about 10 minutes. You have until Thursday to complete it."

This reduces surprise and lets the client mentally schedule the task.

### Phase 2: The Gentle Nudge (1 day before due date)

"If you have not started your worksheet yet, now is a great time. It takes about 10 minutes, and your coach will review it before your session."

This assumes positive intent. It does not say "you have not done it yet." It says "if you have not started yet."

### Phase 3: The Support Check (1 day after due date)

"I noticed the worksheet is still open. No pressure -- life happens. Would a short extension help, or would you like to talk through any resistance that came up?"

This is the most important cue. It shifts from reminder to coaching intervention. If a client consistently needs Phase 3 reminders, the resistance is likely not about time but about something deeper.

The science of timing in behavior change interventions is explored at https://www.behavioraldesign.org/.

## Tone: Encouraging, Not Nagging

The difference between a reminder that strengthens the coaching relationship and one that damages it is tone.

### Avoid These Patterns

- **Guilt-inducing:** "You have not completed your worksheet yet. Please prioritize this."
- **Passive-aggressive:** "Just a reminder that our agreement was to complete worksheets before sessions."
- **Generic:** "Reminder: Worksheet due tomorrow."

These erode trust. They make the client feel like a student who forgot homework rather than a partner in a coaching relationship.

### Use These Patterns Instead

- **Curious:** "How is the worksheet landing for you? Some clients find the values card sort surprisingly challenging."
- **Supportive:** "I am here if any questions come up while you work through the worksheet."
- **Empowering:** "The reflection you do in this worksheet directly shapes our next session. I am excited to hear your insights."

The best reminders feel like the coach is checking in, not checking up.

### Template Messages

Here are message templates you can adapt:

**Preview (Day 0):**
> Hi [Client Name],
>
> Your worksheet "[Worksheet Title]" is ready. It will take about [X] minutes and is designed to help us explore [specific topic]. It is due by [Due Date].
>
> You can access it here: [Worksheet Link]

**Gentle Nudge (Day -1):**
> Hi [Client Name],
>
> A quick heads-up that the "[Worksheet Title]" worksheet is due tomorrow. I review these before our session, so your answers directly shape our conversation.
>
> Here is the link: [Worksheet Link]

**Support Check (Day +1):**
> Hi [Client Name],
>
> I noticed the worksheet is still open. Life gets busy, and there is no judgment here. Would a couple extra days help, or is there something about the questions you would like to discuss?
>
> I am here either way.

## Frequency: Finding the Sweet Spot

Too many reminders feel like nagging and train the client to ignore them. Too few reminders and worksheets get forgotten.

The evidence-based sweet spot for worksheet reminders is **3 total touches**: one preview, one gentle nudge, and one support check. This aligns with the three-phase strategy above.

For clients who consistently complete worksheets without reminders, reduce to 2 touches (preview + one nudge). For clients who struggle, keep 3 touches but adjust the tone of the third to be more supportive and less transactional.

Never send more than 3 reminders for a single worksheet. After the third touch, the issue is no longer about forgetting. It is a coaching conversation about resistance, priorities, or the worksheet design itself.

## Setting Up Automated Reminders in CoachSheets

CoachSheets provides automation rules that handle the reminder sequence automatically. To configure:

1. Navigate to **Automations** in the sidebar.
2. Click **"New Automation Rule"**.
3. Select the trigger: **"When a client is created"** or **"When a session is completed"**.
4. Set the timing type: Send a reminder at a specific offset.
5. Set the timing offset in minutes (e.g., -2880 for 2 days before due date, -1440 for 1 day before, +1440 for 1 day after).
6. Select the worksheet to send.
7. Set the due offset (how many days after sending the worksheet is due).
8. Mark the rule as active.

For a complete reminder sequence, create three automation rules targeting the same worksheet with different timing offsets. CoachSheets handles the rest.

The official CoachSheets documentation on automation rules is linked within the app, and broader marketing automation principles that apply to coaching are discussed at https://www.hubspot.com/resources/behavioral-email.

---

## Assignment

1. Write three reminder messages (preview, nudge, support) for a worksheet called "Identifying Your Core Values." Each should be no more than 100 words and follow the tone guidelines in this lesson.

2. In CoachSheets, set up an automation rule that sends a worksheet 2 days before a client's session with a 48-hour due window. Then configure a follow-up reminder 1 day after the due date.

3. Using the BJ Fogg Behavior Model, analyze a situation where a client has not completed worksheets for two weeks. Identify whether the bottleneck is motivation, ability, or prompt, and write a brief coaching response (200 words) addressing that specific bottleneck.

4. Share your message templates in the course discussion and give feedback to two peers on the tone and effectiveness of their reminders.

---

## Knowledge Check

- What does B=MAP stand for in the BJ Fogg Behavior Model?
- What are the three phases of an effective reminder sequence, and when should each be sent?
- What is the difference between "guilt-inducing" and "supportive" reminder language? Give an example of each.
- What is the maximum recommended number of reminders for a single worksheet?
- What should a coach do if a client consistently needs support-check reminders?
- How do you set up an automation rule in CoachSheets to send a reminder before a session?
- According to the behavior model, what should you check if motivation is high but worksheets are still not being completed?
