# 사용자단 - 클래스 패키지 (클래스 개설 3단계)

> 모두의 트레이닝 [실제 서비스 화면](www.modooclass.net/class/user/class_package)
>
> [Preview link *update 7.31](https://xd.adobe.com/spec/1fb4700d-84a8-4422-7534-b06dd92d64f9-6985/)  



- 이전      
- [**전체인덱스**](../README.md)     
- [다음 : ?]()



### **#목적**

1. 



### #핵심지표

- 



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

   - 호기심을 자극하는 제목을 붙여주세요.
    
     > 클래스명 입력시 자동 변경 처리


3. 정보 입출력 화면 (수강기간 설정)

   - 판매시작일 (필수)

     > 달력 modal로 일자 선택가능

   - 수강기간 (필수)

     > 수강 기간이 몇 일인지 숫자만 입력, 약 몇 주인지 자동 변환 안내



3. 정보 입출력 화면 (패키지 설정, n개 추가 가능)

   - 패키지 이름 (필수)

     > 50byte 제한.

   - 패키지 타입 (필수)

     > 수강권만 판매할건지, 수강권이랑 준비물을 같이 판매할건지 선택.

   - 가격 정보 (필수)

     > 패키지 타입에 따라 수강권 또는 수강권+준비물의 가격 입력
     > 판매가격, 실제 판매가격, 준비물 가격

   - 패키지 구성 정보 (필수)

     > Quill.js 사용.<br />
     > Quill.js Editor 툴바 옵션: bold, sub, blockquote, list-order, list-bullet, clean, image upload, font-size<br />
     > iOS 카메라 촬영 후 업로드시, 이미지가 회전이 되는 현상 발생으로 load-image.all.min.js 사용.



4. 정보 입출력 화면 (준비물 정보)

   - 준비물 안내 (선택)

     > 50byte 제한.
     > Quill.js 사용.<br />
     > Quill.js Editor 툴바 옵션: bold, sub, blockquote, list-order, list-bullet, clean, image upload, font-size<br />
     > iOS 카메라 촬영 후 업로드시, 이미지가 회전이 되는 현상 발생으로 load-image.all.min.js 사용.



5. 정보 입출력 화면 (환급 정보)

   - 환급률 선택 (필수)

     > 기본 패키지 가격이 입력되어 있어야 선택가능.
     > 없음, 10%, 20%, 30%
     > 환급률에 따른 예상 수익 안내



6. 하단

    - [미리보기](www.modooclass.net/class/user/preview), 클래스 오픈 신청<br />
    - 클래 오픈 시청시 [계좌정보](www.modooclass.net/class/user/class_account) 이동 및 활성화



6. 푸터

    - Web

      > [이용약관](www.modooclass.net/app/customer/agreement), [개인정보취급방침](www.modooclass.net/app/customer/policy), [FAQ](www.modooclass.net/modoo/faq), 사업자정보<br />
      > 소셜정보: [페이스북](www.facebook.com/modooclass/), [인스타그램](https://www.instagram.com/modooclass/), [유튜브](https://www.youtube.com/channel/UCQ9WEzhuxE4UR69Ku4kQVSA), [블로그](https://blog.naver.com/enfit), 카카오톡 상담

    - App

      > hide


8. 사이드 스크롤 픽스 메뉴

    - Web: 카카오톡 상담 버튼, move ScollTop 버튼<br />
    - App: hide


<br>

### #디자인

- [Preview link *update 7.31](https://xd.adobe.com/spec/1fb4700d-84a8-4422-7534-b06dd92d64f9-6985/)   
- [XD file *update 7.31](https://drive.google.com/open?id=1LGGAtjVsTVaLOT3Cpa87LOgloo7PCtgH)
- `@김보라`  코멘트 : 발송인에 따라 초대장 타입이 다름*초대 정책 확인 요청 `@김대형`

<br>

### #개선사항

- [ ] 



### **#작업자**

- 기획 - `@김대형` `@신민수`
- 디자인 - `@김보라`
- 서버 API - `@안지환`
- 프론트개발 - `@박정희`  + `@노육민`
