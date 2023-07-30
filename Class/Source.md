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
Topic:: {"type":"Multi","options":{"valuesList":{},"sourceType":"ValuesFromDVQuery","valuesListNotePath":"","valuesFromDVQuery":"dv.pages(\"Topic\").map(p=>p.file.name)"}}