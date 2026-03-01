---
vault: jnj
folder: 30-resources
type: resources
sort-order: 30
description: 주제별 참고 자료 및 지식 베이스
tags:
  - resources
  - para
  - knowledge
---

# 30-resources

**PARA 방법론**의 Resources 영역입니다. 관심 주제별 참고 자료와 지식을 축적합니다.

## 용도

- **주제별 노트**: 특정 분야의 개념, 정리, 요약
- **레퍼런스**: 책, 아티클, 강의 등에서 추출한 내용
- **영구 노트**: Zettelkasten 방식의 자신만의 언어로 정리한 지식

## 폴더 구조 (권장)

주제 단위로 서브폴더를 만들어 관리:
```
30-resources/
  기술/
  의학/
  경영/
  ...
```

## frontmatter 예시

```yaml
---
type: resource
source: "책 제목 또는 URL"
author: 저자명
tags:
  - 주제태그
---
```
