# 📝 Narratix

<div align="center">

**취준생의 경험을 아카이빙하고, 자기소개서를 빠르게 완성하는 플랫폼**

**현대자동차 소프티어 부트캠프 7기 - Team 7. Jackpot**

</div>

---

## 🎯 프로젝트 소개

> **Narratix는 취준생들이 흩어진 경험을 모으고, 자기소개서를 효율적으로 작성/관리할 수 있도록 돕는 플랫폼입니다.**

### 해결하고자 한 문제

- 자소서 초안, 문항, 경험 메모가 여러 곳에 흩어져 재활용이 어렵다
- 지원 일정과 작성 진행도를 함께 관리하기 어렵다
- 첨삭 과정이 메시지/문서로 분산되어 피드백 반영이 비효율적이다

### 핵심 가치

- `경험 아카이빙`: 업로드한 자료를 구조화해 기업/문항 단위로 재활용
- `작성 생산성`: 문항 중심 편집 + 검색/필터로 빠른 작성 흐름 지원
- `피드백 루프`: 공유 기반 첨삭으로 수정 사이클 단축

<img 
  src="https://github.com/user-attachments/assets/1c7ebf79-c4d1-4145-9328-1e58e5c5bfe8"
  alt="Landing Page" 
  width="100%" 
/>

---

## 🧭 사용자 플로우

1. **[나의 채용공고] 공고 등록 또는 [자료 업로드] PDF 업로드로 자기소개서 생성**
   - 텍스트로 공고 정보와 문항 직접 작성
   - PDF 업로드 시 AI가 자동 파싱 후 라이브러리에 저장

2. **[라이브러리] 에서 자료 탐색 및 스크랩**
   - 기업별/문항별로 아카이빙된 자료 열람
   - 재활용할 내용 스크랩

3. **[자기소개서] 에서 문항별 초안 작성 / 수정**
   - 사이드바에서 스크랩하거나 아카이빙된 자료를 참고하며 작성

4. **[자기소개서] 공유 링크 기반 실시간 첨삭 진행**

5. **[나의 채용공고] 채용 캘린더로 지원 일정 관리**

---

## 📸 핵심 기능 시연

### 1) 자료 업로드 + AI 라벨링

<img 
  src="https://github.com/user-attachments/assets/b89e39b2-7aeb-423d-a0c6-849a476570c5"
  alt="Upload Page" 
  width="100%" 
/>

<img 
  src="https://github.com/user-attachments/assets/6fb535cb-c863-4d91-aa34-6ad22ac7470c"
  alt="Labeling Page" 
  width="100%" 
/>

### 2) 채용 일정 캘린더 관리

<img 
  src="https://github.com/user-attachments/assets/5a6a2808-2373-4940-8109-88292da17da3"
  alt="Calendar Page" 
  width="100%" 
/>

### 3) 기업별/문항별 라이브러리 관리

<img 
  src="https://github.com/user-attachments/assets/450c5d0b-44a9-4c23-b322-fb5e925b67fe"
  alt="Library Page" 
  width="100%" 
/>

### 4) 자기소개서 작성

<img 
  src="https://github.com/user-attachments/assets/9b083350-6967-4884-a3fa-848d1ac9eb43"
  alt="Editor Page" 
  width="100%" 
/>

### 5) 첨삭 에디터

> 작성자

<img 
  src="https://github.com/user-attachments/assets/e95e5489-5a80-4aa4-8f19-b9f4b10702be"
  alt="Review Page" 
  width="100%" 
/>
<img 
  src="https://github.com/user-attachments/assets/0f26f1b0-b3f7-46df-90f4-1312e33be278"
  alt="Review Page" 
  width="100%" 
/>

> 첨삭자

<img 
  src="https://github.com/user-attachments/assets/8c5509fb-dbc6-42e6-8de8-2081fe38d53a"
  alt="Review Page" 
  width="100%" 
/>
<img 
  src="https://github.com/user-attachments/assets/2a02447f-b975-407e-a59d-4a7a1a55b341"
  alt="Review Page" 
  width="100%" 
/>

### 전체 기능

- `홈 대시보드`: 작성 통계, 시즌 지원 현황, 임박 일정 확인
- `채용공고 관리`: 캘린더 기반 공고 등록/수정/삭제
- `자료 업로드`: 자기소개서 파일 업로드 후 AI 라벨링 및 저장
- `자기소개서 작성`: 문항 단위 작성, 검색/필터 기반 문서 탐색
- `친구 첨삭`: 공유된 자기소개서 코멘트 작성 및 반영
- `라이브러리`: 기업별/문항별 아카이빙, 스크랩 기반 재활용
- `인증`: 로그인/회원가입 및 보호 라우팅

---

## 🏗 아키텍처 & ERD

### 아키텍처

<img width="5376" height="4176" alt="image" src="https://github.com/user-attachments/assets/e5f0c462-1cba-4735-9cf2-74e2d111cf87" />
<a href="https://www.figma.com/board/WljtFzBLbDfAIAGrQK1p6K/Narratix-Architecture?node-id=21-708&t=8TZda2mGHoarFAGr-0">아키텍처 링크</a>

### ERD

<img width="1940" height="1092" alt="image" src="https://github.com/user-attachments/assets/b2652c7b-f1fb-460d-ac9c-2247836d2d20" />

<a href="https://www.erdcloud.com/d/6JAu9hkvgYjehSFBJ">ERD 링크</a>

---

## 🛠 기술 스택

### Frontend

<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=React&logoColor=black"/> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=TypeScript&logoColor=white"/> <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=Vite&logoColor=white"/> <img src="https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat-square&logo=TailwindCSS&logoColor=white"/>
<br>
<img src="https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=ReactQuery&logoColor=white"/> <img src="https://img.shields.io/badge/React_Router-CA4245?style=flat-square&logo=ReactRouter&logoColor=white"/>
<br>
<img src="https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white"/> <img src="https://img.shields.io/badge/ESLint-4B32C3?style=flat-square&logo=ESLint&logoColor=white"/> <img src="https://img.shields.io/badge/Prettier-F7B93E?style=flat-square&logo=Prettier&logoColor=white"/>

### Backend

<img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=Java&logoColor=white"/> <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=SpringBoot&logoColor=white"/> <img src="https://img.shields.io/badge/Spring_Data_JPA-6DB33F?style=flat-square&logo=Spring&logoColor=white"/> <img src="https://img.shields.io/badge/QueryDSL-007396?style=flat-square&logo=Java&logoColor=white"/>
<br>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=MySQL&logoColor=white"/> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=Redis&logoColor=white"/>
<br>
<img src="https://img.shields.io/badge/AWS_EC2-FF9900?style=flat-square&logo=AmazonEC2&logoColor=white"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=Docker&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=GitHubActions&logoColor=white"/>

---

## 👥 팀 구성

<div align="center">
  <table>
    <tr valign="top">
      <td>
        <table align="center">
          <thead>
            <tr><th style="text-align: center;" colspan="2">🛠️ Backend</th></tr>
          </thead>
          <tbody>
            <tr>
              <td align="center" width="200">
                <a href="https://github.com/kseysh">
                  <img src="https://github.com/kseysh.png" alt="김승환" width="120" style="border-radius: 50%;" />
                  <br />
                  <sub><b>김승환</b></sub>
                </a>
              </td>
              <td align="center" width="200">
                <a href="https://github.com/livebylee">
                  <img src="https://github.com/user-attachments/assets/6ebadb75-050a-4719-ba5e-507e233c3e8b" alt="이정민" width="120" style="border-radius: 50%;" />
                  <br />
                  <sub><b>이정민</b></sub>
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </td>
      <td>
        <table align="center">
          <thead>
            <tr><th style="text-align: center;" colspan="3">💻 Frontend</th></tr>
          </thead>
          <tbody>
            <tr>
              <td align="center" width="200">
                <a href="https://github.com/using2">
                  <img src="https://github.com/user-attachments/assets/8c03c0d6-9ecc-423f-8126-74c2c2e81ec0" alt="강유진" width="120" style="border-radius: 50%;" />
                  <br />
                  <sub><b>강유진</b></sub>
                </a>
              </td>
              <td align="center" width="200">
                <a href="https://github.com/Sminp">
                  <img src="https://github.com/user-attachments/assets/9bc78a33-e446-442f-a40a-71b07d6cfada" alt="박소민" width="120" style="border-radius: 50%;" />
                  <br />
                  <sub><b>박소민</b></sub>
                </a>
              </td>
              <td align="center" width="200">
                <a href="https://github.com/hi224">
                  <img src="https://github.com/user-attachments/assets/76d2ad57-3d3e-443b-a68c-88b939bb62b7" alt="윤종근" width="120" style="border-radius: 50%;" />
                  <br />
                  <sub><b>윤종근</b></sub>
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </td>
    </tr>
  </table>
</div>

---

## 🧑‍💻 역할 및 주요 기여

| 이름   | 포지션          | 담당 도메인                                                                           |
| ------ | --------------- | ------------------------------------------------------------------------------------- |
| 강유진 | Frontend        | 실시간 텍스트 에디터 / 협업 첨삭 UI                                                   |
| 박소민 | Frontend        | 라이브러리(기업·문항) / 나의 채용공고(캘린더) / 자기소개서 작성 (랜딩 페이지 및 검색) |
| 윤종근 | Frontend        | 실시간 첨삭, 실시간 알림, 자료 업로드                                                 |
| 김승환 | Backend & Infra | WebSocket 실시간 첨삭, SSE 알림, 자기소개서, 첨삭 링크 관리                           |
| 이정민 | Backend & Infra | 자료 업로드, 라이브러리, 검색 , aws 인프라 구축                                       |

---

### 김승환 (Backend & Infra)

- **비동기 이벤트 기반 아키텍처 구현**: 자기소개서 PDF 업로드 및 AI 라벨링의 비동기 처리 과정에서 발생할 수 있는 상태 유실 문제를 해결하기 위해 비동기 이벤트 기반 아키텍처 구축
- **WebSocket/STOMP 기반 실시간 자소서 첨삭 기능 구현**: WebSocket과 STOMP를 사용해 작성자(Writer)와 첨삭자(Reviewer) 간 실시간 자소서 첨삭 기능 구현
- **Operational Transformation 알고리즘을 사용한 중앙 집중 동시 편집 기능 구현**: 자기소개서 작성자(Writer)와 첨삭자(Reviewer)가 자기소개서 동시 편집 시 충돌 없이 일관된 상태를 유지하도록 Operational Transformation 알고리즘을 도입하여 모든 사용자가 동일한 결과를 보도록 구현
- **Write Back 패턴을 사용하여 실시간 저장 로직 최적화**: 매 텍스트 변경마다 DB IO를 발생시키지 않고, Redis에 Delta(변경분)를 임시 저장하고, 임계값 도달 시 DB에 Delta를 Flush하는 Write Back 캐싱 전략 구현
- **Redis 분산 락을 이용한 웹소켓 접속 유저 제한 정책 구현**: 하나의 첨삭 링크에 Writer와 Reviewer 각 1명만 동시 접속이 가능하도록 Redis 분산 락 기반 제한 정책 구현, Lock의 TTL을 30초로 설정하여 비정상 종료 시에도 락이 자동 해제되도록 구현, Lock 갱신 로직에서 Pipeline과 Lua Script를 조합해 단일 네트워크 IO로 모든 세션의 Lock TTL을 10초마다 갱신하도록 구현
- **SSE 기반 알림 발송 로직 구축**: Server-Sent Events를 활용하여 서버에서 클라이언트로 단방향 실시간 알림을 전송하는 시스템 구현

## 🚀 기술적 도전

### Backend

- [[김승환] - 비동기 이벤트 아키텍처 개선기](https://velog.io/@kseysh/%EB%B9%84%EB%8F%99%EA%B8%B0-%EC%9D%B4%EB%B2%A4%ED%8A%B8-%EC%95%84%ED%82%A4%ED%85%8D%EC%B2%98-%EA%B0%9C%EC%84%A0%EA%B8%B0)
- [[김승환] ‐ WebSocket vs. SSE ](https://velog.io/@kseysh/Websocket-vs.-SSE)
- [[김승환] ‐ 실시간 첨삭 기능, 어떻게 구현할 것인가? (데이터 구조부터 OT 알고리즘까지)](https://velog.io/@kseysh/%EC%8B%A4%EC%8B%9C%EA%B0%84-%EC%B2%A8%EC%82%AD-%EA%B8%B0%EB%8A%A5-%EC%96%B4%EB%96%BB%EA%B2%8C-%EA%B5%AC%ED%98%84%ED%95%A0-%EA%B2%83%EC%9D%B8%EA%B0%80-%EB%8D%B0%EC%9D%B4%ED%84%B0-%EA%B5%AC%EC%A1%B0%EB%B6%80%ED%84%B0-OT-%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98%EA%B9%8C%EC%A7%80-100t99wu)
- [[김승환] ‐ 동시 편집(OT) 알고리즘 구현 중 만난 버전 충돌 개선기](https://velog.io/@kseysh/%EB%8F%99%EC%8B%9C-%ED%8E%B8%EC%A7%91OT-%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98-%EA%B5%AC%ED%98%84-%EC%A4%91-%EB%A7%8C%EB%82%9C-%EB%B2%84%EC%A0%84-%EC%B6%A9%EB%8F%8C-%EA%B0%9C%EC%84%A0%EA%B8%B0-u8jxlmw6)
- [[김승환] ‐ 트랜잭션 경계 재설계와 낙관적 락을 통한 리뷰 생성 로직 개선](https://velog.io/@kseysh/%ED%8A%B8%EB%9E%9C%EC%9E%AD%EC%85%98-%EA%B2%BD%EA%B3%84-%EC%9E%AC%EC%84%A4%EA%B3%84%EC%99%80-%EB%82%99%EA%B4%80%EC%A0%81-%EB%9D%BD%EC%9D%84-%ED%86%B5%ED%95%9C-%EB%A6%AC%EB%B7%B0-%EC%83%9D%EC%84%B1-%EB%A1%9C%EC%A7%81-%EA%B0%9C%EC%84%A0)
- [[김승환] - 웹소켓 다중 서버 환경에서 Redis 분산락과 Pipelining으로 단일 접속 제어하기](https://velog.io/@kseysh/%EC%9B%B9%EC%86%8C%EC%BC%93-%EB%8B%A4%EC%A4%91-%EC%84%9C%EB%B2%84-%ED%99%98%EA%B2%BD%EC%97%90%EC%84%9C-Redis-%EB%B6%84%EC%82%B0%EB%9D%BD%EA%B3%BC-Pipelining%EC%9C%BC%EB%A1%9C-%EB%8B%A8%EC%9D%BC-%EC%A0%91%EC%86%8D-%EC%A0%9C%EC%96%B4%ED%95%98%EA%B8%B0)
- [[김승환] - WebSocket과 달리, SSE에서는 onCompletion이 왜 바로 호출되지 않았을까?](https://velog.io/@kseysh/WebSocket%EA%B3%BC-%EB%8B%AC%EB%A6%AC-SSE%EC%97%90%EC%84%9C%EB%8A%94-onCompletion%EC%9D%B4-%EC%99%9C-%EB%B0%94%EB%A1%9C-%ED%98%B8%EC%B6%9C%EB%90%98%EC%A7%80-%EC%95%8A%EC%95%98%EC%9D%84%EA%B9%8C)
