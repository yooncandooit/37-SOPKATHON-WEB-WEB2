# 🥪 MIDI MATE
: 짧은 점심시간, 언어 한 스푼
MIDI MATE는 매일 주어진 점심 시간을 언어 교류의 기회로 바꿔주는 미스터리 런치 매칭 서비스입니다.
<br />
교류할 언어를 선택하기만 하면, 근처의 새로운 언어 파트너를 자연스럽게 만나게 됩니다.

> 해당 저장소는 **MIDI MATE**의 **프론트엔드 개발**을 담당하는 레포지토리입니다.

<br />
<img width="2880" height="1620" alt="0" src="https://github.com/user-attachments/assets/21191826-acb8-4f6d-a9e7-e1ab351326e3" />
<img width="2880" height="1620" alt="1" src="https://github.com/user-attachments/assets/3a636946-2921-4deb-8525-c26da2a77979" />
<img width="2880" height="1620" alt="2" src="https://github.com/user-attachments/assets/b23cc613-a094-4751-a0cc-239d4f09c5c5" />
<img width="2880" height="1620" alt="3" src="https://github.com/user-attachments/assets/43e7a8bf-1c8d-4329-af61-ecfe912f8767" />
<img width="2880" height="1620" alt="4" src="https://github.com/user-attachments/assets/e9bb01a5-5baa-4407-a871-0c0318976eb2" />
<img width="2880" height="1620" alt="5" src="https://github.com/user-attachments/assets/6f96b912-29e8-4125-bdb3-86b867813b58" />
<img width="2880" height="1620" alt="6" src="https://github.com/user-attachments/assets/01a9e9a9-761b-4b72-9ca7-02190e4032d5" />
<img width="2880" height="1620" alt="7" src="https://github.com/user-attachments/assets/da95be63-e1c5-4017-bf30-0742e724c6c0" />
<img width="2880" height="1620" alt="8" src="https://github.com/user-attachments/assets/f31d980c-2fdb-4260-ae1f-9b085450442b" />
<img width="2880" height="1620" alt="9" src="https://github.com/user-attachments/assets/e4f7a4eb-9875-45f0-bca5-eb708f36f913" />
<img width="2880" height="1620" alt="10" src="https://github.com/user-attachments/assets/139ec25f-4db7-4335-a61f-0f212cfb41c0" />
<img width="2880" height="1620" alt="11" src="https://github.com/user-attachments/assets/0a1d6e2b-2708-49b3-96e1-0eb3b0bc0294" />
<img width="2880" height="1620" alt="12" src="https://github.com/user-attachments/assets/7495e366-e5c0-4ef8-b5c1-ff89ebbec068" />
<img width="2880" height="1620" alt="13" src="https://github.com/user-attachments/assets/5576c551-3e62-480f-8307-4c7b14e3c5bd" />
<img width="2880" height="1620" alt="14" src="https://github.com/user-attachments/assets/9eaeb92e-ee9b-4889-a89c-ba5470855b00" />


## ❗️ 주요 기능
> **1. 맞춤형 정보 입력**
> - 언어 :구사 가능 언어 / 학습 희망 언어 교차 선택
> - 시간 : 희망하는 시간(30분 단위) 범위 지정
> - 지역 : 선호 지역 선택

> **2. 하이브리드 매칭 시스템 : 대기열 내 조건이 일치하는 유저 간 실시간 매칭 시도**
> - 대기 시간(Timeout) 초과 시 매칭 정보 저장으로 유도

> **3. 인터랙티브 UI : 매칭 성공 시, 직관적인 결과 화면 제공**
> - 매칭 시간 및 장소 : 매칭 시간 및 장소 제안으로 유저의 고민 제거
> - conversation Card : 처음 만났을 때의 어색함 해소를 위해 다국어 질문 카드제공( Animation을 활용한 카드 뒤집기 효과)

> **4. 리뷰 : 복잡한 텍스트 리뷰 대신 Like/Dislike 및 키워드 선택 방식의  간편 평가 시스템**
> - Dislike 선택 시 재매칭 되지 않음
</div>

---

## 📦 기술 스택

| 역할 | 종류 |
|:---:|:---|
| **Library** | ![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=white) ![VITE](https://img.shields.io/badge/VITE-646CFF?style=for-the-badge&logo=Vite&logoColor=white) |
| **Language** | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=TypeScript&logoColor=white) |
| **Styling** | ![Vanilla Extract](https://img.shields.io/badge/Vanilla%20Extract-DB7093?style=for-the-badge&logoColor=white) |
| **Data Fetching** | ![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=Axios&logoColor=white) ![TanStack Query](https://img.shields.io/badge/TanStack%20Query-FF4154?style=for-the-badge&logo=react-query&logoColor=white) |
| **Formatting** | ![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white) ![Prettier](https://img.shields.io/badge/Prettier-F7B93E?style=for-the-badge&logo=prettier&logoColor=white) |
| **Package** | ![pnpm](https://img.shields.io/badge/pnpm-F69220?style=for-the-badge&logo=pnpm&logoColor=white) |
| **Deploy** | ![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=Vercel&logoColor=white) |

<br />

---

## 🚀 시작하기

```bash
# 의존성 설치
pnpm install

# 개발 서버 실행
pnpm dev
```

<br />

---

## 🌿 Git 워크플로우

### 1. develop 브랜치 최신화
```bash
git checkout develop
git pull origin develop
```

### 2. 작업 브랜치 생성
```bash
git checkout -b feat/작업명
```

### 3. PR 전 병합
```bash
git checkout develop
git pull origin develop
git checkout feat/작업명
git merge develop
# 충돌 해결 후 커밋
```

<br />

---

## 📏 컨벤션

| 📌 | 링크 |
|:---:|:---|
| 🌿 Style | [Style Convention](https://peach-shadow-378.notion.site/2b2d94ad82bb80fca793d32a80d43210?source=copy_link) |
| 🪵 Coding | [Coding Convention](https://peach-shadow-378.notion.site/2b2d94ad82bb804ebc00eb8c7687919d?source=copy_link) |
| 📋 Issue | [Issue Convention](https://peach-shadow-378.notion.site/ISSUE-2b3d94ad82bb808faff3dbad8cae874c?source=copy_link) |
| ✅ PR & Branch | [PR&Branch Convention](https://peach-shadow-378.notion.site/PR-2b2d94ad82bb8090b890d4789b4755af?source=copy_link) |
| 🫧 Commit | [Commit Convention](https://peach-shadow-378.notion.site/2b2d94ad82bb80d2a414e3ff78cf2ea3?source=copy_link) |


<br />

---

## 📁 FSD 폴더 구조

```
├── package-lock.json             # 종속성(Dependency)의 정확한 버전 명세 파일
├── package.json                  # 프로젝트의 메타데이터, 스크립트, 설치된 패키지 목록 정의
├── pnpm-lock.yaml                # pnpm 패키지 매니저의 종속성 잠금 파일
├── public                        # 💡 웹 서버에 의해 직접 제공되는 정적 파일 (빌드되지 않음)
│   └── logo.svg                  # 웹사이트 로고 등의 정적 이미지 파일
├── src                           # 💡 애플리케이션의 모든 소스 코드
│   ├── apps                      # 애플리케이션의 핵심 진입점 및 루트 컴포넌트
│   │   ├── App.tsx               # 애플리케이션의 최상위 컴포넌트
│   │   └── main.tsx              # React 애플리케이션의 렌더링 시작점 (root)
│   ├── constant                  # 전역적으로 사용되는 상수 값들
│   │   ├── query-key.ts          # 데이터 쿼리 라이브러리 (React Query 등)의 키 정의
│   │   └── url.ts                # API 엔드포인트 또는 라우트 경로 상수 정의
│   ├── features                  # 💡 특정 도메인(기능)의 비즈니스 로직 (주로 Custom Hooks)
│   │   ├── matching              # 매칭 기능 관련 로직
│   │   │   └── hooks             # 매칭 관련 상태 관리 및 비즈니스 로직을 담은 훅
│   │   │       └── use-matching-info.ts
│   │   └── onboarding            # 온보딩 기능 관련 로직
│   │       └── hooks             # 온보딩 관련 상태 관리 및 비즈니스 로직을 담은 훅
│   │           └── use-onboarding.ts
│   ├── pages                     # 💡 라우팅되는 화면 단위의 컴포넌트
│   │   ├── home.tsx              # 메인/홈 페이지
│   │   ├── matching-complete     # 매칭 완료 페이지 폴더
│   │   │   ├── matching-complete.css.ts # 스타일 파일
│   │   │   └── matching-complete.tsx    # 컴포넌트 파일
│   │   ├── matching-page         # 매칭 진행 페이지 폴더
│   │   │   ├── matching-page.css.ts
│   │   │   └── matching-page.tsx
│   │   ├── matching-progress     # 매칭 로딩/진행 상태 페이지 폴더
│   │   │   ├── matching-progress.css.ts
│   │   │   └── matching-progress.tsx
│   │   ├── on-boarding           # 온보딩 페이지 폴더
│   │   │   ├── on-boarding.css.ts
│   │   │   └── on-boarding.tsx
│   │   └── review-page           # 리뷰 페이지 폴더
│   │       ├── index.ts          # 페이지 진입점 및 내보내기 (export)
│   │       ├── review-page.css.ts
│   │       └── review-page.tsx
│   ├── router                    # 애플리케이션 라우팅 시스템 구성
│   │   ├── constant              # 라우터 관련 상수 (경로, AppBar 설정 등)
│   │   │   ├── app-bar-config.ts # 상단바(AppBar) 관련 설정
│   │   │   └── routes.ts         # 모든 라우트 경로 정의
│   │   ├── global-routes.tsx     # 전역 라우트 설정 컴포넌트
│   │   ├── layout.tsx            # 공통 레이아웃 (header, footer 등) 정의
│   │   ├── lazy.tsx              # 동적 임포트(Lazy Loading) 헬퍼
│   │   └── router.tsx            # 라우터 인스턴스 생성 및 설정
│   ├── shared                    # 💡 애플리케이션 전체에서 공유되는 요소 (재사용성)
│   │   ├── apis                  # 백엔드 API 통신 로직
│   │   │   ├── instance.ts       # Axios 등 HTTP 클라이언트 인스턴스 설정
│   │   │   ├── matching          # 매칭 관련 API 호출 함수
│   │   │   │   └── matching.ts
│   │   │   ├── method.ts         # API 요청 메소드 정의 (GET, POST 등)
│   │   │   ├── onboarding        # 온보딩 관련 API 호출 함수
│   │   │   │   └── onboarding.ts
│   │   │   └── questions.ts      # 질문 관련 API
│   │   ├── assets                # 정적 자산 (아이콘, 이미지)
│   │   │   ├── icons             # SVG 등 아이콘 파일
│   │   │   │   └── ...
│   │   │   └── images            # PNG, JPG 등 일반 이미지 파일
│   │   │       └── ...
│   │   ├── components            # 💡 재사용 가능한 **기본 단위** UI 컴포넌트 (Design System 요소)
│   │   │   ├── app-bar           # 상단바 (AppBar) 컴포넌트
│   │   │   │   └── ...
│   │   │   ├── button            # 버튼 컴포넌트
│   │   │   │   └── ...
│   │   │   ├── flip-card         # 플립 카드 컴포넌트
│   │   │   │   └── ...
│   │   │   └── modal             # 모달 컴포넌트
│   │   │       └── ...
│   │   ├── hooks                 # 범용적인 커스텀 훅 (현재 비어있으나, 공통 훅 위치)
│   │   ├── icons                 # (현재 비어있음) 아이콘 관련 로직 또는 컴포넌트 위치 가능
│   │   ├── query                 # 데이터 쿼리 관련 설정 및 프로바이더
│   │   │   └── query-provider.tsx # React Query Provider 등
│   │   ├── styles                # 전역 스타일 및 테마 시스템
│   │   │   ├── global.css.ts     # 전역 CSS 스타일
│   │   │   ├── reset.css.ts      # CSS 초기화 스타일
│   │   │   ├── theme-provider.tsx# 테마 적용 Provider
│   │   │   ├── theme.css.ts      # 테마 설정
│   │   │   └── token             # 디자인 토큰 (Design Tokens) 정의
│   │   │       ├── color.css.ts  # 색상 토큰
│   │   │       └── ...
│   │   ├── types                 # 전역적으로 사용되는 TypeScript 타입 정의
│   │   │   └── api.ts            # API 데이터 구조 타입
│   │   └── utils                 # 범용적인 헬퍼(Helper) 함수
│   │       └── language.ts       # 언어 처리 유틸리티
│   ├── vite-env.d.ts             # Vite 환경 변수 타입 정의
│   ├── vite-env.override.d.ts    # 환경 변수 재정의 타입 정의
│   └── widgets                   # 💡 여러 컴포넌트를 조합한 복합적인 UI (Feature-specific)
│       ├── matching-form         # 매칭 설정을 위한 폼 위젯
│       │   ├── constants         # 폼 내부에서 사용되는 상수
│       │   │   └── option.ts
│       │   └── ...
│       └── review-form           # 리뷰 작성을 위한 폼 위젯
│           └── ...
├── tsconfig.app.json             # 앱 관련 TypeScript 설정
├── tsconfig.json                 # 기본 TypeScript 설정
├── tsconfig.node.json            # Node 환경(빌드 설정 등) TypeScript 설정
└── vite.config.ts                # Vite 번들러의 설정 파일
```

<br />

---

## 👥 팀원 소개

<table align="center">
  <tr>
    <td align="center">
      <img src="https://github.com/Sohyunnnn.png" width="130" height="130" style="border-radius: 50%;" /><br />
      <b>박소현</b><br />
      <a href="https://github.com/Sohyunnnn">@Sohyunnnn</a><br />
      <sub>프론트엔드 팀장</sub>
    </td>
    <td align="center">
      <img src="https://github.com/yooncandooit.png" width="130" height="130" style="border-radius: 50%;" /><br />
      <b>김윤지</b><br />
      <a href="https://github.com/yooncandooit">@yooncandooit</a><br />
      <sub>프론트엔드 팀원</sub>
    </td>
    <td align="center">
      <img src="https://github.com/seunghye-rain.png" width="130" height="130" style="border-radius: 50%;" /><br />
      <b>양승혜</b><br />
      <a href="https://github.com/seunghye-rain">@seunghye-rain</a><br />
      <sub>프론트엔드 팀원</sub>
    </td>
    <td align="center">
      <img src="https://github.com/jin-evergreen.png" width="130" height="130" style="border-radius: 50%;" /><br />
      <b>박진석</b><br />
      <a href="https://github.com/jin-evergreen">@jin-evergreen</a><br />
      <sub>프론트엔드 팀원</sub>
    </td>
  </tr>
</table>

<br />

## 💝 우리 팀의 그라운드 룰
> - 몰라도 부끄러워 하지 않기
> - 질문 환영
> - 클린코드 !!
> - 해커톤이라고 조급해하지 않기
> - MVP를 기반으로 만들기
> - 소통 !!!
> - 열정 !!
---

## ✨ 웹계인 Before & After

<table>
  <tr>
    <th>Before</th>
    <th>After</th>
  </tr>
  <tr>
    <td>
      <img width="450" alt="before" src="https://github.com/user-attachments/assets/0a57b71d-7234-429e-b9a7-ad3746d576b6" />
    </td>
    <td>
      <img width="450" alt="after" src="https://github.com/user-attachments/assets/c1170129-2496-4020-afd8-c99c242dec55" />
    </td>
  </tr>
</table>

