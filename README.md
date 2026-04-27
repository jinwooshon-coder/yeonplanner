# 연플래너 v4.5 배포용

## 이번 버전 핵심
- 기록 모달에서 날짜와 시간을 바로 수정할 수 있습니다.
- 기록별 복습 예약을 지정할 수 있습니다.
- 학생/선생님 로그인 화면을 보강했습니다.
- Google 로그인 준비 구조를 넣었습니다. Firebase 설정값을 넣으면 실제 Google 로그인과 서버 저장으로 확장할 수 있습니다.
- 현재 설정값이 없으면 체험용 로컬 로그인으로 작동합니다.

## 배포 파일
같은 폴더에 아래 파일을 모두 올리세요.
- index.html
- yeondraw.html
- manifest.json
- service-worker.js

## 실제 Google 로그인 적용
Firebase 프로젝트를 만들고 웹앱 설정값을 index.html 상단의 window.YEON_FIREBASE_CONFIG에 입력하세요.
그 후 Firebase SDK 스크립트와 Firestore 저장 코드를 연결하면 학생별 서버 저장이 가능합니다.
