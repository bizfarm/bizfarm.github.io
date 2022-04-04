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

시스템 운영을 하다 보면 테스트 DB에 입력 후 단위 테스트와 통합 테스트를 진행하고, 해당 정보를 다시 운영 서버에 반영하게 됩니다.

동일한 DBMS이거나 1~2개 테이블만 복제/동기화한다면, 시중에 잘 알려진 복제 툴을 사용해도 괜찮습니다. 그러나 시스템이 복잡해지고 규모가 커질수록 여러 종류의 DB와 Table을 사용하는데, 특정 데이터만 동기화하고 싶다면 단순한 복제 툴로는 해결하기 어렵습니다.

<div align="center">
  <img src="assets/img/portfolio/EDS_1.png" width="80%">
</div>

복잡한 시스템의 경우 하나의 기준을 설정하기 위해 84개의 테이블에 접근하여 800 Row에 가까운 Insert가 이루어집니다. 사람이 화면에서 하나씩 넣다 보면 4~6시간이 걸리기도 합니다.

Easy Data Sync는 Source DB에서 기준 정보를 추출하여 Target DB로 자동 복제하며, 결과에 대한 모니터링 기능을 제공하여 쉽게 확인하고 관리할 수 있습니다.

## 기능

<div align="center">
  <img src="assets/img/portfolio/EDS_2.png" width="80%">
</div>

<div align="center">
  <img src="assets/img/portfolio/EDS_3.png" width="80%">
</div>

## 시연 영상

<div class="video-container">
<iframe width="730" height="511" src="https://www.youtube.com/embed/KCeKnnNfFuQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

{:.list-inline}
- Date: Jul 2019 - Oct 2019
- Client: SKTelecom
- Category: Database, RPA
