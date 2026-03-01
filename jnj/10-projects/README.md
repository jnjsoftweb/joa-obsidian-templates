---
vault: jnj
folder: 10-projects
type: projects
sort-order: 10
description: 현재 진행 중인 프로젝트 노트
tags:
  - projects
  - para
---

# 10-projects

**PARA 방법론**의 Projects 영역입니다. 명확한 목표와 마감이 있는 진행 중 프로젝트를 관리합니다.

## 용도

- **프로젝트 노트**: 목표, 배경, 마일스톤, 관련 노트 모음
- **회의록**: 프로젝트 관련 회의 기록
- **결정 로그**: 주요 의사결정 및 그 이유 기록

## 사용법

1. 프로젝트당 폴더 또는 단일 노트로 관리
2. frontmatter에 `status: active | on-hold | completed` 표기
3. 완료 시 `40-archives`로 이동

## frontmatter 예시

```yaml
---
type: project
status: active
due: 2026-06-30
goal: 한 줄 목표 요약
---
```
