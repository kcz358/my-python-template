name: 🚀 Feature request
description: Suggest an idea for this project
title: "[Feature] "

body:
- type: checkboxes
  attributes:
    label: Checklist
    options:
    - label: 1. Please use English, otherwise it will be closed.
- type: textarea
  attributes:
    label: Motivation
    description: |
      A clear and concise description of the motivation of the feature.
  validations:
    required: true
- type: textarea
  attributes:
    label: Related resources
    description: |
      If there is an official code release or third-party implementations, please also provide the information here, which would be very helpful.