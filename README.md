![header](https://capsule-render.vercel.app/api?type=wave&color=random&height=200&&section=header&text=BANK%20TREE&fontSize=50)

# Team - “김오엄정”

### 엄지영
- 컴퓨터학부 20학번
- Front-End, Leader
- <a href="https://github.com/thumbzzero/" target="_blank"><img src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white"/></a>
<br/> <br/> 
### 오영선
- 컴퓨터학부 20학번
- Back-End
- <a href="https://github.com/oyoungsun/" target="_blank"><img src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white"/></a>
<br/> <br/> 
### 김은정
- 컴퓨터학부 20학번
- Data
- <a href="https://github.com/ezzkimm/" target="_blank"><img src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white"/></a>
<br/> <br/> 
### 정다혜
- 컴퓨터학부 20학번
- Data
- <a href="https://github.com/JeongDaH/" target="_blank"><img src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white"/></a>
<br/> <br/> <br/> 
# 누가 내 발에 똥쌌어?

> **자유세션 - 가로수데이터를 활용하여 은행나무 위치를 표시해 주는 길찾기 지도**
>
![KakaoTalk_Photo_2022-09-25-16-36-01](https://user-images.githubusercontent.com/94179998/192133299-24729711-71ef-4648-a882-54345d2ee7fd.jpeg)

길을 걷다 보면 은행나무를 쉽게 찾을 수 있다. 가을철이 되면 은행나무에는 은행 열매가 열린다. 은행나무는 공해에 강하고 공기 정화 능력이 좋다. 또한 병충해 걱정이 없으며 은행 열매는 식용으로 사용할 수 있어 과거 가로수로 많이 사용되었다.

하지만 은행 열매의 과육에서는 특유의 ~~`똥`~~ 냄새와 비슷한 악취가 발생한다. 이러한 은행 열매를 밟을 경우, 신발에서 나는 악취가 하루 종일 나를 따라다니게 된다.

이동 경로에 은행나무 위치를 미리 알 수 있다면 ~~`똥`~~ 냄새를 피할 수 있지 않을까?

길 찾기 검색을 할 때 동선에 있는 은행나무의 위치를 알려주어 사용자가 이동할 때 은행나무가 없는 도로로 돌아갈 수 있도록 지도를 제공한다. 이를 통해 땅에 떨어진 은행 열매를 피할 수 있고 옆 사람에게 ~~`똥`~~ 냄새를 풍기는 피해를 주는 것을 사전에 예방할 수 있다.
<br/> 
<br/> 

### 주제 :

대구광역시 내 가로수 데이터를 활용하여 이동 동선에 은행나무가 위치한다면 위치를 표시해 주는 길찾기 지도
<br/> 

### 목적 :

이동 경로 위치한 은행나무의 위치를 미리 알고 피해가기
<br/> 

### 기대효과 :

주변인에게 불쾌한 냄새를 풍기는 것을 사전에 방지할 수 있다.

은행나무 위치를 파악하여 관리를 편리하게 할 수 있다.
<br/> 

### 활용방안 :

- 대구 시내 가로수 종류 별 분포도 확인
- 대구 지역 길찾기 Map
<br/> <br/> 

### 차별점 :
보통 맛집 지도나 여행 지도와 같이 특정한 목적을 가지는 지도의 경우 위치만 마킹 되어있다.

하지만, 은행나무 지도의 경우 길찾기 기능을 제공한다.
<br/><br/><br/> 
# 프로젝트에 활용 된 기술

### Front-End

<div align="left">

![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![React](<https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB>) ![SASS](https://img.shields.io/badge/SASS-hotpink.svg?style=for-the-badge&logo=SASS&logoColor=white)

</div>

![KakaoTalk_Photo_2022-09-25-16-52-26](https://user-images.githubusercontent.com/94179998/192133800-1c90d9dd-188a-4da1-9af3-1ed11eb4f882.jpeg)
메인화면에 접속하면 경북대학교로 포커스가 맞춰지고, 대구의 은행나무 거리를 노란색으로 표시됩니다.

![KakaoTalk_Photo_2022-09-25-16-52-30](https://user-images.githubusercontent.com/94179998/192133795-f6bf41c3-b166-442d-b06e-81d8681ac6f8.jpeg)
사용자가 출발/도착 도로명 주소를 입력하면 API를 통해 해당 주소를 위도, 경도 정보로 변환하여 네이버 Map API를 통해 경로 좌표를 받아와 polyline을 표시합니다.



### Back-End

<div align="left">

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white) ![Spring](<https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white>) ![Gradle](https://img.shields.io/badge/Gradle-02303A.svg?style=for-the-badge&logo=Gradle&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)

</div>


<img width="593" alt="KakaoTalk_Photo_2022-09-25-16-42-01" src="https://user-images.githubusercontent.com/94179998/192133486-46600234-7b47-47a9-b6d4-248f587cc521.png">
메인화면에 접속하면 서버에 연결된 jawsDB에 Table을 생성, 가로수데이터를 넣고 은행나무 길(출발 위치-도착 위치)를 반환합니다.


<img width="515" alt="KakaoTalk_Photo_2022-09-25-16-42-05" src="https://user-images.githubusercontent.com/94179998/192133488-f79c8361-375d-45a5-ae7d-eb2223db1013.png">
사용자가 출발/도착 도로명 주소를 입력하면 KAKAO API를 불러와 주소를 매핑하고, API결과와 주소를 반환합니다.






### ETC

<div align="left">

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Pandas](<https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white>) ![GoogleAPI](<https://img.shields.io/badge/google%20API-4285F4?style=for-the-badge&logo=google&logoColor=white>) ![kakaoAPI](<https://img.shields.io/badge/kakao%20API-ffcd00.svg?style=for-the-badge&logo=kakao&logoColor=000000>) ![NAVERAPI](https://img.shields.io/badge/NAVER%20API-2DB400.svg?style=for-the-badge&logo=naver&logoColor=fff)

</div>
