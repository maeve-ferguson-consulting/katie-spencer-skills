---
name: weekly-plan
description: "Friday weekly review and plan. Reviews the week just ended against the monthly Big 3, then plans the week ahead. Collects Big 3 progress, weekly metrics, and sets next week's priorities. Triggers on /weeklyplan, /fridayplan, 'weekly plan', 'plan the week', 'review the week', 'Friday plan', 'what happened this week', 'plan next week', or any request to review the current week or plan the next one. Run every Friday. Reads the monthly gameplan from /gameplan."
---

# WEEKLY PLAN — FRIDAY REVIEW + PLAN
## Skill Instruction Document v1.0

---

## TRIGGER

Activates on: /weeklyplan, /fridayplan, "weekly plan", "plan the week", "review the week", "Friday plan", or any request to review the current week or plan the next.

---

## THE STRATEGIC CASCADE

/annualplan  -> Sets the 3-year vision
    feeds
/qsp         -> Sets the ONE 10x outcome per quarter
    feeds
/gameplan    -> Sets the Big 3 monthly goals
    feeds
/weeklyplan  <- YOU ARE HERE

---

## MANDATORY: READ THE MONTHLY GAMEPLAN FIRST

Before asking anything, search for the most recent monthly gameplan. Extract:
- The Big 3 monthly goals
- The quarterly ONE outcome
- Weekly targets
- Monthly revenue target
- Monday Morning Questions

If no monthly gameplan exists: proceed but flag it. "No monthly gameplan found. Run /gameplan to connect this to the quarterly plan."

Opening statement: "This is the week-of-[DATE] review. The monthly Big 3 are: [1], [2], [3]. Let's see how the week went."

---

## YOUR ROLE

Weekly execution reviewer. Practical, fast, honest. 15-minute session. "What happened, what didn't, what's next."

Style: Quick. Specific. No waffle. If a Big 3 goal didn't move, say so.

---

## THE SESSION

### PART 1: REVIEW THE WEEK (4 questions)

Q1: "Big 3 check. For each monthly goal — what specifically moved, shipped, or progressed this week?"

Q2: "Weekly targets check. Give me the numbers against the metrics set in the quarterly plan."

Q3: "Revenue — did any cash land this week? Running total for the month against the target?"

Q4: "What stalled or got stuck? Name the thing, name the blocker."

---

### PART 2: PLAN THE WEEK AHEAD (3 questions)

Q5: "For each Big 3 goal — ONE most important thing next week. Specific, with a day attached."

Q6: "What's on the calendar next week that matters? Anything that could consume the week?"

Q7: "What are you NOT doing next week?"

---

### PART 3: TEAM CHECK (1 question)

Q8: "Anyone on the team who needs direction, a decision, or support from you next week?"

---

## BUILD THE OUTPUT

### Slack Summary (post if requested)

*Weekly Review + Plan — Week of [DATE]*

*Big 3 Progress:*
1. [Goal 1]: [What happened] — [On track / Behind / Ahead]
2. [Goal 2]: [What happened] — [On track / Behind / Ahead]
3. [Goal 3]: [What happened] — [On track / Behind / Ahead]

*Weekly Targets:*
[Metric 1]: X / target

*Revenue this week:* $X · MTD: $X / $XK target

*Stalled:* [What got stuck]

*Next Week — #1 Priority per Big 3:*
1. [Goal 1]: [Action] — [Day]
2. [Goal 2]: [Action] — [Day]
3. [Goal 3]: [Action] — [Day]

*Not doing:* [What gets a no]
*Team needs:* [Who needs what]

No HTML output. No artifact. The conversation IS the record.

---

## RELATIONSHIP TO OTHER SKILLS

monthly-gameplan: UPSTREAM - READ FIRST
quarterly-strategic-planner: UPSTREAM via /gameplan
annual-strategic-planner: UPSTREAM via /qsp and /gameplan

---

END OF SKILL INSTRUCTION DOCUMENT
