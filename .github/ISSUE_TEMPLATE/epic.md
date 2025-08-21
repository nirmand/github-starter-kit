name: New Epic
description: Suggest or request a new epic
labels: ["product increment"]
body:
  - type: markdown
    attributes:
      value: |
        Please fill out the sections below to properly describe the new epic you are suggesting.
  - type: textarea
    id: description
    attributes:
      label: Describe the epic
        placeholder: User authentication and authorization
    validations:
      required: true
  - type: textarea
    id: businessgoal
    attributes:
      label: This is required so
      placeholder: Authorized Users can use the app  
  - type: textarea
    id: context
    attributes:
      label: Additional context
      placeholder: |
        Add any other context or screenshots about the feature request here.
