# Bubble-style private chat demo

친구 1명(artist) + 나(fan)가 사용하는 버블/프롬 느낌의 1:1 채팅 프로토타입입니다.

## 포함 기능

- 이메일/비밀번호 회원가입·로그인
- fan / artist 역할
- 프로필 이름/닉네임/사진 URL 수정
- 실시간 1:1 메시지
- 팬 메시지에 artist가 답장하면 인용 + "아티가 나에게 답장했어요! ♥"
- artist가 보내는 `@@`를 팬의 닉네임으로 치환
- 팬 상단에 구독 +N일 표시
- 모바일 UI
- Supabase Realtime

## 시작 순서

1. https://supabase.com 에서 새 프로젝트를 만듭니다.
2. SQL Editor에서 `schema.sql` 전체를 실행합니다.
3. Project URL과 Publishable key(또는 anon key)를 확인합니다.
4. `config.js`의 두 값을 채웁니다.
5. `index.html`을 열거나 GitHub Pages에 올립니다.
6. 나와 친구가 각각 회원가입합니다.
7. 친구 계정의 profile을 artist로 바꿉니다.
8. 새로고침하면 채팅방이 생성됩니다.

### 주의

- `service_role` 또는 secret key를 config.js에 넣지 마세요.
- 이 버전은 친구 둘이 쓰는 MVP입니다.
- 다중 아티스트/다중 팬, 이미지 업로드, 푸시 알림, 차단/신고, 관리자 페이지 등은 다음 단계에서 추가할 수 있습니다.
- 폰트는 `style.css`의 font-family만 나중에 교체하면 됩니다.
