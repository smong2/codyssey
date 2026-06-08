# 🚀 Codeyssey: 프롬프트 엔지니어링 프로젝트

> **대규모 언어 모델(LLM)의 환각을 통제하고 원하는 결과물을 안정적으로 도출하기 위한 프롬프트 최적화 및 파이프라인 구축 프로젝트**

---

## 📅 수행 기간
* **2026.06**

## 🛠 사용 기술 스택 (LLMs)
* <img src="https://img.shields.io/badge/Google%20Gemini%201.5%20Pro-4285F4?style=flat-square&logo=googlegemini&logoColor=white"/>
* <img src="https://img.shields.io/badge/Anthropic%20Claude%203.5%20Sonnet-D97706?style=flat-square&logo=anthropic&logoColor=white"/>
* <img src="https://img.shields.io/badge/OpenAI%20GPT--5-412991?style=flat-square&logo=openai&logoColor=white"/>

---

## 🎯 프로젝트 목적
* **환각 제어 (Hallucination Control)**: LLM이 없는 사실을 지어내거나 가공하는 현상을 체계적으로 방어
* **결과물 정교화**: 정해진 비즈니스 규칙과 페르소나를 이탈하지 않는 정교한 제어 기술 확보
* **안전장치 구축**: 입력 조건 누락 시 임의 결론을 내리지 않고, 스스로 확인 질문을 던지는 메커니즘 설계

---

## 🏆 주요 성과

### 1️⃣ 모델 비교를 통한 최적의 자동화 모델 선정
* 동일 과업과 통제된 환경 하에서 `Gemini 1.5 Pro`, `Claude 3.5 Sonnet`, `GPT-5` 3개 모델에 대한 교차 벤치마킹 수행
* 지시 준수, 논리적 추론, 환각 방어, 과도한 출력(Over-helpfulness) 등 4대 평가 축을 기준으로 검증하여 자동화에 가장 최적화된 메인 엔진 모델 발굴 및 선정

### 2️⃣ 단계적 추론 및 확인 질문(안전장치) 시스템 프롬프트 설계
* 필수 정보가 누락되었을 때 임의로 결론짓는 예측 실행을 차단하고, 컨텍스트를 재확인하는 **'되묻기(확인 질문) 규칙'** 프로토콜 확립
* 모델이 임의로 외부 페르소나(예: 튜터의 피드백 등)를 생성하거나 지시하지 않은 과잉 출력을 하지 않도록 제어 구문 고도화

### 3️⃣ 10턴 이상의 대화 문맥 유지 및 환각 방어 성공
* **10턴(Turn) 이상** 장기적으로 지속되는 고밀도 대화 내에서도 초기 지시 사항과 사용자 컨텍스트를 완벽하게 유지
* 비즈니스 안정성을 저해하는 환각 현상(Hallucination)을 완전히 제어하여 신뢰성 높은 결과물 도출 파이프라인 검증 완료
