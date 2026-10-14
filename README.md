# 기니피그 클럽

단일 HTML 파일로 만든 인터랙티브 웹 작품입니다. 별도의 빌드나 패키지 설치 없이 `index.html`을 GitHub Pages에 배포할 수 있습니다.

## GitHub Pages 배포

`main` 브랜치에 변경 사항을 올리면 GitHub Actions가 사이트를 배포합니다. 저장소의 **Settings → Pages → Build and deployment**에서 **GitHub Actions**를 선택해 주세요.

## 함께 수정하기

저장소 소유자는 GitHub 저장소의 **Settings → Collaborators**에서 함께 작업할 사람을 초대할 수 있습니다. 초대받은 사람은 VS Code에서 저장소를 열고 GitHub Copilot Chat으로 코드를 수정한 뒤, 커밋과 푸시로 변경 사항을 사이트에 반영할 수 있습니다.

## 구성

- `index.html`: 화면, 스타일, 인터랙션을 포함한 전체 사이트
- `.github/workflows/pages.yml`: `main` 브랜치 업데이트 시 GitHub Pages로 배포
