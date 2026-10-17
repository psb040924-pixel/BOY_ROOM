# NFC Music Page

NFC 태그를 찍으면 이미지가 보이는 페이지가 열리고 음악이 재생됩니다.

## GitHub Pages로 올리는 방법
1. GitHub에서 새 저장소 생성 (Public)
2. 이 폴더의 파일 4개(`index.html`, `image.webp`, `image.jpg`, `song.mp3`)를 업로드 (Add file → Upload files)
3. Settings → Pages → Branch: `main` / `/ (root)` → Save
4. 1~2분 후 `https://<아이디>.github.io/<저장소이름>/` 주소 생성
5. 그 주소를 NFC 태그에 URL 레코드로 기록 (NFC Tools 등 앱 사용)

## 참고
스마트폰 브라우저는 소리 자동재생을 막는 경우가 많아, 막히면 화면을 한 번 터치할 때 바로 재생됩니다.
