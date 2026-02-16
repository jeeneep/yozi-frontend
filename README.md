![header](https://capsule-render.vercel.app/api?type=blur&color=FDFD96&height=300&section=header&text=YOZI&fontSize=90)


##  프로젝트 소개

- 'YOZI'는 경제적 독립을 시작하는 청년층을 위해 개발된 청년 맞춤형 소비 분석 및 피드백 웹 서비스입니다.
- 시연 영상 (클릭하여 재생⬇️)
<p align="center">
  <a href="https://youtu.be/TRbp46-e4iE" target="_blank">
    <img src="https://img.youtube.com/vi/TRbp46-e4iE/mqdefault.jpg" 
         alt="YOZI 시연 영상 썸네일" 
         style="max-width: 500px; border: 2px solid #ddd; border-radius: 8px;">
  </a>
</p>


## 프로젝트 목표
- 시각적 직관성 강화: 캘린더 및 다양한 차트를 활용해 텍스트 위주 가계부의 낮은 접근성 해결.
- 데이터 기반 피드백: 소비 패턴을 수치화(점수화)하여 실질적인 행동 변화 유도.
- 사용자 편의성(UX) 최적화: 복수 내역 동시 입력, 소셜 로그인 등 청년층 친화적 기능 구현.


## 주요 기능

### 📅 시각적 소비 관리 시스템

- 캘린더 기반 UI: 날짜별 지출·수입 내역을 시각적으로 확인하며, 클릭 시 상세 내역 팝업 지원.
- 복수 입력 지원: 한 화면에서 여러 건의 내역을 동시에 입력할 수 있는 다중 작성 기능으로 입력 시간 단축.
- 필터 및 관리: 카테고리/항목별 필터링과 페이지 전환 없는 즉각적인 수정·삭제 기능.

### 💰 스마트 예산 및 분석

- 실시간 예산 추적: 이번 달 잔여 예산과 지난달 대비 초과 여부를 프로그래스 바와 색상 알림으로 직관적 제시.
- 카테고리별 정밀 분석: 파이 차트를 통해 지출이 집중된 구간(주거, 식비 등)을 한눈에 파악.

### 🧠 데이터 분석 기반 피드백

- 소비 습관 점수화: 예산 준수, 전월 대비 감소 등 5가지 지표를 바탕으로 0~100점 사이의 알고리즘 점수 산출.

- 맞춤형 코칭 메시지: 분석 결과에 따라 "예산 내 소비를 잘 지켰어요!"와 같은 조건 기반 피드백 자동 생성.


## 기술 스택 (Tech Stacks)

### Front-End
<div align="center"> 
  <img src="https://img.shields.io/badge/React-18.3.1-61DAFB?style=for-the-badge&logo=react&logoColor=black"/> 
  <img src="https://img.shields.io/badge/TypeScript-5.8.3-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/Zustand-5.0.7-FFCC00?style=for-the-badge&logoColor=white"/> 
  <img src="https://img.shields.io/badge/Styled_Components-6.1.19-DB7093?style=for-the-badge&logo=styledcomponents&logoColor=white"/> 
  <img src="https://img.shields.io/badge/Recharts-3.1.0-22B5BF?style=for-the-badge&logoColor=white"/> 
  <img src="https://img.shields.io/badge/Axios-1.11.0-5A29E4?style=for-the-badge&logo=axios&logoColor=white"/>
</div>

### Back-End / Infrastructure
<div align="center"> 
  <img src="https://img.shields.io/badge/Spring_Boot-3.x-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white"/> 
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/> 
  <img src="https://img.shields.io/badge/AWS-EC2/RDS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white"/> 
  <img src="https://img.shields.io/badge/Vercel-Deployment-000000?style=for-the-badge&logo=vercel&logoColor=white"/> </div>

## 프론트엔드 개발 상세 (담당)

### React 기반 고도화된 UI/UX 구현

- SPA 아키텍처 구축
  - React를 사용하여 끊김 없는 사용자 경험을 제공하는 싱글 페이지 애플리케이션 구현.

- 반응형 디자인
  - styled-components를 활용하여 모바일과 웹 환경에 최적화된 유연한 레이아웃 설계.

- 컴포넌트 중심 개발
  - 캘린더, 모달, 입력 폼 등 재사용 가능한 컴포넌트 설계를 통해 개발 효율성 증대.


### 데이터 시각화 및 인터랙션

- Recharts 라이브러리 활용
  - 복잡한 소비 데이터를 꺾은선 그래프(월별 흐름), 파이 차트(카테고리 비율), 막대 그래프(전월 비교)로 시각화.

- 실시간 데이터 바인딩
  - 사용자가 내역을 입력하거나 예산을 수정할 때 차트와 점수가 즉각 반영되는 인터랙티브 기능 구현.

### 상태 관리 및 최적화

- Zustand 기반 전역 상태 관리
  - 가벼우면서도 강력한 Zustand를 도입하여 복잡한 유저 정보 및 소비 내역 데이터를 효율적으로 관리하고 렌더링 최적화.

- API 연동
  - 백엔드 REST API와 연동하여 OAuth 2.0 인증 정보 유지 및 사용자별 맞춤 데이터 호출 로직 구현.

### 배포 및 자동화

- CI/CD 파이프라인
  - Vercel을 활용하여 프론트엔드 빌드 및 자동 배포 환경을 구축하여 프로젝트 운영 효율성 확보.
 
