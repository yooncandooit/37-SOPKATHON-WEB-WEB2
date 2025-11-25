# 🥪 MIDI MATE
: 짧은 점심시간, 언어 한 스푼
MIDI MATE는 매일 주어진 점심 시간을 언어 교류의 기회로 바꿔주는 미스터리 런치 매칭 서비스입니다.
<br />
교류할 언어를 선택하기만 하면, 근처의 새로운 언어 파트너를 자연스럽게 만나게 됩니다.

> 해당 저장소는 **MIDI MATE**의 **프론트엔드 개발**을 담당하는 레포지토리입니다.

<br />

<img width="1440" height="810" alt="0" src="https://github.com/user-attachments/assets/eb55e540-a4ae-4138-9f02-b49dbc11cca2" /> <img width="1440" height="810" alt="1" src="https://github.com/user-attachments/assets/c73f9ee2-ca8b-483d-afa7-4504e210a7a0" /> <img width="1440" height="810" alt="2" src="https://github.com/user-attachments/assets/dd850df5-e82e-463d-b047-912edba04f23" /> <img width="1440" height="810" alt="3" src="https://github.com/user-attachments/assets/957441ba-78a9-482a-980a-afe6fb77e91e" /> <img width="1440" height="810" alt="4" src="https://github.com/user-attachments/assets/d12fd9ba-fb1a-4f6f-ba22-9f5af68dd233" /> <img width="1440" height="810" alt="5" src="https://github.com/user-attachments/assets/032996c2-41f7-4070-a312-45ca7d5f09db" /> <img width="1440" height="810" alt="6" src="https://github.com/user-attachments/assets/1ea20ce7-0033-45de-9654-45da3caf9a85" /> <img width="1440" height="810" alt="7" src="https://github.com/user-attachments/assets/b2f24e23-35c3-45bc-910f-0cdf329ca810" /> <img width="1440" height="810" alt="8" src="https://github.com/user-attachments/assets/4669b692-995a-4229-92f1-edcb977b80df" /> <img width="1440" height="810" alt="9" src="https://github.com/user-attachments/assets/09ad9ebd-bc48-4073-8b6d-00baee2896c3" /> <img width="1440" height="810" alt="10" src="https://github.com/user-attachments/assets/bc2657fa-55d0-4c82-8aed-6beea0c2c6ac" /> <img width="1440" height="810" alt="11" src="https://github.com/user-attachments/assets/10a93a96-c330-43b5-91d2-2f3b745bafb2" /> <img width="1440" height="810" alt="12" src="https://github.com/user-attachments/assets/7f413ea4-65f6-4aa2-98c9-a1bc53f08ab8" /> <img width="1440" height="810" alt="13" src="https://github.com/user-attachments/assets/563adce5-6d31-4812-9501-d4a95d7ff885" /> <img width="1440" height="810" alt="14" src="https://github.com/user-attachments/assets/566bca43-8471-4b0d-8394-d6b502c1f93b" />
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
| **State** | ![Zustand](https://img.shields.io/badge/Zustand-433E38?style=for-the-badge&logoColor=white) |
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

## 📁 폴더 구조

```
├── src
│   ├── apps                      # 앱 초기화 및 진입점
│   ├── constant                  # 전역 상수 (Query Key, API URL)
│   ├── pages                     # 라우트별 페이지 컴포넌트
│   ├── router                    # 라우팅 설정
│   │   └── constant              # 라우트 경로 상수
│   ├── shared                    # 공유 리소스
│   │   ├── apis                  # API 인스턴스 및 함수
│   │   ├── assets                # 이미지, 폰트 등 정적 파일
│   │   ├── components            # 재사용 UI 컴포넌트
│   │   ├── hooks                 # 커스텀 훅
│   │   ├── icons                 # SVG 아이콘 export
│   │   ├── query                 # TanStack Query 설정
│   │   ├── styles                # 전역 스타일 및 테마
│   │   │   └── token             # 디자인 토큰 (color, typography 등)
│   │   ├── types                 # TypeScript 타입 정의
│   │   └── utils                 # 유틸리티 함수
│   └── widgets                   # 페이지 단위 복합 컴포넌트
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

## 📖 아티클 모음

| 이름 | 아티클 |
|:---:|:---|
| 박소현 | |
| 김윤지 | |
| 양승혜 | |
| 박진석 | |

<br />



## ✨ Before & After

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

