---
limit: 100
mapWithTag: true
icon: box
excludes: 
extends: 
version: "2.0"
tagNames: 
fields:
  - id: MFBqjR
    name: Status
    options:
      valuesList: {}
      sourceType: ValuesListNotePath
      valuesListNotePath: Templates/Source Status.md
      valuesFromDVQuery: ""
    type: Select
    path: ""
  - id: MHudKK
    name: Notes
    options: {}
    type: Input
    path: ""
  - id: 9cshjH
    name: Topic
    options:
      valuesList: {}
      sourceType: ValuesFromDVQuery
      valuesListNotePath: ""
      valuesFromDVQuery: dv.pages('"Topic"').map(p=>p.file.name)
    type: Multi
    path: ""
  - id: SVWjJP
    name: Rating
    options:
      valuesList:
        "1": ⭐⭐⭐⭐⭐
        "2": ⭐⭐⭐⭐
        "3": ⭐⭐⭐
        "4": ⭐⭐
        "5": ⭐
      sourceType: ValuesList
      valuesListNotePath: ""
      valuesFromDVQuery: ""
    type: Cycle
    path: ""
  - id: 8Ofs3r
    name: Difficulty
    options:
      step: "1"
      min: "1"
      max: "10"
    type: Number
    path: ""
  - id: Zk5vem
    name: Author
    options:
      dvQueryString: dv.pages('"Author"')
    type: File
    path: ""
  - id: ffx47R
    display: asList
    name: Co-Writer
    options:
      dvQueryString: dv.pages('"Auhtor"')
    type: MultiFile
    path: ""
  - id: EeIuyD
    name: Date
    options:
      dateFormat: YYYY-MM-DD
      defaultInsertAsLink: "true"
      dateShiftInterval: 2 days
    type: Date
    path: ""
---

Status:: {"type":"Select","options":{"valuesList":{},"sourceType":"ValuesListNotePath","valuesListNotePath":"Templates/Source Status.md","valuesFromDVQuery":""}}
Notes:: {"type":"Input","options":{}}
Topic:: {"type":"Multi","options":{"valuesList":{},"sourceType":"ValuesFromDVQuery","valuesListNotePath":"","valuesFromDVQuery":"dv.pages('\"Topic\"').map(p=>p.file.name)"}}
Rating:: {"type":"Cycle","options":{"valuesList":{"1":"⭐⭐⭐⭐⭐","2":"⭐⭐⭐⭐","3":"⭐⭐⭐","4":"⭐⭐","5":"⭐"},"sourceType":"ValuesList","valuesListNotePath":"","valuesFromDVQuery":""}}
Difficulty:: {"type":"Number","options":{"step":"1","min":"1","max":"10"}}
Author:: {"type":"File","options":{"dvQueryString":"dv.pages('\"Author\"')"}}
Co-Writer:: {"type":"MultiFile","options":{"dvQueryString":"dv.pages('\"Auhtor\"')"},"display":"asList"}
Date:: {"type":"Date","options":{"dateFormat":"YYYY-MM-DD","defaultInsertAsLink":"true","dateShiftInterval":"2 days"}}

