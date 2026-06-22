# Katie — Strategic Planning Skills

Hi Katie 👋

This plugin powers your AI planning skills inside Claude. Once connected, every skill update reaches you automatically — no downloading or re-uploading.

**About 10 minutes to set up. Five steps.**

---

## Step 1 — Accept the GitHub invitation

You'll receive an email: *"You've been invited to collaborate on maeve-ferguson-consulting/katie-spencer-skills"*

1. Open the email → click **View invitation**
2. Click **Accept invitation**
3. Confirm you can see the repo at `https://github.com/maeve-ferguson-consulting/katie-spencer-skills`

No email? Check spam, or reply to Chad.

---

## Step 2 — Connect Claude to GitHub (one-time)

1. Open the **Claude Code** desktop app
2. Click your profile icon (top-right corner) → **Settings**
3. Scroll to **Integrations** → click **Connect GitHub**
   *(Screenshot: profile → settings → integrations)*
4. Your browser opens to GitHub — click **Authorize**
   *(Screenshot: GitHub authorization page)*

If you already connected GitHub previously, skip to Step 3.

---

## Step 3 — Install the plugin

In any Claude Code conversation, run this command:

```
/plugin marketplace add github:maeve-ferguson-consulting/katie-spencer-skills
```

*(Screenshot: typing the command in Claude Code)*

Claude will find your skill package and ask to install it. Select:
- **Install** when prompted
- Keep **Auto-update** enabled — you'll receive new skills automatically

*(Screenshot: install confirmation dialog)*

---

## Step 4 — Create a project for your planning work

1. In Claude Code, click **Projects** → **New Project**
2. Name it something like "Katie Strategic Planning"
3. Open **Project Knowledge** and paste in any context about your business — your offers, team, revenue, goals. The more context you give, the better the planning sessions will be.

---

## Step 5 — Start with the annual plan

Inside your new project, type:

```
/annualplan
```

This runs you through the full 10x annual planning session. Do this first — it sets the north star that all other planning skills reference.

---

## Your skills

| Skill | What it does | How to trigger |
|-------|-------------|----------------|
| `annual-strategic-planner` | Full annual 10x planning session — sets the 3-year vision, 3 initiatives, quarterly milestones | Type `/annualplan` or "annual planning" |
| `quarterly-strategic-planner` | 90-minute quarterly review and planning — sets the ONE 10x outcome for the quarter | Type `/qsp` or "quarterly planning" |
| `monthly-gameplan` | Monthly execution planning — sets the Big 3 goals tied to the quarterly outcome | Type `/gameplan` or "plan the month" |
| `weekly-plan` | Friday review and plan — reviews the week against the Big 3, sets next week's priorities | Type `/weeklyplan` or "weekly plan" |

---

## How the cascade works

These four skills are designed to work together as a connected planning system:

```
/annualplan  → Sets the 3-year vision and north star
    ↓
/qsp         → Sets ONE outcome per quarter
    ↓
/gameplan    → Sets the Big 3 for the month
    ↓
/weeklyplan  → Reviews the week and plans the next
```

Each skill reads the output of the level above it. Start with `/annualplan`, then run the others in order. If you jump in mid-year, each skill will ask you to confirm the context from the level above.

---

## Getting updates

Skills update automatically when the plugin syncs. You don't need to do anything.

To manually trigger a sync: open Claude Code settings → Plugins → click **Sync** next to this plugin.

---

## Questions

Reply to the email Chad sent you, or text him directly.
