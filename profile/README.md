### <img src="https://github.com/user-attachments/assets/70ef9d52-2bf0-492e-bd62-8fa55825cc88" width="18px"/> 한국마이크로소프트 AI Express 해커톤 <a href="http://msaiex.site/Main" target="_blank">MsaiEx</a>
# MsaiEX (Easy foreign Exchange)
**정보제공부터 외환투자까지 하나에 누구나 쉽게 시작할 수 있는 외환거래 서비스**

### 수행 기간

- **2024.10.01 – 2024.10.28**

### 담당 업무

- **기획, 화면 설계, 서비스 개발**

### 참가 인원
| [성창민](https://github.com/indaegu) | [양진안](https://github.com/moho852) | [김현석](https://github.com/mrbonk97) | [장규은](https://github.com/gyueunnim) |
| :---: | :---: | :---: | :---: |
| <img src="https://github.com/user-attachments/assets/c6c5279d-e34e-4329-8b30-f5e0e30ef6db" width="150"/> | <img src="https://github.com/user-attachments/assets/a6263def-880f-4699-9b8e-9bac79c0eec7" width="150"/> | <img src="https://github.com/user-attachments/assets/78aae1c8-b5cb-4352-a3c9-946395ef7fc2" width="150"/> | <img src="https://github.com/user-attachments/assets/00b2c12e-0a46-46e6-92ae-37b5f2c2cf4d" width="150"/> |

## 프로젝트 개요

### 1. 프로젝트 개요

#### 1-1. 외환시장 관심 증가

- **2024 원/달러 급등**으로 인한 환전을 통한 재테크 "**환테크**" 관심도 급증
- **해외여행 트렌드 및 무료 환전 서비스 대중화**로 고객들의 외화 환전 관심 증가
- **외화시장 규제 완화**

➡️ **외환시장에 대한 관심도 상승으로 인해 수요가 늘어날 것으로 예상되며, 새로운 수요를 위한 FX 서비스가 필요**

#### 1-2. 생성형 AI

- 금융권에서 **생성형 AI 도입이 핵심 과제**로 부상
- 시중 **5대 은행이 생성형 AI 서비스 적용 경쟁**

➡️ **금융권 생성형 AI 트렌드에 맞춰 FX 서비스에 적용**

#### 1-3. 결론

- "**환테크**" 트렌드와 **생성형 AI 기술을 접목**한 새로운 FX 프로젝트 기획

### 2. 프로젝트 목적

#### 2-1. 외환 투자 진입장벽 해소

- **하나환율리포트 및 환율, DXY, 유가, 금리 데이터**를 기반으로 **생성형 AI가 외환 예측 리포트**를 제공하여 투자 판단 기준 제공
- **하나환율노트, 매일경제** 등에서 제공하는 환율 정보를 **생성형 AI가 요약 및 분석**하여 사용자들이 쉽게 정보 습득 가능

## 주요 기능

### 1. 외환거래

- **실시간 외환 가격과 연동**하여 외환 거래 기능 구현
- **스프링 스케줄러**를 활용한 **예약 결제 기능** 구현
- 결제 체결 시 **체결 문자**를 사용자에게 전송

### 2. 인공지능 기반 정보제공

- **금융 데이터를 전문으로 학습한 생성형 AI**를 활용하여 **예측 결과 및 판단 이유** 제공
- 수집한 **뉴스 데이터를 기반으로 감성 분석** 결과 전달
- **현지 뉴스와 한국 뉴스 요약**, 각 뉴스에 대한 **분석 포인트 및 호재/악재 정보** 전달

## 프로젝트 상세
## 사용 기술

![MS_PPT_시스템아키텍처 1](https://github.com/user-attachments/assets/454c71bc-56f3-486d-8ed3-8b9470c2ccb3)

## 시스템 아키텍처

![PPT_시스템아키텍처 1](https://github.com/user-attachments/assets/f2e8918c-8929-4cfa-9040-66caa324954d)

### 개발 환경

- **JAVA**: 17
- **Spring Boot**: 3.2.2
- **React**: 18.3.1
- **Ubuntu**: 24.04

### Language/Tool/DB

- **Language**: JAVA, Python, JavaScript
- **IDE**: VSCode, IntelliJ
- **DB**: Oracle 19c (Oracle Cloud DB), MySQL




## 기대 효과 및 보완점

### 1. 기대 효과

#### 1-1. 손님 관점

- **손쉬운 정보 취득**: 생성형 AI 기반으로 외환 리포트, 경제 뉴스 등을 분석 및 요약하여 손님이 외환 정보를 쉽게 소비할 수 있음
- **진입장벽 해소**: 하나외환리포트 및 환율 기반으로 투자 판단 지표를 제공하여 투자에 대한 진입장벽 해소

#### 1-2. 비즈니스 관점

- **FX 이용객 증가**: 누구나 손쉽게 접근할 수 있는 FX 서비스를 제공하여 이용객 증가 예상
- **FX 수익 증가**: 서비스 이용객 증가로 거래에서 발생하는 수수료 수익 증가 예상

### 2. 보완점

- **결제 트랜잭션 처리**: 결제 중 오류 발생 시를 대비한 트랜잭션 처리 필요
- **보안 요소 추가**: Spring Security를 통해 사용자 인증 보안 강화
- **CI/CD 적용**: 지속적인 코드 통합으로 서비스 개발 효율성 향상 필요
