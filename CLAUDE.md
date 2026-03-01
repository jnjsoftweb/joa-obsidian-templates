# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 프로젝트 개요

이 저장소는 Obsidian 노트 시스템용 템플릿 모음입니다. `old_folders.txt`에는 여러 Obsidian 볼트(JnJ, Home, ilmac, Kmc, JnJsoft)의 폴더 구조 참고 정보가 담겨 있습니다.

## 볼트 폴더 구조 패턴

`old_folders.txt`에 기록된 볼트들은 두 가지 주요 방법론을 혼합해 사용합니다:

- **Zettelkasten 계층**: `00_Map_Of_Contents`, `10_Fleeting_Notes`, `20_Literature_Notes`, `30_Permanent_Notes`
- **PARA 계층**: `10-projects`, `20-areas`, `30-resources`, `40-archives`

숫자 접두사(00, 10, 20, ...)는 Obsidian 사이드바에서 폴더 순서를 제어합니다.

## 템플릿 작성 규칙

Obsidian 템플릿 파일(`.md`)을 작성할 때:

- **Frontmatter**: YAML 형식 사용 (`---` 블록)
- **Dataview 쿼리**: ` ```dataview ``` ` 코드 블록으로 작성
- **Templater 문법**: `<% %>` 구문 사용 (Templater 플러그인 기반)
- **태그**: `#태그명` 또는 frontmatter의 `tags:` 필드 사용
- **링크**: `[[내부링크]]` 또는 `[[파일명|표시텍스트]]` 형식
