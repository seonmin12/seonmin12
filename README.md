<div align= "center">
    <img src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=180&text=Welcome%20to%20my%20space!&animation=&fontColor=ffffff&fontSize=60" />
    </div>
    <div style="text-align: left;"> 
    <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> About myself </h2>  
    <div style="font-weight: 700; font-size: 15px; text-align: left; color: #282d33;"> 데이터 흐름을 이해하고, 이를 기반으로 서비스 구조를 설계하는 백엔드 개발자 김선민입니다.🌱<br>Hello! I'm Seonmin from South Korea, working to get better at both programming and life. I am a backend developer who focuses on understanding data flow and designing services based on it. I strive to build reliable systems that connect data and user experience. </div> 
    </div>

    
## 🎓 Education

🇰🇷 **Bachelor’s Degree in Geography** – Kyung Hee University  
🇳🇴 **Exchange Student** – University of Oslo  
💻 **Java Backend Developer Course** – Shinsegae I&C


## 🌍 Languages

🇰🇷 Korean – Native  
🇺🇸 English – Fluent  
🇩🇪 German – Beginner

## 💼 Experience

### MVNO Strategy Team – LG U+ (2026.05 ~ )
- Large-scale performance data validation with GCP BigQuery & Data Lake  
  (BigQuery/데이터레이크 기반 대용량 실적 데이터 검증)
- SQL query automation (hardcoded date conditions → CTE-based dynamic calculation)  
  (쿼리 기준월 자동화)
- Legacy table migration & query optimization for large datasets (~82M rows)  
  (대용량 테이블 전환 및 쿼리 성능 개선)
- Excel pivot table based performance reporting  
  (피벗테이블 기반 실적 장표 구성)

## 📦 Projects

### MVNO Report Automation (Performance Data Validation & Reporting)
- Automated recurring performance validation/reporting workflow (Python + FastAPI)  
  (반복적인 실적 검증·리포트 업무 자동화)
- Excel report generation with openpyxl, summary image with matplotlib  
  (엑셀 리포트·요약 이미지 자동 생성)
- FastAPI JSON API + Vue 3 SPA, deployed on Vercel  
  (FastAPI API + Vue 3 SPA, Vercel 배포)
- 100% dummy data, portfolio project  
  (전 데이터 100% 더미, 포트폴리오 목적)

### LINKI (Influencer-Advertiser Matching Platform)
- Manual, spreadsheet-based influencer contracts had no unified state tracking, and settlement/review were disconnected from the contract flow  
  (계약이 수기로 진행되어 상태 추적이 어렵고, 정산/리뷰 프로세스가 계약과 단절됨)
- Designed enum-based contract state management so proposal → contract → e-signature → settlement/review runs as one connected flow, integrated UCanSign e-signature API, and used `@Scheduled` for automatic status transitions  
  (Enum 기반 상태 관리로 매칭~정산/리뷰를 하나의 흐름으로 통합, UCanSign 전자서명 연동, 스케줄러 기반 상태 자동 전환)
- Later refactored independently to add Redis caching, indexing, and an authorization audit: 98% cache hit rate (P95 19ms), up to 88x faster queries, 5 authorization issues found and fixed  
  (이후 개인 리팩토링으로 Redis 캐싱·인덱스 최적화·인가 점검 진행 — 캐시 적중률 98%, 조회 성능 최대 88배 개선, 인가 취약점 5건 수정)

### WMS (Warehouse Management System)
- Simple field updates during inbound/outbound processing risked inventory data mismatches  
  (입출고 처리 시 단순 업데이트만으로는 재고 데이터 불일치 발생 가능)
- Designed an event-driven structure so stock quantities update based on inbound/outbound events, separated data access by role (vendor/admin), and built conditional queries with MyBatis  
  (입출고 이벤트 기반 재고 반영 구조 설계, 입점업체/관리자 권한 분리, MyBatis 기반 조건 조회 구현)
- Result: consistent inventory data with inbound/outbound events properly reflected, and a layered structure (Controller-Service-Repository) that kept the codebase maintainable as query logic grew  
  (재고 데이터 정합성 확보, 계층 구조로 유지보수성 향상)
  
    <div style="text-align: left;">
    <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> 🛠️ Tech Stacks </h2> <br> 
    <div  align= "center"> <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white">
          <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white">
          <img src="https://img.shields.io/badge/Github-181717?style=for-the-badge&logo=Github&logoColor=white">
          <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=Java&logoColor=white">
          <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white">
          <img src="https://img.shields.io/badge/Javascript-F7DF1E?style=for-the-badge&logo=Javascript&logoColor=white">
          <br/><img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=HTML5&logoColor=white">
          <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=Linux&logoColor=white">
          <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white">
          <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white">
          <img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=Slack&logoColor=white">
          <br/><img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=Spring&logoColor=white">
         <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
          <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=FastAPI&logoColor=white">
          <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=Vue.js&logoColor=white">
          <br/><img src="https://img.shields.io/badge/Google%20BigQuery-4285F4?style=for-the-badge&logo=Google%20BigQuery&logoColor=white">
          <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=Redis&logoColor=white">
          </div>
    </div>
    <div style="text-align: left;">
    <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> 🧑‍💻 Contact me </h2> <br> 
    <div align= "center"> <a href=https://velog.io/@seonmink12/posts> <img src="https://img.shields.io/badge/Velog-20C997?style=for-the-badge&logo=Velog&logoColor=white&link=https://velog.io/@seonmink12/posts"> </a>
         <a href=mailto:seonmin.kim1030@gmail.com> <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=Gmail&logoColor=white&link=mailto:seonmin.kim1030@gmail.com"> </a>
          </div>  <br> 
    <div align= "center">  </div> 
    </div>
    <div style="text-align: left;"> 
    <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> 🏅 Stats </h2> <div align= "center"> <img src="https://github-readme-stats.vercel.app/api?username=seonmin12&bg_color=180,ffffff,00000000&title_color=000000&text_color=000000"
         /> <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=seonmin12&layout=compact&bg_color=180,ffffff,00000000&title_color=000000&text_color=000000"
           /> </div> 
    </div>
