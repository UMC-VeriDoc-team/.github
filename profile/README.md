### VeriDoc - 사용자 맞춤형 의료 정보 큐레이션 서비스

<div align="center">
  <img src="./assets/veridoc-intro.svg" alt="VeriDoc Logo" />
</div>

<br/>

<div align="center">
  <a href="https://veridoc-umber.vercel.app/">홈페이지</a>
  |  
  <a href="https://distinct-manchego-e2f.notion.site/VeriDoc-2d91c66fccee8038bc97f39cfde05dfd?source=copy_link">Notion</a>
  |
  <a href="http://13.125.170.209/api-docs">Swagger</a>
</div>

---

## ✍️ 프로젝트 개요

- **프로젝트명:** VeriDoc (베리닥)
- **프로젝트 기간:** 2025.12.22 ~ 2026.02.19
- **프로젝트 형태:** UMC 9th 프로젝트
- **목표:** 정보 과잉 시대에 사용자가 자신의 증상을 쉽고 정확하게 기록하고, 검증된 전문의 콘텐츠를 통해 신뢰도 높은 의료 탐색을 할 수 있도록 돕는 서비스 개발
- **주요 타겟 사용자:** 정확한 건강 정보와 빠른 자가 대처법을 찾는 모든 사용자

---

## ✍️ 프로젝트 소개

### 프로젝트 배경

기존의 의료 정보 검색 프로세스는 다음과 같은 문제점이 있었습니다:

1. **정보의 과부하 및 부정확성**: 검색 결과가 너무 많거나, 광고성 정보로 인해 신뢰할 수 있는 정보를 찾기 어려움
2. **증상 기록의 파편화**: 자신의 증상을 구체적으로 기록하고 관리할 수 있는 직관적인 도구의 부재
3. **초기 대응의 막막함**: 병원 방문 전, 신뢰할 수 있는 임시 대처법(스트레칭, 찜질 등)을 찾기 힘듦

**VeriDoc**은 위 문제를 해결하기 위해 증상 라벨링 시스템과 검증된 전문의 답변 큐레이션, 그리고 위치 기반 병원 추천을 결합하여 사용자에게 최적화된 의료 여정을 선사합니다.

---

## 🚀 프로젝트 목표

1. **의료 정보의 신뢰성 확보**: 검증된 기관 및 전문의의 데이터만 노출하여 사용자 신뢰도 구축
2. **직관적인 사용자 경험(UX)**: 웹과 모바일 어디서든 매끄러운 반응형 환경과 쉬운 증상 입력 제공
3. **탐색 효율성 극대화**: 사용자의 위치와 증상에 기반한 병원 추천으로 진료 장벽 완화

---

## 📌 주요 기능

### **1. 증상 라벨링 기반 입력**
- 대표 증상과 세부 증상을 태그 형태로 선택하여 현재 상태를 정확하고 간편하게 기록합니다.

### **2. 검증된 전문의 답변 & 임시 대처**
- 증상별로 출처가 명확한 전문의 답변 1건과 즉각적인 도움이 되는 스트레칭/응급 처치 정보를 제공합니다.

### **3. 위치 기반 병원 추천**
- 선택한 증상과 연관된 진료과 병원 중, 사용자 위치에서 가장 가까운 TOP 3 정보를 추천합니다.

<table>
  <tr>
    <td><img src="./assets/1.svg" width="100%" /></td>
    <td><img src="./assets/2.svg" width="100%" /></td>
    <td><img src="./assets/3.svg" width="100%" /></td>
    <td><img src="./assets/4.svg" width="100%" /></td>
  </tr>
  <tr>
    <td><img src="./assets/5.svg" width="100%" /></td>
    <td><img src="./assets/6.svg" width="100%" /></td>
    <td><img src="./assets/7.svg" width="100%" /></td>
    <td><img src="./assets/8.svg" width="100%" /></td>
  </tr>
</table>

---

## ⚙️ 기술 스택

<table>
  <thead>
    <tr>
      <th>분류</th>
      <th>기술 스택</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Frontend</td>
      <td>
        <img alt="React" src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB">
        <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white">
        <img alt="Vite" src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white">
        <img alt="TailwindCSS" src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white">
        <img alt="Axios" src="https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white">
        <img alt="Zustand" src="https://img.shields.io/badge/Zustand-F06611?style=for-the-badge">
      </td>
    </tr>
    <tr>
      <td>Backend</td>
      <td>
        <img alt="Node.js" src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white">
        <img alt="Express" src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white">
        <img alt="JWT" src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white">
        <img alt="Swagger" src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black">
        <img alt="Nodemailer" src="https://img.shields.io/badge/Nodemailer-0A66C2?style=for-the-badge">
      </td>
    </tr>
    <tr>
      <td>Infrastructure</td>
      <td>
        <img alt="Amazon EC2" src="https://img.shields.io/badge/Amazon_EC2-FF9900?style=for-the-badge&logo=amazon-ec2&logoColor=white">
        <img alt="Amazon S3" src="https://img.shields.io/badge/Amazon_S3-569A31?style=for-the-badge&logo=amazon-s3&logoColor=white">
        <img alt="Nginx" src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white">
        <img alt="Vercel" src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white">
        <img alt="PM2" src="https://img.shields.io/badge/PM2-2B037A?style=for-the-badge">
      </td>
    </tr>
    <tr>
      <td>Database</td>
      <td>
        <img alt="MySQL" src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
      </td>
    </tr>
    <tr>
      <td>DevOps</td>
      <td>
        <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white">
        <img alt="SSH" src="https://img.shields.io/badge/SSH-000000?style=for-the-badge">
      </td>
    </tr>
    <tr>
      <td>External API</td>
      <td>
        <img alt="Kakao Map API" src="https://img.shields.io/badge/Kakao_Map_API-FFCD00?style=for-the-badge&logo=kakao&logoColor=black">
        <img alt="Google SMTP" src="https://img.shields.io/badge/Google_SMTP-EA4335?style=for-the-badge&logo=gmail&logoColor=white">
      </td>
    </tr>
    <tr>
      <td>Collaboration Tools</td>
      <td>
        <img alt="Git" src="https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white">
        <img alt="GitHub" src="https://img.shields.io/badge/GitHub-121011?style=for-the-badge&logo=github&logoColor=white">
        <img alt="Notion" src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white">
        <img alt="Figma" src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white">
        <img alt="Discord" src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white">
      </td>
    </tr>
  </tbody>
</table>


---

## 🛠️ 시스템 아키텍처
<div align="center">
  <img src="./assets/system-architecture.svg" alt="VeriDoc System Architecture" style="border-radius: 10px;"/>
</div>

---

## 👥 팀원 소개

| 이름 | 역할 |
| --- | --- |
| [주니마니정/정준희](https://github.com/jjh-98) | ![PM(Team Lead)](https://img.shields.io/badge/PM(Team%20Lead)-FF5A5F?style=for-the-badge) |
| 리버/임지윤 | ![Designer](https://img.shields.io/badge/Designer-FFC107?style=for-the-badge) |
| [밍/김민지](https://github.com/min-minnn) | ![Frontend Lead](https://img.shields.io/badge/Frontend%20Lead-38BDF8?style=for-the-badge) |
| [블루/강민석](https://github.com/Mallandaine) | ![Frontend](https://img.shields.io/badge/Frontend-38BDF8?style=for-the-badge) |
| [여비/김준엽](https://github.com/junyeop22) | ![Frontend](https://img.shields.io/badge/Frontend-38BDF8?style=for-the-badge) |
| [윤/정윤주](https://github.com/dbswn0) | ![Frontend](https://img.shields.io/badge/Frontend-38BDF8?style=for-the-badge) |
| [토리/이윤재](https://github.com/Yoonjae0923) | ![Backend Lead](https://img.shields.io/badge/Backend%20Lead-22C55E?style=for-the-badge) |
| [진이/차현진](https://github.com/Coconut-lab) | ![Backend](https://img.shields.io/badge/Backend-22C55E?style=for-the-badge) |
| [다니/김다니엘](https://github.com/jagabi816) | ![Backend](https://img.shields.io/badge/Backend-22C55E?style=for-the-badge) |
| [몬트/안상현](https://github.com/ashB1124) | ![Backend](https://img.shields.io/badge/Backend-22C55E?style=for-the-badge) |
| [딤봉/최규찬](https://github.com/DimbongCHOI) | ![Backend](https://img.shields.io/badge/Backend-22C55E?style=for-the-badge) |



