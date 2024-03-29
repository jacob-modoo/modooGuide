# 사용자단 - 코치 정보 입력 (코치 신청)

> 모두의 트레이닝 [실제 서비스 화면](www.modooclass.net/class/user/coach_propose)
>
> [Preview link *update 7.31](https://xd.adobe.com/spec/3f1e59d5-a1e2-4f77-41ee-1fc2fd40c535-492f/)   



- 이전      
- [**전체인덱스**](../README.md)     
- [다음 : ?]()



### **#목적**

1. 클래스 개설 희망 사용자로부터 정보를 입력받는다.



### #핵심지표

- 복잡한 UI를 지양하며, 누구나 쉽게 접근할 수 있는 방향을 지향한다.



### **#구성 - #기능**
```App: WebView```

1. 헤더 

   - 뒤로가기 버튼

     > Web: 이전 페이지로 이동<br />
     > App: 화면 닫기 (나가기)

   - 로고

     > Web: 모클 메인 이동<br />
     > App: 앱 메인 이동

   - 프로필 이미지

     > Web: 마이페이지 이동<br />
     > App: 앱 마이페이지 화면 이동


2. 가이드

   - 누구나 무료로 자신만의 클래스를 개설할 수 있습니다!


3. 정보 입출력 화면 (기본 정보)

   - 프로필 사진 (필수)

     > 코치 프로필 이미지 업로드 기능<br />
     > iOS 카메라 촬영 후 업로드시, 이미지가 회전이 되는 현상 발생으로 load-image.all.min.js 사용.

   - 닉네임 (필수)

     > 16byte 제한, 특수문자 허용 
     
   - 연락처 또는 카카오톡 아이디 (택 1 필수)

     > 연락처를 입력받는다.<br />
     > 연락처 입력시, 휴대폰 인증절차가 있다.<br />
     > SNS 카카오톡 로그인시 닉네임값을 자동으로 불러온다.<br />
     > 해외거주자 여부에 따라 연락처 또는 카카오톡 아이디를 입력할 수 있다.


4. 정보 입출력 화면 (자기 소개)

   - 자기 소개 (필수)

     > 클래스 개설 희망 사용자의 디테일한 자기 소개 입력단<br />
     > Quill.js 사용.<br />
     > Quill.js Editor 툴바 옵션: bold, sub, blockquote, list-order, list-bullet, clean, link, image upload, link to video<br />
     > iOS 카메라 촬영 후 업로드시, 이미지가 회전이 되는 현상 발생으로 load-image.all.min.js 사용.

   - 인터뷰 (최소 3개 필수)

     > 인터뷰 질문은 최소 3개를 선택하여 답변한다.<br />
     > 인터뷰 질문은 DB에서 지정하여 SelectBox로 사용자에게 보여준다.<br />
     > iOS 카메라 촬영 후 업로드시, 이미지가 회전이 되는 현상 발생으로 load-image.all.min.js 사용.


5. 정보 입출력 화면 (클래스 소개 및 채널 정보)

   - 클래스 소개 (필수)

     > 사용자로부터 오픈하고 싶은 자신의 클래스의 정보를 입력받는다.<br />
     > Quill.js 사용. (추후 툴바 옵션 기능을 사용할 것으로 예상되어 사용)<br />
     > Quill.js Editor 툴바 옵션: 없음.

   - 콘텐츠 채널 정보 (선택사항)

     > 사용자로부터 SNS 채널 정보를 입력받는다.<br />
     > 또한, 그 주소가 맞는지 '연결확인' 버튼으로 확인할 수 있도록 도와준다.<br />
     > 입력요청: 페이스북, 유튜브, 인스타그램


6. 푸터

    - Web

      > [이용약관](www.modooclass.net/app/customer/agreement), [개인정보취급방침](www.modooclass.net/app/customer/policy), [FAQ](www.modooclass.net/modoo/faq), 사업자정보<br />
      > 소셜정보: [페이스북](www.facebook.com/modooclass/), [인스타그램](https://www.instagram.com/modooclass/), [유튜브](https://www.youtube.com/channel/UCQ9WEzhuxE4UR69Ku4kQVSA), [블로그](https://blog.naver.com/enfit), 카카오톡 상담

    - App

      > hide


7. 사이드 스크롤 픽스 메뉴

    - Web: 카카오톡 상담 버튼, move ScollTop 버튼<br />
    - App: hide



<br>

### #디자인

- [Preview link *update 7.31](https://xd.adobe.com/spec/3f1e59d5-a1e2-4f77-41ee-1fc2fd40c535-492f/)   
- [XD file *update 7.31](https://drive.google.com/open?id=1RxOXHqS-x4QbSlbaZwZfrFDhRzEqU-E7)
- `@김보라`  코멘트 : 발송인에 따라 초대장 타입이 다름*초대 정책 확인 요청 `@김대형`

  

<br>


### #개선사항

- [ ] 기술 개선 작업 필요 (속도 및 화면 전환 등의 사유)
- [x] 푸터 소셜 정보 재정리 필요 - 유효하지 않은 링크 연결 존재



### **#작업자**

- 기획 - `@김대형` `@신민수`
- 디자인 - `@김보라`
- 서버 API - `@안지환`
- 프론트개발 - `@박정희`  + `@노육민`
