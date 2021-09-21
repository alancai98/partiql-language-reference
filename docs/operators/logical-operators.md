---
layout: default
title: Logical Operators
parent: Operators
---

# [](#header-1) Logical Operators

PartiQL supports the following logical operators:
- AND
- OR
- NOT

# [](#header-2) AND
```sql
condition AND condition
```
`AND` evaluates to `TRUE` if and only if both conditions are `TRUE`.

# [](#header-2) OR
```sql
condition OR condition
```
`OR` evaluates to `TRUE` if at least one of the conditions is `TRUE`.

# [](#header-2) NOT
```sql
NOT condition
```
`NOT` evaluates to `TRUE` if and only if condition is `FALSE`.