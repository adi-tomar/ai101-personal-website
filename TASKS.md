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

**Overall Status:** In Review

---

## Current Issue

**GitHub Issue:** [#3 — Add About and Experience sections](https://github.com/adi-tomar/ai101-personal-website/issues/3)

**Status:** In Review

**Priority:** High

**Objective:** Add a biography and career history to the existing classroom portfolio.

### Acceptance Criteria

GitHub Issue #3 has an empty description. The criteria below follow the approved plan.

- [x] The About section summarizes professional focus and experience supported by the classroom resume.
- [x] Two clearly labeled fictional experience entries show the verified sample employers, roles, dates, and responsibilities.
- [x] About and Experience navigation links work by keyboard and pointer within the existing responsive layout.
- [x] The sections follow `BRAND.md` and reference files are outside the `docs/` site root.

### Implementation Checklist

- [x] Confirm the merged homepage and retrieve Issue #3.
- [x] Review the project guidelines and approved classroom content.
- [x] Present the plan and obtain implementation approval.
- [x] Build the sections and update navigation and styles.
- [x] Test the acceptance criteria, review the diff, and record results.
- [ ] Obtain separate approval to stage and commit.

## Current Progress

**Last Updated:** November 17, 2026

**Work Completed:** Added a short biography and two reverse-chronological experience cards. Linked both sections from the header.

**Work Remaining:** User review and separate approval to stage and commit.

**Blockers:** None for Issue #3. A real professional biography and a public LinkedIn profile URL remain pending approved sources.

**Files Changed:** `docs/index.html`, `docs/styles.css`, and `TASKS.md`.

**Tests Performed:** Chrome at 320, 390, 768, and 1440px. Checked section anchors, visible keyboard focus, skip-link behavior, role details against the sample resume, card layout, horizontal overflow, stylesheet loading, and console errors.

**Test Results:** All local checks passed. The cards stacked at 320 and 390px and sat side by side at 768 and 1440px. Both reference URLs returned HTTP 404. The existing LinkedIn destination was checked in the markup.

## Git and Approval Status

| Action | Status |
|---|---|
| Implementation approval | Granted |
| Code review | Ready for user review |
| Commit approval | Awaiting separate explicit approval |
| Local commit | Not created |
| Push approval | Not requested |
| Remote push | Not performed |
| Pull-request approval | Not requested |
| Pull request | Not created |
| Merge approval | Not requested |
| Merge | Not performed |

**Git Status:** Uncommitted on local branch `feature/issue-3-about-experience`.

**Proposed Commit Message:** `feat: add about and experience sections (#3)`

**Important:** Approval to implement an Issue does not grant approval to commit, push, open a pull request, or merge. Each action requires separate explicit approval.

---

## Next Recommended Issue

**GitHub Issue:** [#4 — Add Projects and Contact sections](https://github.com/adi-tomar/ai101-personal-website/issues/4)

**Status:** Backlog

**Priority:** High

**Objective:** Add project cards and contact information using approved content.

**Dependencies:** Issue #3

**Next Action:** Recommend after Issue #3 is reviewed and approved.

Do not begin automatically.

---

## GitHub Issue Backlog

GitHub Issues are the authoritative source for development tasks, requirements, acceptance criteria, and Issue status.

`TASKS.md` is the local development dashboard. Codex should retrieve the latest Issue information from GitHub before starting work and update this file as progress is made.

### Sprint 1 — Website Foundation

| Issue | Title | Status | Priority | Dependency |
|---|---|---|---|---|
| #2 | Build responsive portfolio homepage | Closed on GitHub | High | None |
| #3 | Add About and Experience sections | In Review | High | #2 |
| #4 | Add Projects and Contact sections | Backlog | High | #3 |
| #5 | Test responsive design and accessibility | Backlog | High | #2–#4 |

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
| `feature/issue-2-homepage` | Development branch for Issue #2 |
| `feature/issue-3-about-experience` | Development branch for Issue #3 |
| `demo-integration` | Optional branch for demonstrating pull requests |

**Branch Rules:**

- Protect `master` and `starter` from accidental direct changes.
- Create feature branches from the appropriate starting branch.
- Never commit directly to protected branches.
- Do not merge classroom demonstration work into the completed production website without a deliberate review.
- Obtain approval before pushing, opening pull requests, or merging.

---

## Completed Issues

Issue #2 was closed on GitHub and merged into `master` in [PR #7](https://github.com/adi-tomar/ai101-personal-website/pull/7). The homepage uses the LinkedIn homepage pending an approved public profile URL.

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