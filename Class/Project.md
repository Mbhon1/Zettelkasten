---
limit: 100
mapWithTag: false
icon: file-check
excludes: 
extends: 
version: "2.0"
tagNames: 
fields:
  - id: SPUnTw
    command:
      id: insert__Project__Status
      icon: list-plus
      label: Insert Status field
    name: Status
    options:
      valuesList:
        "1": To Do
        "2": WIP
        "3": Done
      sourceType: ValuesList
      valuesListNotePath: ""
      valuesFromDVQuery: ""
    type: Select
    path: ""
  - id: 5JZ3G2
    command:
      id: insert__Project__Priority
      icon: list-plus
      label: Insert Priority field
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

Status:: {"type":"Select","options":{"valuesList":{"1":"To Do","2":"WIP","3":"Done"},"sourceType":"ValuesList","valuesListNotePath":"","valuesFromDVQuery":""},"command":{"id":"insert__Project__Status","icon":"list-plus","label":"Insert Status field"}}
Priority:: {"type":"Select","options":{"valuesList":{"1":"High","2":"Medium","3":"Low"},"sourceType":"ValuesList","valuesListNotePath":"","valuesFromDVQuery":""},"command":{"id":"insert__Project__Priority","icon":"list-plus","label":"Insert Priority field"}}