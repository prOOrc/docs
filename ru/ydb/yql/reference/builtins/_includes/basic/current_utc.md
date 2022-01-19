---
sourcePath: core/yql/reference/yql-docs-core-2/builtins/_includes/basic/current_utc.md
sourcePath: yql/reference/yql-docs-core-2/builtins/_includes/basic/current_utc.md
---

## CurrentUtc... {#current-utc}

`CurrentUtcDate()`, `CurrentUtcDatetime()` и `CurrentUtcTimestamp()` - получение текущей даты и/или времени в UTC. Тип данных результата указан в конце названия функции.

Аргументы опциональны и работают по тому же принципу, что и у [RANDOM](#random).

**Примеры**
``` yql
SELECT CurrentUtcDate();
```
``` yql
SELECT CurrentUtcTimestamp(TableRow()) FROM my_table;
```