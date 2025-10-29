# CLAUDE.md

이 파일은 이 저장소에서 작업할 때 Claude Code (claude.ai/code)에게 가이드를 제공합니다.

## 프로젝트 개요

이것은 정적 HTML/CSS/JS 프로젝트 디렉토리입니다. 현재 포함된 파일:
- `index.html` - 유명한 명언을 보여주는 웹페이지
- `test.txt` - 간단한 텍스트 파일

## 프로젝트 구조

- `index.html` - CSS와 JavaScript가 임베디드된 독립형 HTML 파일로, 영감을 주는 명언을 표시
- `test.txt` - 테스트 텍스트 파일
- 모든 스타일과 스크립트가 단일 파일에 포함된 정적 HTML 프로젝트

## 개발 방법

이것은 정적 HTML 프로젝트입니다. 웹페이지를 보려면:

1. HTML 파일을 브라우저에서 직접 열거나,
2. 개발용 HTTP 서버를 사용:
   ```bash
   # Python 3
   python -m http.server 8000

   # Node.js (http-server가 설치된 경우)
   npx http-server
   ```
   그런 다음 브라우저에서 `http://localhost:8000`을 엽니다.

## 코드 스타일

- CSS와 JavaScript가 임베디드된 자체 포함형 HTML 파일
- 한국어 지원 (UTF-8 인코딩)
- 모바일과 데스크톱을 위한 반응형 디자인
- 그라데이션과 애니메이션을 활용한 현대적인 CSS
