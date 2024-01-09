---
limit: 100
mapWithTag: false
icon: pencil
tagNames: 
excludes:
  - Priority
extends: Project
version: "2.0"
fields:
  - id: 77RaYA
    name: Workflow
    options:
      valuesList:
        "1": Workflow_1
        "2": Workflow_2
        "3": Workflow_3
        "4": Workflow_4
      sourceType: ValuesList
      valuesListNotePath: ""
      valuesFromDVQuery: ""
    type: Select
    path: ""
  - id: ZaeETs
    name: Priority
    options:
      valuesList:
        "1": High
        "2": Medium
        "3": Low
      sourceType: ValuesList
      valuesListNotePath: ""
      valuesFromDVQuery: ""
    type: Select
    path: ""
---

Workflow:: {"type":"Select","options":{"valuesList":{"1":"Workflow_1","2":"Workflow_2","3":"Workflow_3","4":"Workflow_4"},"sourceType":"ValuesList","valuesListNotePath":"","valuesFromDVQuery":""}}
Priority:: {"type":"Select","options":{"valuesList":{"1":"High","2":"Medium","3":"Low"},"sourceType":"ValuesList","valuesListNotePath":"","valuesFromDVQuery":""}}