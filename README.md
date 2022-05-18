# Happy House Vue 관통 프로젝트

## 정찬우 이연의

## 구현 기능 

### 0. 메인페이지
    - HappyHouse Project 메인페이지입니다.
![Main](/uploads/466c5dc96cf6272a8377ca7940ab3e5e/Main.png)

#### 0-1. Summary
    - HappyHouse Project에서 제공하는 기능을 확인할 수 있습니다.
![MainSummary](/uploads/1d4ceae14cb28ce96375563671eb20bd/MainSummary.png)

#### 0-2. DirectMove
    - 가시성이 높은 버튼을 통하여 HappyHouse가 제공하는 서비스로 바로 이동할 수 있습니다.
    - 현재 Parking Area Service는 구현중입니다.
![MainDirectMove](/uploads/f4f5994878f5613a2a49662a38bfc9a9/MainDirectMove.png)

### 1. QnA 게시판

#### 1-1. QnA 게시판 List출력
    - DataBase에 저장된 QnA 게시글을 출력 합니다.
![QnaList](/uploads/f3ecc8ad01be6b8d006430d65f3ce4fb/QnaList.png)

#### 1-2. QnA 게시판 글 작성
    - [글쓰기] 버튼을 통해 QnA를 작성할 수 있습니다.
    - 작성이 완료된 QnA를 DataBase에 저장합니다.
    - 작성이 완료된 QnA를 List에서 확인할 수 있습니다.
![QnaWrite](/uploads/71c6cb5c2d0da13c035895470240e4c9/QnaWrite.png)
![QnaAfterWrite](/uploads/a294c9d702e641bd2a9356fb7244a151/QnaAfterWrite.png)

#### 1-3. QnA 게시판 글 상세보기
    - 게시글 항목을 선택하여 상세내용을 확인할 수 있습니다.
![QnaDetail](/uploads/032a91a1784ee80199f07c7870cc0774/QnaDetail.png)

#### 1-4. QnA 게시판 글 수정
    - [글수정] 버튼을 통해 QnA를 수정할 수 있습니다.
    - 수정이 완료된 QnA를 DataBase에 저장합니다.
    - 수정이 완료된 QnA를 List에서 확인할 수 있습니다.
![QnaModify](/uploads/c68e6ba4604b04b0a9b1ee69fdc2d7fa/QnaModify.png)
![QnaAfterModify](/uploads/82d6bcbd06eb89f7df9f8358c822b91b/QnaAfterModify.png)

#### 1-5. QnA 게시판 글 삭제
    - [글삭제] 버튼을 통해 QnA를 삭제할 수 있습니다.
    - 삭제가 완료되면, DataBase를 갱신합니다.
    - 삭제가 완료된 QnA는 List에서 출력되지 않습니다.
![QnaDelete](/uploads/4039ad1be6198ced58ae9f31cb6d3fea/QnaDelete.png)
![QnaAfterDelete](/uploads/c06e1c6908a609d6e52f19a5a09604fa/QnaAfterDelete.png)

### 2. 로그인/회원가입 & 회원정보

#### 2-1. 회원가입
    - 회원가입 form 작성 후, [SUBMIT] 버튼을 통해 회원가입을 할 수 있습니다.
    - [RESET] 버튼을 통해 회원가입 form을 초기화 할 수 있습니다.
![회원가입](/img/2-0.png)

#### 2-2. 로그인
    - 아이디와 비밀번호로 로그인을 할 수 있습니다.
![로그인](/img/2-1.png)

#### 2-3. 회원정보 조회
    - [Profile] 메뉴를 통해 로그인할 사용자의 정보를 확인할 수 있습니다.
    - [EDIT] 버튼을 통해 회원정보 수정화면으로 전환할 수 있습니다.
![회원정보 조회](/img/2-2.png)

#### 2-4. 회원정보 수정
    - 아이디를 제외한 항목에 한해 회원정보를 수정할 수 있습니다.
    - 비밀번호 form 오른쪽의 [변경]버튼을 통해 비밀번호 변경을 위한 모달창을 띄울 수 있습니다.
![회원정보 수정](/img/2-3.png)

#### 2-5. 비밀번호 변경
    - 비밀번호 변경을 위한 모달창입니다.
    - 현재 비밀번호와 새 비밀번호를 입력받아 현재 비밀번호가 일치할 경우 비밀번호를 변경할 수 있습니다.
![비밀번호  변경](/img/2-4.png)

#### 2-6. 비밀번호 찾기
    - 로그인 페이지의 [FORGET PASSWORD] 버튼을 통해 비밀번호 찾기을 위한 모달창을 띄울 수 있습니다.
    - 아이디를 통해 비밀번호를 찾을 수 있습니다.
![비밀번호  찾기](/img/2-5.png)

### 3. 아파트 매매가 조회 서비스
    - 메인페이지의 [Nav-Bar]-[House]를 통해 아파트 매매가 조회 서비스를 이용할 수 있습니다.
    - 현재 조회되는 아파트가 없는경우, 조회 내용이 없음을 알립니다.
    - 조회된 아파트를 선택한경우, 해당 아파트의 상세 정보를 확인할 수 있습니다.
![HouseNoSearch](/uploads/1f2daf94053471bc8d4776aed838e02f/HouseNoSearch.png)
![HouseSearch](/uploads/ff9132ca54f8f2ae23866b09b866adf9/HouseSearch.png)

