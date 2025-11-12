---
name: technical_debt_burndown.md
about: Template for tracking technical or maintenance work such as burndown chart
  setup and other internal improvements.
title: ''
labels: bug, documentation, enhancement, help wanted, product backlog, sprint backlog,
  technical debt
assignees: ''

---

### User Story
As a developer, I need to set up a burndown chart for the sprint so that I can visualize daily progress and ensure the team stays on track.

---

### Acceptance Criteria

#### Scenario 1: Create Burndown Chart
Given the sprint milestone "Sprint 1 – Core Features" exists  
And all stories have estimates assigned  
When the developer generates a burndown chart using GitHub Insights or a manual dashboard  
Then the chart should show remaining story points per day  
And update automatically as issues are closed

#### Scenario 2: Verify Chart Accuracy
Given the chart is displayed  
When an issue moves to “Closed”  
Then the remaining story points on the burndown chart should decrease accordingly

---

### Additional Notes
- The chart can be created in **GitHub Projects → Insights → Burndown** or exported manually.  
- Ensure all issues in the sprint have story points and milestones linked.  
- This counts as *technical debt* since it improves project monitoring, not functionality.

---

### Story Points
2

---

### Labels
technical debt, product backlog
