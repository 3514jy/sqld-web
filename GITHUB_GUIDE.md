# 🚀 GitHub 업로드 완벽 가이드

## 📦 준비물

- ✅ GitHub 계정
- ✅ sqld_final.zip 파일

---

## 🎯 방법 1: GitHub 웹에서 바로 업로드 (가장 쉬움!)

### Step 1: 새 저장소 생성

1. GitHub.com 로그인
2. 우측 상단 `+` 클릭 → `New repository`
3. 저장소 설정:
   - Repository name: `sqld-webtoon` (또는 원하는 이름)
   - Description: `SQLD 웹툰 학습 사이트`
   - Public 선택
   - ✅ Add a README file (체크 해제)
4. `Create repository` 클릭

### Step 2: 파일 업로드

1. `uploading an existing file` 클릭
2. ZIP 압축 해제한 파일들 **전체 선택**
3. 드래그 앤 드롭 (또는 `choose your files`)
4. Commit message: `Initial commit - SQLD 웹툰 학습 사이트`
5. `Commit changes` 클릭

### Step 3: GitHub Pages 활성화

1. `Settings` 탭 클릭
2. 좌측 메뉴에서 `Pages` 클릭
3. Source 설정:
   - Branch: `main` 선택
   - Folder: `/ (root)` 선택
4. `Save` 클릭
5. **5분 정도 기다리면 배포 완료!**

### Step 4: 완료!

배포된 URL: `https://your-username.github.io/sqld-webtoon/`

---

## 🎯 방법 2: Git 명령어로 업로드 (개발자용)

### 1. Git 설치 확인

```bash
git --version
```

없으면 [git-scm.com](https://git-scm.com)에서 다운로드

### 2. 파일 압축 해제

```bash
unzip sqld_final.zip -d sqld-webtoon
cd sqld-webtoon
```

### 3. Git 초기화

```bash
git init
git add .
git commit -m "Initial commit - SQLD 웹툰 학습 사이트"
```

### 4. GitHub 저장소 연결

```bash
# GitHub에서 저장소 생성 후
git remote add origin https://github.com/your-username/sqld-webtoon.git
git branch -M main
git push -u origin main
```

### 5. GitHub Pages 활성화

Settings → Pages → Branch: `main` 선택 → Save

---

## 🎯 방법 3: GitHub Desktop 사용 (비개발자 추천!)

### 1. GitHub Desktop 설치

[desktop.github.com](https://desktop.github.com)에서 다운로드

### 2. 저장소 생성

1. `File` → `New repository`
2. Name: `sqld-webtoon`
3. Local path: 원하는 폴더 선택
4. `Create repository`

### 3. 파일 추가

1. ZIP 파일 압축 해제
2. 모든 파일을 저장소 폴더로 복사

### 4. Commit & Push

1. GitHub Desktop에서 변경사항 확인
2. Summary: `Initial commit`
3. `Commit to main`
4. `Publish repository` 클릭
5. Public 선택 → `Publish repository`

### 5. GitHub Pages 활성화

GitHub 웹사이트 → Settings → Pages → Branch: `main` → Save

---

## ✅ 확인 사항

### 배포 확인

1. GitHub 저장소 → `Actions` 탭
2. `pages build and deployment` 워크플로우 확인
3. 초록색 체크 표시 = 성공!

### 접속 테스트

```
https://your-username.github.io/sqld-webtoon/
```

---

## 🔧 문제 해결

### 404 에러가 나요!

**해결책:**
- Settings → Pages에서 Branch가 `main`으로 설정되었는지 확인
- 5-10분 정도 기다려보기
- 저장소가 Public인지 확인

### 파일이 너무 많아요!

**해결책:**
- GitHub는 한 번에 100개 파일까지 업로드 가능
- Git 명령어 사용 (방법 2)
- 또는 여러 번 나눠서 업로드

### 스타일이 안 나와요!

**해결책:**
- 모든 파일이 같은 폴더에 있는지 확인
- index.html과 chapter*.html이 같은 위치에 있어야 함
- 브라우저 캐시 삭제 (Ctrl + Shift + R)

---

## 📝 커스터마이징

### 저장소 이름 변경

Settings → General → Repository name

### README 수정

README.md 파일 편집:
- 저장소 URL 업데이트
- 배포 URL 업데이트
- 본인 정보 추가

---

## 🎊 완료!

이제 전 세계 누구나 접속 가능한 SQLD 학습 사이트가 완성되었습니다!

**배포 URL을 친구들과 공유하세요!** 🎉

---

**💡 Tip:** Star를 받으면 검색 노출이 올라갑니다!
