---
layout: default
title: String Operators
parent: Operators
---

# [](#header-1) String Operators
PartiQL supports the concatenation string operator `||`. The result is a string.

```sql
<string> || <string>
```

Query:
```sql
'happy' || ' ' || 'birthday'
```

Result:
```sql
'happy birthday'
```