name: 🐛 Bug Report
description: Report something that isn't working as expected
labels: [bug]

body:

- type: textarea
  id: description
  attributes:
  label: Describe the bug
  description: What happened? What did you expect to happen?
  placeholder: A clear and concise description of the problem...
  validations:
  required: true

- type: textarea
  id: steps
  attributes:
  label: Steps to reproduce
  description: Provide a step-by-step guide to reproduce the issue
  placeholder: |

  1. Go to '...'
  2. Click on '...'
  3. Scroll down to '...'
  4. See error
     validations:
     required: true

- type: input
  id: environment
  attributes:
  label: Environment
  description: Device/browser/app version, if applicable
  placeholder: e.g. Chrome 125 on macOS 14.5

- type: textarea
  id: attachments
  attributes:
  label: Screenshots or logs
  description: Drag and drop images or copy logs here
