# discord-web-hook
디스코드에 관리자 권한이 없어 webhook으로 리마인더를 보내기 위한 방식입니다.

### 목표 기능
회고 리마인더를 보냅니다.
특정 시간까지 회고가 작성되지 않으면, 회고 알림을 "이름"과 함께 알립니다.

참고: https://github.com/marketplace/actions/discord-webhook-action
1. WEBHOOK_URL 시크릿 설정 (url 뒤에 /github 붙여야 한다)
