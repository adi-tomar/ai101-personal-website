# Development Task Tracker

## Project

**Name:** AI 101 Academy — Personal Portfolio Website

**Repository:** `ai101-personal-website`

**Primary Branch:** `master`

**Classroom Starter Branch:** `starter`

**Issue Tracking:** GitHub Issues

**Development Assistant:** OpenAI Codex in VS Code

## Current Sprint

**Sprint:** Sprint 1 — Website Foundation

**Sprint Goal:** Build a functional, responsive personal portfolio website using approved professional content.

**Overall Status:** Ready

---

## Current Issue

**GitHub Issue:** #1 — Build Responsive Portfolio Homepage

**Status:** Ready

**Priority:** High

**Objective:** Create the initial website structure and homepage using the project requirements, brand guidelines, and approved profile information.

### Acceptance Criteria

- [ ] Responsive navigation is implemented
- [ ] Homepage hero section is implemented
- [ ] Professional headline uses approved content
- [ ] LinkedIn profile link is included
- [ ] Website follows `BRAND.md`
- [ ] Website works on desktop and mobile
- [ ] No private documents are exposed

### Implementation Checklist

- [ ] Review `README.md`, `ROADMAP.md`, `BRAND.md`, and `AGENTS.md`
- [ ] Review `references/PROFILE.md`
- [ ] Read the approved resume content, if available
- [ ] Retrieve the latest GitHub Issue requirements
- [ ] Propose an implementation plan
- [ ] Obtain implementation approval
- [ ] Create the website structure
- [ ] Implement homepage and navigation
- [ ] Implement responsive styling
- [ ] Test against acceptance criteria
- [ ] Review code changes and check for sensitive information
- [ ] Update `TASKS.md` with results
- [ ] Prepare proposed commit message
- [ ] Obtain commit approval
- [ ] Obtain push approval
- [ ] Obtain pull-request approval
- [ ] Obtain merge approval, if applicable

## Current Progress

**Last Updated:** Not started

**Work Completed:** Project planning documents prepared

**Work Remaining:** Initial website implementation

**Blockers:** None identified

**Files Changed:** None

**Tests Performed:** None

**Test Results:** Not tested

## Git and Approval Status

| Action | Status |
|---|---|
| Implementation approval | Pending |
| Code review | Not started |
| Commit approval | Not requested |
| Local commit | Not created |
| Push approval | Not requested |
| Remote push | Not performed |
| Pull-request approval | Not requested |
| Pull request | Not created |
| Merge approval | Not requested |
| Merge | Not performed |

**Proposed Commit Message:** Not yet prepared

**Pull Request:** None

**Important:** Approval to implement an Issue does not grant approval to commit, push, open a pull request, or merge. Each action requires separate explicit approval.

---

## Next Recommended Issue

**GitHub Issue:** #2 — Add About and Experience Sections

**Status:** Backlog

**Priority:** High

**Objective:** Build professional biography and experience sections using verified resume information.

**Dependencies:** Issue #1

**Next Action:** Recommend after Issue #1 is reviewed and approved.

Do not begin automatically.

---

## GitHub Issue Backlog

GitHub Issues are the authoritative source for development tasks, requirements, acceptance criteria, and Issue status.

`TASKS.md` is the local development dashboard. Codex should retrieve the latest Issue information from GitHub before starting work and update this file as progress is made.

### Sprint 1 — Website Foundation

| Issue | Title | Status | Priority | Dependency |
|---|---|---|---|---|
| #1 | Build Responsive Portfolio Homepage | Ready | High | None |
| #2 | Add About and Experience Sections | Backlog | High | #1 |
| #3 | Add Projects and Contact Sections | Backlog | High | #2 |
| #4 | Test Responsive Design and Accessibility | Backlog | High | #1–#3 |

### Sprint 2 — Content and Design

| Issue | Title | Status | Priority | Dependency |
|---|---|---|---|---|
| TBD | Refine Professional Biography | Backlog | Medium | Sprint 1 |
| TBD | Add Approved Profile Image | Backlog | Medium | Sprint 1 |
| TBD | Improve Project Cards | Backlog | Medium | Sprint 1 |
| TBD | Improve Accessibility and Visual Design | Backlog | High | Sprint 1 |

### Sprint 3 — Deployment

| Issue | Title | Status | Priority | Dependency |
|---|---|---|---|---|
| TBD | Verify Content and Privacy | Backlog | High | Sprint 2 |
| TBD | Configure GitHub Pages | Backlog | High | Sprint 2 |
| TBD | Deploy and Test Published Website | Backlog | High | GitHub Pages setup |

**Note:** Issue numbers are planning references until confirmed in GitHub. Replace them with actual Issue numbers after creation.

---

## Issue Status Definitions

| Status | Meaning |
|---|---|
| Backlog | Identified but not ready to begin |
| Ready | Requirements defined and ready for approval |
| In Progress | Implementation approved and underway |
| Blocked | Cannot proceed until a dependency or issue is resolved |
| In Review | Code completed and awaiting review |
| Awaiting Approval | Waiting for an explicitly required user approval |
| Completed | Verified, approved, and integrated through the agreed workflow |

---

## Issue Synchronization Rules

1. GitHub Issues are the authoritative source for Issue details and status.
2. Codex must retrieve the latest GitHub Issue before implementation when GitHub access is available.
3. If GitHub access is unavailable, ask the user to provide the Issue details.
4. Update the current Issue, progress, blockers, tests, and approval status in `TASKS.md`.
5. Keep the Issue backlog synchronized with GitHub.
6. Recommend the next Issue after the current Issue is completed.
7. Do not automatically begin the next Issue.
8. Do not change GitHub Issue status, close Issues, or modify Issue details without user approval.
9. Do not mark an Issue completed until its acceptance criteria are verified and required approvals are obtained.

---

## Development Workflow

### Step 1 — Select Issue

- Identify the next approved GitHub Issue.
- Read its description and acceptance criteria.
- Review the relevant project documents.
- Update `TASKS.md` with the selected Issue.

### Step 2 — Plan Implementation

- Summarize the objective.
- Identify required files and changes.
- Identify dependencies and risks.
- Present the implementation plan.
- Wait for user approval before coding.

### Step 3 — Implement

- Work only on the approved Issue.
- Follow `AGENTS.md` and `BRAND.md`.
- Use approved content from `references/PROFILE.md` and the resume.
- Keep changes focused.
- Update progress in `TASKS.md`.

### Step 4 — Test and Review

- Verify all acceptance criteria.
- Test responsive behavior and relevant functionality.
- Review changed files and code differences.
- Check for exposed personal information, credentials, and private documents.
- Record test results in `TASKS.md`.

### Step 5 — Commit Approval

- Present the changed files.
- Summarize implementation and tests.
- Propose a commit message.
- Wait for explicit approval before staging or committing changes.

### Step 6 — Push Approval

- Confirm the intended branch and remote.
- Request explicit approval before pushing.
- Never push directly to protected `master` or `starter`.

### Step 7 — Pull Request

- Propose a pull request with a clear description.
- Identify the intended base branch.
- Request approval before opening or updating the pull request.
- Follow applicable GitHub branch protection rules.

### Step 8 — Merge

- Verify required checks and reviews.
- Request explicit merge approval.
- Never merge automatically.
- Update GitHub Issue status and `TASKS.md` after the approved merge.

---

## Branch Strategy

| Branch | Purpose |
|---|---|
| `master` | Completed production website |
| `starter` | Clean starting point for classroom exercises |
| `feature/issue-1-homepage` | Development branch for Issue #1 |
| `demo-integration` | Optional branch for demonstrating pull requests |

**Branch Rules:**

- Protect `master` and `starter` from accidental direct changes.
- Create feature branches from the appropriate starting branch.
- Never commit directly to protected branches.
- Do not merge classroom demonstration work into the completed production website without a deliberate review.
- Obtain approval before pushing, opening pull requests, or merging.

---

## Completed Issues

No completed Issues yet.

For each completed Issue, record:

- GitHub Issue number and title
- Completion date
- Summary of changes
- Acceptance criteria verified
- Tests passed
- Commit reference
- Pull-request reference, if applicable
- Required approvals obtained

---

## Definition of Done

An Issue is **Completed** only when:

- [ ] Acceptance criteria are satisfied
- [ ] Changes are reviewed and tested
- [ ] No private information is unintentionally exposed
- [ ] `TASKS.md` reflects the implementation and test results
- [ ] Required commit, push, and pull-request approvals are obtained
- [ ] Changes are integrated through the agreed Git workflow
- [ ] GitHub Issue status is updated
- [ ] Next recommended Issue is identified

---

## Instructions for Codex

Before beginning any development task:

1. Read `AGENTS.md`, `README.md`, `ROADMAP.md`, `BRAND.md`, and `TASKS.md`.
2. Read `references/PROFILE.md` and the resume when professional content is required.
3. Retrieve the current GitHub Issue.
4. Verify its acceptance criteria and dependencies.
5. Propose a plan and wait for implementation approval.
6. Work only on the approved Issue.
7. Update `TASKS.md` as progress is made.
8. Show changed files, test results, and a proposed commit message.
9. Request separate approval before committing, pushing, opening or updating a pull request, and merging.
10. Recommend the next Issue but do not start it without approval.

**Core Principle:** GitHub manages the tasks, Codex assists with implementation, `TASKS.md` tracks progress, and the user retains control over all repository changes.