

```dataviewjs
const {fieldModifier: f} = this.app.plugins.plugins["metadata-menu"].api;

dv.table(["Project", "Status", "Priority", "Workflow"],
await Promise.all(dv.pages('"Projects"').map(async p => [
p.file.link,
await f(dv,p, "Status"),
await f(dv,p, "Priority"),
await f(dv,p, "Workflow")])
))
```

