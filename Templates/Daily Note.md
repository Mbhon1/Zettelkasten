---
tag: dailies
Class: Daily
---
Created: {{date}}

## New Tasks

> [!warning]+ OverDue
> ```tasks
> not done
> sort by due date
> due before <% tp.date.now("YYYY-MM-DD")%>
> hide due date
> hide backlink
> limit 5```

> [!todo]+ Today's Tasks
> ```tasks
> not done
> due <% tp.date.now("YYYY-MM-DD")%>
> sort by priority
> hide due date
> hide backlink
> limit 5```

> [!Warning]+ Unscheduled Tasks
> ```tasks
> not done
> no due date
> ```

> [!success]+ Tasks Done Today
> ```tasks
> done <% tp.date.now("YYYY-MM-DD")%>
> hide due date
> hide backlink
> ```
