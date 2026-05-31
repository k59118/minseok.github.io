# Minseok Kang — Academic Homepage

개인 academic homepage입니다. 순수 HTML/CSS로 작성되어 별도의 빌드 과정 없이 동작합니다.

## 파일 구조

```
.
├── index.html          # 메인 페이지 (Profile, News, Education, Publications)
├── style.css           # 스타일시트
├── Minseok_photo.jpeg  # 프로필 사진
└── Minseok_s_CV.pdf    # CV
```

## 로컬에서 실행

```bash
python3 -m http.server 8000
```

브라우저에서 `http://localhost:8000` 접속.

## GitHub Pages 배포

1. GitHub에 새 저장소를 만들고 이 폴더의 파일을 push 합니다.

```bash
git init
git add .
git commit -m "Add academic homepage"
git branch -M main
git remote add origin https://github.com/<username>/<repo>.git
git push -u origin main
```

2. 저장소 **Settings → Pages** 로 이동합니다.
3. **Source** 를 `Deploy from a branch` 로 설정하고, Branch 를 `main` / `(root)` 로 지정한 뒤 Save.
4. 잠시 후 `https://<username>.github.io/<repo>/` 에서 사이트가 공개됩니다.

> 사용자 페이지(`https://<username>.github.io`)로 쓰려면 저장소 이름을 `<username>.github.io` 로 만들면 됩니다.
