# EXP-MISSION-Netflix
HTML과 CSS를 이용하여 넷플릭스 메인화면 클론 만들기 실습.

- 실습에서 사용된 이미지는 넷플릭스 메인 페이지 개발자도구 또는 캡처에서 가져왔습니다. (캡처에서 가져온 부분은 TOP 10 로고)
<br>

1. 프로젝트 구성
- HTML 시멘틱 요소 header, nav, section, footer를 활용하였습니다.
- 헤더 태그에는 넷플릭스 로고, 기타 목록, 검색 돋보기 아이콘, 알림 아이콘, 프로필로 구성했습니다.
- 섹션은 크게 2개로 메인 배너와 설명 등이 들어있는 섹션, 추천 콘텐츠 영화 리스트를 보여주는 섹션으로 구성했습니다.
- 추천 콘텐츠는 예시로 2개의 영화 리스트로 두었고 위에서 말한 크게 나눈 섹션의 한 개인 영화 리스트 섹션입니다. (섹션은 리스트 별로 구분지어서 리스트는 2개의 섹션으로 관리하였습니다.)

<br>

2. 스타일
- 스타일은 크게 4개로 구분하여 진행했습니다. 이는 시멘틱 요소를 구성하고 해당 요소에 필요로 하는 구성요소를 먼저 계획하고 HTML 코드를 작성하였습니다.
- 배너 스타일은 hero class로 설정하였고 배너의 크기, 배너가 사용하는 화면의 구성을 중심으로 설정하였습니다.
- header 스타일로 위 목록을 구성하였고 nav 스타일로 홈, 시리즈, 영화 등 목록 스타일링 하였습니다.
- 영화 리스트는 recommend-section으로 추천하는 영화 리스트 row를 나누었고 thumbnail-list로 영화 목록을 flex로 정렬하여 나열했습니다.
- 리스트 속 영화 이미지는 thumbnail-item으로 관리하였고 각 이미지들은 img라는 이름으로 설정하였습니다. 이미지의 경우 hover 기능을 차질없이 사용하기 위해 container롤 묶어서 관리했습니다.
- footer는 영화 리스트 아래의 기타 설정을 넷플릭스 화면을 참고하여 스타일링 하였습니다.

<br>

3. 기능
- 프로젝트의 기능 중 가장 신경을 많이 쓴 기능은 영화 리스트의 영화 아이템에 마우스를 올려두었을 때 확대되는 기능(hover)을 중심적으로 구성했습니다.

<br>

4. 느낀점
- HTML은 많이 사용해봐서 시멘틱요소 구성, 리스트 등의 구성은 어렵지 않았지만 스타일링(CSS)은 개인적으로 많이 약한 부분이 있었는데 물론 지금 현재도 능숙하게 다루지는 못하지만 클론을 만드는 실습으로 스타일링의 걱정을 많이 줄인 것 같아서 부담감은 크지 않은 상태로 실습하였습니다. 다만 배너의 크기 각 요소들의 위치의 경우하는 하나 하나 설정해보며 위치를 잡았기 때문에 시간이 오래걸렸습니다. 이번 실습에서 가장 힘들었던 부분은 영화 리스트의 hover에서 기능이 리스트 레이아웃 내에서 이미지 사이즈가 커지고, 각 아이템들이 위치를 잡지 않아 호버될 경우 앞으로 당겨지는 등의 기능에서 정상적으로 작동되지 않아서 그 버그를 잡는 부분이 힘들었습니다. 끝내 버그를 수정하고 정상작동하는 부분에서 성취감을 느꼈습니다. 하지만 '이게 왜 되는 거지?' 하는 의문을 갖는 코드가 몇 군데 있었기 때문에 완벽하게 이해하는 작업을 가지는 것이 필요하다고 생각들었습니다.

<br>
# 완성 화면
<img width="1511" alt="Image" src="https://github.com/user-attachments/assets/564c7620-7323-45ad-8a18-5caf356c5187" />
