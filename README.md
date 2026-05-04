# paintjaengi

`paintjaengi`는 페인트 시공 브랜드용 랜딩 페이지를 만들고 배포해 보는 정적 웹 프로젝트입니다.

HTML과 CSS 중심으로 구성되어 있고, Cloudflare Pages 같은 정적 호스팅에 바로 올릴 수 있도록 정리되어 있습니다.

## 포함 파일

- `index.html`: 메인 랜딩 페이지
- `styles.css`: 페이지 스타일
- `CI.jpg`: 대표 이미지 또는 브랜딩용 이미지
- `backup-index-original.html`: 초기 백업본
- `backup-test-v1.html`: 시안 테스트 백업본
- `backup-test-v2.html`: 시안 테스트 백업본

## 용도

- 브랜드 소개 페이지 시안 제작
- 정적 웹 배포 연습
- 디자인/레이아웃 테스트 결과 보관

## 배포 방법

Cloudflare Pages 기준으로는 폴더 안의 정적 파일을 그대로 업로드하면 됩니다.

1. Cloudflare에 로그인합니다.
2. `Workers & Pages`로 이동합니다.
3. `Create application`을 선택합니다.
4. `Pages`를 선택합니다.
5. 정적 파일 업로드 방식으로 `index.html`, `styles.css`, `CI.jpg`를 포함한 파일을 올립니다.

## 메모

- 현재 폴더는 정적 사이트 구조라서 별도 빌드 과정이 필요하지 않습니다.
- 문구 수정은 `index.html`, 스타일 수정은 `styles.css`에서 바로 진행하면 됩니다.
- 백업 HTML 파일은 이전 시안 비교용으로 남겨둔 파일입니다.
