---
title: Release {{ env.VERSION }}
assignees: Terro216
labels: RELEASE
---

## [Release] {{ env.VERSION }}

- Дата: {{ env.DATE | date('D MMMM YYYY') }}
- Автор: {{ env.AUTHOR }}

## Changelog

{{ env.CHANGELOG }}

## More info

Предыдущая версия: {{ env.LASTVERSION }}
