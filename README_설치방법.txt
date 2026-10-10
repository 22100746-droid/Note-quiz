계 이름 트레이너 · PWA 설치 방법

이 폴더는 FINAL v2를 PWA로 만든 배포용 패키지입니다.

중요: PWA 설치/오프라인 기능은 file://로 index.html을 직접 열면 동작하지 않습니다.
HTTPS 웹주소에 이 폴더 전체를 업로드해야 합니다.

아이폰 설치
1. 이 폴더 전체를 HTTPS 정적 호스팅에 업로드합니다.
2. iPhone에서 Safari로 해당 주소를 엽니다.
3. 공유 버튼 → 홈 화면에 추가.
4. 홈 화면의 '계 이름 트레이너' 아이콘으로 실행합니다.
5. 한 번 정상 로드된 뒤에는 서비스 워커가 앱 파일을 캐시하므로 오프라인에서도 사용할 수 있습니다.

파일 구성
- index.html: 앱 본체
- manifest.webmanifest: PWA 앱 정보
- sw.js: 오프라인 캐시
- icons/: 홈 화면 및 PWA 아이콘

무료 정적 호스팅 예: GitHub Pages, Netlify, Cloudflare Pages 등
