---
limit: 100
mapWithTag: true
icon: clipboard-list
tagNames: [Source, Author]
excludes: 
extends: 
version: 3
---

Papers:: {"type":"Lookup","options":{"autoUpdate":true,"outputType":"LinksBulletList","builtinSummarizingFunction":"Count","customListFunction":"page.file.name","customSummarizingFunction":"return pages.length","dvQueryString":"dv.pages('#source')","targetFieldName":"Author"}}