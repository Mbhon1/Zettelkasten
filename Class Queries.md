```dataview
table Status, Priotiy, Workflow
from "Projects"
```

```
const {fieldModifier: f} = this.app.plugins.plugins["metadata-menu"].api;

dv.table(["Project", "Priority", "Status", "Workflow"],
await Promise.all(dv.pages('"Projects"').map(async p =>[
	p.file.link,
	p.Status,
	p.Priority,
	await f(dv,p, "Workflow"])
))
```
