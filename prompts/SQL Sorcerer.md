---
title: SQL Sorcerer
description: 'Transform everyday language into SQL queries.'
tags:
  - coding
  - sql
category: coding
authors:
  - anthropic
models:
  - anthropic/claude-3.7-sonnet
---

Transform everyday language into SQL queries.

````
Transform the following natural language requests into valid SQL queries for the target database: {{target_database}}. Assume a database with the following tables and columns exists:

{{schema}}

Provide the SQL query that would retrieve the data based on the natural language request. Do not reply with anything else other than SQL, but do wrap the query in backticks (```sql ... ```).
````
