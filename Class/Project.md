---
limit: 100
mapWithTag: false
icon: file-check
excludes: 
extends: 
version: 5
tagNames: 
---

Status:: {"type":"Select","options":{"valuesList":{"1":"To Do","2":"WIP","3":"Done"},"sourceType":"ValuesList","valuesListNotePath":"","valuesFromDVQuery":""},"command":{"id":"insert__Project__Status","icon":"list-plus","label":"Insert Status field"}}
Priority:: {"type":"Select","options":{"valuesList":{"1":"High","2":"Medium","3":"Low"},"sourceType":"ValuesList","valuesListNotePath":"","valuesFromDVQuery":""},"command":{"id":"insert__Project__Priority","icon":"list-plus","label":"Insert Priority field"}}