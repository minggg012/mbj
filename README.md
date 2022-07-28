# MinByeongJae
> 2022 여름 몰입캠프 2분반 박병현 김민 정재모
- 미니언즈와 함께 지휘해요 ~! ^_______^


## A. 개발 팀원
- DGIST 기초학부 [박병현](http://github.com/ByeongHyunPak)
- KAIST 전산학부 [김민](http://github.com/minggg012)
- KAIST 전산학부 [정재모](http://github.com/Jaemojung)

## B. 개발 환경
> html, css, javascript
> 
> tensorflow.js posenet

## C. 프로젝트 설명
### 1. Loading Page
<img width="1512" alt="start" src="https://user-images.githubusercontent.com/85171279/181438278-aadbb13a-a55d-4fa6-b18f-73260e8b8bad.png">

#### Major Features
- 직접 만든 로고가 gif 형식으로 띄워져 있다.
- 접속하는 동안 로딩 중이라는 문구가 뜨고, 로딩이 완료되면 START 버튼을 눌러 다음 페이지로 넘어갈 수 있다.


--------------------------------------


### 2. File Register Page
<img width="1512" alt="register" src="https://user-images.githubusercontent.com/85171279/181438370-2d6a98ee-cee9-43c0-9e77-f958435f38ba.png">

#### Major Features
- 원하는 영상을 형식에 맞춰 직접 넣을 수 있다.
- 지휘하는 동안 뜰 제목을 직접 입력하여 넣을 수 있다.
- 넣고 싶은 영상이 없거나 원하는 영상을 넣었다면 START 버튼을 눌러 다음 페이지로 넘어갈 수 있다.


-------------------------------


### 3. Main Page
<img width="1512" alt="main1" src="https://user-images.githubusercontent.com/85171279/181438397-3f7a7dfd-b4cf-4714-92b6-fd4b83a7fbba.png">

#### Major Features
- 노트북에 달린 카메라를 이용하여 사용자의 얼굴, 몸통, 팔을 인식한다.
- 지휘자가 인식되면 곡이 시작된다.
- 지휘 방법은 다음과 같다.
  - 팔의 높낮이에 따라 노래의 크기가 변하고, 화면에 나타난다.
  - 팔의 움직임의 빠르기에 따라 노래의 템포가 변하고, 화면에 나타난다.
  - 팔을 오른쪽에서 왼쪽으로 빠르게 한 번 움직이면 이전 곡으로, 왼쪽에서 오른쪽으로 빠르게 한 번 움직이면 다음 곡으로 넘어갈 수 있다.
- restart 버튼을 눌러 다시 시작할 수 있다.

#### Implementation Methods
-

--------------------------------------------------


### 4. Ending Page
<img width="1512" alt="ending" src="https://user-images.githubusercontent.com/85171279/181440186-25003484-499b-4485-b032-26a8d662a675.jpg">

#### Major Features
- 노래 지휘가 끝나면 엔딩 페이지가 나온다.
- play again 버튼을 눌러 다시 시작할 수 있다.
