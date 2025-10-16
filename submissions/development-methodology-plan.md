---
layout: default
title: Development Methodology Plan - Beyond RGB 2
date: 2025-09-23
author: Team BeyondRGB
---

# Development Methodology Plan - Beyond RGB 2

Source (Google Doc):
- [Development Methodology Plan - Beyond RGB 2](https://drive.google.com/?tab=oo&authuser=1) → open “Submissions” → “Development Methodology Plan - Beyond RGB 2”

## Selected Methodology
Hybrid Agile: Scrum with Kanban elements via GitHub. Two-week iterations, structured artifacts, flexibility for research work.

## Planned Activities and Artifacts
- Sprint Cycles: two-week
- Artifacts: Product backlog, sprint backlog, burndown charts, increment releases
- GitHub Milestone Planning: capacity estimates per sprint
- Velocity Tracking: based on past two iterations

## Team Roles
- Project Manager: Jakob Langtry
- Sponsor Communication Lead: Nat Manoucheri
- Git Tsar: Taylor Lineman

## Standards and Quality
- Code Review: two reviewers per PR, one cross-functional
- Testing: 90% target for new code + regression
- Linting: clang-format/tidy (C++), ESLint (frontend)
- Error Handling: standardized severity levels
- Deployment Verification: pre-release QA + post-deploy smoke

## Tools & Infrastructure
- GitHub (structured branches, squash merge)
- Kanban board: Backlog → Sprint → In Progress → In Review → Done
- CI/CD: builds, unit tests, lint, integration
- Communication: in-person + virtual standups
- Docs: GitHub Wiki

## Metrics
- Velocity, burndown, defect rates, code quality (coverage, complexity, tech debt), team satisfaction

## Meetings
- Sprint Planning: bi-weekly, planning poker
- Standups: Mon/Wed/Thu
- Sprint Review/Demo: end of sprint
- Retrospective: team-only

## Sponsor Engagement
- Demos every iteration
- Release cadence: per sprint, SemVer, release notes
- Documentation updated per release
- Feedback loop: structured incorporation into backlog

## Adaptation Strategy
Review after first two sprints; continuous improvement via retrospectives.

## Timeline
- Week 1: methodology training, tool setup
- Week 2: backlog creation/prioritization
- Weeks 3–16: sprints with demos
- Final sprint: wrap-up, docs, transition
