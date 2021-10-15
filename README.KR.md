# 원신 호요랩 자동 출석체크

🤖 Github Actions를 사용한 호요랩 자동 출석체크

[KOR](README.KR.md), [ENG](README.md)

# 사용법

1. 이 저장소를 포크(Fork) 합니다
2. 포크한 저장소에서 `Settings -> Secrets` 탭으로 이동합니다
3. `New repository secret` 버튼을 클릭합니다
4. `LTUID`, `LTOKEN`를 각각 Name 으로 지정하고 Value 에 아래의 가이드를 따라서 개인 인증 데이터를 입력합니다
5. Actions 메뉴에 들어가서, `Enable Actions Workflow` 버튼을 클릭합니다
6. 좌측의 목록에서 `HoYoLAB Attendance`를 클릭한 후, `Enable Workflow` 버튼을 눌러 활성화 해주세요
7. 모두 완료되었습니다! 이제 매일 16:00(UTC+0): Asia 서버시간 기준 0:00에 자동으로 실행됩니다!

# 인증 데이터 가져오기

크롬 기준 가이드:

1. [HoYoLAB](http://hoyolab.com) 으로 이동합니다
2. 본인 계정으로 로그인 합니다
3. F12 버튼을 눌러 개발자 도구를 엽니다
4. 애플리케이션 -> 쿠키 -> `https://www.hoyolab.com` 으로 이동합니다
5. `ltuid`와 `ltoken`을 찾아 복사합니다

# 라이센스

[MIT License](LICENSE)
