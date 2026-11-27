# 요한계시록 암송 — 휴대폰 앱(PWA)

이 폴더를 GitHub Pages에 올리면, 휴대폰 홈 화면에 앱처럼 설치해서 인터넷 없이도 쓸 수 있습니다.

## 들어 있는 파일

- `index.html` — 앱 본체 (개역한글 1–22장, 404절 포함)
- `manifest.webmanifest` — 앱 이름·아이콘·색 정보
- `sw.js` — 오프라인 저장
- `icons/` — 앱 아이콘

## 1. GitHub에 올리기

1. github.com에 로그인한 뒤 오른쪽 위 **+** → **New repository**를 누릅니다.
2. 저장소 이름을 적고(예: `revelation-memory`) **Public**으로 둔 뒤 **Create repository**를 누릅니다.
3. 새 저장소 화면에서 **uploading an existing file**을 누릅니다.
4. 압축을 푼 폴더 안의 파일들(`index.html`, `manifest.webmanifest`, `sw.js`, `README.md`)과 `icons` 폴더를 통째로 끌어다 놓습니다. 폴더 자체가 아니라 그 안의 내용물을 올려야 합니다.
5. 아래 **Commit changes**를 누릅니다.

## 2. GitHub Pages 켜기

1. 저장소의 **Settings** → 왼쪽 **Pages**로 갑니다.
2. **Source**를 **Deploy from a branch**로, Branch를 **main**, 폴더를 **/(root)**로 고른 뒤 **Save**를 누릅니다.
3. 1–2분 뒤 같은 화면 위쪽에 주소가 나타납니다: `https://아이디.github.io/revelation-memory/`

## 3. 휴대폰에 설치하기

- **아이폰:** Safari로 주소를 열고 → 아래 공유 버튼 → **홈 화면에 추가**
- **안드로이드:** Chrome으로 주소를 열고 → 오른쪽 위 ⋮ → **앱 설치** 또는 **홈 화면에 추가**

한 번 열어 두면 그다음부터는 비행기 모드에서도 열립니다.

## 고칠 때

- 본문 오타를 고치거나 내용을 바꾼 뒤에는 `sw.js` 맨 위의 `rev-v1`을 `rev-v2`처럼 바꿔서 함께 올려야, 이미 설치한 휴대폰에도 새 내용이 반영됩니다.
- 진도와 붙여넣은 번역본은 각 휴대폰의 브라우저에 저장됩니다. Claude 링크에서 쓰던 진도는 이 앱으로 옮겨지지 않습니다.

본문: 개역한글(퍼블릭 도메인). 개역개정 등 저작권이 있는 번역본은 앱 안의 붙여넣기 기능으로 개인적으로만 사용하세요.
