---
name: Zimfarm Recipe Issue
about: To report an issue on a openZIM Zimfarm (farm.openzim.org) recipe
title: '<recipe_name> is failing'
labels: 
 - bug
body:
- type: input
  id: recipe_url
  attributes:
    label: Recipe URL
    description: The recipe which encountered a problem
    placeholder: https://farm.openzim.org/pipeline/xxxx
  validations:
    required: true
---
