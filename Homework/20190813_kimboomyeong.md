----
## what is Database?
see [Wikipedia](https://ko.wikipedia.org/wiki/Markdown)

> 여러 사람이 공유하고 사용할 목적으로 통합 관리되는 *정보의 집합*. 논리적으로 연관된 하나 이상의 자료의 모음으로 그 내용을 고도로 구조화함으로써 검색과 갱신의 *효율화* 를 꾀한 것이다.  
> 즉, 몇 개의 자료 파일을 조직적으로 통합하여 자료 항목의 중복을 없애고 자료를 구조화하여 기억시켜 놓은 *자료의 집합체* 라고 할 수 있다.
----
## 데이터베이스의 장점
1. 일관성, 무결성, 보안성 유지.
2. 데이터의 논리적, 물리적 독립성.
3. 데이터 중복 최소화

----

## 데이터베이스의 단점
1. 데이터베이스 전문가 필요.
2. 대용량 디스크로 엑세스가 집중되면 과부하 발생.
3. 데이터 백업과 복구가 어려움

----

## 데이터베이스 자료구조
# 인덱싱
> 데이터베이스는 흔히 다음과 같은 ACID 규칙을 만족해야 한다. 


**strong**

* 원자성
* 일관성
* 격리성
* 내구성 

----
## 트랜잭션
> 하나의 논리적 단위를 구성하는 데이터베이스 연산의 모임


* 동시성제어 모듈(concurreny control module): 데이터베이스를 일관성 있게 유지하기 위하여 동시에 수행되는 트랜잭션들 사이의 상호작용을 제어한다.
* 회복제어 모듈(recovery control module): 데이터베이스를 일관성 있게 유지하기 위하여 업데이트를 하는 동안 시스템 장애에도 데이터베이스의 기존 상태가 유지된다.

----
## 트랜잭션 스케줄링
> 하나의 논리적 단위를 구성하는 데이터베이스 연산의 모임


* 직렬 스케줄링(serial scheduling): 트랜잭션 연산들을 각 트랜잭션별로 연속적으로 실행하는 방법
* 비직렬 스케줄링(nonserial scheduling): 트랜잭션 연산들을 상호적으로 병행 실행하는 방법
* 직렬 가능 스케줄링(serializable scheduling): 비직렬 스케줄링 S가 항상 직렬 스케줄링 SS에 대해서 같은 결과를 가질 때 "S를 직렬가능"하다고 한다

----
## thanks
* [markdown-js](https://github.com/evilstreak/markdown-js)