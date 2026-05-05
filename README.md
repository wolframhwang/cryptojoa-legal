# CryptoJoa (코인좋아) — Legal & Support

> 한국어 버전 아래에 English version 있어요. (English version below.)

---

## 개인정보처리방침 / Privacy Policy

**최종 업데이트: 2026년 5월 5일**

CryptoJoa(이하 "본 앱")는 사용자의 개인정보를 매우 중요하게 생각하며, "개인정보 보호법" 등 관련 법령을 준수합니다.

### 1. 수집하는 개인정보 항목

본 앱은 **어떤 개인정보도 수집하지 않습니다.**

- 회원가입이 없습니다.
- 거래소 API 키, 자산, 거래 내역을 요구하지 않습니다.
- 이메일, 이름, 연락처를 수집하지 않습니다.
- 사용 행태, 광고 식별자(IDFA)를 추적하지 않습니다.

### 2. 디바이스 내부 저장 정보

본 앱은 다음 정보를 **사용자의 디바이스 내부에만(UserDefaults)** 저장합니다. 이 정보는 외부 서버로 전송되지 않습니다.

- 관심 종목 리스트 (예: BTCUSDT, KRW-ETH)
- 즐겨찾기 종목
- 언어 / 새로고침 간격 / 알림 설정
- 마지막으로 본 시장 상태 (regime 변동 알림 판단용)
- 면책 동의 버전
- 인앱 결제 잠금 해제 상태 캐시

위 정보는 앱을 삭제하면 함께 삭제되며, 복구할 수 없습니다.

### 3. 외부로 전송되는 데이터

본 앱이 네트워크로 통신하는 곳은 다음 두 곳뿐입니다. 모두 공개 API이며, 인증 정보(API 키 등)를 전송하지 않습니다.

- `https://api.binance.com` — Binance 공개 시세 데이터
- `https://api.upbit.com` — Upbit 공개 시세 데이터

각 거래소 서버는 표준 HTTPS 요청에 따라 IP 주소·요청 시각 등을 자체 로그로 기록할 수 있으며, 이는 본 앱의 통제 범위를 벗어납니다.

### 4. 결제 처리

전략 백테스트 잠금 해제(₩1,000, 1회 결제)는 Apple의 **StoreKit**을 통해서만 처리됩니다. 본 앱은 결제 카드 정보·거래 영수증을 직접 처리하거나 저장하지 않습니다. 결제 처리·복원·환불은 모두 Apple 정책에 따릅니다.

### 5. 푸시 알림

본 앱은 시장 상태 변동을 알리는 **로컬 알림**만 사용합니다. 디바이스 토큰을 서버로 전송하지 않으며, 원격(서버) 푸시는 사용하지 않습니다. 알림은 설정에서 언제든 끌 수 있습니다.

### 6. 만 14세 미만 아동의 개인정보

본 앱은 만 14세 미만 아동의 개인정보를 의도적으로 수집하지 않습니다.

### 7. 거래소와의 관계

본 앱은 Binance, Upbit, 또는 다른 어떤 거래소·금융기관과도 제휴, 후원, 파트너 관계가 없습니다. 거래소 명칭은 데이터 출처를 명시하기 위해서만 사용됩니다.

### 8. 본 방침의 변경

본 방침이 변경될 경우, 본 페이지의 "최종 업데이트" 날짜를 갱신하고 변경 사항을 이 페이지에 기재합니다. 중대한 변경의 경우 앱 내부에서도 안내합니다.

### 9. 개인정보처리책임자 / 문의처

- 책임자: 황지웅
- 이메일: wltkak2@gmail.com

---

<a id="support"></a>

## 지원 / Support

### 자주 묻는 질문 (FAQ)

**Q. 어떤 데이터를 보여주나요?**

공개 거래소(Binance, Upbit)의 일봉/시간봉 시세 데이터와, 그 위에 EMA·RSI·ATR·Bollinger Bands 같은 공개 기술 지표를 적용한 결과를 보여줍니다.

**Q. "안전" "위험" 라벨은 매수·매도 신호인가요?**

아닙니다. 공개 지표를 기반으로 한 시장 상태 분류일 뿐입니다. 모든 매매 판단은 사용자 본인의 책임입니다.

**Q. 백테스트 결과의 수수료·슬리피지는?**

백테스트는 % 기반으로 단순 시뮬레이션하며, 거래소 수수료와 슬리피지(체결 지연으로 인한 가격 차이)는 반영되지 않습니다. 실제 거래 시에는 결과가 달라질 수 있습니다.

**Q. 백테스트 결제를 환불받고 싶어요.**

Apple 환불 정책에 따라 [reportaproblem.apple.com](https://reportaproblem.apple.com)에서 환불을 요청해주세요. 본 앱은 결제 처리에 직접 관여하지 않습니다.

**Q. 새 거래소(예: Bithumb, Coinbase)를 추가해주세요.**

요청은 환영합니다. 아래 이메일로 보내주세요.

### 문의

- 이메일: **wltkak2@gmail.com**
- 응답 시간: 영업일 기준 1~3일

---

## 면책 / Disclaimer

CryptoJoa는 매매 추천 앱도, 투자 자문 앱도 아닙니다. 본 앱이 제공하는 모든 정보는 개인 참고용이며, 정확성·시점성·가용성은 외부 거래소 데이터에 따릅니다. 모든 매매 결정과 그로 인한 손익에 대한 책임은 사용자 본인에게 있습니다.

---

# Privacy Policy (English)

**Last updated: May 5, 2026**

CryptoJoa ("the App") respects your privacy.

### What data we collect

**None.** No accounts. No exchange API keys. No tracking. No analytics. No advertising identifiers.

### What we store locally on your device

The App stores the following on your device's UserDefaults only. This data is never transmitted to our servers (we don't have any).

- Your watchlist symbols
- Favorite symbols
- Language / refresh interval / notification preferences
- Last seen market regime per symbol (for change notifications)
- Disclaimer acceptance version
- IAP entitlement cache

This data is deleted when you delete the App.

### External services

The App makes HTTPS requests only to:

- `https://api.binance.com` — public market data
- `https://api.upbit.com` — public market data

Both are public, unauthenticated endpoints. Each exchange may log IP/request metadata per their own policies, which is outside our control.

### In-app purchases

The Backtest Unlock (₩1,000 one-time purchase) is processed entirely by Apple StoreKit. We never see or store your payment card information.

### Push notifications

The App uses **local** notifications only — no device tokens are sent to any server, and no remote push is used.

### Children's privacy

The App is not directed at children under 13 (or under 14 in Korea), and we do not knowingly collect their data.

### Exchange affiliation

We are not affiliated with, sponsored by, or partnered with Binance, Upbit, or any exchange or financial institution. Exchange names are referenced solely to identify data sources.

### Changes

If this policy changes, we'll update the "Last updated" date above.

### Contact

- Email: wltkak2@gmail.com
- Operator: Jiwoong Hwang

---

## Disclaimer

CryptoJoa is **not** investment advice. Labels and indicators are for personal reference only. All trading decisions and resulting outcomes are your own responsibility.
