---
name: "User Story"
about: "Capture user stories with clear roles, goals, and benefits"
labels: user story
title: "[User Story]: As a [role], I need [function]"
body:
  - type: input
    attributes:
      label: "As a"
      placeholder: "Describe the role (e.g., user, admin)"
    validations:
      required: true
  - type: input
    attributes:
      label: "I need"
      placeholder: "State the functionality or feature needed"
    validations:
      required: true
  - type: input
    attributes:
      label: "So that"
      placeholder: "Explain the benefit or goal to achieve"
    validations:
      required: true
  - type: textarea
    attributes:
      label: "Details and Assumptions"
      description: "Document what you know about this user story"
      placeholder: "E.g., prerequisites, constraints, or other key details"
    validations:
      required: false
  - type: textarea
    attributes:
      label: "Acceptance Criteria (Gherkin)"
      description: |
        Define the acceptance criteria using Gherkin syntax. For example:
        ```
        Given [context]
        When [action]
        Then [outcome]
        ```
      placeholder: "Use Gherkin syntax to describe the criteria for acceptance"
    validations:
      required: true
---
