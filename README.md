# 🍜 후쿠오카 일본어 마스터

후쿠오카 여행용 일본어 학습 웹앱. 메뉴 한자·히라가나·카타카나 읽기 + 구매/주문 상황별 회화를 한 페이지에 담았습니다. 휴대폰 브라우저에서 바로 열리고, 글자·문장을 탭하면 일본어 발음이 나옵니다.

## 들어있는 내용

- **50음** — 히라가나·카타가나 전체 + 탁음/반탁음
- **메뉴** — 후쿠오카 명물·면·고기·해산물·밥·음료·옵션 단어 70여 개 (한자/가나/발음/뜻)
- **상황** — 입장, 식권 발매기, 주문, 라멘 면굳기, 추가요청, 결제, 편의점, 카페, 야타이, 회전초밥, 면세 쇼핑, 문제상황, 인사 등 13개 시나리오
- **숫자** — 숫자·개수 세기·금액(円)
- **퀴즈** — 가나/메뉴뜻/숫자 읽기 연습

> 💡 발음은 휴대폰·브라우저의 음성합성 기능을 씁니다. 첫 화면 우측 상단 "🔇 소리 켜기"를 한 번 눌러주세요. (일본어 음성이 깔린 아이폰/안드로이드에서 가장 잘 들립니다.)

---

## 📲 GitHub에 올려서 매일 보기 (GitHub Pages)

### 방법 A — 웹사이트에서 드래그&드롭 (가장 쉬움, PC 권장)

1. https://github.com 로그인 → 우측 상단 **+** → **New repository**
2. Repository name에 `fukuoka-nihongo` 입력 → **Public** 선택 → **Create repository**
3. 새로 생긴 페이지에서 **uploading an existing file** 링크 클릭
4. 이 폴더 안의 `index.html` 과 `README.md` 를 끌어다 놓기 → **Commit changes**
5. 상단 **Settings** → 왼쪽 **Pages** 메뉴
6. Source를 **Deploy from a branch**, Branch를 **main / (root)** 으로 설정 → **Save**
7. 1~2분 뒤 같은 페이지에 뜨는 주소(`https://아이디.github.io/fukuoka-nihongo/`)를 휴대폰에 즐겨찾기/홈화면 추가

### 방법 B — git 명령어 (터미널)

```bash
cd fukuoka-nihongo          # 이 폴더로 이동
git init
git add .
git commit -m "후쿠오카 일본어 앱"
git branch -M main
# 아래 URL은 본인 저장소 주소로 바꿔주세요
git remote add origin https://github.com/<아이디>/fukuoka-nihongo.git
git push -u origin main
```

이후 GitHub 저장소 **Settings → Pages** 에서 Branch를 `main / (root)` 으로 지정하면 공개됩니다.

---

## 📱 홈 화면에 앱처럼 추가

- **아이폰(사파리):** 공개된 주소 접속 → 공유 버튼 → "홈 화면에 추가"
- **안드로이드(크롬):** 주소 접속 → 메뉴(⋮) → "홈 화면에 추가"

이렇게 하면 앱 아이콘처럼 한 번에 열려서 매일 보기 좋아요.

## 수정하고 싶을 때

`index.html` 안의 `WORDS`(메뉴 단어), `SCENES`(상황 회화), `PHRASES` 배열에 항목을 추가하면 됩니다. 같은 형식으로 한 줄 더 넣고 저장 → GitHub에 다시 업로드하면 끝.
