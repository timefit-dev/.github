<div align="center">

  # ⏰ TimeFit

  ### 약속 시간, 이제 쉽게 정하세요

  *여러 명의 일정을 한눈에 비교하고, 모두가 가능한 시간을 찾아주는 스마트 스케줄링 솔루션*

  <br/>

  [![GitHub Stars](https://img.shields.io/github/stars/timefit-dev?style=social)](https://github.com/timefit-dev)
  [![GitHub Issues](https://img.shields.io/github/issues/timefit-dev/timefit-server)](https://github.com/timefit-dev/timefit-server/issues)
  [![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

  [Features](#-features) • [Tech Stack](#-tech-stack) • [Repositories](#-repositories) • [Team](#-team) • [Convention](#-convention)

  </div>

  ---

  ## ✨ Features

  🎯 **스마트 매칭** - 참여자들의 가능 시간을 자동으로 분석
  📅 **직관적인 UI** - 한눈에 보이는 시간표 인터페이스
  🔔 **실시간 알림** - 약속 확정 시 즉시 알림
  🌐 **크로스 플랫폼** - 모바일과 웹에서 자유롭게

  ## 🏗 Tech Stack

  ### Backend
  ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.5.6-6DB33F?style=flat-square&logo=springboot&logoColor=white)
  ![Java](https://img.shields.io/badge/Java-17-007396?style=flat-square&logo=java&logoColor=white)
  ![Gradle](https://img.shields.io/badge/Gradle-8.14-02303A?style=flat-square&logo=gradle&logoColor=white)

  ### Frontend
  ![TBD](https://img.shields.io/badge/Coming-Soon-gray?style=flat-square)

  ## 📦 Repositories

  | Repository | Description | Status |
  |------------|-------------|--------|
  | [📡 timefit-server](https://github.com/timefit-dev/timefit-server) | Spring Boot 기반 REST API서버 | 🚧 In Progress |
  | 📱 timefit-app | 크로스 플랫폼 모바일 앱 | 📅 Planned |

  ## 👥 Team

  <table>
    <tr>
      <td align="center"><b>Frontend</b></td>
      <td>크로스플랫폼 개발 2명</td>
    </tr>
    <tr>
      <td align="center"><b>Backend</b></td>
      <td>서버 & API 개발 3명</td>
    </tr>
  </table>

  ## 📋 Convention

  ### 📝 Commit Message Format

  ():

  Types

  | Type        | Description  |
  |-------------|--------------|
  | ✨ feat      | 새로운 기능 추가    |
  | 🐛 fix      | 버그 수정        |
  | 📝 docs     | 문서 수정        |
  | ♻️ refactor | 코드 리팩토링      |
  | ✅ test      | 테스트 코드       |
  | 🔧 chore    | 빌드, 설정 파일 수정 |
  | 💄 style    | 코드 포맷팅       |
  | ⚡️ perf     | 성능 개선        |

  🌿 Branch Strategy
```
  main
    └── develop
         ├── feature/기능명
         ├── fix/버그명
         └── refactor/리팩토링명
```

  | Branch     | Purpose     |
  |------------|-------------|
  | main       | 프로덕션 배포 브랜치 |
  | develop    | 개발 통합 브랜치   |
  | feature/*  | 새로운 기능 개발   |
  | fix/*      | 버그 수정       |
  | refactor/* | 코드 리팩토링     |

  📌 Code Review

  - PR 최소 1명 이상 approve 필요
  - 모든 CI 테스트 통과 필수
  - 코드 컨벤션 준수 확인

  ---
  💬 Contact

  프로젝트에 대한 문의사항은 https://github.com/timefit-dev/timefit-server/issues 를 활용해주세요

  Made with ❤️ by TimeFit Team
