
# 웹 매뉴얼 (반응형 버전)

이 프로젝트는 Adobe InDesign으로 제작된 매뉴얼을 HTML로 변환하고, 반응형 웹 형식으로 개선하여 GitHub Pages를 통해 배포할 수 있도록 구성된 웹 매뉴얼입니다.

## 📁 구성

```
.
├── index.html              # 홈 화면 (기존 start.html 내용 포함)
├── live.html               # 실시간 영상
├── recorded.html           # 녹화 영상
├── event.html              # 이벤트
├── setup.html              # 설정
├── etc.html                # 기타
├── reference.html          # 참고
├── [각 페이지별 리소스 폴더들]
```

## 🌐 GitHub Pages 배포 방법

1. 이 폴더 전체를 GitHub 저장소에 업로드
2. 저장소에서 **Settings > Pages**로 이동
3. **Source**를 `main` 브랜치의 `/ (root)`로 설정
4. 배포 주소 예시:  
   `https://yourusername.github.io/repository-name/`

## ✅ 특징

- 모바일, 태블릿, 데스크탑 대응 반응형 웹 구조
- 모든 페이지에 공통 상단 메뉴 탑재
- 기존 InDesign 콘텐츠 스타일 및 구조 보존
- `index.html`은 기존 `start.html` 콘텐츠로 구성된 홈 화면

## 🛠 사용 기술

- HTML5 + CSS3 (반응형 레이아웃)
- GitHub Pages
- InDesign HTML Export 기반 콘텐츠

## ✨ 커스터마이징 팁

- 메뉴 수정은 `index.html` 및 각 HTML 파일의 `<nav>` 태그 수정
- 스타일 수정은 각 HTML의 `<style>` 또는 개별 리소스 폴더 내 CSS에서 가능
- 이미지 리소스는 각 `*-web-resources/image/` 폴더에 포함됨

---

문의사항이나 추가 요청이 있다면 언제든지 알려주세요!
