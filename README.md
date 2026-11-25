# (주)세주농업회사법인 홈페이지

> 함께 성장하는 농업의 미래

여주고구마 계약재배 전문 기업 **(주)세주농업회사법인**의 원페이지 홍보·안내 웹사이트입니다.
빌드 과정 없이 HTML/CSS/JS만으로 구성된 정적 사이트입니다.

## 메뉴 구성

| 섹션 | 내용 |
|---|---|
| 회사소개 | 인사말, 핵심 가치, 고구마 우수성, 유통 과정(콜드체인) |
| 계약재배 | 계약재배의 가치, 5단계 프로세스, 농가 인터뷰 |
| 농가소통 | 게시판(공지/재배 노하우/시장 정보/Q&A), 농가 전용 공간 |
| 고객센터 | 연락처, 자주 묻는 질문, 온라인 문의 양식 |

## 폴더 구조

```
.
├── index.html            # 사이트 전체 (HTML + CSS + JS)
├── assets/
│   ├── img/              # 사진
│   └── logo/             # 심벌 (흰색 / 진한색)
├── .nojekyll             # GitHub Pages 설정용
└── README.md
```

## 로컬에서 보기

`index.html`을 브라우저로 열면 됩니다. 또는:

```bash
npx serve .
# 또는
python3 -m http.server 8000
```

## GitHub에 올리기

```bash
git init
git add .
git commit -m "세주농업회사법인 홈페이지 초기 버전"
git branch -M main
git remote add origin https://github.com/changbaeyoon-prog/seju-website.git
git push -u origin main
```

## GitHub Pages로 공개하기

1. 저장소 **Settings → Pages** 이동
2. **Source**: `Deploy from a branch` / **Branch**: `main`, 폴더 `/ (root)` 선택 후 저장
3. 1~2분 후 `https://changbaeyoon-prog.github.io/seju-website/` 에서 확인

### 자체 도메인(www.sejufarm.com) 연결

1. Settings → Pages → **sejufarm.com**에 `www.sejufarm.com` 입력
2. 도메인 업체 DNS에 CNAME 레코드 추가: `www` → `changbaeyoon-prog.github.io`
3. **Enforce HTTPS** 체크

## 운영 시 참고

- **온라인 문의 양식**은 현재 화면 시연용입니다. 실제 접수하려면 [Formspree](https://formspree.io) 같은 폼 서비스나 서버 연동이 필요합니다.
- **게시판 글**은 `index.html` 하단 `<script>`의 `posts` 객체에 들어 있는 예시입니다.
- **농가 로그인 / 개인정보처리방침 / 이용약관** 링크는 아직 연결되지 않았습니다.
- 폰트: Noto Serif KR (Google Fonts), Pretendard (jsDelivr CDN)

## 연락처

- 주소: 경기도 여주시 북내면 신접1길 29-19
- Tel 010.4761.5327 · Fax 031-883-9457
- sangjun1@hotmail.com · www.sejufarm.com

---

© 2026 (주)세주농업회사법인. All rights reserved.
