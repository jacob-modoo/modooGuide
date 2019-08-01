

# 메세지단 개발

`목적`

#### 사용자간 원할한 인스턴트 메세지 남기기. 

> 예외 사항이 있는 사용자 없이 모든 사용자의    
> 커뮤니 케이션이 가능 하도록 만든다. 

## 기능

>  1. 메세지
>  2. 이모티콘
>  3. 다른 채팅방으로의 이동
>  4. 채팅방 푸쉬 알림 안받기. 
>  5. 참여중인 사용자 보기.
>  6. 이미지 보내기 기능.
>  7. ~공지 사항 띠우기. 기능~

> 당일(오전/오후 시간 | 일자)

[프로젝트 링크](https://github.com/jacob-modoo/modooGuide/projects/8#column-6058247)

1차버전 업데이트후 디벨롭 예정. 

푸쉬알림에 따른 해당 메세지 단으로 이동 추가. 

## App Part
### 앱 푸시 타입
업데이트 일시 : _2019_07_31_

작성자 : @이대준

> Foreground
```
0 : 알림리스트 클릭 - [웹뷰]웹앱
1 : 알림리스트 클릭 - [클래스상세]해당 클래스내 수업 (class_id)
2 : 알림리스트 클릭 - [커뮤니티]해당 클래스내 커뮤니티 (class_id)
3 : 알림리스트 클릭 - [댓글]댓글의 댓글 혹은 좋아요. (comment_id)
4 : 알림리스트 클릭 - [친구프로필]친구앱 프로필 (friend_id)
5 : 알림리스트 클릭 - [홈-bottomMenu]
6 : 알림리스트 클릭 - [프로필-bottomMenu]
7 : 알림리스트 클릭 - [알림-bottomMenu]
8 : 알림리스트 클릭 - [메세지-bottomMenu]
```

> Background
```
0 : 디바이스 알림 클릭 - [웹뷰]메인화면 - 웹앱
1 : 디바이스 알림 클릭 - [클래스상세]해당 클래스내 수업 (class_id)
2 : 디바이스 알림 클릭 - [커뮤니티]해당 클래스내 커뮤니티 (class_id)
3 : 디바이스 알림 클릭 - [댓글]댓글의 댓글 혹은 좋아요. (comment_id)
4 : 디바이스 알림 클릭 - [친구프로필]친구앱 프로필 (friend_id)
5 : 디바이스 알림 클릭 - [알림-bottomMenu]알림리스트
6 : 디바이스 알림 클릭 - [나의프로필-bottomMenu]
7 : 디바이스 알림 클릭 - [알림-bottomMenu]
8 : 디바이스 알림 클릭 - [웹뷰]메인화면 - 웹앱
```

### 앱 처리 사항 
(@이대준,@조현민)

> 0. CHAT 메뉴 클릭시, 앱에서 스크립트 호출 ( 새로고침 활용목적 : AppActive(); )
> 1. 회원 프로필 (앱)에서 "메세지 보내기" 아이콘 클릭시 웹뷰(new) "https://chat.modooclass.net/class/chat/유저아이디" 주소
> 창 닫을 경우, 해당 창만 닫음
> 2. push_type 8 : 새로운 메세지 알림, 클릭시 웹뷰(new) 주소는 push_url 정의 "https://chat.modooclass.net/class/chat/활성대화방ID"
````comment
# 채팅화면에서는 푸쉬 메세지(CHAT내용에 한함) 동작안함
# 활성대화방ID는 친구프로필에서 메세지보내기 아이콘 터치시 "친구ID"로 설정되며,
 그룹대화방인경우 "G그룹ID"로 설정됨
````

> 앱 브리지

Chat 상세 화면 이동
```
ios : webkit.messageHandlers.goToChatDetail.postMessage('room_id')
android : window.android.goToChatDetail(String room_id)
```

외부 브라우저 호출
```
ios :
android : window.android.outLinkForBrowser(String url)

```

## 작업자

@김대형 @신민소 @김혜진 @안지환. 
