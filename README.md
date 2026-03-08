# mineworker-x29.github.io

개인 GitHub 블로그(Jekyll + GitHub Pages) 초기 세팅 저장소입니다.
기존 테마 샘플 콘텐츠를 정리하고, 바로 글을 발행할 수 있는 최소 구조로 구성했습니다.

## 포함 내용

- GitHub Pages 호환 Jekyll 설정
- 홈 / 소개 / 글 목록 / 연락처 페이지
- 첫 번째 환영 포스트 템플릿

## 빠른 시작

1. 저장소 이름을 `사용자이름.github.io`로 맞춥니다.
2. `_config.yml`의 `title`, `description`, `author`, `url`을 수정합니다.
3. `_data/settings.yml`의 메뉴/소셜 링크를 본인 정보로 바꿉니다.
4. `_posts` 폴더에 `YYYY-MM-DD-title.md` 형식으로 글을 추가합니다.

## 로컬 실행

```bash
bundle install
bundle exec jekyll serve
```

브라우저에서 `http://127.0.0.1:4000` 접속 후 확인할 수 있습니다.

## 배포

`main` 브랜치에 푸시하면 GitHub Pages가 자동으로 빌드/배포합니다.
