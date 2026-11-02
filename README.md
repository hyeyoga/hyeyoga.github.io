# 휴의요가 홈페이지(배포)
 
이 폴더(index.html, img 폴더)를 통째로 올리면 바로 동작하는 정적 홈페이지입니다.

## 무료로 올리는 방법 (Cloudflare Pages)

1. https://dash.cloudflare.com 에서 무료 계정을 만듭니다.
2. Workers & Pages > Create > Pages > Upload assets(직접 업로드)를 고릅니다.
3. 프로젝트 이름을 `hyuyoga`처럼 정합니다. 주소가 `hyuyoga.pages.dev`가 됩니다.
4. 이 폴더를 끌어다 놓고 Deploy를 누릅니다.

내용을 고친 뒤에는 같은 프로젝트에서 Create deployment로 폴더를 다시 올리면 됩니다.

## 네이버 검색 등록

1. https://searchadvisor.naver.com 에서 사이트 등록 > 주소 입력.
2. 소유 확인에서 HTML 태그 방식을 고르고, 받은 `<meta name="naver-site-verification" ...>` 태그를
   index.html 위쪽의 안내 주석 자리에 붙여 넣은 뒤 다시 올립니다.

## 시간표·수강료가 바뀌면 고칠 곳

- 시간표: index.html에서 `<h2 id="sched-h">시간표</h2>`를 찾아 그 아래 표를 고칩니다.
- 수강료: `<tbody>` 안의 가격과, 아래쪽 스크립트의 rows 숫자를 함께 고칩니다.
