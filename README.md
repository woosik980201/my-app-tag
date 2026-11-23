# my-app-tag — 상품 태그 정리 도우미 (Streamlit 화면)

휴대폰 카메라로 상품 태그를 찍으면 [my-api-tag](https://github.com/woosik980201/my-api-tag) API 로 보내 결과를 표로 보여 주는 Streamlit 화면입니다.
이 화면에는 Gemini 키가 없고, 제목과 결과 칸은 API 의 `GET /` 에서 받아 옵니다.

- Secrets: `API_URL` (my-api-tag 의 vercel.app 주소) · `APP_ACCESS_CODE` (Vercel 과 같은 값)
- `tag.png` 는 코드로 그린 가상 브랜드(SOFT ARCHIVE)의 예시 태그입니다.
