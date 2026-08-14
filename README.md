# Interaction Test

디테일 인터랙션 테스트용 클릭 가능한 프로토타입입니다. Xcode 프로젝트 `Playground`(로컬: `~/Developer/Playground`)의 Effects Test / Haptic Feedback 시나리오를 웹으로 옮겼습니다.

- **Effects Test** — Feedback/Background 섹션 메뉴
- **Haptic Feedback** — Notification/Impact/Selection 그룹별 진동 트리거 (진동은 브라우저에서 느낄 수 없어 탭 시 토스트로만 표시)
- **Screen Sweep / Mesh Gradient / Particle System** — 자리표시자 화면 (미구현)

## 구조

`index.html` 하나로 완결된 정적 페이지입니다 (별도 빌드 스텝 없음). Manta 다크 토큰 색상, Poppins 폰트를 인라인으로 내장하고 있어 외부 리소스 없이 그대로 열립니다.

## 배포

https://interaction-test-psi.vercel.app
