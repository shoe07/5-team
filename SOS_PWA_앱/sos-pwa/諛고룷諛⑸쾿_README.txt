============================================
  SOS 긴급알림 PWA - GitHub Pages 배포 가이드
============================================

■ 준비물
---------
- GitHub 계정 (없으면 github.com에서 무료 가입)
- 이 폴더 안의 파일 4개:
    index.html
    manifest.json
    sw.js
    icon-192.png
    icon-512.png


■ 배포 방법 (5분이면 완료!)
-----------------------------

[1단계] GitHub 로그인 후 새 저장소 만들기
  - github.com 접속 → 로그인
  - 오른쪽 상단 "+" 버튼 → "New repository"
  - Repository name: sos-app  (원하는 이름)
  - Public 선택 (중요!)
  - "Create repository" 클릭

[2단계] 파일 업로드
  - 생성된 저장소 페이지에서
  - "uploading an existing file" 클릭
  - 이 폴더의 파일 5개를 모두 드래그 앤 드롭
  - "Commit changes" 클릭

[3단계] GitHub Pages 활성화
  - 저장소 상단 "Settings" 탭 클릭
  - 왼쪽 메뉴 "Pages" 클릭
  - Source: "Deploy from a branch"
  - Branch: "main" 선택 → "/" (root) → Save

[4단계] 완료!
  - 1~2분 후 아래 주소로 앱 접속 가능:
    https://[내GitHub아이디].github.io/sos-app/
  - 이 링크를 휴대폰으로 접속하면 됩니다!


■ 휴대폰 홈 화면에 앱 추가하기
---------------------------------

[안드로이드 - Chrome]
  1. 위 링크를 Chrome으로 열기
  2. 우상단 점 3개 메뉴 → "홈 화면에 추가"
  3. 또는 자동으로 설치 배너가 뜸

[아이폰 iOS - Safari]
  ※ 반드시 Safari로 열어야 합니다
  1. 위 링크를 Safari로 열기
  2. 하단 공유 버튼(□↑) 탭
  3. "홈 화면에 추가" 탭
  4. "추가" 탭


■ 주의사항
-----------
- iOS에서는 반드시 Safari 브라우저 사용
- Chrome/Firefox에서는 홈 화면 추가 불가 (iOS 한정)
- 안드로이드는 Chrome, Samsung Internet 모두 가능
- 입력한 정보는 기기 내 브라우저에 저장됨
  (앱 삭제 시 데이터도 삭제될 수 있음)

============================================
