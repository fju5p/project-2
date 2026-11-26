# StudyLog

과목별 공부 시간을 측정하고 일별·주별·월별·시간대별 학습 데이터를 분석할 수 있는 웹 앱입니다.

## 주요 기능
- **타이머 (`#/timer`)**: 과목 선택 후 시작/정지, 일시정지, 집중 타이머 가이드(자유/25분/50분), 이탈 시 자동 정지(딴짓 방지)
- **심층 분석 (`#/analytics`)**: 오늘·이번 주·최근 30일·전체 누적 통계, 시간대별 학습 효율, 집중도 분포
- **전체 기록 (`#/records`)**: 과목·기간·집중도·검색 필터, 기록 수정/삭제, CSV 내보내기
- **목표 · D-Day (`#/goals`)**: 주간 목표 달성률, 시간 배분 제안, 시험·수행평가 D-Day 관리
- **과목 · 설정 (`#/manage`)**: 과목 및 주간 목표 설정, 라이트/다크 모드, 집중도별 배경 음악 & 노이즈 재생, JSON 백업/복원

## GitHub 업로드 및 Vercel 배포 방법
1. 이 프로젝트 폴더를 GitHub 저장소에 업로드(Push)합니다.
2. [Vercel](https://vercel.com)에 로그인 후 **Add New... → Project**를 클릭합니다.
3. 업로드한 GitHub 저장소를 선택하고 **Import**를 누릅니다.
4. `vercel.json` 설정(Framework: `Vite`, Build Command: `npm run build`, Output Directory: `dist`)이 자동 적용되므로 별도 환경 변수 없이 **Deploy**를 클릭하면 배포 주소(`https://프로젝트명.vercel.app`)가 생성됩니다.

## 로컬 실행
```bash
npm install
npm run dev
```
