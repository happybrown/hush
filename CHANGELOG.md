# Changelog

[English](#english) · [한국어](#한국어)

## English

### 1.3.2 — 2026-11-01

- Pages that open in other browsers no longer stop on a certificate warning, most of all in the
  middle of a redirect. A bad certificate on something a page loads (a picture, a script, an
  ad) is refused quietly, as other browsers do; only the page's own address is asked about.
- A site without working `https` opens over `http`, as in other browsers, instead of ending on
  an error page. `https` is still tried first, and an `https` page never loads anything over
  plain HTTP.
- The privacy policy says so; you'll see a one-time notice of the change.

## 한국어

### 1.3.2 — 2026-11-01

- 다른 브라우저에서는 열리는 페이지가, 특히 리다이렉트 도중에 인증서 경고로 멈추던 문제를
  고쳤습니다. 페이지가 불러오는 이미지·스크립트·광고의 인증서 오류는 다른 브라우저처럼 조용히
  막고, 페이지 자체의 주소일 때만 묻습니다.
- `https`가 제대로 동작하지 않는 사이트는 오류 페이지에서 멈추지 않고 다른 브라우저처럼 `http`로
  엽니다. 먼저 `https`로 시도하는 것은 그대로이고, `https` 페이지는 평문 HTTP로 아무것도 불러오지
  않습니다.
- 개인정보처리방침에 이 내용을 반영했으며, 변경 알림이 한 번 표시됩니다.
