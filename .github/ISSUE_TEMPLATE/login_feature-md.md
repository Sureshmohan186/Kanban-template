---
name: login_feature.md
about: Template for creating a login-related user story.
title: ''
labels: bug, documentation, enhancement, product backlog, sprint backlog, technical
  debt
assignees: Sureshmohan186

---

### User Story
As a student, I need to log in to the system so that I can securely access my assignments and grades.

---

### Acceptance Criteria

#### Scenario 1: Successful Login
Given the student has a registered account  
And is on the login page  
When they enter valid credentials  
Then the system authenticates the user  
And redirects them to the dashboard

#### Scenario 2: Invalid Credentials
Given the student is on the login page  
When they enter an incorrect username or password  
Then an error message “Invalid login credentials” should appear

#### Scenario 3: Empty Fields
Given the student is on the login page  
When they click “Login” without entering credentials  
Then the system shows “Username and password cannot be empty”

---

### Story Points
3

---

### Labels
feature, product backlog
