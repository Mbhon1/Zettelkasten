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
Co-Worker:: {"type":"Canvas","options":{"direction":"bothsides","nodeColors":["3"],"edgeColors":["1"],"edgeFromSides":["top"],"edgeToSides":["right"],"edgeLabels":["co-worker"],"canvasPath":"Untitled.canvas"}}
Profession:: {"type":"CanvasGroup","options":{"groupColors":["4","6","2"],"groupLabels":["Accountant","Lawyer"],"canvasPath":"Untitled.canvas"}}
Related Fields:: {"type":"CanvasGroupLink","options":{"groupColors":[],"nodeColors":[],"edgeColors":[],"edgeFromSides":[],"edgeToSides":[],"groupLabels":[],"edgeLabels":[],"direction":"bothsides","canvasPath":"Untitled.canvas"}}