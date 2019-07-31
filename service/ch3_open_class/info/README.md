# 사용자단 - 클래스 개요 (클래스 개설 1단계)

> 모두의 트레이닝 [실제 서비스 화면](www.modooclass.net/class/user/class_creat)
>
> [디자인화면 - 링크필요]() 



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


3. 정보 입출력 화면 (클래스 기본 정보)

   - 클래스명 (필수)

     > 50byte, 특수문자 제한

   - 클래스 짧은 이름 (필수)

     > 12byte 제한, 특수문자 제한

   - 클래스 커버 이미지 (필수)

     > iOS 카메라 촬영 후 업로드시, 이미지가 회전이 되는 현상 발생으로 load-image.all.min.js 사용.

   - 클래스 한 줄 소개 (필수)

     > 60byte 제한
    


4. 정보 입출력 화면 (클래스 상세 정보)

   - 상세 내용 (필수)

     > Quill.js 사용.<br />
     > Quill.js Editor 툴바 옵션: bold, sub, blockquote, list-order, list-bullet, clean, link, image upload, link to video, font-size<br />
     > iOS 카메라 촬영 후 업로드시, 이미지가 회전이 되는 현상 발생으로 load-image.all.min.js 사용.

   - 클래스 이미지 (최대 10개, 1장 이상 필수)

     > iOS 카메라 촬영 후 업로드시, 이미지가 회전이 되는 현상 발생으로 load-image.all.min.js 사용.


5. 정보 입출력 화면 (부가정보)

   - 클래스 타입 (필수)

     > 클래스 타입 또는 1:1타입<br />
     > 1:1타입 선택시, [클래스 커리큘럼](www.modooclass.net/class/user/class_curriculum) 단계는 생략된다.

   - 클래스 카테고리 (필수)

     > 기타 사항 선택시 직접 입력을 받을 수 있다.

   - 클래스 상세 카테고리 (필수)

     > 보다 상세한 카테고리 입력<br />
     > 12byte 제한

   - 클래스 난이도 (필수)

     > 입문자, 중급자, 상급자 택 1

   - 클래스 추천대상 (최대 4개, 1개 이상 필수)

   - 검색용 태그 (최대 4개, 1개 이상 필수)



6. 하단

    - [미리보기](www.modooclass.net/class/user/preview), [다음](www.modooclass.net/class/user/class_curriculum)<br />
    - 클래스 타입에서 1:1선택시 [다음](www.modooclass.net/class/user/class_package)



7. 푸터

    - Web

      > [이용약관](www.modooclass.net/app/customer/agreement), [개인정보취급방침](www.modooclass.net/app/customer/policy), [FAQ](www.modooclass.net/modoo/faq), 사업자정보<br />
      > 소셜정보: [페이스북](www.facebook.com/modooclass/), [인스타그램](https://www.instagram.com/modooclass/), [유튜브](https://www.youtube.com/channel/UCQ9WEzhuxE4UR69Ku4kQVSA), [블로그](https://blog.naver.com/enfit), 카카오톡 상담

    - App

      > hide


8. 사이드 스크롤 픽스 메뉴

    - Web: 카카오톡 상담 버튼, move ScollTop 버튼<br />
    - App: hide




### **#디자인**

- [디자인 이미지 링크 (최근 업데이트 이미지) - 링크필요]()

- `@김보라`  코멘트

  > 디자이너의 코멘트



### #개선사항

- [ ] 



### **#작업자**

- 기획 - `@김대형` `@신민수`
- 디자인 - `@김보라`
- 서버 API - `@안지환`
- 프론트개발 - `@박정희`  + `@노육민`
