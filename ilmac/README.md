---
vault: ilmac
type: vault-root
owner: Moon Jung Sam
scope: business
domain: engineering-it
description: 일맥 구조엔지니어링 기업 IT 업무 관리 볼트
tags:
  - vault
  - engineering
  - it
  - business
created: 2026-03-02
---

# ilmac 볼트

일맥 구조엔지니어링의 IT 인프라 관리 및 사내 시스템 개발·운영을 위한 Obsidian 볼트입니다.

## 용도

- **하드웨어 관리**: Synology NAS 등 장비 사양, 설정, 장애 이력
- **서버 관리**: 서버 구성, 접속 정보, 유지보수 기록
- **웹앱 개발/운영**: 입찰 업무용 웹앱, 프로젝트/일정 관리 웹앱 개발 및 운영 기록

## 폴더 구조

| 폴더 | 용도 |
|------|------|
| `00-dashboard` | 홈 화면 — 시스템 현황, 진행 이슈 |
| `01-inbox` | 장애 보고, 요청 사항 빠른 메모 |
| `02-daily` | IT 업무 일지, 작업 로그 |
| `10-projects` | 진행 중 개발/도입 프로젝트 |
| `20-areas` | 지속 관리 영역 (NAS, 서버, 보안, 사내 시스템 등) |
| `30-resources` | 장비 매뉴얼, 벤더 문서, 기술 레퍼런스 |
| `40-archives` | 완료된 프로젝트, 구형 장비 기록 |
| `90-meta` | 템플릿 (장비 등록, 장애 처리 양식 등), 설정 |
| `91-attachments` | 네트워크 다이어그램, 장비 사진, 계약서 |

## 권장 플러그인

- **Dataview**: 장비 목록 테이블, 이슈 현황 대시보드
- **Kanban**: 장애 처리 및 개발 요청 워크플로우
- **Excalidraw**: 네트워크/시스템 아키텍처 다이어그램
