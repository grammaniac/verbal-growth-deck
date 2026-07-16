# 송종옥 GRE Verbal 성장 전략 덱

내부 검토용 정적 HTML 프레젠테이션입니다. 별도 빌드나 외부 JavaScript 의존성이 없습니다.

## 로컬 미리보기

```sh
python3 -m http.server 8000
```

브라우저에서 `http://localhost:8000/`을 엽니다. 방향키, Page Up/Down, Space, Home/End, 화면 클릭·탭, 하단 화살표, 좌우 스와이프를 지원합니다. 마지막으로 본 슬라이드는 브라우저에 저장됩니다.

## 검증

- `index.html`에 `noindex, nofollow`가 있고 `/robots.txt`가 전체 크롤링을 차단하는지 확인합니다.
- 19장 전체를 데스크톱과 iPad 가로·세로 크기로 확인합니다.
- 브라우저 콘솔 오류, 키보드·클릭·스와이프, 새로고침 복원, 인쇄 미리보기를 확인합니다.
- 오프라인에서는 원격 글꼴만 시스템 글꼴로 대체되어야 합니다.

## 배포

Samantha의 최종 검증 후 GitHub Pages 루트에서 `index.html`과 `robots.txt`를 제공합니다. 이 저장소에서는 커밋·푸시·배포를 수행하지 않습니다.
