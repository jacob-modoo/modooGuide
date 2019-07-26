# DB 시스템 구성

## 로드밸런싱 MySQL Replication

> Write : Master
> Read : Slave1, Slave2

154 (Master) -> 159 (Slave1), 181 (Slave2)

> Master - 전체 데이터
> Slave1 - modootraining 데이터, modooclass 데이터
> Slave2 - modooclass 데이터

CMS.ENFIT.NET (+ 모두의트레이닝앱 API)
> write Master, read Slave1 와 연결
모두의클래스 API 
> write Master, read Master, Slave1, Slave2와 연결
