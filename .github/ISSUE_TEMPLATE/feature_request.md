---
name: Feature Request
description: Suggest an idea for this project
title: "Feature: "
labels: enhancement
assignees:
body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to suggest a feature!
  - type: textarea
    id: feature
    attributes:
      label: Feature Description
      description: A clear and concise description of the feature you'd like to see.
      placeholder: Tell us what you want!
    validations:
      required: true
  - type: textarea
    id: use-case
    attributes:
      label: Use Case
      description: Explain how this feature would benefit users and use cases.
    validations:
      required: true
  - type: textarea
    id: alternatives
    attributes:
      label: Alternatives Considered
      description: Describe alternatives you've considered.
  - type: textarea
    id: additional
    attributes:
      label: Additional Context
      description: Add any other context or screenshots related to the feature request.
---