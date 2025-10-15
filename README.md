# Portfolio Website

개인 포트폴리오 웹사이트입니다. 현대적이고 반응형 디자인으로 제작되었으며, GitHub Pages를 통해 배포할 수 있습니다.

## 🚀 주요 기능

- **반응형 디자인**: 모바일, 태블릿, 데스크톱 모든 기기에서 최적화된 경험
- **현대적인 UI/UX**: 미니멀하고 깔끔한 디자인
- **부드러운 애니메이션**: 스크롤 애니메이션과 호버 효과
- **접근성 고려**: 키보드 네비게이션 및 스크린 리더 지원
- **빠른 로딩**: 최적화된 코드와 리소스

## 📁 프로젝트 구조

```
portfolio/
├── index.html          # 메인 HTML 파일
├── styles/
│   └── style.css       # CSS 스타일시트
├── scripts/
│   └── main.js         # JavaScript 파일
├── assets/
│   └── images/         # 이미지 파일들
└── README.md           # 프로젝트 설명서
```

## 🛠️ 기술 스택

- **HTML5**: 시맨틱 마크업
- **CSS3**: Flexbox, Grid, 애니메이션
- **Vanilla JavaScript**: ES6+ 문법 사용
- **Font Awesome**: 아이콘
- **Google Fonts**: Inter 폰트

## 🎨 디자인 특징

- **컬러 팔레트**: 그라데이션 블루/퍼플 톤
- **타이포그래피**: Inter 웹폰트 사용
- **레이아웃**: CSS Grid와 Flexbox 활용
- **애니메이션**: CSS Transitions와 JavaScript

## 📱 반응형 브레이크포인트

- **Desktop**: 1200px 이상
- **Tablet**: 768px - 1199px
- **Mobile**: 767px 이하

## 🚀 배포 방법

### GitHub Pages 사용

1. GitHub 저장소에 코드 업로드
2. Settings > Pages 메뉴로 이동
3. Source를 "Deploy from a branch"로 설정
4. Branch를 "main"으로 선택
5. Save 버튼 클릭

### Netlify 사용

1. [Netlify](https://netlify.com)에 가입
2. "New site from Git" 선택
3. GitHub 저장소 연결
4. Build settings에서 빌드 명령어는 비워두기
5. Deploy site 클릭

## ✏️ 커스터마이징

### 개인 정보 수정

1. **HTML 파일 수정** (`index.html`):
   - 이름, 소개글, 연락처 정보 변경
   - 프로젝트 정보 업데이트
   - 기술 스택 수정

2. **CSS 파일 수정** (`styles/style.css`):
   - 컬러 팔레트 변경
   - 폰트 변경
   - 레이아웃 조정

3. **JavaScript 파일 수정** (`scripts/main.js`):
   - 애니메이션 효과 조정
   - 새로운 기능 추가

### 프로젝트 추가

`index.html`의 projects 섹션에서 새로운 프로젝트 카드를 추가:

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-your-icon"></i>
    </div>
    <div class="project-content">
        <h3>프로젝트 이름</h3>
        <p>프로젝트 설명</p>
        <div class="project-tech">
            <span class="tech-tag">기술1</span>
            <span class="tech-tag">기술2</span>
        </div>
        <div class="project-links">
            <a href="#" class="project-link">
                <i class="fab fa-github"></i> GitHub
            </a>
            <a href="#" class="project-link">
                <i class="fas fa-external-link-alt"></i> Live Demo
            </a>
        </div>
    </div>
</div>
```

## 🔧 개발 환경 설정

1. 저장소 클론:
```bash
git clone https://github.com/yourusername/portfolio.git
cd portfolio
```

2. 로컬 서버 실행:
```bash
# Python 3 사용
python -m http.server 8000

# Node.js 사용
npx serve .

# Live Server 확장 프로그램 사용 (VS Code)
```

3. 브라우저에서 `http://localhost:8000` 접속

## 📄 라이선스

이 프로젝트는 MIT 라이선스 하에 배포됩니다.

## 🤝 기여하기

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 연락처

- 이메일: your.email@example.com
- GitHub: [@yourusername](https://github.com/yourusername)
- LinkedIn: [Your Name](https://linkedin.com/in/yourprofile)

---

⭐ 이 프로젝트가 도움이 되었다면 Star를 눌러주세요!
