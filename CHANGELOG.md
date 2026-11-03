# Changelog

[English](#english) · [한국어](#한국어)

Versions 1.3.6 and 1.3.8 were built but never released. ·
1.3.6과 1.3.8은 빌드만 되고 배포되지 않았습니다.

## English

### 1.4.8 — 2026-11-03

- Updates are now yours to install. Download update fetches the new version from GitHub, checks it, and saves it to your Downloads folder only if it matches the checksum published with the release and is signed by the same key as your Hush. The sheet shows each check with a tick and opens Downloads, where you tap the file to install it, as you installed Hush.
- Hush no longer asks for the permission to install apps (REQUEST_INSTALL_PACKAGES), which 1.4.7 used to install updates itself. If you allowed it, you can turn "Install unknown apps" off for Hush in Android's settings.
- Hush deletes the saved file once that version is running. The privacy policy says so; you will see a notice about the change once.

### 1.4.7 — 2026-11-03

- Updates in the app: when a new version is out, its notice shows what changed in every version since yours, and Update downloads it, checks it and hands it to Android to install. Nothing is installed unless the file matches the checksum published with the release and is signed by the same key as your Hush. Android asks once to allow Hush to install apps, and asks you to confirm each installation. You can also skip a version.
- Settings › About › Check for updates now asks at once, whether or not the daily check is on, and says when it last looked and what it found.
- The privacy policy says what the update downloads, from where, how it is checked and how long the file is kept, and lists the permission to install apps. You will see a notice about the change once.
- The release APK no longer lists android.permission.DUMP. It was never a permission Hush asked for: a library's receiver was guarded by it, so that only a developer's computer could reach it. Release builds now leave that receiver out.

### 1.4.6 — 2026-11-02

- The Black style is truly black: its discs and headings are all but pure black. In dark mode each disc has a thin charcoal ring so it still stands out.
- The cards in Settings › Appearance › Style are all the same width.
- Everything from 1.4.5 is here too, for anyone updating from 1.4.4: an arrangeable menu with a dark mode tile, one card for the site with what ad blocking did on the page, a choice of what stays of a hidden address bar, and the Black style in place of Blue.

### 1.4.5 — 2026-11-02

- The menu can be arranged: hold any tile and drag it where you want it, into the top row of round tiles too (it holds six; a tile dropped into it full trades places). Default order puts everything back. With TalkBack, each tile has Move earlier and Move later.
- Dark mode is a tile in the menu: one tap switches between light and dark.
- The menu's site area is one card instead of half the menu: the site's name with its ad blocking switch, then Hide an area, Hidden areas and Ad blocking.
- Ad blocking in the menu now shows what it did on the page, instead of going to Settings: requests and pop-ups blocked, hidden areas, the servers blocked and how often, and which of the blocking is on. The list of servers is kept only in memory, for the page in front.
- Settings › Appearance › When the address bar hides: the notch, a thin strip with the site's name that the page keeps clear of, or nothing at all.
- A new Black style replaces Blue (Settings › Appearance › Style): near-black discs, gold when a tool is on. If you used Blue, you get Black.
- Sharing one site's hidden areas with another is gone. Sites that were linked keep a copy of the hidden areas they used, and older rule files still import.
- Smaller things: "Tab closed" goes after 3 seconds, the fullscreen exit button is smaller, dialog buttons no longer squeeze long names, and the hidden areas sheet's buttons line up.

### 1.4.4 — 2026-11-01

- No changes to the app itself. This version is here so that Check for updates has a newer version to find and can be tried end to end.

### 1.4.3 — 2026-11-01

- Turning on Check for updates (Settings › About) now looks right away and tells you what it found: a newer version with a link to it, that you have the latest, or that GitHub couldn't be reached. After that it checks once a day, as before.
- The privacy policy says so: the check runs when you turn it on, then once a day. Nothing else it sends has changed.

### 1.4.2 — 2026-11-01

- Dark mode is darker: Hush's screens sit on near-black, its cards and the address bar are a quiet charcoal instead of navy, and the App icons style draws each icon in a soft pastel inside a faint outline.
- An incognito tab shows its mask and plum colour even while the address bar is hidden, and TalkBack says so.
- The lock in the address bar speaks only of the connection; an insecure page is read out as not secure.
- The address bar, tab switcher and notice buttons are bigger and easier to tap, without the bar getting taller.
- The menu says whether ad blocking is on, partly on or off in words, and the row that opens its settings is set apart from the switch for this site.
- With gesture navigation, the right edge is always your phone's Back; Forward is in the menu.
- Swipes and pulls show more clearly, and with a tick, when letting go will act.
- When all tabs are in use, Hush offers to close the oldest one or show your tabs instead of just saying no.
- TalkBack hears Settings' switches as switches and its headings as headings, and the tab switcher names the current tab.
- A few one-time tips point out what has no button: swiping the address bar between tabs, bringing the bar back, and hiding parts of a page.
- Settings rows are separated by hairlines, the app look is now called Style, and the bookmarks screen offers to import bookmarks when it is empty.

### 1.4.1 — 2026-11-01

- A fresh look: Hush's own screens and sheets now sit on a soft lavender ground with white cards, the accent is a calmer indigo, and private tabs have a plum colour of their own so the two modes never look alike.
- Icons are recoloured so none clash or stand out too much, in every app style and in dark mode.
- Pop-ups follow your app style. Warnings stay easy to spot but no longer use a harsh red.
- Payment and identity apps (ISP, card apps, bank pay, KakaoPay, Toss, Payco, PASS) now open straight away from shop pages, even when the page calls them a moment after you tap Pay.
- When a payment app isn't installed, Hush takes you to its store page.
- A pop-up that only opened an app no longer leaves an empty tab behind.
- Back on a link another app opened (KakaoTalk, a mail) takes you straight back to that app.

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

### 1.4.8 — 2026-11-03

- 업데이트 설치는 이제 이용자가 합니다. '업데이트 내려받기'를 누르면 GitHub에서 새 버전을 받아 확인하고, 릴리스와 함께 공개된 체크섬과 일치하고 지금 Hush와 같은 키로 서명된 경우에만 다운로드 폴더에 저장합니다. 확인한 항목을 체크 표시로 보여 주고 다운로드 폴더를 열어 주니, Hush를 처음 설치할 때처럼 파일을 눌러 설치하면 됩니다.
- Hush는 더 이상 앱 설치 권한(REQUEST_INSTALL_PACKAGES)을 요청하지 않습니다. 1.4.7에서 업데이트를 직접 설치하는 데 쓰던 권한입니다. 허용해 두셨다면 안드로이드 설정에서 Hush의 '출처를 알 수 없는 앱 설치'를 끄셔도 됩니다.
- 저장한 파일은 그 버전이 실행되면 Hush가 지웁니다. 개인정보처리방침에 이 내용을 적었고, 변경 안내가 한 번 표시됩니다.

### 1.4.7 — 2026-11-03

- 앱 안에서 업데이트합니다. 새 버전이 나오면 알림에서 지금 버전 이후 모든 버전의 바뀐 점을 보여 주고, '업데이트'를 누르면 내려받아 확인한 뒤 안드로이드에 설치를 맡깁니다. 파일이 릴리스와 함께 공개된 체크섬과 일치하고 지금 Hush와 같은 키로 서명된 경우에만 설치합니다. 처음 한 번 안드로이드가 Hush의 앱 설치를 허용할지 묻고, 설치할 때마다 확인을 묻습니다. 원하지 않는 버전은 건너뛸 수 있습니다.
- 설정 › 정보 › '지금 업데이트 확인'은 매일 확인을 켜지 않았어도 바로 확인하고, 마지막으로 언제 확인했는지와 결과를 보여 줍니다.
- 개인정보처리방침에 업데이트가 무엇을 어디서 내려받는지, 어떻게 확인하는지, 파일을 얼마나 두는지와 앱 설치 권한을 적었습니다. 변경 안내가 한 번 표시됩니다.
- 배포용 APK에 더 이상 android.permission.DUMP가 나오지 않습니다. Hush가 요청하던 권한이 아니라, 개발자 컴퓨터만 접근할 수 있도록 라이브러리의 수신기에 걸려 있던 보호 장치였습니다. 이제 배포용 빌드에서는 그 수신기를 뺍니다.

### 1.4.6 — 2026-11-02

- 블랙 스타일이 진짜 검정이 되었습니다. 원과 제목이 거의 순수한 검정이고, 다크 모드에서는 원마다 얇은 짙은 회색 테두리를 둘러 잘 보이게 했습니다.
- 설정 › 모양 › 스타일의 카드가 모두 같은 너비가 되었습니다.
- 1.4.4에서 바로 업데이트하는 분께는 1.4.5의 변경 사항도 함께 들어 있습니다. 배치를 바꿀 수 있는 메뉴와 다크 모드 타일, 광고 차단이 이 페이지에서 한 일을 보여 주는 사이트 카드, 숨은 주소창 자리 선택, 블루를 대신한 블랙 스타일입니다.

### 1.4.5 — 2026-11-02

- 메뉴를 원하는 대로 배치할 수 있습니다. 아이콘을 길게 눌러 원하는 자리로 끌면 되고, 맨 위의 동그란 아이콘 줄로도 옮길 수 있습니다(6개까지, 꽉 찬 줄에 넣으면 자리를 맞바꿉니다). '기본 순서'로 처음 배치로 돌아갑니다. TalkBack에서는 아이콘마다 '앞쪽으로 옮기기·뒤쪽으로 옮기기'가 있습니다.
- 다크 모드가 메뉴에 생겼습니다. 한 번 누르면 라이트와 다크가 바뀝니다.
- 메뉴의 사이트 영역이 메뉴의 절반을 차지하던 것에서 카드 하나로 줄었습니다. 사이트 이름과 광고 차단 스위치 아래에 '영역 숨기기', '숨긴 영역', '광고 차단'이 있습니다.
- 메뉴의 '광고 차단'을 누르면 설정 대신 이 페이지에서 한 일을 보여 줍니다. 막은 요청과 팝업, 숨긴 영역, 차단한 서버와 횟수, 켜져 있는 차단 기능을 볼 수 있습니다. 서버 목록은 보고 있는 페이지에 대해서만 메모리에 둡니다.
- 설정 › 모양 › '주소창이 숨었을 때'에서 노치, 페이지를 가리지 않는 얇은 띠, 아무것도 없음 중에서 고를 수 있습니다.
- 블루 스타일 대신 새 블랙 스타일이 생겼습니다(설정 › 모양 › 스타일). 짙은 검정 원에 켜진 기능은 금빛입니다. 블루를 쓰던 분은 블랙으로 바뀝니다.
- 한 사이트의 숨긴 영역을 다른 사이트와 공유하는 기능을 없앴습니다. 연결되어 있던 사이트에는 쓰던 숨긴 영역이 그대로 복사되고, 예전 규칙 파일도 그대로 가져올 수 있습니다.
- 그 밖에: '탭을 닫았습니다' 알림이 3초 뒤에 사라지고, 전체 화면의 나가기 버튼이 작아졌고, 확인 창의 버튼이 긴 이름을 찌그러뜨리지 않고, 숨긴 영역 시트의 버튼이 가지런해졌습니다.

### 1.4.4 — 2026-11-01

- 앱 자체에는 바뀐 점이 없습니다. '업데이트 확인'이 새 버전을 찾는 과정을 처음부터 끝까지 시험해 볼 수 있도록 낸 버전입니다.

### 1.4.3 — 2026-11-01

- 설정 › 정보에서 '업데이트 확인'을 켜면 바로 확인하고 결과를 알려 줍니다. 새 버전이 있으면 바로 갈 수 있는 링크를, 최신이면 최신 버전이라는 것을, GitHub에 연결하지 못하면 그 사실을 알려 줍니다. 그 뒤로는 지금처럼 하루에 한 번 확인합니다.
- 개인정보처리방침에도 이 내용을 반영했습니다. 켜는 즉시, 그리고 그 뒤로 하루에 한 번 확인합니다. 보내는 정보는 달라지지 않았습니다.

### 1.4.2 — 2026-11-01

- 다크 모드가 더 깊어졌습니다. 화면은 검정에 가까워지고, 카드와 주소창은 남색 대신 차분한 차콜이 되었으며, 앱 아이콘 스타일은 연한 테두리 안에 은은한 파스텔 아이콘을 그립니다.
- 주소창이 숨어 있어도 시크릿 탭의 마스크와 자주색이 보이고, TalkBack도 시크릿 탭이라고 알려 줍니다.
- 주소창의 자물쇠는 연결 상태만 나타냅니다. 안전하지 않은 페이지는 '안전하지 않음'으로 읽어 줍니다.
- 주소창, 탭 전환기, 알림의 버튼이 커져 누르기 쉬워졌습니다. 주소창 높이는 그대로입니다.
- 메뉴에서 광고 차단이 켜짐·일부·꺼짐인지 단어로 보여 주고, 설정을 여는 행과 이 사이트 스위치를 구분했습니다.
- 제스처 탐색을 쓰면 오른쪽 가장자리는 항상 휴대폰의 뒤로 가기입니다. 앞으로 가기는 메뉴에 있습니다.
- 밀거나 당길 때 손을 떼면 실행되는 순간이 더 분명하게 보이고, 진동으로도 알려 줍니다.
- 탭이 가득 차면 거절만 하지 않고, 가장 오래된 탭을 닫거나 탭 목록을 보여 줍니다.
- TalkBack이 설정의 스위치를 스위치로, 머리말을 제목으로 읽고, 탭 전환기에서 현재 탭을 알려 줍니다.
- 버튼이 없는 기능은 한 번씩 팁으로 알려 줍니다: 주소창을 밀어 탭 전환, 숨은 주소창 다시 보기, 페이지 일부 숨기기.
- 설정 행 사이에 얇은 구분선이 생겼고, 앱 모양 설정의 이름이 '스타일'로 바뀌었으며, 북마크가 없을 때 바로 가져오기를 할 수 있습니다.

### 1.4.1 — 2026-11-01

- 새 디자인: Hush의 화면과 시트가 부드러운 라벤더 바탕 위의 흰 카드로 바뀌었고, 강조색은 차분한 인디고가 되었습니다. 시크릿 탭은 자두빛 색을 따로 써서 일반 탭과 헷갈리지 않습니다.
- 아이콘 색을 다시 정리해, 어떤 앱 스타일과 다크 모드에서도 서로 겹치거나 튀지 않습니다.
- 팝업이 앱 스타일을 따릅니다. 경고는 여전히 눈에 잘 띄지만 자극적인 빨강을 쓰지 않습니다.
- 쇼핑몰에서 결제·본인인증 앱(ISP, 카드사 앱카드, 뱅크페이, 카카오페이, 토스, 페이코, PASS)이 바로 열립니다. "결제하기"를 누르고 잠시 뒤에 앱을 부르는 페이지도 마찬가지입니다.
- 결제 앱이 설치되어 있지 않으면 스토어 페이지로 안내합니다.
- 앱을 열기만 하는 팝업이 빈 탭을 남기지 않습니다.
- 카카오톡이나 메일처럼 다른 앱에서 연 링크는 뒤로 가기로 그 앱에 바로 돌아갑니다.

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
