# be04-1st-IamDeveloper-WLOP
## Team Members
김재현, 백동현, 서승엽, 이드보라, 윤재은, 조수빈

![WLOP LOGO](https://github.com/beyond-sw-camp/be04-1st-IamDeveloper-WLOP/assets/71023617/3d064349-0410-4504-b1cc-0c0855986f81)

# 1. 프로젝트 기획서

<img src="https://github.com/beyond-sw-camp/be04-1st-IamDeveloper-WLOP/assets/71023617/1b14eb7e-4587-4c7d-a44d-259119c3bb79" alt="시장조사"  width="600" height="400"/>

**💫프로젝트 개요**

    - 한국인 4명 가운데 1명이 반려동물을 키우는 반려인구 1500만 시대가 열렸다고 한다. 이에따라 반려동물
    시장도 성장하고 있는데, 한국농촌경제연구원에 따르면, 2015년 1조9천억원 규모였던 국내 반려동물 시장이
    올해는 23년에는 4조5786억원에 이르고, 2027년에는 6조원 규모까지 성장할것으로 보고있다.
    - 주변에 반려동물과 함께 갈수있는 식당이나, 숙박업소 그리고 반려동물들을 위한 병원까지 하나씩 지도에서 
    찾기에는 너무 귀찮고 어려울 수 있겠다는 생각에 반려동물과 함께 할수있는 장소들에 대한 정보를 제공하고,
    게시판을 통해 반려동물들을 자랑하고, 정보를 공유하는등의 활동을 할 수 있는 커뮤니티 서비스를 제공한다.

**🐶프로젝트 소개**

     - 우리의 커뮤니티 서비스인 WLOP(we love our pet)은 반려인구가 늘어나는 현대사회에서 하나의 가족으로
     자리잡고 있는 반려동물들과 함께 할 수 있는 병원, 식당, 카페, 숙박업소에 대한 정보를 한눈에 볼 수 있게
     제공하고, 함께 리뷰와 댓글도 남기며 같은 반려인들 끼리 정보도 나누고 무료로 물품도 나눌  수 있는 기능을 제공한다.
     - 우리의 서비스를 통해 많은 반려인들이 하나되고, 즐거운 시간을 보내며 크게는 반려동물에 대한 인식이 좋아짐에 따라
     더 많은 장소를 우리의 반려동물들과 함께 할 수 있는 사회를 만드는데 기여하고자 한다.
----------------------------------------------------------------    
# 2. 업무 흐름도
<img src="https://github.com/Bodrami/SWcamp_BORA/assets/149561287/11d7752c-df69-418b-8705-628bee1cedc3" alt="업무흐름도" width="900" height="600"/>

-----------------------------
# 3. 요구사항
  ## 사용자 요구사항 분석
<details>
  <summary>정보게시판</summary>
    <li> 소개글
    
    - 소개글 작성(중요도:상, 난이도: 상)
    - 소개글 수정(중요도:하, 난이도: 하)
    - 소개글 삭제(중요도:하, 난이도: 하)

   <li> 리뷰
    
    - 리뷰 작성(중요도:상, 난이도: 상)
    - 리뷰 수정(중요도:하, 난이도: 하)
    - 리뷰 삭제(중요도:하, 난이도: 하)
    
   <li>댓글
    
    - 댓글 작성(중요도:하, 난이도: 하)
    - 댓글 수정(중요도:하, 난이도: 하)
    - 댓글 삭제(중요도:하, 난이도: 하)
   
   <li> 추천
       
    - 리뷰 추천(중요도:중, 난이도: 하)
    - 리뷰 추천 취소(중요도:하, 난이도: 상)
   
   <li> 신고

    - 신고 작성(중요도:중, 난이도: 하)
    - 신고 철회(중요도:하, 난이도: 하)
</details>

<details>
  <summary>자유게시판</summary>
  <li> 게시글
    
    - 게시물 작성(중요도:중, 난이도: 상)
    - 게시물 수정(중요도:하, 난이도: 하)
    - 게시물 삭제 (중요도:하, 난이도: 하)
    - 게시글 조회(조회수 반영)(중요도:하, 난이도: 상)
  <li> 댓글
  
    - 댓글 작성(중요도:하, 난이도: 하)
    - 댓글 수정(중요도:하, 난이도: 하)
    - 댓글 삭제(중요도:하, 난이도: 하)
    
  <li> 추천
    
    - 게시글 추천(중요도:하, 난이도: 하)
    - 추천 취소(중요도:하, 난이도: 상)
    
  <li> 신고
  
    - 신고 작성(중요도:중, 난이도: 하)
    - 신고 철회(중요도:하, 난이도: 하)
</details>

<details>
  <summary>공지게시판</summary>
  <li> 공지 작성(중요도:중, 난이도: 하)
  <li> 공지 수정(중요도:하, 난이도: 하)
  <li> 공지 삭제(중요도:하, 난이도: 하)
</details>

<details>
  <summary>문의게시판</summary>
 <li> 문의게시물 작성(중요도:하, 난이도: 하)
 <li> 문의게시물 수정(중요도:하, 난이도: 하)
 <li> 문의게시물 삭제(중요도:하, 난이도: 하)
 <li> 문의 답변(중요도:하, 난이도: 중)
</details>

<details>
  <summary>무료나눔게시판</summary>
 <li> 나눔게시글
     
    - 나눔게시글 작성(중요도:중, 난이도: 상)
    - 나눔게시글 수정(중요도:하, 난이도: 하)
    - 나눔게시글 삭제(중요도:하, 난이도: 하)
  <li> 댓글
    
    - 댓글 작성(중요도:하, 난이도: 하)
    - 댓글 수정(중요도:하, 난이도: 하)
    - 댓글 삭제(중요도:하, 난이도: 하)
</details>

<details>
  <summary>회원</summary>
 <li> 회원가입(중요도:상, 난이도: 하)
 <li> 회원탈퇴(중요도:상, 난이도: 상)
 <li> 로그인(중요도:중, 난이도: 하)
 <li> 로그아웃(중요도:중, 난이도: 하)
 <li> 마이페이지
     
    - 회원정보 조회(중요도:하, 난이도: 하)
    - 회원정보 수정(중요도:하, 난이도: 하)
    - 회원등급 조회(중요도:하, 난이도: 하)
    - 작성 게시물 조회(중요도:하, 난이도: 중)
    - 작성 댓글 조회(중요도:하, 난이도: 중)
    - 문의내역 조회(중요도:하, 난이도: 하)
    - 신고내역 조회(중요도:하, 난이도: 하)
    - 사업자 등록(중요도:하, 난이도: 하)
<li> 프로필
    
    - 내소개내용 작성(중요도:하, 난이도: 하)
    - 내소개내용 수정(중요도:하, 난이도: 하)
    - 내소개내용 삭제(중요도:하, 난이도: 하)
    - 내사진 추가(중요도:하, 난이도:상 )
    - 내사진 수정(중요도:하, 난이도: 하)
    - 내사진 삭제(중요도:하, 난이도: 하)
<li> 반려동물 프로필
    
    - 반려동물 프로필 작성(중요도:하, 난이도: 상)
    - 반려동물 프로필 수정(중요도:하, 난이도: 하)
    - 반려동물 프로필 삭제(중요도:하, 난이도: 하)
<li> 휴면회원
    
    - 정상회원 복구(중요도:하, 난이도: 상)
</details>

<details>
  <summary>관리자</summary>
<li> 문의내역 처리(중요도:하, 난이도: 하)
<li> 신고내역 처리(중요도:하, 난이도: 하)
<li> 블랙리스트 처리(중요도:하, 난이도: )
<li> 다이아몬드 회원 등업(중요도:중, 난이도: 하)
<li> 공지 관리(중요도:하, 난이도: 하)
</details>

  
  ## 요구사항 명세서
  <img src="https://github.com/dongh810/Beyond_SW_Camp_Study/assets/105986200/1da4106f-bd5e-4c63-a4d2-1849846c5678" alt="요구사항 명세서 이미지" width="900" height="400"/>
  
---------------------------
# 4. 프로젝트 모델링
  ## 프로젝트 설계 내역
<details>
  <summary>ERD(개념논리모델)</summary>
<img src="https://github.com/beyond-sw-camp/be04-1st-IamDeveloper-WLOP/assets/149561287/85f03e9a-f583-4cf3-813b-1a4f6bc4805b" alt="개념논리 모델" width="900" height="400"/>
</details>

  ## 프로젝트 구현 내역
<details>
  <summary>바커표기법(물리모델)</summary>
<img src="https://github.com/Bodrami/SWcamp_BORA/assets/149561287/40e16618-8f71-4669-accf-0c720a625277" alt="개념논리모델" width="900" height="400"/>
</details>

-----------------------------
# 5. 테스트 진행
  ## 테스트 진행 영상 첨부 
   <li> 회원가입
  
  ## 테스트케이스 정의서
  <img src="https://github.com/beyond-sw-camp/be04-1st-IamDeveloper-WLOP/assets/71023617/45d1389e-baf9-48e6-b68d-937f8bc52a6b" alt="테스트케이스 이미지" width="900" height="400"/>


----------------------------
# 6. 시스템 아키텍처
<img src="https://github.com/Bodrami/SWcamp_BORA/assets/149561287/4ee64be1-d5ec-49eb-859d-25d7b4ed988f" alt="시스템 아키텍처" width="900" height="600"/>

---------------------------
# 7. WBS  
<img src="https://github.com/beyond-sw-camp/be04-1st-IamDeveloper-WLOP/assets/71023617/f30549aa-b5cb-4875-8106-a3c999af8f50" alt="WBS" width="900" height="600"/>

---------------------------
# 8. 회의록 및 개인 회고
## 주제선정 및 필요한 테이블 의견 모으기(23/12/29)

<img src="https://github.com/Bodrami/SWcamp_BORA/assets/149561287/d7a13d5e-f167-4ac3-a67e-67e8634e6efd" alt="회의사진" width="300" height="300"/>

> <li> 회의 내용: 단위 프로젝트 주제구상 및 관련 테이블 정보를 모으고 회의를 통해 의견을 나누어봄
> <li> 오늘 해낸것: 주제 선정, ERDcloud 논리모델 구상하기(PK,FK 생각하면서 연결)
> <li> 이슈: 회의를 통해 각자 생각했던 주제에 대해 의견을 나누고 그 중에서 가장 사회적으로 이슈가 되고 있는반려동물을 위한 커뮤니티로 주제를 선정하였음.

## 개념•논리모델 테이블 수정 및 추가(24/01/02)

<img src="https://github.com/Bodrami/SWcamp_BORA/assets/149561287/c1befe5a-d4d5-4d12-8d9c-5e57c15dd55e" alt="회의 사진" width="300" height="400"/>

> <li> 회의 내용: 개념 논리 모델을 수정하고 추가할 테이블이나 컬럼에 대해 의견을 나누며 수정작업 진행함.
> <li> 오늘 해낸것: ERDcloud 수정 및 삭제, 업무흐름도
> <li> 이슈:  금일 각 팀이 준비한 ERD로 개념 및 물리모델 발표가 있어 우리조의 모델의 피드백을 받을 수 있었고 다른팀의 피드백과 아이디어를 통해 ERD를 좀 더 구체화하여 수정할 수 있었음.

## 바커표기법으로 변경 및 문서화작업(24/01/03)

> <li> 회의 내용: ERDcluod에서 모델링한 것을 기반으로 DA#을 사용하여 바커표기법으로 변경하고 프로젝트 기획서(업무흐름도) 및 요구사항 명세서&정의서 작성을 진행했음.
> <li> 오늘 해낸것: 바커 표기법으로 논리모델링 수정, 프로젝트 기획서 작성, 업무흐름도
> <li> 이슈: 바커 표기법으로 진행하면서 테이블 연결의 문제점을 발견할 수 있었고 이를 수정하는 과정에서 테이블 수정 및 추가가 진행되었고 문서화 작업를 통해 프로젝트의 흐름과 진행과정을 정리할 수 있었음.

## 물리모델, 데이터 insert 및 테스트케이스 진행 및 문서화 작업(24/01/05)
> <li> 회의 내용: 3 정규화를 통해 물리모델로 수정하고 테스트케이스를 정하고, 마무리 하지 못한 문서화 작업을 이어서 진행함.
> <li> 오늘 해낸것: 물리모델, 데이터베이스쌓기, 테스트케이스 나누기
> <li> 이슈: 물리모델을 하면서 수정사항이 생겨나면서 한 테이블씩 확인하며 NOTNULL&NULL값을 정확하게 넣고 insert절을 사용해 데이터를 쌓았음. 또 강사님의 피드백을 통해 블랙리스트 처리를 신고마다 관리자가 확인하는 처리결과에수 5번 신고를 받으면 관리자가 확인 후 처리하는 결과로 나올 수 있게 수정함.

## 프로젝트관련 문서 수정 및 프로젝트 산출물 확인(24/01/08)
> <li> 회의 내용: 프로젝트 관련하여 필수 산출물을 문서화하여 github ReadMe에 업로드하며 정리함. 각자 맡은 테스트 케이스 영상으로 만들어 구현한 ReadMe 기능관련해 업로드.
> <li> 오늘 해낸것: DB모델링 마무리, 필수 산출물들 내용 정리하고 GITHUB README에 업로드
> <li> 이슈: 트리거, 인덱스 관련 쿼리문 작동될 수 있도록 수정함.

## 단위 프로젝트 마무리 개인 회고
<li> 회고록

    - 김재현:
    - 백동현:
    - 서승엽:
    - 이드보라:
    - 윤재은:
    - 조수빈:
    
