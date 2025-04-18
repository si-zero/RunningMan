## 기획배경

최근 들어, MZ세대에서 성행하고 있는 러닝이라는 취미에서 아이디어를 얻었습니다.

자신이 달리고 싶은 장소에 정보를 얻기 위해서는 다양한 포털 사이트를 통해 날씨, 인원 정보를 따로따로 검색해야 하는데요. 이를 간소화하고 더욱 빠르게 접근하기 위해 해당 정보들을 통합하여 사용자에게 빠르게 정보를 제공하고 싶어 기획하게 되었습니다.

‘러닝’ 이라는 좋은 취미를 더욱 재밌고 즐겁게 즐길 수 있는 앱을 만들고 싶어서 제작하게 되었습니다. 감사합니다.

---

---

---

> 기능 ( * 우선 순위 높음 )
> 

1. 회원 정보 관리
    1. 로그인 및 회원가입 : 데이터베이스에 데이터 저장
        1. 아이디, 비번, 이메일 인증, 주민번호 등 서버에 저장

1. 러닝 장소 추천
    1. 장소 날씨 및 인원 정보 실시간 갱신
        1. 날씨 정보 API
        2. 앱 사용자 위치 정보 수집 및 갱신
        3. 나이키런 같은 인원 정보 수립
        4. 구글 맵, 네이버 지도와 같은 기타 지도 API 사용

1. 러닝 크루 채팅방
    1. 실시간 크루
        1. 오픈채팅 형식
        2. 인기순 / 최신순과 같은 정렬 기준

1. 러닝 랭킹
    1. 지역별, 거리별과 같은 정렬 기준 활용하여 표시
        1. 서버 데이터베이스를 통해 데이터를 불러와서 정렬하여 가공하고 표시
    2. 일정 주기마다 초기화
        1. 서버 데이터는 남겨두되, 새롭게 갱신만 진행
        2. 일정 순위 이하 데이터는 제거
    3. 순위권 보상 시스템
        1. 미정

> 우선 순위 낮음
> 
1. 프로필 * 시간 남으면
    1. 테마, 프로필, 관련 제품

---

> UI
> 
1. 러닝 장소
    1. 인원 혼잡도 : 게이지 바
