---
limit: 100
mapWithTag: true
icon: box

excludes: 
extends: 
version: 8

tagNames: 
---

Status:: {"type":"Select","options":{"valuesList":{},"sourceType":"ValuesListNotePath","valuesListNotePath":"Source Status.md","valuesFromDVQuery":""}}
Notes:: {"type":"Input","options":{}}
Topic:: {"type":"Multi","options":{"valuesList":{},"sourceType":"ValuesFromDVQuery","valuesListNotePath":"","valuesFromDVQuery":"dv.pages('\"Topic\"').map(p=>p.file.name)"}}
Rating:: {"type":"Cycle","options":{"valuesList":{"1":"⭐⭐⭐⭐⭐","2":"⭐⭐⭐⭐","3":"⭐⭐⭐","4":"⭐⭐","5":"⭐"},"sourceType":"ValuesList","valuesListNotePath":"","valuesFromDVQuery":""}}
Difficulty:: {"type":"Number","options":{"step":"1","min":"1","max":"10"}}
Author:: {"type":"File","options":{"dvQueryString":"dv.pages('\"Author\"')"}}
Co-Writer:: {"type":"MultiFile","options":{"dvQueryString":"dv.pages('\"Auhtor\"')"},"display":"asList"}
Date:: {"type":"Date","options":{"dateFormat":"YYYY-MM-DD","defaultInsertAsLink":"true","dateShiftInterval":"2 days"}}

