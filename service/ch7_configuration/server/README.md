# 서버

## 개요
> 모두의 트레이닝, 모두의 클래스 서비스 위한 서버 사항

## 핵심목표
> 100만명이 서비스 받아도 원활한 서비스가 가능해야한다.

## Content
### 서비스별 서버 구성

> 웹서버 : 홈페이지 (www.modooclass.net)
- 175.207.13.181
> 웹서버 : modooclass APP API (api2.enfit.net)
- 175.207.13.159
> 웹서버 : CMS, modootraining APP API  (cms.enfit.net/user, api.enfit.net)
- 175.207.13.154
> DB서버: modootraining APP, modooclass APP, tracking DATA
- 175.207.13.154 (175.207.13.159/175.207.13.181)
> Redis
```redis
Redis는 데이터베이스의 여러 솔루션 중 하나로 메모리를 사용하는 키, 밸류 형식의 데이터베이스이다. Redis의 최고 장점은 메모리를 사용하기 때문에 매우 빠른 속도를 자랑한다. 일반적인 하드 디스크에 비하여 상대적으로 엄청나게 빠를수도 있다. 다만 메모리라는 제약으로 공간이 크지 않고 키, 밸류(Key, Value) 형식의 입출력 방식이기에 복잡한 데이터베이스에 적합하지 않다.
```
- 175.207.13.154
- Queue 데이터
- JWT 데이터
> Sendbird: https://sendbird.com/solutions/chat-for-online-communities

: modootraining Chat - Push
: modooclass Chat

> Firebase: https://console.firebase.google.com/

: RealtimeDatabase(사용자 활동추적,앱/웹 동기화,Sendbird Chat 도입전 테스트)

## 개선사항

> [이미지 최적화](image_optimize)

> [이미지 CDN](cdn)

> [웹서버 로드밸런싱](load_balancing)

> [DB서버 로드밸런싱](load_balancing)

## 작업자
> @안지환
