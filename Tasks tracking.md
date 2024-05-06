```dataview
TASK
FROM "Tasks"
WHERE !completed
GROUP BY file.link
```
---
### Histórico de tareas completadas
```dataview
TASK
FROM "Tasks"
WHERE completed
```

