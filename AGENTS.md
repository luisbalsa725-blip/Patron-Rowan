# AGENTS.md

## Project

This is a static personal tracker/dashboard deployed on Vercel.

The app is used for:
- school and academic performance
- subject averages and assessment tracking
- gym/workout tracking
- recovery and health reminders
- water tracking
- habits
- morning and night routines
- reading time
- goals
- finance
- Supabase sync between desktop and phone

## Design Direction

The app is being redesigned as a dark premium personal operating system.

Primary references:
- Fey for dark premium data-rich visual atmosphere
- Linear for workspace structure, speed, hierarchy, and clean product discipline

## Visual Style

Target style:
- near-black background
- premium glass cards
- subtle borders
- soft shadows
- restrained gradients
- compact data cards
- clear typography
- strong hierarchy
- floating navigation dock
- mobile-first layout
- polished empty states
- smooth but subtle micro-interactions

Avoid:
- generic AI dashboard look
- random neon gradients
- inconsistent card styles
- oversized desktop-first layouts
- duplicate CSS systems
- breaking existing logic for visual changes

## Technical Constraints

Preserve existing functionality.

Do not break:
- Supabase sync
- localStorage data
- Vercel deployment
- existing page links
- existing user data structures

Do not remove or rename localStorage keys unless migration code is added.

Prefer:
- shared CSS variables
- reusable classes
- one global theme system
- mobile-first CSS
- simple static-web-app architecture

Do not suggest a full React/Next rewrite unless explicitly requested.

## Implementation Order

Use this order for major UI/UX work:

1. Audit and plan.
2. Shared design tokens/theme.
3. Homepage/dashboard.
4. Command palette.
5. Highest-use pages.
6. Remaining pages.
7. Polish, animations, accessibility.

Do not redesign every page in one uncontrolled pass.

## Component System

Build reusable components for:

- app shell
- page header
- top status area
- floating nav dock
- mobile bottom nav
- desktop sidebar/nav
- dashboard cards
- glass cards
- stat cards
- chart containers
- habit tiles
- workout cards
- assessment cards
- progress bars
- progress rings
- command palette
- modals/sheets
- forms/inputs
- chips/tabs
- empty states
- toast notifications
- sync status


## Definition of Done

Before finishing a task:

- existing functionality still works
- page links still work
- mobile layout is clean
- desktop layout is usable
- shared CSS system is used
- no duplicate design systems are created
- Supabase/localStorage logic is not broken
- changed files are summarized
- risks are listed clearly
