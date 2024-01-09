---
limit: 100
mapWithTag: true
icon: clipboard-list
tagNames:
  - Source
  - Author
excludes: 
extends: 
version: "2.0"
fields:
  - id: by0Zgi
    name: Papers
    options:
      autoUpdate: true
      outputType: LinksBulletList
      builtinSummarizingFunction: Count
      customListFunction: page.file.name
      customSummarizingFunction: return pages.length
      dvQueryString: dv.pages('#source')
      targetFieldName: Author
    type: Lookup
    path: ""
  - id: fpqCr0
    name: Co-Worker
    options:
      direction: bothsides
      nodeColors:
        - "3"
      edgeColors:
        - "1"
      edgeFromSides:
        - top
      edgeToSides:
        - right
      edgeLabels:
        - co-worker
      canvasPath: Untitled.canvas
    type: Canvas
    path: ""
  - id: vXt8g6
    name: Profession
    options:
      groupColors:
        - "4"
        - "6"
        - "2"
      groupLabels:
        - Profession 1
        - Profession 2
        - Profession 3
      canvasPath: Profession.canvas
    type: CanvasGroup
    path: ""
  - id: hycPWp
    name: Related Fields
    options:
      groupColors: []
      nodeColors: []
      edgeColors: []
      edgeFromSides: []
      edgeToSides: []
      groupLabels: []
      edgeLabels: []
      direction: bothsides
      canvasPath: Profession.canvas
    type: CanvasGroupLink
    path: ""
---

Papers:: {"type":"Lookup","options":{"autoUpdate":true,"outputType":"LinksBulletList","builtinSummarizingFunction":"Count","customListFunction":"page.file.name","customSummarizingFunction":"return pages.length","dvQueryString":"dv.pages('#source')","targetFieldName":"Author"}}
Co-Worker:: {"type":"Canvas","options":{"direction":"bothsides","nodeColors":["3"],"edgeColors":["1"],"edgeFromSides":["top"],"edgeToSides":["right"],"edgeLabels":["co-worker"],"canvasPath":"Untitled.canvas"}}
Profession:: {"type":"CanvasGroup","options":{"groupColors":["4","6","2"],"groupLabels":["Profession 1","Profession 2","Profession 3"],"canvasPath":"Profession.canvas"}}
Related Fields:: {"type":"CanvasGroupLink","options":{"groupColors":[],"nodeColors":[],"edgeColors":[],"edgeFromSides":[],"edgeToSides":[],"groupLabels":[],"edgeLabels":[],"direction":"bothsides","canvasPath":"Profession.canvas"}}