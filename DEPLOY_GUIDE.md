# 🚀 웹 호스팅 배포 가이드

## 1️⃣ GitHub Pages (무료, 추천!)

### 단계별 가이드:

**Step 1: GitHub 저장소 생성**
1. GitHub.com 로그인
2. 우측 상단 `+` → `New repository`
3. Repository name: `sqld-webtoon`
4. Public 선택
5. `Create repository`

**Step 2: 파일 업로드**
1. `Add file` → `Upload files`
2. 모든 HTML 파일 드래그 앤 드롭
3. `Commit changes`

**Step 3: GitHub Pages 활성화**
1. `Settings` 탭 클릭
2. 좌측 `Pages` 클릭
3. Source: `Deploy from a branch`
4. Branch: `main` 선택, 폴더: `/ (root)`
5. `Save` 클릭

**Step 4: 완료!**
- 5분 정도 기다리면 배포 완료
- URL: `https://your-username.github.io/sqld-webtoon/`

---

## 2️⃣ Netlify (매우 쉬움!)

### 드래그 앤 드롭 배포:

1. [Netlify.com](https://netlify.com) 접속
2. 회원가입 (GitHub 계정으로 가능)
3. `Sites` → `Add new site` → `Deploy manually`
4. **폴더 전체를 드래그 앤 드롭**
5. 완료! (2분 안에 배포 완료)

**장점:**
- ✅ 즉시 배포 (2분)
- ✅ 무료 SSL (https)
- ✅ 커스텀 도메인 가능
- ✅ GitHub 연동 가능

---

## 3️⃣ Vercel (빠름!)

1. [Vercel.com](https://vercel.com) 접속
2. GitHub 계정으로 로그인
3. `New Project`
4. GitHub 저장소 선택
5. `Deploy` 클릭
6. 완료!

---

## 4️⃣ Cloudflare Pages (무료, 빠름!)

1. [Cloudflare Pages](https://pages.cloudflare.com) 접속
2. `Create a project`
3. GitHub 저장소 연결
4. 배포 설정 (기본값 사용)
5. `Save and Deploy`

---

## 📝 추천 순서

1. **가장 쉬움:** Netlify (드래그 앤 드롭)
2. **인기:** GitHub Pages
3. **빠름:** Vercel
4. **CDN:** Cloudflare Pages

---

## 💡 Tips

### 커스텀 도메인 연결
- Netlify/Vercel: 무료 제공
- GitHub Pages: 설정 가능
- 예: `sqld-study.com`

### HTTPS (SSL)
- 모든 서비스에서 무료 제공 ✅

### 자동 배포
- GitHub에 push하면 자동으로 재배포

---

**🎊 1시간 안에 배포 완료 가능합니다!**
