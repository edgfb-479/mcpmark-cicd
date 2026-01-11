---
name: Maintenance Report
description: Report a maintenance or housekeeping task
title: "Maintenance: "
labels: maintenance
assignees:
body:
  - type: markdown
    attributes:
      value: |
        Thanks for reporting this maintenance task!
  - type: textarea
    id: task
    attributes:
      label: Maintenance Task
      description: A clear and concise description of the maintenance task needed.
      placeholder: Tell us what needs to be maintained!
    validations:
      required: true
  - type: textarea
    id: impact
    attributes:
      label: Impact
      description: Explain the impact of this maintenance task.
    validations:
      required: true
  - type: textarea
    id: priority
    attributes:
      label: Priority
      description: How urgent is this maintenance task?
      placeholder: Low, Medium, High
    validations:
      required: true
---