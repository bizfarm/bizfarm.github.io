---
caption:
  title: Easy Data Sync
  subtitle: Database 동기화
  thumbnail: assets/img/portfolio/eds_thumbnail.jpg

title: Easy Data Sync
subtitle: Database Migration & Synchronization
image: assets/img/portfolio/eds_thumbnail.jpg
alt: Easy Data Sync
---

## Description

시스템을 운영하다보면 테스트 DB에 반영하고 단위테스트와 통합테스트를 진행하고 변경한 데이타를 운영기에  반영해는 경우가 많습니다. 동일한 DBMS이거나 한 두개 정도의 테이블만 복제/동기화 해야한다면 시중에 잘 알려진 복제 툴을 사용해도 문제가 아닐 것입니다. 허나 시스템이 방대해지면서 여러 종류의 DB와 Table을 사용해야하고 특정 데이타만 동기화 하고 싶다면 단순한 복제 툴로 해결하기 어려워 집니다.

<div align="center">
  <img src="assets/img/portfolio/EDS_1.png" width="80%">
</div>

실제로 하나의 기준을 설정하기 위해 84개의 테이블에 접근하고 800Row에 가까운 Insert가 이루어집니다. 화면을 통해 기준을 넣다보면 4~6시간이 소요됩니다.


## 기능

<div align="center">
  <img src="assets/img/portfolio/EDS_2.png" width="80%">
</div>

>   1) 모니터링
>> - OBJECT(상품/할인) 기준으로 정의된 Table의 데이타를 조회
>> - 각 테이블별로 조회된 Souce DB / Target DB 결과값이 다른 경우 표시
>> - 'NOT EXISTS' Row의 경우 해당 DB에는 존재하지 않는 값
>> - 2개 이상의 Table을 참조하여 결과를 추출하는 경우 다른 Table의 결과값이 영향 줄 수 있음
>> - Data 검증 시 비교하는 Column에서 제외하려면 [Table] 우클릭 > 'Column Setting'

>   2) 데이타 동기화
>> - 오처리를 방지하기 위해 데이타 동기화를 단방향으로만 가능하도록 설정가능 (Source -> Target)
>> - 데이타 동기화 시 Object가 Table에 직접적으로 포함되어 있는 경우 먼저 처리
>> - 2개 이상의 Table을 참조하는 경우는 Object를 직접적으로 포함하고 있는 Table 선처리 후 처리

>    3) 순환 SQL
>> - 정해진 Cycle에 따라 반복적으로 SQL을 수행
>> - 결과값을 SMS/MMS으로 전송

## 시연 영상

<div class="video-container">
<iframe width="730" height="511" src="https://www.youtube.com/embed/KCeKnnNfFuQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

{:.list-inline}

- Date: Jul 2019 - Oct 2019
- Client: SKTelecom
- Category: Database, RPA
