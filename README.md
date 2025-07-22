# KakaoTalk Clone 2025

카카오톡 로그인 페이지를 클론한 프로젝트입니다.

## 📱 프로젝트 개요

- **목적**: 카카오톡 UI/UX 학습 및 CSS 실습
- **기술 스택**: HTML5, CSS3, FontAwesome
- **학습 내용**: BEM 방법론, CSS 변수, 반응형 디자인

## 🎨 주요 기능

### 상태바 (Status Bar)
- 모바일 상태바 UI 구현
- 배터리, 시간, 신호 표시
- FontAwesome 아이콘 활용

### 로그인 폼 (Login Form)
- 이메일/전화번호 입력
- 비밀번호 입력
- 포커스 시 노란색 underline 효과
- 호버 효과가 있는 로그인 버튼

### 반응형 디자인
- 모바일 우선 디자인
- 768px 이하에서 최적화된 레이아웃

## 📁 파일 구조

```
kokoa-clone-2025/
├── index.html              # 메인 HTML 파일
├── CSS/
│   ├── reset.css           # CSS 초기화
│   ├── variables.css       # CSS 변수 정의
│   ├── status-bar.css      # 상태바 스타일
│   ├── welcome-header.css  # 환영 헤더 스타일
│   ├── login-form.css      # 로그인 폼 스타일
│   └── styles.css          # 메인 스타일 파일
├── screenshots/            # 참고 이미지들
└── README.md              # 프로젝트 문서
```

## 🎯 학습 포인트

### BEM 방법론
- Block: `.status-bar`, `.welcome-header`
- Element: `.status-bar__column`, `.welcome-header__title`
- Modifier: `.fa-battery-quarter--low`

### CSS 변수 활용
```css
:root {
    --yellow: #fee500;      /* 카카오톡 노란색 */
    --gray: #666666;        /* 회색 */
    --black: #000000;       /* 검정색 */
}
```

### 시맨틱 HTML
- `<header>` 태그 활용
- 의미있는 HTML 구조

## 🚀 실행 방법

1. 프로젝트 클론
```bash
git clone [repository-url]
cd kokoa-clone-2025
```

2. 브라우저에서 열기
```bash
open index.html
```

## 📱 반응형 지원

- **데스크톱**: 768px 이상
- **모바일**: 768px 이하
- **태블릿**: 768px ~ 1024px

## 🎨 디자인 시스템

### 색상 팔레트
- Primary: `#fee500` (카카오톡 노란색)
- Text: `#000000` (검정색)
- Background: `#ffffff` (흰색)
- Border: `rgba(0, 0, 0, 0.2)` (투명 회색)

### 타이포그래피
- Font: "Open Sans"
- Weight: 400 (Regular), 600 (Semi-bold)

## 📝 개발 노트

### CSS 구조
- **Reset CSS**: 브라우저 기본값 초기화
- **Variables**: 전역 CSS 변수 관리
- **Component**: 각 UI 컴포넌트별 파일 분리
- **Main**: 전체 스타일 통합

### 접근성 고려사항
- 시맨틱 HTML 태그 사용
- 적절한 색상 대비
- 키보드 네비게이션 지원

## 🔄 업데이트 로그

- **v1.0**: 기본 로그인 페이지 구현
- **v1.1**: 시맨틱 HTML 개선
- **v1.2**: 반응형 디자인 추가
- **v1.3**: 접근성 개선

## 📚 참고 자료

- [KakaoTalk Design System](https://design.kakao.com/)
- [BEM Methodology](https://en.bem.info/)
- [CSS Custom Properties](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties)

---

**학습 목적으로 제작된 프로젝트입니다.**