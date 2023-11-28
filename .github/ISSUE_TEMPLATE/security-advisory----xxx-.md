---
name: Security Advisory - <xxx>
about: Security Advisory For Sentry.io & Codecov.io Vulnerabilities
title: Security Advisory - <xxx>
labels: ''
assignees: ''

---

name: Security Advisory
description: Security Advisory for a Vulnerability
body:
  - type: textarea
    id: desc
    attributes:
      label: Vulnerability Description
      description:
      placeholder: 
        1. Description of Vulnerability: 
    validations:
      required: true
 - type: textarea
    id: impact
    attributes:
      label: Vulnerability Impact
      description:
      placeholder: 
        1. Impact of Vulnerability: 
    validations:
      required: true
 - type: textarea
    id: Patches
    attributes:
      label: Vulnerability Patches
      description:
      placeholder: 
        1. Patches for Vulnerability: 
    validations:
      required: true
 - type: textarea
    id: workaround
    attributes:
      label: Vulnerability Workaround(s)
      description:
      placeholder: 
        1. Workaround(S) for Vulnerability: 
    validations:
      required: true
 - type: textarea
    id: moreinfo
    attributes:
      label: For More Information
      description:
      placeholder: 
        1. More Informations: 
    validations:
      required: true
