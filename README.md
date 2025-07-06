# Personal Portfolio Website

모던하고 반응형인 개인 포트폴리오 웹사이트입니다. GitHub Pages를 통해 배포할 수 있도록 설계되었습니다.

## 🚀 Features

- **반응형 디자인**: 모바일, 태블릿, 데스크톱 모든 기기에서 최적화
- **모던 UI/UX**: 깔끔하고 세련된 디자인
- **부드러운 애니메이션**: 스크롤 효과와 호버 애니메이션
- **인터랙티브 요소**: 타이핑 효과, 패럴랙스 스크롤
- **접근성**: 키보드 네비게이션과 스크린 리더 지원
- **SEO 최적화**: 메타 태그와 시맨틱 HTML 구조

## 📁 Project Structure

```
Portfolio/
├── index.html          # 메인 HTML 파일
├── styles.css          # CSS 스타일시트
├── script.js           # JavaScript 기능
└── README.md           # 프로젝트 설명서
```

## 🛠️ Technologies Used

- **HTML5**: 시맨틱 마크업
- **CSS3**: Flexbox, Grid, CSS Variables, Animations
- **JavaScript**: ES6+, DOM Manipulation, Intersection Observer
- **Font Awesome**: 아이콘 라이브러리
- **Google Fonts**: Inter 폰트 패밀리

## 🎨 Design Features

### Color Scheme

- Primary: `#6366f1` (Indigo)
- Secondary: `#f8fafc` (Light Gray)
- Text: `#1e293b` (Dark Gray)
- Background: `#ffffff` (White)

### Typography

- Font Family: Inter (Google Fonts)
- Weights: 300, 400, 500, 600, 700

### Animations

- Fade-in effects on scroll
- Hover animations on cards and buttons
- Typing effect on hero title
- Parallax scrolling
- Smooth transitions

## 📱 Sections

1. **Hero Section**: 인상적인 첫인상과 CTA 버튼
2. **About Section**: 자기소개와 기술 스택
3. **Projects Section**: 프로젝트 포트폴리오
4. **Contact Section**: 연락처 정보와 문의 폼

## 🚀 GitHub Pages 배포 방법

### 1. GitHub 저장소 생성

```bash
# 로컬에서 Git 초기화
git init
git add .
git commit -m "Initial portfolio commit"

# GitHub에 새 저장소 생성 후
git remote add origin https://github.com/yonghyeon-dev/portfolio.git
git branch -M main
git push -u origin main
```

### 2. GitHub Pages 설정

1. GitHub 저장소 페이지로 이동
2. **Settings** 탭 클릭
3. 왼쪽 메뉴에서 **Pages** 선택
4. **Source** 섹션에서 **Deploy from a branch** 선택
5. **Branch**를 `main`으로 설정
6. **Folder**를 `/ (root)`로 설정
7. **Save** 클릭

### 3. 배포 확인

- 몇 분 후 `https://yonghyeon-dev.github.io/portfolio`에서 사이트 확인 가능

## 🔧 커스터마이징

### 개인 정보 수정

`index.html` 파일에서 다음 부분을 수정하세요:

```html
<!-- 이름과 직함 -->
<h1 class="hero-title">
  안녕하세요, 저는 <span class="highlight">개발자</span>입니다
</h1>

<!-- 자기소개 -->
<div class="about-text">
  <p>안녕하세요! 저는 웹 개발에 열정을 가진 개발자입니다...</p>
</div>

<!-- 연락처 정보 -->
<a href="mailto:kryou1@naver.com" class="contact-link"> kryou1@naver.com </a>
```

### 색상 변경

`styles.css` 파일의 CSS 변수를 수정하세요:

```css
:root {
  --primary-color: #6366f1; /* 메인 색상 */
  --primary-dark: #4f46e5; /* 어두운 메인 색상 */
  --text-primary: #1e293b; /* 주요 텍스트 색상 */
  /* ... */
}
```

### 프로젝트 추가/수정

Projects 섹션에서 프로젝트 카드를 추가하거나 수정하세요:

```html
<!-- 첫 번째 프로젝트: 카드 혜택 비교 사이트 -->
<div class="project-card">
  <div class="project-image">
    <div class="project-placeholder">
      <i class="fas fa-credit-card"></i>
    </div>
  </div>
  <div class="project-content">
    <h3 class="project-title">카드 혜택 비교 사이트</h3>
    <p class="project-description">
      다양한 신용카드의 혜택을 비교할 수 있는 웹 애플리케이션입니다.
    </p>
    <div class="project-tech">
      <span class="tech-tag">HTML</span>
      <span class="tech-tag">CSS</span>
      <span class="tech-tag">JavaScript</span>
    </div>
    <div class="project-links">
      <a
        href="https://yonghyeon-dev.github.io/My-project.io/"
        class="project-link"
        target="_blank"
      >
        <i class="fas fa-external-link-alt"></i> Live Demo
      </a>
      <a
        href="https://github.com/yonghyeon-dev/My-project.io"
        class="project-link"
        target="_blank"
      >
        <i class="fab fa-github"></i> GitHub
      </a>
    </div>
  </div>
</div>

<!-- 두 번째 프로젝트: 카드 비교 실험실 -->
<div class="project-card">
  <div class="project-image">
    <div class="project-placeholder">
      <i class="fas fa-chart-line"></i>
    </div>
  </div>
  <div class="project-content">
    <h3 class="project-title">카드 비교 실험실</h3>
    <p class="project-description">
      카드 혜택 비교 기능을 개선하고 실험하는 프로젝트입니다.
    </p>
    <div class="project-tech">
      <span class="tech-tag">React</span>
      <span class="tech-tag">HTML</span>
      <span class="tech-tag">CSS</span>
      <span class="tech-tag">JavaScript</span>
    </div>
    <div class="project-links">
      <a
        href="https://yonghyeon-dev.github.io/Card_Comparison_Lab/"
        class="project-link"
        target="_blank"
      >
        <i class="fas fa-external-link-alt"></i> Live Demo
      </a>
      <a
        href="https://github.com/yonghyeon-dev/Card_Comparison_Lab"
        class="project-link"
        target="_blank"
      >
        <i class="fab fa-github"></i> GitHub
      </a>
    </div>
  </div>
</div>
```

## 📧 Contact Form

현재 연락 폼은 프론트엔드만 구현되어 있습니다. 실제 이메일 전송을 위해서는 다음 중 하나를 선택하세요:

1. **Formspree**: 무료 서비스로 폼 데이터를 이메일로 전송
2. **Netlify Forms**: Netlify 배포 시 자동으로 폼 처리
3. **EmailJS**: 클라이언트 사이드에서 이메일 전송
4. **백엔드 API**: Node.js, PHP 등으로 직접 구현

### Formspree 사용 예시

```html
<form
  class="contact-form"
  action="https://formspree.io/f/your-form-id"
  method="POST"
>
  <!-- 폼 필드들 -->
</form>
```

## 🌟 추가 기능 아이디어

- [ ] 다크 모드 토글
- [ ] 다국어 지원 (한국어/영어)
- [ ] 블로그 섹션 추가
- [ ] 프로젝트 필터링 기능
- [ ] 다운로드 가능한 이력서
- [ ] 소셜 미디어 통합
- [ ] 방문자 통계
- [ ] 댓글 시스템

## 📄 License

MIT License - 자유롭게 사용하고 수정하세요!

## 🤝 Contributing

버그 리포트나 기능 제안은 언제든 환영합니다!

---

**Happy Coding! 🚀**
132323
