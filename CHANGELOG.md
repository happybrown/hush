# Changelog

[English](#english) · [한국어](#한국어)

Versions 1.3.6 and 1.3.8 were built but never released. ·
1.3.6과 1.3.8은 빌드만 되고 배포되지 않았습니다.

## English

### 1.4.0 — 2026-11-01

- A new first-run setup walks you through one choice at a time: light or dark, where the address bar goes, ad blocking, and YouTube's ad skipping and background play.
- Opening a link from another app with 12 tabs open no longer replaces the tab you're on: the tab you haven't looked at longest makes room, and you can undo it. A private link never opens in a normal tab.
- Ad blocking now also covers what sites' service workers fetch, which could slip past it before.
- Fixed a crash when tapping a link to an app that isn't installed.
- The menu has a "Block ads on this site" switch, so you can turn blocking off for a site that looks broken in one tap.
- Hush can tell you when a new version is out. It's off until you turn it on (Settings › About), and it only asks GitHub once a day.
- Better with TalkBack: the address bar stays put while you scroll, and the slim bar at the edge reads out the site. Hint text is easier to read.
- Korean and Japanese text no longer breaks in the middle of a word (Android 13 and later).
- The privacy policy now describes the update check.

### 1.3.9 — 2026-11-01

- When you tap the address bar, your bookmarks (or most visited sites) and your history now sit in two sections, each under its own heading.
- The buttons at the bottom of the tab switcher (Close all, New tab and the incognito button) are lower and lighter, leaving more room for your tabs.

### 1.3.7 — 2026-11-01

- No changes to the app itself. This version is the first one built and published automatically from the source, signed with the same key as every earlier release.

### 1.3.5 — 2026-11-01

- **The address bar tucks into a notch.** While you read, the page runs to the edge of the
  screen and the address bar becomes a small see-through notch rising from the bottom edge,
  with the site's name. It shows a load's progress along its edge, in the site's own colour,
  and steps aside at the end of a page. Tap it for the full bar.
- **Bookmark from the menu.** The star moved from the address bar to the top row of the menu,
  giving the address more room.
- **Swiping between tabs says where you're going.** Slide the address bar sideways and a chip
  names the tab you'll land on and its place ("2/5").
- **Lower, quicker notices.** Notices take less height, and "Tab closed" offers its undo for
  3.5 seconds.

### 1.3.4 — 2026-11-01

- Your favourite sites now head the list when you tap the address bar, above the current page
  and recent history, and the list reads the same way whether the bar is at the top or bottom.
- No more dark shadow over the favourite tiles as you swipe through them.

### 1.3.3 — 2026-11-01

- **Bookmarks up front.** New tabs show your bookmarks above the sites you visit most, and
  tapping the address bar shows your favourite sites as tiles before you type. Drag a bookmark
  to the top of the list to put it there.
- **A cleaner address bar.** Buttons are evenly sized and quieter, the address gets more room,
  and the site's name stands out from the rest of the address. While you type, everything but
  the address steps aside and the text grows, with a button to clear it.
- **Tidier look throughout.** Corners are smaller and consistent across cards, sheets, buttons
  and dialogs.
- **Shorter settings.** Each setting's description says in about a line what it does.
- **Old tabs.** "Close old tabs automatically" adds 15 and 90 days, and also applies when you
  come back to Hush, not only when it starts.

### 1.3.2 — 2026-11-01

- Pages that open in other browsers no longer stop on a certificate warning, especially in the middle of a redirect. A bad certificate on something a page loads (a picture, a script, an
  ad) is refused quietly, as other browsers do; only the page's own address is asked about.
- A site without working `https` opens over `http`, as in other browsers, instead of ending on
  an error page. `https` is still tried first, and an `https` page never loads anything over
  plain HTTP.
- The privacy policy says so; you'll see a one-time notice of the change.

## 한국어

### 1.4.0 — 2026-11-01

- 처음 실행하면 테마, 주소창 위치, 광고 차단, YouTube 광고 건너뛰기와 백그라운드 재생을 한 단계씩 고르는 설정 화면이 나옵니다.
- 탭이 12개일 때 다른 앱에서 링크를 열어도 보고 있던 탭을 덮어쓰지 않습니다. 가장 오래 보지 않은 탭이 자리를 내주고, 실행취소할 수 있습니다. 시크릿 링크는 일반 탭에 열리지 않습니다.
- 사이트의 서비스 워커가 보내는 요청에도 광고 차단이 적용됩니다. 전에는 이 경로로 새어 나갈 수 있었습니다.
- 설치되지 않은 앱을 여는 링크를 누르면 앱이 종료될 수 있던 문제를 고쳤습니다.
- 메뉴에 "이 사이트에서 광고 차단" 스위치가 생겨, 깨져 보이는 사이트에서 한 번에 차단을 끌 수 있습니다.
- 새 버전이 나오면 알려 드릴 수 있습니다. 직접 켜기 전에는 꺼져 있고(설정 › 정보), 하루에 한 번 GitHub에만 확인합니다.
- TalkBack에서 더 편해졌습니다. 스크롤해도 주소창이 사라지지 않고, 가장자리의 얇은 바가 사이트 이름을 읽어 줍니다. 입력란의 안내 글자도 더 잘 보입니다.
- 한국어와 일본어 문장이 단어 중간에서 줄바꿈되지 않습니다(Android 13 이상).
- 개인정보 처리방침에 업데이트 확인에 관한 내용을 더했습니다.

### 1.3.9 — 2026-11-01

- 주소창을 누르면 북마크(또는 자주 방문한 사이트)와 방문 기록이 각자 제목이 붙은 두 섹션으로 나뉘어 나옵니다.
- 탭 목록 아래의 버튼(모두 닫기, 새 탭, 시크릿 버튼)을 낮고 가볍게 다듬어 탭이 보이는 자리가 넓어졌습니다.

### 1.3.7 — 2026-11-01

- 앱 자체에는 바뀐 점이 없습니다. 소스에서 자동으로 빌드·배포한 첫 버전이며, 이전 버전과 같은 키로 서명되었습니다.

### 1.3.5 — 2026-11-01

- **노치로 접히는 주소창.** 읽는 동안 페이지가 화면 끝까지 넓어지고, 주소창은 화면 아래 가장자리에서
  솟아오른 반투명한 작은 노치가 되어 사이트 이름을 보여 줍니다. 가장자리를 따라 로딩 진행 상황을 사이트 색으로 보여 주고,
  페이지 끝에서는 비켜납니다. 누르면 주소창이 다시 나옵니다.
- **북마크는 메뉴에서.** 별 버튼을 주소창에서 메뉴 맨 윗줄로 옮겨 주소가 들어갈 자리를 넓혔습니다.
- **탭을 넘길 때 어디로 가는지 표시.** 주소창을 옆으로 밀면 넘어갈 탭의 이름과 위치("2/5")가 나옵니다.
- **더 낮고 빠른 알림.** 알림 카드의 높이를 줄였고, '탭을 닫았습니다'의 실행취소는 3.5초 동안 나옵니다.

### 1.3.4 — 2026-11-01

- 주소창을 누르면 즐겨 찾는 사이트가 목록 맨 위, 현재 페이지와 최근 방문 기록보다 앞에 나옵니다. 주소창이
  위에 있든 아래에 있든 목록이 같은 순서로 나옵니다.
- 즐겨 찾는 사이트 타일을 옆으로 밀 때 가장자리에 어두운 그림자가 생기던 문제를 고쳤습니다.

### 1.3.3 — 2026-11-01

- **북마크를 앞으로.** 새 탭에 자주 가는 사이트 위로 북마크가 나오고, 주소창을 누르면 입력하기
  전에 즐겨 찾는 사이트가 타일로 나옵니다. 북마크 목록에서 맨 위로 끌어 올린 사이트가 여기에
  나옵니다.
- **더 깔끔한 주소창.** 버튼 크기를 고르게 맞추고 색을 차분하게 했으며, 주소가 들어갈 자리가
  넓어지고 사이트 이름이 눈에 띄게 표시됩니다. 주소를 입력하는 동안에는 주소창만 남고 글자가
  커지며, 지우기 버튼이 나옵니다.
- **전체적으로 정돈된 디자인.** 카드, 시트, 버튼, 대화상자의 모서리를 작고 일정하게 맞췄습니다.
- **간결한 설정.** 각 설정의 설명을 한 줄 안팎으로 줄였습니다.
- **오래된 탭.** '오래된 탭 자동으로 닫기'에 15일과 90일을 추가했고, 앱을 시작할 때뿐 아니라
  다시 돌아올 때도 적용됩니다.

### 1.3.2 — 2026-11-01

- 다른 브라우저에서는 열리는 페이지가, 특히 리다이렉트 도중에 인증서 경고로 멈추던 문제를
  고쳤습니다. 페이지가 불러오는 이미지·스크립트·광고의 인증서 오류는 다른 브라우저처럼 조용히
  막고, 페이지 자체의 주소일 때만 묻습니다.
- `https`가 제대로 동작하지 않는 사이트는 오류 페이지에서 멈추지 않고 다른 브라우저처럼 `http`로
  엽니다. 먼저 `https`로 시도하는 것은 그대로이고, `https` 페이지는 평문 HTTP로 아무것도 불러오지
  않습니다.
- 개인정보 처리방침에 이 내용을 반영했으며, 변경 알림이 한 번 표시됩니다.
