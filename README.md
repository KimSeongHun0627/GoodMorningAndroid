# GoodMorningAndroid
## 개요

특정시간대에 밝기가 일정이상인 경우 알람을 울리는 어플리케이션

## 사용목적

밤에 불을 키고 자는 일을 방지하기 위함

## 주 기능

1.알람

2.알람 시간 설정

3.알람 간격 설정

4.알람음 설정

5.알람 요일 설정

6.화면상에 출력할 메시지 설정

7.알람을 울릴 밝기 정도 설정

## 화면 구성


### 메인 화면

1.새 알람 추가

2.알람 리스트

#### 새 알람 추가/ 작성된 알람 클릭시

1. 알람 시간 설정

2. 알람 간격 설정

3. 알람 요일 설정

4. 알람음 설정

5.화면상에 출력할 메시지 설정

6.알람을 울릴 밝기 정도 설정

7.알람 활성/비활성화

## 필요한 기술

### android api

#### 1.alarm

https://developer.android.com/develop/background-work/services/alarms/schedule?hl=ko#java

#### 2.빛 감지

https://developer.android.com/develop/sensors-and-location/sensors/sensors_environment?hl=ko&_gl=1*1jolfme*_up*MQ..*_ga*MTQ5OTA4NTg4My4xNzA4Njg3ODY4*_ga_6HH9YJMN9M*MTcwODY4Nzg2Ny4xLjAuMTcwODY4Nzg2Ny4wLjAuMA..

https://source.android.com/docs/core/interaction/sensors/sensor-types?hl=ko

### 알람 데이터 저장

id integer NotNull AutoIncrement

월요일 Monday integer

화요일 Tuesday integer

수요일 Wednesday integer

목요일 Thursday integer

금요일 Friday integer

토요일 Saturday integer

일요일 Sunday integer

간격 Interval integer

시작 시간 startTime integer NotNull

마지막 시간 endTime integer NotNull

알람음 alarmSound BLOB NotNull

메시지 message text

밝기 brightness integer NotNull

활성화/비활성화 activation integer







