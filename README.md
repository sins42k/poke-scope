# 🧭 PokeScope

**PokeScope**는 [PokeAPI](https://pokeapi.co/)를 기반으로 제작된 반응형 포켓몬 도감 웹사이트입니다.  
검색, 언어 번역, 모달 상세 정보, 테마 전환 등의 기능을 갖추고 있어 직관적이고 편리한 UX를 제공합니다.

---

## 🌐 배포 링크
> [https://sins42k.github.io/poke-scope/](https://sins42k.github.io/poke-scope/)

---

## ⚙️ 주요 기능

| 기능 | 설명 |
|------|------|
| 🔍 **검색 필터링** | 이름 검색, `type:fire`, `#number` 입력 등 다양한 방식으로 포켓몬 필터링 가능 |
| 🌙 **다크/라이트 모드** | 사용자의 선택에 따라 다크/라이트 테마 전환 가능 (로컬 저장됨) |
| 🈺 **다국어 지원** | 영어(🇬🇧), 한국어(🇰🇷), 일본어(🇯🇵), 프랑스어(🇫🇷) 포켓몬 이름 번역 지원 |
| 📄 **모달 상세 정보** | 포켓몬 클릭 시 진화, 능력치, 특성 등 상세 정보 팝업 |
| 📄 **페이지네이션** | 카드 12개씩 페이지네이션 및 탐색 버튼 (`first`, `prev`, `next`, `end`) |
| 🎨 **타입 컬러 반영** | 타입에 따른 색상 배경 및 시각적 태그 제공 |

---

## 🛠️ 기술 스택

- **Frontend**: React JS (Vite), Tailwind CSS
- **API**: [PokeAPI](https://pokeapi.co/)
- **기타**:
  - CSS 다크모드: Tailwind `darkMode: 'class'` 방식
  - 번역: 정적 JSON 기반 다국어 이름 데이터
  - 상태관리: `useState`, `useEffect` 등 React 훅 활용

---

## 📁 프로젝트 구조

```
PokeScope/
├── public/
│   └── assets/
│       └── logo/
├── src/
│   ├── components/
│   │   ├── Header.jsx
│   │   ├── PokemonCard.jsx
│   │   ├── Pagination.jsx
│   │   └── PokemonModal.jsx
│   ├── data/
│   │   └── translations.json
│   ├── pages/
│   │   └── HomePage.jsx
│   ├── utils/
│   │   └── api.js
│   └── index.jsx
└── vite.config.js
```

---

## 🙇 Special Thanks

- [PokeAPI](https://pokeapi.co/) — 방대한 포켓몬 데이터를 제공한 API
- Tailwind CSS — 빠른 디자인 적용을 가능하게 해주는 유틸리티 퍼스트 프레임워크

---

## 📜 라이선스

이 프로젝트는 MIT 라이선스를 따릅니다.
