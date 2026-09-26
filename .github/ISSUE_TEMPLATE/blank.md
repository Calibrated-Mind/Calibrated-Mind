name: Blank Issue
description: Create a blank issue for custom topics and sovereign architectural notes.
title: "[BLANK]: "
labels: ["custom", "discussion"]
body:
  - type: textarea
    id: content
    attributes:
      label: Sovereign Content
      description: Describe your custom topic, architectural question, or idea.
      placeholder: Write your details here...
    validations:
      required: true
