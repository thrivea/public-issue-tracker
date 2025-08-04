name: 💡 Feature Request
description: Suggest a new idea or improvement
labels: [enhancement]

body:

- type: textarea
  id: proposal
  attributes:
  label: What would you like to see improved or added?
  description: Describe the feature or enhancement in detail.
  placeholder: I’d like to be able to...
  validations:
  required: true

- type: textarea
  id: motivation
  attributes:
  label: Why is this feature important?
  description: Describe the problem it solves or value it brings.
  placeholder: This would help because...

- type: textarea
  id: alternatives
  attributes:
  label: Alternatives considered
  description: Have you tried workarounds or other tools?
