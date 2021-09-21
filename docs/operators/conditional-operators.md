---
layout: default
title: Conditional Operators
parent: Operators
---

# [](#header-1) Conditional Operators
PartiQL supports SimpleCaseWhen and SearchedCaseWhen to evaluate conditional logic.

# [](#header-2) Simple Case When
```sql
CASE expression
    [WHEN expression THEN expression]*
    [ELSE expression]
END
```


# [](#header-2) Searched Case When
```sql
CASE
    [WHEN expression THEN expression]*
    [ELSE expression]
END
```