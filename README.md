# Trading Learning

크립토 트레이딩 학습을 위한 개인 프로젝트.

## 목표

초보 단계에서 시작해 직접 트레이딩 능력 향상. 1-2년 장기 학습 계획.

## 학습 단계

- ✅ 단계 0: 위험 관리 기초
- 🔄 단계 1: 시장·차트 기초 (진행 중)
- ⬜ 단계 2: 트레이더 165건 사례 학습
- ⬜ 단계 3: 페이퍼 트레이딩 + 일지
- ⬜ 단계 4: 소액 실전

## 책 학습

**『주식시장에서 살아남는 심리 투자 법칙』** (알렉산더 엘더, 신가을 옮김)

- [Q&A 노트](./learning/04_book_notes/elder_trading_psychology/00_qa_notes.md): 책 읽다 막힌 용어·개념 정리
- [핵심 개념](./learning/04_book_notes/elder_trading_psychology/key_concepts.md): 굵직한 통찰 누적

## 디렉토리 구조

```
.
├── README.md
├── learning/
│   ├── 00_roadmap.md
│   ├── 01_risk_management.md           # 단계 0 — 위험 관리
│   ├── 02_market_basics.md
│   ├── 03_chart_reading.md
│   ├── 04_book_notes/
│   │   └── elder_trading_psychology/
│   │       ├── 00_qa_notes.md          # 용어·개념 Q&A
│   │       └── key_concepts.md         # 핵심 통찰 누적
│   ├── 04_trader_study/                # 외부 트레이더 사례 (원본은 비공개)
│   ├── 05_user_journal/                # 거래 일지 (예정)
│   └── 99_resources.md
└── tools/                              # 학습 보조 도구 (예정)
```

## 사용 도구

- **차트 분석**: TradingView
- **멘토**: Claude 데스크톱 (대화형 학습)
- **파일 작업**: Claude Code (문서 생성·정리)

## 작업 흐름

1. 사용자 ↔ 멘토(Claude 데스크톱) 토론
2. 멘토가 클코(Claude Code) 작업 명세 작성
3. 사용자가 클코에 명세 전달
4. 클코가 파일 작성·수정 + 커밋·푸시
5. 멘토가 GitHub URL로 결과 검증

## 비공개 자료

라이선스·개인정보 문제로 본 저장소에 포함되지 않음:

- **외부 트레이더 165건 원본 거래 로그** (`all_trades.json`, 1m OHLCV CSV)
- **1월 청산 관련 구체 금융 정보** (사용자 본인 계좌·거래소 정보)

학습 콘텐츠에 외부 트레이더 사례를 인용할 때는 **명목가 대비 비율(%)** 로만 표현하며,
KRW·USD 절대값은 노출하지 않습니다.

## 라이선스

개인 학습용. 인용된 책 내용은 해당 출판사·저자 저작권에 따름.
