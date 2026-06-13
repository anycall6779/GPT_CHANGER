# ChatGPT Team Plan 링크 생성기

국가와 프로모션 코드를 선택하면 ChatGPT Team Plan 결제 스크립트를 자동으로 만들어주는 도구입니다.

## 기능

- 국가 선택 시 통화(Currency)가 자동으로 변경됨
- 각 국가의 기본 프로모션 코드가 자동으로 채워짐
- 프로모션 코드는 직접 타이핑으로 변경 가능
- 좌석 수 조절 가능
- 생성된 스크립트를 클립보드에 복사

## GitHub Pages 배포 방법

1. 이 저장소를 GitHub에 Push
2. **Settings → Pages** 메뉴로 이동
3. **Source**: `Deploy from a branch` 선택
4. **Branch**: `main` / `(root)` 선택 후 **Save**
5. 잠시 후 `https://<username>.github.io/<repo>/` 에서 확인 가능

## 사용 방법

1. 사이트에서 국가, 프로모션 코드, 좌석 수를 설정
2. **스크립트 생성하기** 버튼 클릭
3. `chatgpt.com` 에 로그인한 상태에서 개발자 도구(F12) → Console 탭 열기
4. 생성된 스크립트를 붙여넣고 Enter

## 지원 국가

| 국가 | 통화 | 기본 프로모 코드 | 가격(2석/월) |
|------|------|----------------|-------------|
| 🇺🇸 미국 | USD | wedoaius | $25.00 |
| 🇲🇽 멕시코 | MXN | wedoaimx | $24.74 |
| 🇵🇰 파키스탄 | PKR | wedoaipk | $25.14 |
| 🇩🇪 독일 | EUR | loptrde | $25.24 |
| 🇦🇺 호주 | AUD | 27aiau | $24.52 |
| 🇮🇳 인도 | INR | 27aiin | $23.59 |
| 🇳🇿 뉴질랜드 | NZD | 27ainz | $23.79 |
| 🇯🇵 일본 | JPY | archinesjp | $23.99 |
