# 조진희

**Senior Game Client Programmer / Technical Lead Candidate**

| | |
|---|---|
| **Email** | jinenim@naver.com |
| **Portfolio** | [GitHub Portfolio](https://github.com/jinenim/Resume/blob/main/Portfolio.md) |

---

## Professional Summary

- 게임 클라이언트 개발 경력 **15년 이상**, 모바일·온라인 상용 게임 다수 출시 및 라이브 서비스 경험
- Unity 기반 **메인 클라이언트 프로그래머**로 전투·스킬·스탯·UI·서버 연동·결제·최적화 전 영역 담당
- 대규모 스크립트 규모 코드베이스를 아키텍처 관점에서 정리 및 안정화
- 성능(GC/프레임), 네트워크 안정성, 운영 확장성을 중시하는 실전형 시니어 개발자

---

## Core Competencies

| 영역 | 역량 |
|------|------|
| **전투 시스템** | FSM / Behavior Tree 기반 전투 및 캐릭터 상태 관리 아키텍처 설계 |
| **성능 최적화** | GC Zero Allocation 최적화 (LinqGen, ZString, Addressables) |
| **네트워크** | 라이브 서비스 서버 동기화, 재시도 로직, 네트워크 안정성 설계 |

---

## Professional Experience

### Freelance – Senior Client / Web Server Programmer
**2025.05 – 2026.01**

#### K 데몬헌터 키우기 – Mobile Idle Action RPG

🔗 [Google Play](https://play.google.com/store/apps/details?id=com.codedragon.woochi&hl=ko)

- **초기 개발부터 출시까지** 메인 클라이언트 프로그래머로 참여
- 다수의 액티브/패시브 스킬이 공존하는 구조에서 스킬 발동 조건·쿨타임·효과 적용을 공통화하여 **확장 가능한 스킬 시스템** 설계
- **150개 이상 스탯**이 실시간 전투 계산에 사용되는 구조에서 캐싱 + 이벤트 기반 갱신 구조를 도입하여 **프레임당 연산 비용 대폭 감소**
- 80+ UI Notification 상태를 **ReactiveProperty 기반으로 중앙 관리**하여, 폴링 제거·상태 의존성 단순화·운영 확장 비용을 절감한 알림 시스템 구축
- 라이브 서비스 환경에서 누적되는 메모리/GC 이슈를 분석하여 **GC 발생 구간 제거 및 크래시 빈도 감소** 중심으로 클라이언트 안정성 개선
- 전투·성장·소환·길드 시스템을 **모듈 단위로 분리·구성**하여 유지보수성과 확장성 확보
- PHP + MySQL 기반 서버 데이터 구조 및 API 설계로 클라이언트–서버 데이터 흐름 안정화
- **Google / Apple 인기 순위 1위**, Google Play 매출 상위권 달성

---

### 네오큐브게임즈 – Senior Client Programmer
**2023.09 – 2025.05**

#### 팡팡수호대 – Defense (2024.09 – 2025.05)

- **초기 개발부터 출시까지** 메인 클라이언트 프로그래머로 참여
- **Photon Quantum** 기반 결정론적 멀티플레이 시스템 구현 – 모든 클라이언트가 동일 입력으로 동일 결과 보장
- **ECS(Entity Component System)** 아키텍처로 게임 로직 설계 – 5종 캐릭터 클래스별 독립 시스템
- 콘텐츠(Stage/Challenge)별 필요한 시스템만 동적 등록하여 성능 최적화
- Unsafe 포인터 + 구조체 기반 고성능 게임 루프 구현
- Photon Realtime 매치메이킹 + BSON/AES 암호화 데이터 동기화

#### 가디언즈 디펜스 – Defense (2023.09 – 2024.08)

🔗 [YouTube](https://www.youtube.com/watch?v=DU6c8LZxf3o)

- **초기 개발부터 출시까지** 메인 클라이언트 프로그래머로 참여
- 실시간 전투/상태 동기화를 위해 **gRPC + MagicOnion** 기반 저지연 통신 구조 도입
- **26종 이상의 캐릭터 AI**를 공통 베이스 위에 개별 패턴 확장 구조로 설계하여 관리 비용 최소화
- Firebase 로그인, Android/iOS 인앱 결제 처리
- 로비–전투–상점 등 클라이언트 전체 흐름 담당

---

### NHN – Senior Client Programmer
**2022.08 – 2023.08**

#### 소셜 카지노

- 서버로부터 최소 상태 데이터만 수신 후 **클라이언트 사이드에서 게임 세션을 재구성**하는 구조 설계
- 접속 시점과 무관하게 즉시 플레이 가능한 UX 구현으로 라이브 서비스 안정성 확보
- 실시간 베팅 기반 커뮤니티 게임 로직 구현

---

### 초콜릿소프트 – Senior Client / Web Server Programmer
**2017.05 – 2022.08**

#### 합성 소녀 – Idle RPG (2021.01 – 2022.08)

🔗 [Google Play](https://play.google.com/store/apps/details?id=com.gamepub.hab.g)

- **초기 개발부터 출시까지** 메인 클라이언트 프로그래머로 참여
- **Excel → C# 코드 자동 생성 파이프라인** 구축으로 대규모 테이블(90+종) 관리 및 기획–개발 협업 효율 개선
- **Addressables 기반 동적 에셋 로딩** 시스템 설계로 메모리 사용량 최적화
- **WebSocket + Protobuf + MsgPack** 기반 저지연 실시간 통신 아키텍처 설계
- 치트 탐지 및 서버 기반 검증 로직 구현
- **Google Play 50만 다운로드**, 매출 순위 37위 달성

#### 대장장이 용병단 – Idle RPG (2019.01 – 2020.12)

🔗 [Google Play](https://play.google.com/store/apps/details?id=com.gamepub.mc.g)

- **초기 개발부터 출시까지** 메인 클라이언트 프로그래머로 참여
- 전투·버프·머지·아이템·상점 등 클라이언트 핵심 시스템 전반 설계 및 구현
- Google Play / App Store / OneStore **멀티 플랫폼 인앱 결제** 구조 통합
- Firebase, Adjust, OneSignal 연동으로 운영 분석 및 푸시 파이프라인 구축
- 글로벌 출시 후 **100만 다운로드 이상** 달성

#### 다크 타운 – Action RPG (2017.05 – 2018.12)

🔗 [YouTube](https://www.youtube.com/watch?v=JWXYGugWevs) | [Naver Cafe](https://cafe.naver.com/soullike)

- **초기 개발부터 출시까지** 메인 클라이언트 프로그래머로 참여
- **20종 이상의 보스 AI** 및 패턴 설계
- 매 입장 시 구성이 변경되는 **동적 던전 생성 시스템** 설계로 반복 플레이 구조 개선
- 전투·아이템 등 클라이언트 시스템의 90% 이상 담당
- **Google Play 10만 다운로드 이상** 달성

---

### 인피니티게임즈 (Netmarble 자회사) – Senior Client Programmer
**2015.06 – 2016.04**

#### NOW – MORPG (Unreal Engine / C++)

- Unreal Engine 기반 MORPG 클라이언트 개발에 참여하며 대규모 온라인 RPG 구조 및 Unreal/C++ 환경 실무 경험 축적
- 장비·소비·강화 아이템 등 아이템 시스템 전반을 담당, 아이템 획득 → 장착 → 강화 → 상태 반영까지의 전체 플로우 구현
- 아이템 상태 변경 시 발생하는 클라이언트–서버 간 데이터 불일치 문제를 고려한 동기화 로직 설계
- C++ 환경에서의 메모리 관리, 객체 수명 관리, 성능 이슈를 고려한 구현 경험 축적

---

### 아이덴티티게임즈 – Senior Client Programmer
**2013.10 – 2015.06**

#### SD건담 G제네레이션 프론티어 (2014.12 – 2015.01)

- 일본 서비스 중이던 타이틀의 한국 서비스 로컬라이징 작업 전반 담당
- 언어별 텍스트 길이 차이로 인한 UI 깨짐, 레이아웃 붕괴 이슈를 구조적으로 해결
- 리소스, 문자열, 설정 데이터의 지역별 분기 처리 체계 정비
- 운영 중 발생하는 지역화 관련 이슈를 지속적으로 대응하며 라이브 서비스 환경에서의 빠른 수정·배포 경험 축적

#### 절벽대전 for Kakao (2013.12 – 2014.03)

- **초기 개발부터 출시까지** 클라이언트 프로그래머로 참여
- Cocos2D 기반 실시간 액션 전투 로직 구현
- 입력 반응성, 프레임 유지 등을 고려한 모바일 환경 성능 최적화 경험
- 카카오 플랫폼 로그인 및 서비스 연동 처리
- 플랫폼 요구사항에 따른 빌드 및 운영 이슈 대응 경험

#### 밀리언아서 for Kakao (2013.10 – 2013.11)

- 기존 서비스 중이던 타이틀을 카카오 플랫폼에 연동하기 위한 클라이언트 작업 담당
- 로그인·친구·초대 등 카카오 플랫폼 API 연동
- 기존 게임 로직과 플랫폼 기능 간 충돌 이슈를 분석·해결
- 라이브 서비스 환경에서의 플랫폼 종속 이슈 및 운영 리스크 대응 경험 축적

---

### Wemade Creative – Client Programmer
**2011.06 – 2012.11**

#### 히어로 스퀘어 – Hybrid SNG / RPG

- Unity 기반 클라이언트 시스템 개발
- 마을 지형 시스템 구현 (맵 이동, 오브젝트 배치, 상호작용 처리)
- 메뉴, 팝업, 캐릭터 관리 등 UI 전반 구현
- 퀘스트 조건 체크 및 보상 처리 로직 개발
- SNG와 RPG 요소가 결합된 구조를 경험하며 이후 모바일 RPG 설계에 대한 이해도 확보

---

### 엠게임 (MGame) – Client Programmer
**2006.08 – 2009.11**

#### 열혈강호 온라인 – MMORPG

- C++ 기반 MMORPG 클라이언트 업데이트 및 유지보수 개발
- 신규 콘텐츠 추가에 따른 클라이언트 기능 반영
- UI 및 게임 로직 전반의 버그 수정 및 안정화 작업
- 수년간 서비스된 대규모 온라인 게임의 레거시 코드베이스를 다루며 '운영 중인 게임을 건드리는 감각'과 안정성 중심 개발 방식 체득
- 다수의 유저가 동시에 플레이하는 환경에서 발생하는 실서비스 이슈 대응 경험 축적

---

## Skills

| 분류 | 기술 |
|------|------|
| **Languages** | C#, C++, PHP |
| **Engines** | Unity, Unreal Engine |
| **Database** | MySQL |
| **Async / Reactive** | UniTask, ReactiveProperty |
| **Optimization** | LinqGen, ZString, Addressables |
