---
name: Bug Report
description: File a bug report for this project
title: "Bug: "
labels: bug
assignees:
body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to fill out this bug report!
  - type: textarea
    id: description
    attributes:
      label: Description
      description: A clear and concise description of what the bug is.
      placeholder: Tell us what you see!
    validations:
      required: true
  - type: textarea
    id: steps
    attributes:
      label: Steps to Reproduce
      description: Steps to reproduce the behavior.
      placeholder: |
        1.
        2.
        3.
    validations:
      required: true
  - type: textarea
    id: expected
    attributes:
      label: Expected Behavior
      description: A clear and concise description of what you expected to happen.
    validations:
      required: true
  - type: textarea
    id: actual
    attributes:
      label: Actual Behavior
      description: A clear and concise description of what actually happened.
    validations:
      required: true
  - type: textarea
    id: screenshots
    attributes:
      label: Screenshots
      description: Add screenshots to help explain your problem.
  - type: textarea
    id: environment
    attributes:
      label: Environment
      description: |
        - Browser:
        - Version:
        - OS:
  - type: textarea
    id: additional
    attributes:
      label: Additional Context
      description: Add any other context about the problem here.
---