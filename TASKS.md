# Development Task Tracker

## Project

**Name:** AI 101 Academy — Personal Portfolio Website

**Repository:** `ai101-personal-website`

**Primary Branch:** `master`

**Classroom Starter Branch:** `starter`

**Issue Tracking:** GitHub Issues

**Development Assistant:** OpenAI Codex in VS Code

## Current Sprint

**Sprint:** Sprint 2 — Content and Design

**Sprint Goal:** Refine portfolio content, project presentation, and accessibility using approved sources.

**Overall Status:** In Review

---

## Current Issues

**Branch:** `feature/issues-11-14-content-design`

| GitHub issue | Status | Work completed | Remaining work |
|---|---|---|---|
| [#11 — Refine Professional Biography](https://github.com/adi-tomar/ai101-personal-website/issues/11) | Blocked | Edited the hero and About copy using the fictional classroom resume and kept the sample designation. | Provide an approved name, headline, and supporting professional information to replace the classroom biography. |
| [#12 — Add Approved Profile Image](https://github.com/adi-tomar/ai101-personal-website/issues/12) | Blocked | Checked the repository and approved sources for a portrait. | Supply an image approved for public use and confirm who it depicts so its alternative text can be written. |
| [#13 — Improve Project Cards](https://github.com/adi-tomar/ai101-personal-website/issues/13) | In Review | Refined the three source-backed descriptions, retained the concept labels, and linked the portfolio card to the public repository. | User review. |
| [#14 — Improve Accessibility and Visual Design](https://github.com/adi-tomar/ai101-personal-website/issues/14) | In Review | Reviewed typography, contrast, spacing, and keyboard focus. Section links now move keyboard focus to the named destination. | Verify keyboard navigation in Safari and announcements with VoiceOver. |

## Current Progress

**Last Updated:** November 17, 2026

**Files Changed:** `docs/index.html`, `docs/styles.css`, and `TASKS.md`.

**Tests Performed:** Chrome at 320, 390, 768, 1024, and 1440px, plus 320 and 640px at 200% root text size. Checked reflow, tab order, visible focus, fragment focus, section names, console output, and reference-file isolation. System WebKit layout checks at 320, 768, and 1440px.

**Test Results:** All Chrome checks passed and axe-core reported zero violations. System WebKit showed one, two, and three project columns without horizontal overflow. The public GitHub repository returned HTTP 200. Both reference URLs returned HTTP 404 from the local site root.

**Test Limitations:** Safari WebDriver requires Allow Remote Automation. System WebKit verified layout, while Chrome verified keyboard navigation and exposed roles and names. VoiceOver announcements remain untested.

## Git and Approval Status

**Implementation Approval:** Granted for Issues #11–#14.

**Git Status:** Unstaged and uncommitted on `feature/issues-11-14-content-design`. The previously recorded backlog numbers are included in the branch baseline.

**Proposed Commit Message:** `feat: refine portfolio content and accessibility (#11, #13, #14)`

**Approval Required:** Separate approval to stage and commit these three files. Push, pull request, and merge require their own approvals.

---

## Next Recommended Issue

[**#15 — Verify Content and Privacy**](https://github.com/adi-tomar/ai101-personal-website/issues/15) follows review of the Sprint 2 work and resolution of the outstanding content and image decisions.

---

## GitHub Issue Backlog

GitHub Issues are the authoritative source for development tasks, requirements, acceptance criteria, and Issue status.

`TASKS.md` is the local development dashboard. Codex should retrieve the latest Issue information from GitHub before starting work and update this file as progress is made.

### Sprint 1 — Website Foundation

| Issue | Title | Status | Priority | Dependency |
|---|---|---|---|---|
| #2 | Build responsive portfolio homepage | Closed on GitHub | High | None |
| #3 | Add About and Experience sections | Merged via PR #8, issue open | High | #2 |
| #4 | Add Projects and Contact sections | Merged via PR #9, issue open | High | #3 |
| #5 | Test responsive design and accessibility | Merged via PR #10 | High | #2–#4 |

### Sprint 2 — Content and Design

| Issue | Title | Status | Priority | Dependency |
|---|---|---|---|---|
| #11 | Refine Professional Biography | Blocked | Medium | Sprint 1 |
| #12 | Add Approved Profile Image | Blocked | Medium | Sprint 1 |
| #13 | Improve Project Cards | In Review | Medium | Sprint 1 |
| #14 | Improve Accessibility and Visual Design | In Review | High | Sprint 1 |

### Sprint 3 — Deployment

| Issue | Title | Status | Priority | Dependency |
|---|---|---|---|---|
| #15 | Verify Content and Privacy | Backlog | High | Sprint 2 |
| #16 | Configure GitHub Pages | Backlog | High | Sprint 2 |
| #17 | Deploy and Test Published Website | Backlog | High | GitHub Pages setup |

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
| `feature/issue-4-projects-contact` | Development branch for Issue #4 |
| `feature/issue-5-responsive-accessibility` | Development branch for Issue #5 |
| `feature/issues-11-14-content-design` | Development branch for Issues #11–#14 |
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