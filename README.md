<h1 align="center">안녕하세요, 백엔드 개발자 장준영입니다 👋</h1>

<p align="center">
  <a href="https://jangabc3.tistory.com/"><img src="https://img.shields.io/badge/Tistory-FF5544?style=flat-square&logo=tistory&logoColor=white" alt="Tistory" /></a>
</p>

<br />

<p align="center">
  <em>동작하는 코드에도 질문을 던지고, 문제를 해결한 과정과 이유를 기록합니다.<br />
  사용자가 마주할 예외까지 생각하는 백엔드 개발자로 성장 중입니다.</em>
</p>

<br />

## 🛠 Tech Stack

<table>
  <tr><td>Backend</td><td><img alt="Java" src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" /> <img alt="Spring Boot" src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" /> <img alt="Spring Security" src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white" /> <img alt="JPA" src="https://img.shields.io/badge/JPA-59666C?style=flat-square" /> <img alt="Gradle" src="https://img.shields.io/badge/Gradle-02303A?style=flat-square&logo=gradle&logoColor=white" /></td></tr>
  <tr><td>Frontend</td><td><img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" /> <img alt="React" src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=white" /> <img alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" /></td></tr>
  <tr><td>Database</td><td><img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" /> <img alt="Redis/Valkey" src="https://img.shields.io/badge/Redis%2FValkey-DC382D?style=flat-square&logo=redis&logoColor=white" /></td></tr>
  <tr><td>Infra</td><td><img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" /> <img alt="Nginx" src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white" /> <img alt="Linux" src="https://img.shields.io/badge/Linux-333333?style=flat-square&logo=linux&logoColor=white" /></td></tr>
  <tr><td>Tools</td><td><img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" /> <img alt="GitHub" src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" /> <img alt="Git Flow" src="https://img.shields.io/badge/Git%20Flow-F05032?style=flat-square&logo=git&logoColor=white" /> <img alt="Postman" src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white" /> <img alt="Swagger" src="https://img.shields.io/badge/Swagger-228B22?style=flat-square&logo=swagger&logoColor=white" /> <img alt="Notion" src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white" /> <img alt="Figma" src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white" /></td></tr>
</table>

## 💻 Projects

<table>
  <tr>
    <th width="50%">🔗 Linker · 링커</th>
    <th width="50%">🎭 Showmoa · 쇼모아</th>
  </tr>
  <tr>
    <td align="center"><a href="https://linker.newlecture.com/feed"><img src="https://github.com/user-attachments/assets/fbfdb319-2e04-40ab-8e71-ee83eab90139" alt="Linker — GitHub와 연결된 개발자 협업 플랫폼 소개" height="160" /></a></td>
    <td align="center"><a href="https://showmoa.vercel.app/"><img src="https://github.com/user-attachments/assets/e46fbce1-64b0-4b55-9680-fa0c7aa62aa5" alt="SHOW MOA" height="160" /></a></td>
  </tr>
  <tr>
    <td valign="top">
      <b>GitHub 이슈·보드·캘린더를 연결하는 협업 플랫폼</b>
      <ul>
        <li><b>이슈 중복 생성 방지</b><br />요청 식별자로 작업을 구분하고, 부분 실패 시 남은 단계부터 재시도</li>
        <li><b>동기화 실패 시 데이터 보호</b><br />조회 실패와 삭제를 구분하고, 버전 비교로 오래된 응답의 덮어쓰기 방지</li>
      </ul>
      <sub>Java · Spring Boot · PostgreSQL · Next.js</sub><br /><br />
      <a href="https://linker.newlecture.com/feed">서비스 ↗</a> · <a href="https://github.com/likelion-backendschool-9th/Linker">GitHub ↗</a> · <a href="https://jangabc3.tistory.com/216">개발 회고 ↗</a>
    </td>
    <td valign="top">
      <b>전국 공연을 검색하고 관심 공연을 저장하는 서비스</b>
      <ul>
        <li><b>소셜 로그인 장애 해결</b><br />도메인 간 쿠키 전달 문제를 추적하고, PKCE 기반 코드 교환으로 재설계</li>
        <li><b>인증 처리의 동시성 개선</b><br />Valkey의 Lua·GETDEL로 인증 확인·소비 과정의 경쟁 상태 개선</li>
      </ul>
      <sub>Java · Spring Boot · JPA · PostgreSQL</sub><br /><br />
      <a href="https://showmoa.vercel.app/">서비스 ↗</a> · <a href="https://github.com/dawn-guys/showmoa-backend">GitHub ↗</a> · <a href="https://jangabc3.tistory.com/193">개발 회고 ↗</a>
    </td>
  </tr>
</table>
