# 엔지니어랩 학습 가이드

엔지니어링 학습 과정과 자격 준비를 검토하는 사용자를 위한 순수 정적 정보 사이트입니다. 별도 빌드나 서버 없이 GitHub Pages에서 바로 동작합니다.

## 저장소 정보

- Organization: `engineerlab-info`
- Repository: `engineerlab-info.github.io`
- 공개 주소: `https://engineerlab-info.github.io/`

## GitHub Pages 배포 방법

1. GitHub에서 `engineerlab-info` Organization을 만들고, 그 안에 `engineerlab-info.github.io` 이름의 공개 저장소를 생성합니다.
2. 이 폴더의 파일을 압축 해제한 뒤 저장소 최상단에 모두 업로드합니다. `index.html`이 하위 폴더가 아닌 저장소 첫 화면에 보여야 합니다.
3. 저장소의 **Settings → Pages**로 이동합니다.
4. **Build and deployment**의 Source를 **Deploy from a branch**로 선택합니다.
5. Branch는 `main`, 폴더는 `/(root)`를 선택하고 저장합니다.
6. 배포가 완료되면 공개 주소에서 사이트를 확인합니다. 최초 배포에는 몇 분이 걸릴 수도 있습니다.

## 파일 구성

- `index.html`: 메인 콘텐츠와 SEO 메타 정보
- `style.css`: 반응형 디자인
- `robots.txt`: 검색엔진 크롤링 설정
- `sitemap.xml`: 사이트맵
- `404.html`: 오류 페이지
- `favicon.svg`: 사이트 아이콘

콘텐츠나 주소를 수정한 뒤에는 canonical, Open Graph URL, robots.txt, sitemap.xml의 주소도 함께 확인하세요.
