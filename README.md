# discord-web-hook
디스코드에 관리자 권한이 없어 webhook으로 리마인더를 보내기 위한 방식입니다.

### 목표 기능
회고 리마인더를 보냅니다.
특정 시간까지 회고가 작성되지 않으면, 회고 알림을 "이름"과 함께 알립니다.

참고: 

https://github.com/marketplace/actions/discord-webhook-action
https://discord.com/developers/docs/interactions/message-components
https://velog.io/@yundori97/%EB%94%94%EC%8A%A4%EC%BD%94%EB%93%9C-%EC%95%8C%EB%A6%BC%EB%B4%87-%EB%A7%8C%EB%93%A4%EA%B8%B0

1. WEBHOOK_URL 시크릿 설정 (url 뒤에 /github 붙여야 한다)
