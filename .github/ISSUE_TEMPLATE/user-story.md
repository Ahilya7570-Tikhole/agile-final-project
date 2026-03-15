---
name: User Story
about: Describes a feature from the user's perspective
title: ''
labels: enhancement
assignees: ''
---

## User Story
As a [role], I need [function], so that [benefit].

## Acceptance Criteria
Given [context], When [action], Then [outcome].

## Additional Notes
(Add any extra details here)
```

4. Scroll down, click **"Commit new file"**
5. Copy the URL of this file — you will submit it for **Task 3**
   - It will look like: `https://github.com/YOURUSERNAME/agile-final-project/blob/main/.github/ISSUE_TEMPLATE/user-story.md`

---

### STEP 4 — Create a GitHub Project (Kanban Board)
1. Go to your repository page
2. Click the **"Projects"** tab → **"New project"**
3. Choose **"Board"** layout
4. Name it: `Agile Final Project Board`
5. Click **"Create project"**
6. You'll see default columns — **rename/add columns** so you have exactly these 5:
   - `Product Backlog`
   - `Sprint Backlog`
   - `In Progress`
   - `Review/QA`
   - `Done`

---

### STEP 5 — Create Labels
1. Go to your repo → **Issues** tab → **Labels**
2. Create these labels if they don't exist:
   - `enhancement` (green)
   - `technical debt` (yellow/orange)

---

### STEP 6 — Create a Milestone (Your "Sprint")
1. Go to **Issues** tab → **Milestones** → **"New milestone"**
2. Title it: `Sprint 1`
3. Set a due date (e.g., 2 weeks from today)
4. Click **"Create milestone"**
5. **Screenshot this page** → save as `05-sprint-created.png` ✅ **(Task 5)**

---

### STEP 7 — Create User Story Issues
You need to create about **10 issues** (user stories). Here's how:

1. Go to **Issues** tab → **"New issue"**
2. Your `user-story.md` template should appear — click it
3. Create stories like these examples:

| # | Title | Label | Column |
|---|-------|-------|--------|
| 1 | As a user, I need to log in, so that I can access my account | enhancement | Done |
| 2 | As a user, I need to reset my password, so that I can regain access | enhancement | Done |
| 3 | As an admin, I need to view all users, so that I can manage them | enhancement | In Progress |
| 4 | As a user, I need to update my profile, so that my info is current | enhancement | In Progress |
| 5 | As a user, I need to search products, so that I can find items quickly | enhancement | Review/QA |
| 6 | As a user, I need to add items to cart, so that I can purchase them | enhancement | Sprint Backlog |
| 7 | As a user, I need to view order history, so that I can track purchases | enhancement | Sprint Backlog |
| 8 | As a user, I need to receive email notifications, so that I stay informed | enhancement | Product Backlog |
| 9 | As a dev, I need to refactor login code, so that it is maintainable | **technical debt** | Product Backlog |
| 10 | As a dev, I need to update dependencies, so that the app is secure | **technical debt** | Product Backlog |

> ⚠️ **Stories 9 and 10 must be labeled `technical debt`** — this is required for Task 4

For each issue:
- Fill in the template text
- Add the appropriate **label**
- Assign it to **yourself**
- Assign it to **Sprint 1** milestone (for stories in In Progress, Review/QA, Done)
- Add a story point estimate in the title or description like `[3 pts]`

---

### STEP 8 — Add Issues to the Kanban Board
1. Go to your **Project board**
2. For each issue, drag it or add it to the correct column
3. Your board should look like:
```
Product Backlog | Sprint Backlog | In Progress | Review/QA | Done
     Story 8    |    Story 6     |   Story 3   |  Story 5  | Story 1
     Story 9    |    Story 7     |   Story 4   |           | Story 2
     Story 10   |                |             |           |
