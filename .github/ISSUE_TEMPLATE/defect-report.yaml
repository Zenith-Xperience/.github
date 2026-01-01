name: Defect Report
description: Log a defect using the QA defect format
labels:
  - bug
body:
  - type: input
    attributes:
      label: Defect ID
      description: Optional internal reference (e.g. BUG-008)
      placeholder: 'BUG-###'
    required: false
  - type: dropdown
    attributes:
      label: Status
      description: Current defect status
      options:
        - New
        - Working on
        - Verified
        - Done
    required: true
  - type: textarea
    attributes:
      label: Preconditions
      description: Any setup required before reproducing the issue
    required: false
  - type: textarea
    attributes:
      label: Steps to Reproduce
      description: Clear step-by-step instructions
      placeholder: |
        1.
        2.
        3.
    required: true
  - type: textarea
    attributes:
      label: Expected Result
      description: What should happen
    required: true
  - type: textarea
    attributes:
      label: Actual Result
      description: What actually happens
    required: true
  - type: textarea
    attributes:
      label: Suggestions
      description: 'Optional suggestions, observations, or possible fixes'
      placeholder: 'Any ideas, edge cases, or related notes'
    required: false
  - type: input
    attributes:
      label: Environment Details
      description: 'OS, browser, app version, etc.'
      placeholder: Mac OS / Browser / App version
    required: false
  - type: markdown
    attributes:
      value: |
        ### Labels (Required)
        After creating the issue, please add:
        - **Severity**: `severity:low`, `severity:medium`, `severity:high`
        - **Priority**: `priority:P1` – `priority:P5`
        - Any other relevant labels (`ui`, `backend`, `feature`, etc.)

        ### Attachments
        Add screenshots, videos, or logs using GitHub’s attachment area below.
