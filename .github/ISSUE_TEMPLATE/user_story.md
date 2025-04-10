---
name: "User Story"
about: "Capture user stories with clear roles, goals, and benefits"
labels: "user story"
title: "User Story"
body:
  - type: input
    attributes:
      label: As a 
      placeholder: "Describe the role (e.g., user, admin)"
    validations:
      required: true
  - type: input
    attributes:
      label: I need 
      placeholder: "State the functionality or feature needed"
    validations:
      required: true
  - type: input
    attributes:
      label: So that 
      placeholder: "Explain the benefit or goal to achieve"
    validations:
      required: true
---
