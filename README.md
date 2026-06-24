# ☁️ AWS 실전 모의고사 (GitHub Pages 버전)

PDF Dump 파일을 **브라우저에서 직접** 파싱하는 퀴즈 앱입니다.  
서버가 없어도 GitHub Pages URL만 있으면 PC / 모바일 어디서나 실행됩니다.

🔒 **PDF는 서버로 전송되지 않습니다** — 모든 처리가 브라우저 안에서 이루어집니다.

---

## 🚀 GitHub Pages 배포 (3단계)

### 1. 저장소 만들기
```bash
git init
git add index.html README.md
git commit -m "init"
git remote add origin https://github.com/내아이디/저장소이름.git
git push -u origin main
```

### 2. GitHub Pages 활성화
1. 저장소 → **Settings** 탭
2. 왼쪽 메뉴 → **Pages**
3. Source: **Deploy from a branch**
4. Branch: **main** / **/ (root)**
5. **Save** 클릭

### 3. 접속
약 1~2분 후 아래 URL로 접근 가능:
```
https://내아이디.github.io/저장소이름/
```

---

## ✨ 기능

- 📄 클릭 업로드 + 드래그 앤 드롭
- 📱 PC / 모바일 반응형
- 🔀 문제 랜덤 셔플
- 📊 점수 확인 모달 (합격선 72%)
- 🔤 글자 크기 조절
- 💾 세션 중 풀이 자동 저장
- 🔒 PDF는 브라우저에서만 처리 (서버 전송 없음)
