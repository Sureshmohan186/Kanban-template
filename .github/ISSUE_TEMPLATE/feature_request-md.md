---
name: feature_request.md
about: Template for creating new user stories in the required "As a / I need / So
  that" format.
title: ''
labels: ''
assignees: ''

---

### User Story

As a student, I need to upload assignments so that my instructor can grade them.

---

### Acceptance Criteria

Scenario: Successful file upload
Given the student is logged into the system
And is on the assignment submission page
When they upload a valid PDF file
Then the file should be saved successfully
And a confirmation message should appear

Given the student is logged into the system  
And is on the “Submit Assignment” page  
When the student selects an unsupported file type (e.g., .exe)  
Then the system should reject the file  
And display an error message explaining the allowed file formats

Given the student is logged into the system  
And has not chosen any file  
When the student clicks the “Upload” button  
Then the system should prevent submission  
And display “Please select a file before uploading.”

---

### Additional Notes
- (Add any extra info, links, or details here)

---

### Story Points
(Estimate effort in numbers: 1, 2, 3, 5, 8…)
