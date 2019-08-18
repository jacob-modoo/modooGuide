

# ALALYSIS

`화면단과 기능별 핵심 지표 분석`

#### **노하우** 를 배우고 나누는 클래스 마켓 

#### 하고싶은 일을 좋아하는 사람들과 함께하세요.
#### ~언제 어디서나 함께 하는 즐거움~ 

> 모클은 다음세대에 대한 일과 사람간의 관계를 재정의 합니다. 
>
> "하고싶은 일을 좋아하는 사람들과 함께하세요."    
> 우리는 `사람과 + 기술` 에 대한 고민으로 위 문제를 해결해 나갑니다.  





## **개 요**

>  **모두의 클래스**는 누구나 코치(선생님)가 될 수 있는 온라인 클래스 플랫폼(웹/앱) 서비스로 
>  새로운 일의 형태 | 사람과 사람의 연결에 가치를 두고 있다. 


###  1장. 사용자단  `web`

모두의 클래스의 얼굴 - 3전략 (보다 싸게, 많은 클래스, 최적화된 클래스 찾아주는 것. )
해당 장의 유저 목표는 기분 좋은 클래스 경험과 전환율을 높이는 것이다.

**핵심지표 : 전환율(결제/알림/신청)**

- [홈화면](service/ch1_home)  => [`web`](https://www.modooclass.net/) 

- [검색단](service/ch1_home/search) => [`web`](https://www.modooclass.net/class/search)  

- [로그인](service/ch1_home/login)   =>   [`web`](https://www.modooclass.net/modoo/login)

- [상세 (알림|1:1코칭|무료|선결제|환급|일반)](service/ch1_home/detail)   =>  [`web`](https://www.modooclass.net/class/classDetail/483)

- [패키지](service/ch1_home/package)   =>  [`web`](https://www.modooclass.net/class/pay/package/488)

- [결제화면](service/ch1_home/pay)   =>  [`web`](https://www.modooclass.net/class/pay/payinfo/488/214)

- [결제완료](service/ch1_home/confirm)   =>   [`web`](https://www.modooclass.net/class/group/436)

- [알림지페이지](service/ch1_home/alram)   =>  [`web`](https://www.modooclass.net/class/confirm/alarm/646/member/140019?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJodHRwczpcL1wvYXBpLmVuZml0Lm5ldFwvYXBpXC92M1wvb3BlbmNhbGxcLzY0NiIsImlhdCI6MTU2MjcxNDczNSwiZXhwIjoxNTYzOTI0MzM1LCJuYmYiOjE1NjI3MTQ3MzUsImp0aSI6IlY4cUZlNVdUZVppbk9YYzYiLCJzdWIiOjE0MDAxOSwicHJ2IjoiOTYyYTE0ZDQ4YzQyOWUzYTZhYWIzNjEwYzAzNTJiZmJiNDVlZmM1OCJ9.42H7yjucquFfqHzDn5Xoo_Rf9qqEs16Oa50c3iO0T-g)

- [초대장](service/ch1_home/detail_invitation.md)  =>  `web` (링크 달아줘야해요. `@김혜진`이 화면 링크를 달아주실수 있나요?)

- [추가개선 : QA 문서](service/ch1_home/upgrade)

- [사용자단 - configuration ](service/ch1_home/config)



###  2장. 마이페이지  `web` 

마이페이지에서 참여/운영/관심 있는 클래스 및 이웃과의 허브 역활을 한다.   

가장 많이 이용하는 지점을 찾아 유저가 다른 클래스 | 회원과 연결점을 잘 찾을 수 있게 하는 것이 목표.  
(해당페이지의 이탈율 최소가 페이지의 목표)  

**핵심지표 : 이동페이지경로 및 이탈율**

- [마이페이지(클래스)](service/ch2_my_class)  => [`web`](https://www.modooclass.net/class/user/mypage) 

- [팔로워/팔로윙](service/ch2_my_class/follow)  => [`web`](https://www.modooclass.net/class/user/following/140019) 

- [친구페이지](service/ch2_my_class/friend) => [`web`](https://www.modooclass.net/class/user/friend_profile/138568)

- [프로필수정](service/ch2_my_class/edit)  => [`web`](https://www.modooclass.net/class/user/following/140019) 

- [포인트내역 | 결제내역](service/ch2_my_class/point) => [`web`](https://www.modooclass.net/class/user/point) [`web`](https://www.modooclass.net/class/user/payment) 

- [내가남긴리뷰](service/ch2_my_class/review) => [`web`](https://www.modooclass.net/class/user/review) 

- [정산(기획 미완료)](service/ch2_my_class/accounts) => [`web`](https://www.modooclass.net/class/user/following/140019) 

- [공지사항 | 이벤트 | 문의하기 | 자주묻는질문](service/ch2_my_class/board) => [`web`](https://www.modooclass.net/class/user/following/140019) 

- [이용약관 | 개인정보처리방침](service/ch2_my_class/notice) => [`web`](https://www.modooclass.net/class/user/following/140019) 

- [추가개선 :  QA문서](service/ch2_my_class/upgrade)

- [마이페이지 - configuration](service/ch2_my_class/config)

  
  
  

###  3장. 클래스 개설  `web`

누구나 코치가 될 수 있도록 한다. 코치가이드 화면을 거쳐 쉽게 영상 업로드후 정보 입력 하면 수익화 할 수 있는 클래스를 가질 수 있는 사용성에 초점을 두고 개발한다. 

쉽고 편한 사용성 중심의  UI/UX 에 기반한 단계를 줄이거나 정보입력에 빠져들게 한다. 

**핵심지표 : 페이지 이탈율**

- [코치가이드](service/ch3_open_class/) => [`web`](https://www.modooclass.net/class/center) 
- [코치정보입력](service/ch3_open_class/coach) => [`web`](https://www.modooclass.net/class/user/coach_propose) 
- [클래스개요](service/ch3_open_class/info) => [`web`](https://www.modooclass.net/class/user/class_create) 
- [커리큘럼](service/ch3_open_class/curriculum) => [`web`](https://www.modooclass.net/class/user/class_curriculum) 
- [패키지정보](service/ch3_open_class/package) => [`web`](https://www.modooclass.net/class/user/class_package) 
- [알림정보](service/ch3_open_class/alram) => [`web`](https://www.modooclass.net/class/user/class_complete) 
- [정산정보]=> `web`ㅣ [`xd작업파일`](https://drive.google.com/file/d/1VWz6TPJ8OQfcsPJJlW0humVNY2EoA55Z/view?usp=sharing) [`preview link`](https://xd.adobe.com/spec/e3c529c2-4fd2-4f43-4a29-f5e5b723e65c-95f4/) -> 기획문서 생성부탁드려요! `@김대형`
- [추가개선 :  QA문서](service/ch3_open_class/upgrade)
- [클래스개설 - configuration](service/ch3_open_class/config)


###  4장. 클래스 관리  `web`

클래스 관리는 코치(선생님)쓰는 화면으로 최소한의 리소스로 많은 회원들을 관리 할 수 있는가? 쉬운 커뮤니티 관리에 집중한다. 추가적으로 코치에게 회원들이 주는 응원과 격려를 통한 지속가능한 에너지를 갖도록 만드는 UI/UX를 고려한다. 

적은 리소스로 커뮤니티 운영 + 회원의 응권과 격려를 받을 수 있는  UI/UX

**핵심지표 : 리텐션 (페이지 머무르는 시간, 재방문 횟수)**

- [클래스 관리 리스트](service/ch4_manage_class/) => [`web`](https://www.modooclass.net/class/manager/list) 

- [커뮤니티](service/ch4_manage_class/community) => [`web`](https://www.modooclass.net/class/manager/course/468/community) 

- [커리큘럼](service/ch4_manage_class/curriculum) => [`web`](https://www.modooclass.net/class/manager/course/468/curriculum) 

- [리뷰](service/ch4_manage_class/review) => [`web`](https://www.modooclass.net/class/manager/course/468/review) 

- [수강생](service/ch4_manage_class/member) => [`web`](https://www.modooclass.net/class/manager/course/468/attendee) 

- [수익](service/ch4_manage_class/curriculum/profit) => [`web`](https://www.modooclass.net/class/user/following/140019) [`xd작업파일`](https://drive.google.com/open?id=1IUoOJ3roo3wUhXRmvJGRm07KUyLRdQIl) [`preview link`](https://xd.adobe.com/spec/777b7762-cc4a-4ab0-7925-bd6ec53676f4-014a/) -> 기획문서 생성부탁드려요! `@김대형`
- [추가개선 :  QA문서](service/ch4_manage_class/upgrade)

- [클래스관리 - configuration](service/ch4_manage_class/config)


###  5장. 클래스 참여  `app`

모두의 클래스 앱으로 수업에 참여

사용자 참여(클래스 완강율)를 주요 관점으로 보고, 이를 위해 사용자들끼리의 네트워크를 통한 리텐션을 높이도록 한다. 

**핵심지표 : 리텐션 (클래스별 완강율, 일/주간 앱내 머무르는 시간, 재방문율, 재결제율)**

- [홈](service/ch5_join_class/) => [`app down`](https://www.modooclass.net/class/user/following/140019) 

- [클래스(수업)](service/ch5_join_class/class) => [`app down`](https://www.modooclass.net/class/user/following/140019) 

- [클래스(커리큘럼)](service/ch5_join_class/curriculum) => [`app down`](https://www.modooclass.net/class/user/following/140019) 

- [클래스(응원하기)](service/ch5_join_class/cheer) => [`app down`](https://www.modooclass.net/class/user/following/140019) 

- [클래스(커뮤니티)](service/ch5_join_class/community) => [`app down`](https://www.modooclass.net/class/user/following/140019) 

- [채팅](service/ch5_join_class/chat) => [`app down`](https://www.modooclass.net/class/user/following/140019) 

- [알림](service/ch5_join_class/alram) => [`app down`](https://www.modooclass.net/class/user/following/140019) 플랫폼(웹/앱) 서비스로 
  새로운 일을 형태 | 사람과 사람의 연결에 가치를 두고 있다. 

  해당 문서는 내부 가이드 문서로서 팀원간 원활한 소통과 서비스 정책을 공유 하기 위함.

  총 5개의 섹터로 구성

- [프로필](service/ch5_join_class/profile) => [`app down`](https://www.modooclass.net/class/user/following/140019) 

- [추가개선 :  QA 문서](service/ch5_join_class/upgrade)

- [클래스참여 - configuration](service/ch5_join_class/config)



### 6장. CMS 최종 관리자단  `web`

고객관리 센터 화면 : 환불 정산등을 효율적으로 처리 할 수 있도록 한다. 

- [회원관리](service/ch6_admin_cms/members) => [`web`](https://www.modooclass.net/class/user/following/140019) 

- [코치관리](service/ch6_admin_cms/coachs) => [`web`](https://www.modooclass.net/class/user/following/140019) 

- [클래스 관리](service/ch6_admin_cms/class) => [`web`](https://www.modooclass.net/class/user/following/140019) 랫폼(웹/앱) 서비스로 
  새로운 일을 형태 | 사람과 사람의 연결에 가치를 두고 있다. 

  해당 문서는 내부 가이드 문서로서 팀원간 원활한 소통과 서비스 정책을 공유 하기 위함.

  총 5개의 섹터로 구성

- [결제관리](service/ch6_admin_cms/payments) => [`web`](https://www.modooclass.net/class/user/following/140019) 

- [카테고리 및 배너 제어](service/ch6_admin_cms/etc) => [`web`](https://www.modooclass.net/class/user/following/140019) 

- [추가개선 :  QA문서](service/ch6_admin_cms/upgrade)

- [CMS - configuration](service/ch6_admin_cms/config)


###  7장. Configuration  `git-text`git

- [서버구성](service/ch7_configuration/server)

- [DB구성](service/ch7_configuration/db)

- [Config (status, level, etc...)](service/ch7_configuration/config)




## **#5.ANALYSIS**

- 









![](assets/image/logo1024.png)

-----------------------------------------------------------------------------------------------------------------------------------

