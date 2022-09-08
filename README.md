# Happy House Vue 관통 프로젝트

## 정찬우 이연의

## 구현 기능 

### 0. 메인페이지
    - HappyHouse Project 메인페이지입니다.
    - *그림과 다르게 일부 수정 되었습니다.
![Main](https://user-images.githubusercontent.com/77624879/189170854-d33d2592-36dd-4c5e-b8ac-f63bb97a2d59.png)

#### 0-1. Summary
    - HappyHouse Project에서 제공하는 기능을 확인할 수 있습니다.
![MainSummary](https://user-images.githubusercontent.com/77624879/189170863-e651d7e6-8681-4af1-aa49-1e7a4cdd5f74.png)

#### 0-2. DirectMove
    - 가시성이 높은 버튼을 통하여 HappyHouse가 제공하는 서비스로 바로 이동할 수 있습니다.
    - 현재 Parking Area Service는 구현중입니다.
![MainDirectMove](https://user-images.githubusercontent.com/77624879/189170858-6f59b11f-5c27-472c-b07a-675158a989ab.png)

### 1. QnA 게시판

#### 1-1. QnA 게시판 List출력
    - DataBase에 저장된 QnA 게시글을 출력 합니다.
![QnaList](https://user-images.githubusercontent.com/77624879/189170890-47f1f8fd-7f73-46b1-8096-8f7e082e897c.png)

#### 1-2. QnA 게시판 글 작성
    - [글쓰기] 버튼을 통해 QnA를 작성할 수 있습니다.
    - 작성이 완료된 QnA를 DataBase에 저장합니다.
    - 작성이 완료된 QnA를 List에서 확인할 수 있습니다.
![QnaWrite](https://user-images.githubusercontent.com/77624879/189170897-7d757b2e-e49e-4ed1-abde-081e1bd4af53.png)
![QnaAfterWrite](https://user-images.githubusercontent.com/77624879/189170878-8b3c4aac-8a2a-4e7d-be47-9dc69feb4c93.png)

#### 1-3. QnA 게시판 글 상세보기
    - 게시글 항목을 선택하여 상세내용을 확인할 수 있습니다.
![QnaDetail](https://user-images.githubusercontent.com/77624879/189170885-89b642ca-0a89-4879-a05a-41b228d72790.png)

#### 1-4. QnA 게시판 글 수정
    - [글수정] 버튼을 통해 QnA를 수정할 수 있습니다.
    - 수정이 완료된 QnA를 DataBase에 저장합니다.
    - 수정이 완료된 QnA를 List에서 확인할 수 있습니다.
![QnaModify](https://user-images.githubusercontent.com/77624879/189170894-45fac9f3-7976-4f04-b9ce-8fabc18597d6.png)
![QnaAfterModify](https://user-images.githubusercontent.com/77624879/189170872-a06020b9-6173-41ca-85b9-0aeaa82216aa.png)

#### 1-5. QnA 게시판 글 삭제
    - [글삭제] 버튼을 통해 QnA를 삭제할 수 있습니다.
    - 삭제가 완료되면, DataBase를 갱신합니다.
    - 삭제가 완료된 QnA는 List에서 출력되지 않습니다.
![QnaDelete](https://user-images.githubusercontent.com/77624879/189170879-a0274ade-7e8e-403f-b0de-08d5f426c260.png)
![QnaAfterDelete](https://user-images.githubusercontent.com/77624879/189170867-8f2412ee-cbd1-429d-865e-9548216b4f93.png)

### 2. 공지사항
    - 공지사항은 관리자만 작성할 수 있으며, 공지사항에 댓글 또한 관리자만 삭제가 가능합니다.
    
#### 2-1. 공지사항 게시판 출력
    - DataBase에 저장된 공지사항 게시글을 출력합니다.
![image](https://user-images.githubusercontent.com/77624879/189174729-088f90c5-3d65-4ea3-9f3b-0c4801709e97.png)

#### 2-2. 공지사항 확인, 댓글 입력 및 삭제
    - 공지사항을 확인하고, 댓글 입력/ 자신이 입력한 댓글 삭제가 가능합니다.
![image](https://user-images.githubusercontent.com/77624879/189175103-541df7b8-0d45-47c9-bbd6-de4eb92b1b3d.png)

#### 2-3. 공지사항 글 등록
    - 관리자 계정만 공지사항에 글을 등록할 수 있습니다.
![image](https://user-images.githubusercontent.com/77624879/189175234-ee60abf1-b32f-4474-8272-5efded1dadae.png)

### 3. 로그인/회원가입 & 회원정보

#### 3-1. 회원가입
    - 회원가입 form 작성 후, [SUBMIT] 버튼을 통해 회원가입을 할 수 있습니다.
    - [RESET] 버튼을 통해 회원가입 form을 초기화 할 수 있습니다.
<img width="609" alt="2-0" src="https://user-images.githubusercontent.com/77624879/189170816-6ac878f0-2b51-4776-b9bf-255ddb188d09.png">

#### 3-2. 로그인
    - 아이디와 비밀번호로 로그인을 할 수 있습니다.
![2-1](https://user-images.githubusercontent.com/77624879/189170826-55d6c797-b5ab-4e50-a17b-d07740b22fdb.png)

#### 3-3. 회원정보 조회
    - [Profile] 메뉴를 통해 로그인할 사용자의 정보를 확인할 수 있습니다.
    - [EDIT] 버튼을 통해 회원정보 수정화면으로 전환할 수 있습니다.
![2-2](https://user-images.githubusercontent.com/77624879/189170829-10bdf865-9702-44f6-92e6-69084ac82ff9.png)

#### 3-4. 회원정보 수정
    - 아이디를 제외한 항목에 한해 회원정보를 수정할 수 있습니다.
    - 비밀번호 form 오른쪽의 [변경]버튼을 통해 비밀번호 변경을 위한 모달창을 띄울 수 있습니다.
<img width="578" alt="2-3" src="https://user-images.githubusercontent.com/77624879/189170831-1d9d552e-64da-44b4-b6b3-e631550cb39d.png">

#### 3-5. 비밀번호 변경
    - 비밀번호 변경을 위한 모달창입니다.
    - 현재 비밀번호와 새 비밀번호를 입력받아 현재 비밀번호가 일치할 경우 비밀번호를 변경할 수 있습니다.
<img width="497" alt="2-4" src="https://user-images.githubusercontent.com/77624879/189170837-13ba6ad5-ce22-4c74-b9d2-e71d32738d0b.png">

#### 3-6. 비밀번호 찾기
    - 로그인 페이지의 [FORGET PASSWORD] 버튼을 통해 비밀번호 찾기을 위한 모달창을 띄울 수 있습니다.
    - 아이디를 통해 비밀번호를 찾을 수 있습니다.
<img width="481" alt="2-5" src="https://user-images.githubusercontent.com/77624879/189170838-7d45dce8-8991-49a2-8dee-dc9f49030ca6.png">

#### 3-7. 즐겨찾는 매물 조회
    - 마이페이지에서 자신이 즐겨찾기에 추가한 즐겨찾는 매물을 조회할 수 있습니다.
![image](https://user-images.githubusercontent.com/77624879/189174188-14b109cc-c141-4c92-80e3-9ac28fa01acf.png)

### 4. 아파트 매매가 조회 서비스
    - 메인페이지의 [Nav-Bar]-[House]를 통해 아파트 매매가 조회 서비스를 이용할 수 있습니다.
    - 현재 조회되는 아파트가 없는경우, 조회 내용이 없음을 알립니다.
    - 조회된 아파트를 선택한경우, 해당 아파트의 상세 정보를 확인할 수 있습니다.

#### 4-1. 행정동별 아파트 조회
    - 시/도, 구/군, 동/읍/면을 선택하여 해당 지역의 아파트 실거래가를 확인할 수 있습니다.
    - 조회한 아파트를 클릭하여 아파트 실거래가를 확인할 수 있습니다.
![image](https://user-images.githubusercontent.com/77624879/189172932-28f08c56-602d-4e10-8212-9e0575943250.png)
![image](https://user-images.githubusercontent.com/77624879/189172986-fe38c131-1f25-4d07-98be-dd866a73b68f.png)

#### 4-2. 마커 주변 아파트 검색
    - 지도에 원하는 지역을 선택하여 마커를 표기하고, 마커 범위 내의 아파트를 조회하고, 즐겨찾기에 추가할 수 있습니다.
    - 조회한 아파트를 클릭하여 아파트 실거래가를 확인할 수 있습니다.
![image](https://user-images.githubusercontent.com/77624879/189173230-d49c4366-1b0f-4ff5-9903-312a9aeede83.png)
![image](https://user-images.githubusercontent.com/77624879/189173276-8e12d58d-8514-4a83-a333-7f3cdce7f47f.png)

### 5. 주변상권 조회
    - 아파트 실거래가 검색 후, 출력된 리스트의 아이콘을 통해 해당 아파트 주변상권 정보를 조회할 수 있습니다.
![image](https://user-images.githubusercontent.com/77624879/189173410-e93743fc-cd28-4ba5-b1c1-5025240afd83.png)

### 6. 행정동별 주차장 조회
    - 시/도, 구/군, 동/읍/면을 선택하여 해당 지역의 주차장과 주차장 세부정보를 확인할 수 있습니다.
![image](https://user-images.githubusercontent.com/77624879/189173847-9a0f787e-a98e-4da2-9551-a16b87a5c51e.png)
![image](https://user-images.githubusercontent.com/77624879/189173908-871635e4-61a7-4e97-a39f-5ae8083e9132.png)

## ERD
![image](https://user-images.githubusercontent.com/77624879/189175331-f47babce-0e30-4b5b-8d64-4be7d1ee769d.png)

## Class Diagram
![image](https://user-images.githubusercontent.com/77624879/189175746-47d2e8d6-b794-4e66-a8ac-893a1924ed6b.png)
