---
name: view_grades_feature.md
about: Template for creating a story to view grades and academic progress.
title: ''
labels: bug, documentation, product backlog, question, sprint backlog
assignees: ''

---

### User Story
As a student, I need to view my grades so that I can track my academic performance.

---

### Acceptance Criteria

#### Scenario 1: View Available Grades
Given the student is logged into the system  
And has submitted assignments  
When the student clicks “Grades”  
Then a list of assignments with corresponding grades is displayed

#### Scenario 2: No Grades Yet
Given the student is logged in  
And has not submitted any assignments  
When they open the “Grades” page  
Then the system displays “No grades available yet”

#### Scenario 3: Refresh Grades
Given the student is on the grades page  
When they click “Refresh”  
Then the latest grades load from the server

---

### Story Points
2

---

### Labels
feature, product backlog
