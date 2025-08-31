# 📚 용어사전 (Glossary)



## A

### API
**정의:** Application Programming Interface, 서로 다른 소프트웨어 간 상호작용을 가능하게 하는 인터페이스.  
**기사 참조:** [보안뉴스, 2025-08-27](https://m.boannews.com/html/detail.html?mtype=2&tab_type=7&idx=138647)  
**설명/예시:** SOAR 솔루션에서 다양한 보안 장비와 연동할 때 활용. 일부 솔루션은 API 제공이 제한되어 연동에 제약이 있을 수 있음.

### ASA Engine (Advanced Security Analytics)
**정의:** 안랩 SOAR에 적용된 머신러닝 기반 분석 엔진. 위협 종류 분류 및 정·오탐 식별 자동화 기능 제공.  
**기사 참조:** [보안뉴스, 2025-08-27](https://m.boannews.com/html/detail.html?mtype=2&tab_type=7&idx=138647)  
**설명/예시:** 보안 이벤트의 맥락을 학습하고, 기존 패턴에 없는 새로운 위협도 탐지할 수 있도록 지원.

## C

### Cloud
**정의:** 인터넷 기반 서버에서 서비스를 제공하고 관리하는 방식.  
**기사 참조:** [보안뉴스, 2025-08-27](https://m.boannews.com/html/detail.html?mtype=2&tab_type=7&idx=138647)  
**설명/예시:** SaaS 형태 SOAR 제공, 온프레미스 설치 없이 서비스 사용 가능.

## E

### EDR (Endpoint Detection and Response)
**정의:** 엔드포인트(PC, 서버, 모바일 기기)에서 발생하는 위협을 탐지하고 대응하는 솔루션.  
**기사 참조:** [보안뉴스, 2025-08-27](https://m.boannews.com/html/detail.html?mtype=2&tab_type=7&idx=138647)  
**설명/예시:** 엔드포인트 악성코드 감지, 의심 프로세스 차단, 랜섬웨어 확산 방지 등.  
**추가 설명:**  
- **격리 방식:** 네트워크 차단, 악성 프로세스 종료, 의심 파일을 격리 디렉토리에 이동  
- **샌드박스 활용:** 의심 파일을 가상 환경에서 실행해 실제 시스템에 영향 없이 악성 여부 분석  
- **SOC 연계:** 탐지된 이벤트와 로그는 보안관제센터(SOC)로 전달되어 중앙에서 모니터링 가능 

## M

### MTTR (Mean Time To Respond)
**정의:** 평균 대응 시간, 보안 이벤트 발생 시 대응 완료까지 걸리는 평균 시간.  
**기사 참조:** [보안뉴스, 2025-08-27](https://m.boannews.com/html/detail.html?mtype=2&tab_type=7&idx=138647)  

### MTTD (Mean Time To Detect)
**정의:** 평균 탐지 시간, 보안 위협이 발생했을 때 탐지까지 걸리는 평균 시간.  
**기사 참조:** [보안뉴스, 2025-08-27](https://m.boannews.com/html/detail.html?mtype=2&tab_type=7&idx=138647)  

## N

### NDR (Network Detection and Response)
**정의:** 네트워크 트래픽 기반 위협 탐지 및 대응 솔루션.  
**기사 참조:** [보안뉴스, 2025-08-27](https://m.boannews.com/html/detail.html?mtype=2&tab_type=7&idx=138647)  
**설명/예시:** 풀패킷 기반의 전수검사로 알려진 위협은 물론 잠재적 이상행위까지 탐지 가능. 쿼드 마이너 Network Blackbox 등이 대표 솔루션.  
**추가 설명:**  
- **대응 방식:** 비정상 세션 종료, 방화벽과 연동해 특정 IP/도메인 차단, SOC로 경고 전달  
- **활용 예시:** 내부 서버에서 대량의 데이터가 해외로 유출되는 트래픽을 탐지 → 즉시 차단  
- **EDR과 차이:** EDR은 개별 기기 수준, NDR은 네트워크 전체 트래픽 감시 및 대응

## O

### On-Premise
**정의:** 자체 서버 및 인프라에서 시스템을 운영하는 방식.  
**기사 참조:** [보안뉴스, 2025-08-27](https://m.boannews.com/html/detail.html?mtype=2&tab_type=7&idx=138647)  
**설명/예시:** SOAR 솔루션을 사내 서버에서 직접 설치 및 운영.

## Q

### QPL (Query Processing Language)
**정의:** Query Processing Language, 쿼리 시스템즈 QTIE에서 사용하는 키바나 스타일의 검색 문법.  
**기사 참조:** [보안뉴스, 2025-08-27](https://m.boannews.com/html/detail.html?mtype=2&tab_type=7&idx=138647)  
**설명/예시:** 위협 탐지와 분석 편의성을 위해 직관적이고 간단한 문법으로 로그·이벤트 검색을 가능하게 함.

## R

### R1, R2, R3
**정의:** 시큐어시스템즈 SecureOrchestra의 AI 기반 분석 모델 단계.  
**기사 참조:** [보안뉴스, 2025-08-27](https://m.boannews.com/html/detail.html?mtype=2&tab_type=7&idx=138647)  
**설명/예시:** 웹 공격, 악성코드, 네트워크 공격 등을 정밀하게 탐지하고 분석하기 위해 다단계 모델(R1, R2, R3)을 적용. 정·오탐 판별 정확도를 높이는 데 활용됨.

## S

### SaaS
**정의:** Software as a Service, 클라우드 기반 소프트웨어 서비스.  
**기사 참조:** [보안뉴스, 2025-08-27](https://m.boannews.com/html/detail.html?mtype=2&tab_type=7&idx=138647)  
**설명/예시:** SOAR 솔루션을 SaaS 형태로 제공하면 온프레미스 설치 없이 웹 브라우저에서 사용 가능.

### SIEM
**정의:** Security Information and Event Management, 보안 이벤트와 로그를 통합 수집·분석하는 시스템.  
**기사 참조:** [보안뉴스, 2025-08-27](https://m.boannews.com/html/detail.html?mtype=2&tab_type=7&idx=138647)  
**설명/예시:** 위협 탐지와 리포팅 중심. SOAR와 연계되어 실시간 대응 가능.

### SOAR
**정의:** Security Orchestration, Automation and Response, 보안 오케스트레이션, 자동화, 대응 솔루션.  
**기사 참조:** [보안뉴스, 2025-08-27](https://m.boannews.com/html/detail.html?mtype=2&tab_type=7&idx=138647)  
**설명/예시:** SIEM과 연계하여 탐지 → 분석 → 대응까지 자동화. 플레이북 구축 용이성, 평균대응시간(MTTR), 평균탐지시간(MTTD), 오탐 감소율이 성능 지표.

### UEBA (User and Entity Behavior Analytics)
**정의:** 사용자 및 엔티티(장비, 시스템 등)의 정상 행위 패턴을 분석해 이상 징후를 탐지하는 기술.  
**기사 참조:** [보안뉴스, 2025-08-27](https://m.boannews.com/html/detail.html?mtype=2&tab_type=7&idx=138647)  
**설명/예시:** 평소 접속·업무 패턴과 다른 행위(예: 비정상 지역 로그인, 대량 데이터 다운로드 등)를 자동 감지해 내부자 위협, 계정 탈취 탐지에 활용.

## X

### XDR (Extended Detection and Response)
**정의:** Extended Detection and Response, SIEM·SOAR·EDR·NDR 등 여러 보안 솔루션을 통합해 위협 탐지와 대응을 확장한 보안 플랫폼.  
**기사 참조:** [보안뉴스, 2025-08-27](https://m.boannews.com/html/detail.html?mtype=2&tab_type=7&idx=138647)  
**설명/예시:** 단일 환경에서 엔드포인트, 네트워크, 클라우드 등 다양한 보안 데이터를 연계 분석해 대응 속도와 정확성을 높임.
