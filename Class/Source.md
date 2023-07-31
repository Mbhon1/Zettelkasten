---
limit: 100
mapWithTag: false
icon: store
tagNames: 
excludes: 
extends: 
version: 1
---

Status:: {"type":"Select","options":{"valuesList":{},"sourceType":"ValuesListNotePath","valuesListNotePath":"Source Status.md","valuesFromDVQuery":""}}
Notes:: {"type":"Input","options":{}}
Topic:: {"type":"Multi","options":{"valuesList":{},"sourceType":"ValuesFromDVQuery","valuesListNotePath":"","valuesFromDVQuery":"dv.pages('\"Topic\"').map(p=>p.file.name)"}}
Rating:: {"type":"Cycle","options":{"valuesList":{"1":"⭐⭐⭐⭐⭐","2":"⭐⭐⭐⭐","3":"⭐⭐⭐","4":"⭐⭐","5":"⭐"},"sourceType":"ValuesList","valuesListNotePath":"","valuesFromDVQuery":""}}
Difficulty:: {"type":"Number","options":{"step":"1","min":"1","max":"10"}}