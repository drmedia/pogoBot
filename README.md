# 포켓몬고 기능 추가
포켓몬고 도곡대치방에 하입님이 만드신 포켓몬고봇을 가져와 수정 했습니다.<br>
https://github.com/drmedia/pogoBot

<br>1.	포켓몬고 날씨 예보 기능
<br>2.	레이드 시간 45분, 1시간 변경 가능하도록 수정
<br>3.	시간 계산시 오류 수정
<br>4.	체육관 검색 기능 추가(강서구)
<br>5.	스탑 검색 기능 추가(강서구)
<br>6.	둥지 사이트 가져고올때 수도권만 가지고 오도록 수정
<br>7.	필요한 기능만 사용 설정 기능


# 포켓몬고 레이드/출석부 제보봇
포켓몬고 도곡대치방 도리에 사용된 스크립트입니다.<br>
저는 해당 방에서 하입이라는 아이디를 사용한 유저구요.<br>
제 미천한 코드가 도움이 될지 모르겠으나, 편하게 가져가서 쓰세요.<br>
출처 남기지 않으셔도 됩니다. (원출처인 Dark Tornado님껀 남겨주세요) <br><br>
만약 이게 어떻게 돌아가는건지 일단 확인 해보고싶으신분들 계시면<br>
도리용 방을 파두었으니, 와서 찔러보세요<br>https://open.kakao.com/o/gTDj2gmb 


# 기본적인 세팅
Dark Tornado 님의 카카오톡 봇을 사용했다가..최근 바꿨습니다

<br>[닼토님의 블로그](https://m.blog.naver.com/PostView.nhn?blogId=dt3141592&logNo=221213789127&proxyReferer=https%3A%2F%2Fwww.google.com%2F) / [닼토님의 깃헙](https://github.com/DarkTornado) / [닼토님의 카카오톡봇](https://play.google.com/store/apps/details?id=com.darktornado.kakaobot&hl=ko) / [메신저봇](https://play.google.com/store/apps/details?id=com.xfl.kakaotalkbot)
<br>1. 포켓몬고 하시는분들 대부분 2폰이실테니, 메인폰이 아닌 곳에 카톡봇을 돌리시면 됩니다.
<br>2. [메신저봇](https://play.google.com/store/apps/details?id=com.xfl.kakaotalkbot) 어플을 설치하시고 환경설정을 하시면 됩니다.
<br>3. 카카오톡봇 앱에서 카카오톡봇을 자바스크립트(javascript)로 생성합니다. (이름을 지어주세요. 간단하게 도리쓰시면 됩니다)
<br>4. 생성 후 폰을 컴퓨터에 연결하시면 katalkbot 폴더 내에 아까 생성한 봇 이름으로 .js파일이 있을 겁니다. 그 안에 이 깃헙에 있는 도리.js 파일을 넣어주세요 (처음에 설정하신 이름이 "도리"라면, 그대로 덮어 써주세요).
<br>5. 폰에 컴퓨터를 연결하고 폰에 접속하자마자 있는 폴더에 DoriDB와 UniqueDB를 폴더째로 넣어주세요.
<br>6. 카카오톡봇 앱에 접속하여 시계방향으로 화살표 표시가 되어있는 버튼을 눌러 리로드를 해주세요
<br>7. 이러면 대충 가장 필요한 기능들 (제보와 팟은) 돌아갈겁니다. 안돌아가면 그때부터 코드를 좀 보셔야할텐데 굳럭입니다.

# 기본 명령어 모음
![명령어 리스트](https://user-images.githubusercontent.com/24535854/61108561-9198df80-a4bd-11e9-9607-a50cf1b88b8b.png)
<br><br><br>
# 레이드 제보, 팟, 리서치 관련 명령어 그림
## 레이드 현황, 삭제, 변경, 리셋
<img src="https://user-images.githubusercontent.com/24535854/61108316-f869c900-a4bc-11e9-80e7-2bd33125de98.jpg" width="350"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://user-images.githubusercontent.com/24535854/61108315-f7d13280-a4bc-11e9-82eb-1427ec5231fe.jpg" width="350"><br><br>
## 팟 생성, 삭제, 리셋, 명단추가, 명단제거, 내용변경, 연타추가
<img src="https://user-images.githubusercontent.com/24535854/61105450-ed129f80-a4b4-11e9-8e1d-76d119e0ed99.jpg" width="215"> <img src="https://user-images.githubusercontent.com/24535854/61105468-ef74f980-a4b4-11e9-8615-919c20aa3fd3.jpg" width="215"> <img src="https://user-images.githubusercontent.com/24535854/61105460-edab3600-a4b4-11e9-9f12-7cfb9a6eca99.jpg" width="215"> <img src="https://user-images.githubusercontent.com/24535854/61105467-ef74f980-a4b4-11e9-82f7-e809c8cc3812.jpg" width="215"><br><br>

## 리서치 제보, 현황, 삭제, 리셋
<img src="https://user-images.githubusercontent.com/24535854/61105457-edab3600-a4b4-11e9-86cf-23a691fdf1a3.jpg" width="350"><br><br>

## 전부 리셋
<img src="https://user-images.githubusercontent.com/24535854/61105463-eedc6300-a4b4-11e9-9fd8-9f75edd8152c.jpg" width="300"><br><br>
<br><br>
# 레이드 관련이 아닌 정보 명령어
## 포켓몬 도감 검색
<img src="https://user-images.githubusercontent.com/24535854/61105451-ed129f80-a4b4-11e9-8c25-4df2fedd7a53.jpg" width="350"><br><br>
## 특정 타입 정보
<img src="https://user-images.githubusercontent.com/24535854/61105465-eedc6300-a4b4-11e9-9c65-3dbfe9bbf8e2.jpg" width="350"><br><br>
## 리서치 검색
<img src="https://user-images.githubusercontent.com/24535854/61105455-ed129f80-a4b4-11e9-82e0-2353637cb121.jpg" width="350"><br><br>
## 이벤트, 커뮤데이 정보
<img src="https://user-images.githubusercontent.com/24535854/61105462-ee43cc80-a4b4-11e9-9b09-5655c4603529.jpg" width="350"><br><br>
## 둥지
<img src="https://user-images.githubusercontent.com/24535854/61108662-e2a8d380-a4bd-11e9-944b-72b24fcd72dc.jpg" width="350"><br><br>

# 그 외
## 방 관련 정보
<img src="https://user-images.githubusercontent.com/24535854/61105466-eedc6300-a4b4-11e9-8adb-8513e9e4f469.jpg" width="350"><br><br>
## 사용방법
<img src="https://user-images.githubusercontent.com/24535854/61105464-eedc6300-a4b4-11e9-96d9-11038f7d70eb.jpg" width="350"><br><br>
## EX나눔, 현황, 완료
<img src="https://user-images.githubusercontent.com/24535854/61105434-dff5b080-a4b4-11e9-8829-6900eccf8a77.jpg" width="350"><br><br>
## 잡다 기능
<img src="https://user-images.githubusercontent.com/24535854/61105459-edab3600-a4b4-11e9-9f68-a8f801e8862b.jpg" width="350"><br><br>


# 기본적인 업데이트 방법
리서치, 레이드 정보 등이 바뀜에 따라, 업데이트가 필요할겁니다.<br>
DoriDB 안에 텍스트파일의 이름을 보시고 대충 바꾸시면 될겁니다.<br>
ex1) 리서치를 바꿔야 한다 -> research____.txt<br>
ex2) 이벤트 정보를 업데이트 해야한다 -> event.txt<br>

# 내역
- 2018.09.03 봇 생성 (레이드 제보봇)<br>
- 2018.09.03 아무말 추가<br>
- 2018.10.02 레이드 팟 기능 추가<br>
- 2018.10.15 도감 추가<br>
- 2018.10.15 트레이너코드 추가<br>
- 2018.12.27 둥지 정보 추가<br>
- 2018.02.05 위치 크롤 시작<br>
- 그 외 버그들 추가<br>
- 2019.06.05 공개용 리포 생성<br>