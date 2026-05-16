# Nana Beauty & Care Service Template

## 실행 방법
1. VS Code에서 이 폴더를 엽니다.
2. 확장 프로그램 `Live Server`를 설치합니다.
3. `index.html`을 우클릭 → `Open with Live Server`를 누릅니다.

## 문구 수정 위치
- 한국어: `language/korea.js`
- 영어: `language/english.js`
- 언어 콤보박스 표시 여부: `language/language.js`
- 메뉴/서비스/후기/블로그/파트너 데이터: 각 언어 파일 안의 `menus`, `pages`, `cards`, `stories`, `testimonials`, `insights` 영역

## 이미지 교체 위치
- `assets/images/` 폴더에 이미지를 넣고
- `language/korea.js` 또는 `language/english.js`에서 image 값을 바꾸면 됩니다.

예: `image: "assets/images/spa-room.svg"`

## 배포 추천
- 베타: Cloudflare Pages
- 상용 초기: Cloudflare Pages + 폼 서비스 또는 서버리스 함수
- 예약/결제/회원/관리자 화면이 필요해지면 별도 백엔드와 데이터베이스 도입
