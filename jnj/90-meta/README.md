---
vault: jnj
folder: 90-meta
type: meta
sort-order: 90
description: 볼트 운영을 위한 템플릿, 설정, 가이드 문서
tags:
  - meta
  - templates
  - settings
---

# 90-meta

볼트 자체를 관리하기 위한 시스템 폴더입니다.

## 용도

- **templates/**: Templater 기반 노트 템플릿 파일
- **settings/**: 플러그인 설정 메모, 단축키 가이드
- **guides/**: 이 볼트의 사용 방법, 워크플로우 문서

## 폴더 구조 (권장)

```
90-meta/
  templates/   ← 노트 유형별 템플릿 (.md)
  settings/    ← 플러그인 설정값 메모
  guides/      ← 볼트 사용 가이드
```

## 주의사항

- 실제 Obsidian 설정 파일은 `.obsidian/` 폴더에 저장됩니다
- 이 폴더는 **메모 형태의 설정 문서**를 담는 곳입니다
- Templater 플러그인의 템플릿 폴더 경로를 `90-meta/templates`로 설정하세요
