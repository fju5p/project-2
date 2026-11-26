# StudyLog

프레임워크나 빌드 도구(`npm`, `build`, `dist`, `Vite`, `React` 등) 없이 **순수 HTML · CSS · JavaScript 단일 `index.html` 파일**로 동작하는 고등학생용 공부 시간 측정 및 학습 분석 웹 앱입니다.

## 실행 방법 (더블 클릭 바로 실행)
- `index.html` 파일을 내려받아 브라우저에서 **더블 클릭**하면(`file://`) 별도 서버나 설치 없이 즉시 실행됩니다.
- 모든 공부 기록, 과목, 목표, 설정은 브라우저의 `localStorage`에 자동 저장됩니다.

## GitHub → Vercel 즉시 배포 방법
1. `index.html` (원하면 `vercel.json`, `README.md` 포함)을 GitHub 저장소에 업로드합니다.
2. [Vercel](https://vercel.com)에서 **Add New... → Project**를 누르고 해당 GitHub 저장소를 **Import**합니다.
3. 빌드 설정 없이(`Framework Preset: Other`) **Deploy**를 누르면 즉시 배포 주소(`https://프로젝트명.vercel.app`)가 생성됩니다.
