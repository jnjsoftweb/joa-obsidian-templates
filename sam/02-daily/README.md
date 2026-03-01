---
vault: sam
folder: 02-daily
type: daily
sort-order: 2
description: 일일/주간/월간 주기 노트 저장소
tags:
  - daily
  - periodic
---

# 02-daily

날짜 기반 주기 노트(Daily / Weekly / Monthly Note)를 저장합니다.

## 용도

- **일일 노트**: 오늘의 할 일, 일정, 생각, 회고
- **주간 노트**: 한 주 목표 설정 및 회고
- **월간 노트**: 월별 목표, 성과, 다음 달 계획

## 폴더 구조 (권장)

```
02-daily/
  daily/    ← YYYY-MM-DD.md
  weekly/   ← YYYY-Www.md  (예: 2026-W10.md)
  monthly/  ← YYYY-MM.md
```

## 사용법

1. **Periodic Notes** 플러그인으로 자동 생성 설정
2. **Calendar** 플러그인으로 날짜 클릭 네비게이션
3. 템플릿은 `90-meta/templates/`에 저장
