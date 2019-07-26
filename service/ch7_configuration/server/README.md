# 서버

## 개요
> 모두의 트레이닝, 모두의 클래스 서비스 위한 서버 사항

## 핵심목표
> 100만명이 서비스 받아도 원활한 서비스가 가능해야한다.

## Content
### 서비스별 서버 구성
> 웹서버 : 홈페이지 (www.modooclass.net)
> 웹서버 : modooclass APP API (api2.enfit.net)
> 웹서버 : CMS, modootraining APP API  (cms.enfit.net/user, api.enfit.net)
> DB서버: modootraining APP, modooclass APP, tracking DATA
> Sendbird: https://sendbird.com/solutions/chat-for-online-communities
: modootraining Chat(예정), modooclass Chat(예정)
> Firebase: https://console.firebase.google.com/
: RealtimeDatabase(사용자 활동추적,앱/웹 동기화,Sendbird Chat 도입전 테스트)

## 개선사항
> 이미지 최적화
> 이미지 CDN
> 웹서버 로드밸런싱
> DB서버 로드밸런싱

## 작업자
> @안지환
