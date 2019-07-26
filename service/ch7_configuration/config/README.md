# config

## 영상 저장

> 미디서버 https://midibus.kinxcdn.com/login

## Server : web - 181

> PHP Version 7.3.6
> ubuntu 16.04.1
> mysql 8.0.16 (Slave2)

## Server : cms, api (모두의 트레이닝) - 154
> PHP Version 7.3.6
> ubuntu 16.04.1
> mysql 5.7.26 (Master)

## Server : file, api (모두의 클래스) - 159
> PHP Version 7.3.6
> ubuntu 16.04.1
> mysql 8.0.16 (Slave1)

## Master -> Slave (/etc/mysql/mysql.conf.d/mysqld.cnf)
```config
replicate-do-db = fitDb
replicate_ignore-db = fitDb_test
replicate-ignore-table = fitDb.jobs
replicate-ignore-table = fitDb.stat_repay
replicate-ignore-table = fitDb.failed_jobs
replicate-ignore-table = fitDb.meal_group
replicate-ignore-table = fitDb.user_activity_status
replicate-ignore-table = fitDb.messages_group
replicate-ignore-table = fitDb.exercises_group
#replicate-ignore-table = fitDb.trace_team
replicate-ignore-table = fitDb.stat_actrecord
#slave-skip-errors = 1062, 1032, 1050, 1054, 1061, 13146, 1060
slave-skip-errors = All
```
