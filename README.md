# iLog-iTrace-legal

iLog · iTrace · iLogMobile 앱의 법적 약관 페이지를 호스팅하는 GitHub Pages 저장소입니다.

## 페이지 URL

- **위치기반서비스 이용약관**: https://iveandor.github.io/iLog-iTrace-legal/location.html
- **개인정보 처리방침**: https://iveandor.github.io/iLog-iTrace-legal/privacy.html
- **서비스 이용약관**: https://iveandor.github.io/iLog-iTrace-legal/service.html
- **사용자 가이드**: https://iveandor.github.io/iLog-iTrace-legal/user-guide.html
- **기기 권한 설정 가이드**: https://iveandor.github.io/iLog-iTrace-legal/permissions-guide.html

## 파일 구성

| 파일 | 설명 |
|------|------|
| `location.html` | 위치기반서비스 이용약관 |
| `privacy.html` | 개인정보 처리방침 |
| `service.html` | 서비스 이용약관 |
| `user-guide.html` | 사용자 가이드 |
| `permissions-guide.html` | 기기 권한 설정 가이드 |

## 관련 프로젝트

iLog · iTrace · iLogMobile — 가족 위치 추적 시스템

## 문의

support@iveandor.com

## 변경 이력

- **2026-04-28 (iLog 인증 방식 변경 · 영상 녹화 기능 반영)**:
  - `privacy.html`: iLog 인증 방식 "Firebase 익명 인증" → "Silent Google Sign-In" 정정. SOS 녹음 항목을 "SOS 음성·영상 녹음"으로 분리(iLog=음성 m4a, iLogMobile=영상+음성 mp4). 원격 모니터링 파일 형식 aac/mp4로 업데이트. 원격 모니터링 세션 기록 보유기간 10일→90일 수정(DynamoDB TTL 90일 반영).
  - `service.html`: iLog 인증 방식 "Firebase 익명 인증" → "Silent Google Sign-In" 정정. "원격 음성 모니터링" → "원격 음성·영상 모니터링"으로 업데이트.
  - `user-guide.html`: SOS 섹션에서 iLog(음성 녹음)와 iLogMobile(영상+음성 녹화) 동작 분리. 스트리밍 섹션에 오디오/영상+오디오 모드 안내 추가.
  - 전 문서 최종 수정일 2026-04-28 갱신.

- **2026-04-26 (유료 서비스 전환 업데이트)**:
  - `service.html`: 제5조 결제 및 구독 관리 신설 (App Store / Google Play 인앱 구독, 자동 갱신, 취소 방법), 제6조 환불 정책 신설, 이후 조항 번호 재정렬 (제7조~제14조), 제11조 배상 책임 한도를 '최근 1개월 구독 요금' 기준으로 구체화.
  - `privacy.html`: 구독·결제 정보 수집 항목 추가 (구독 상태·만료일·Transaction ID), 처리 위탁에 Apple App Store / Google Play 결제 처리 항목 추가, 구독 유효성 확인 목적 추가.
  - `user-guide.html`: FAQ에 구독 가입 방법, 구독 취소 방법 항목 추가, 목차 업데이트.
  - `location.html`, 전체 파일 수정일 2026-04-26 갱신.
  - `README.md`: 파일 구성 표에 `user-guide.html`, `permissions-guide.html` 추가.
  - 전 문서 고객센터 이메일을 `support@iveandor.com` 별칭으로 통일 (이전: `dev+support@iveandor.com`, `service.html`은 `dev.support@iveandor.com` 오타). ⚠️ 메일 서비스에서 `support@iveandor.com → dev@iveandor.com` 별칭(alias) 설정 필요.
