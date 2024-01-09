---
limit: 100
mapWithTag: false
icon: file
tagNames: 
excludes: 
extends: 
version: "2.0"
fields:
  - id: iUtuWK
    name: Class
    options:
      valuesList:
        "3": All
        "4": Author
        "5": Blog
        "6": Project
        "7": Source
        "8": Video
      sourceType: ValuesFromDVQuery
      valuesListNotePath: ""
      valuesFromDVQuery: dv.pages('"Class"').map(p=>p.file.name)
    type: Select
    path: ""
---

Class:: {"type":"Select","options":{"valuesList":{"3":"All","4":"Author","5":"Blog","6":"Project","7":"Source","8":"Video"},"sourceType":"ValuesFromDVQuery","valuesListNotePath":"","valuesFromDVQuery":"dv.pages('\"Class\"').map(p=>p.file.name)"}}
