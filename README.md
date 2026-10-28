# TEAMPRACTICE — 우리 팀 취미 모음 사이트

팀원 4명이 각자 좋아하는 취미로 자기 페이지를 꾸미는 정적 웹사이트입니다.

## 팀원 소개

| 팀원 | 취미 | 한 줄 소개 | 페이지 |
|---|---|---|---|
| 팀원1 | 🤖 AI 캐릭터 채팅 | 케이브덕·젠잇에서 AI 캐릭터와 이야기 만들기 | [보러 가기](https://rlacksals0618-collab.github.io/TEAMPRACTICE/members/member1/index.html) |
| 팀원2 · 이재원 | ⚽ 축구 시청 | 해외축구의 전술과 멋진 플레이를 즐겨 봅니다 | [보러 가기](https://rlacksals0618-collab.github.io/TEAMPRACTICE/members/member2/index.html) |
| 팀원3 | 준비 중 | — | [보러 가기](https://rlacksals0618-collab.github.io/TEAMPRACTICE/members/member3/index.html) |
| 팀원4 | 준비 중 | — | [보러 가기](https://rlacksals0618-collab.github.io/TEAMPRACTICE/members/member4/index.html) |

> 자기 페이지를 꾸몄다면 이 표의 내 줄도 함께 수정해주세요.

## 폴더 구조

```
index.html              ← 홈 (팀원 카드 목록)
css/common.css          ← 공통 스타일 (가급적 수정 X)
members/
  member1/              ← 팀원1 전용 폴더
    index.html          ← 내 페이지 내용
    style.css           ← 내 페이지 꾸미기
    images/             ← 내 사진 넣는 곳
  member2/ ...
  member3/ ...
  member4/ ...
```

**자기 폴더(`members/memberN/`)만 수정하면** 다른 팀원과 충돌이 나지 않아요.
홈(`index.html`)에서는 자기 카드의 이모지·이름·한 줄 소개만 바꿔주세요.

## 내 페이지 꾸미는 방법

1. 레포 받기
   ```bash
   git clone https://github.com/rlacksals0618-collab/TEAMPRACTICE.git
   cd TEAMPRACTICE
   ```
2. 내 폴더 수정
   - `members/memberN/index.html` — 이름, 취미, 소개글, TOP 3 등 내용
   - `members/memberN/style.css` — 색상(`--theme-1`, `--theme-2`, `--theme-bg`), 폰트, 레이아웃 등 자유롭게
   - 사진은 `members/memberN/images/`에 넣고 `<img src="images/사진.jpg" alt="설명">`으로 사용
3. 홈 카드 수정 — `index.html`에서 내 카드(`팀원N`)의 이모지·이름·한 줄 소개, 그리고 상단 메뉴의 내 이름
4. 브라우저로 `index.html`을 열어 확인
5. README의 **팀원 소개** 표에서 내 줄 수정
6. 새 브랜치에서 올리고 Pull Request 보내기
   ```bash
   git checkout main
   git pull
   git checkout -b memberN-hobby
   git add .
   git commit -m "팀원N 페이지 꾸미기"
   git push -u origin memberN-hobby
   ```
   GitHub에서 Pull Request를 만들면 확인 후 `main`에 merge됩니다.

> 푸시 권한이 없다면 레포를 Fork해서 내 Fork에 올린 뒤 Pull Request를 보내주세요. (팀원2가 이 방식으로 올렸어요)

## 사이트 주소

GitHub Pages: https://rlacksals0618-collab.github.io/TEAMPRACTICE/
(푸시 후 1~2분 뒤 반영됩니다)
