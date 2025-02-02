# SPOTL - 소규모 공연 명단관리 앱/웹

## 소개
**SPOTL**은 "Spotlight"에서 이름을 따온 플랫폼으로, 모든 사람이 주인공이 될 수 있는 공연 환경을 제공합니다.  
공연 기획, 개최, 관람까지 손쉽게 이루어질 수 있는 통합 솔루션을 제공합니다.

---

## 개발 개요

### 공연 시장 성장
- 2023년 기준, 공연 및 티켓 거래액이 **1조 원** 돌파 (출처: 인터파크 공연 결산)
- 2021년 대비 **134% 성장**  
  - 2021년: 코로나19로 침체된 시장  
  - 2022년: 두 배 이상의 성장률 기록  

### 시장 문제점 및 해결 방안
#### **AS-IS**  
1. **회원 관리 부재**  
   - 관객 정보 수집이 구글폼 등 비체계적 방식에 의존
   - 무단 입장 및 입금 확인 오류 발생 가능  
2. **티켓 발행 및 배송 절차 부재**  
   - 비체계적 티켓 발권, 번거로운 개별 메시지 전송  
3. **입장 관리의 비효율성**  
   - 수기 확인으로 관객 대기 시간 증가, 입장 혼란  
4. **관객 규모 파악의 어려움**  
   - 사전 관객 정보 수기로 관리  

#### **TO-BE**  
1. **회원 및 고객 관리 디지털화**  
   - 관리자: 관객 정보 통합 관리, 입금 확인 자동화  
   - 고객: 본인 인증 및 정보 확인 가능  
2. **티켓 발행 및 배송 시스템 구축**  
   - 관리자: QR 코드 티켓 발행 및 자동 발송  
   - 고객: QR 티켓을 통한 간편 확인 및 입장  
3. **입장 관리 자동화**  
   - QR 스캔으로 관객 정보 및 입금 여부 확인  
4. **공연 준비 효율성 개선**  
   - 관객 정보 실시간 파악으로 대기 시간 단축  

---

## 주요 고객
 **소규모 공연 주최 단체** : 대학생 동아리, 독립 밴드, 연극 팀 등  

---

## 주요 기능 및 서비스 플로우
![서비스플로우](https://github.com/user-attachments/assets/72bf1865-5b92-4175-a31c-75de5f27ae59)

**📅 공연 주최 및 예약 관리**
소규모 공연 기획자들을 위한 통합 예약 시스템
간편한 공연 등록 및 관리 기능
<br/><br/>
**🎫 공연 리스트 확인**
다양한 공연 정보 한눈에 보기
실시간 공연 목록 업데이트
<br/><br/>
**🔐 QR 기반 티켓 관리**
디지털 티켓 발행 및 스캔
간편하고 안전한 입장 관리 시스템
<br/><br/>
<br/><br/>
![UserDiagram](https://github.com/user-attachments/assets/4636fecf-5f09-4581-9101-348ff7185402)
<br/><br/>
 **역할 기반 UML 다이어그램**
<br/><br/>

---

## 기술 스택

### Frontend
| 기술       | 상세 내용                                                                                          |
|------------|---------------------------------------------------------------------------------------------------|
| **Expo**   | `Expo route`, `Expo Notification(Push Notification)`, `Expo Image` |
| **언어**   | Typescript                                                                                       |
| **스타일** | Styled Component                                                                                 |
| **라이브러리** | Axios, Zustand, Tanstack Query                                                                 |
| **테스트** | Jest, Detox, MSW                                                                                 |
| **Linting** | ESLint & Prettier                                                                               |


### Backend
| 기술              | 상세 내용                        |
|-------------------|----------------------------------|
| **프레임워크**     | Spring Framework                |
| **DB**            | MySQL                           |
| **API 문서화**     | Swagger                         |
| **테스트 도구**    | Postman                         |
| **배포 환경**      | CloudType                       |
| **SMS 서비스**     | CoolSmsServiceAPI               |
| **지도 서비스**    | NaverMapAPI                     |
| **파일 저장소**    | Amazon S3                       |

---

## 개발 기간
**2024년 9월 9일 ~ 2024년 12월 10일**
