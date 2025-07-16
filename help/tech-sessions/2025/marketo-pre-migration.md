---
title: Adobe Admin Console으로 Marketo 마이그레이션 - (마이그레이션 전)
description: Adobe은 향상된 사용자 관리를 위해 Marketo Engage을 Admin Console으로 마이그레이션하고 있습니다. 자동 및 자가 마이그레이션 유형, 사전 요구 사항, 마이그레이션 후 변경 사항, 모범 사례, 일반적인 위험 요소 및 지원에 대해 알아봅니다. Adobe의 Experience League 웹 사이트에서 세션 녹화에 액세스합니다.
solution: Marketo Engage
role: Admin, Developer, Leader, User
level: Beginner, Intermediate, Experienced
doc-type: Event
duration: 2280
last-substantial-update: 2025-03-14T00:00:00Z
jira: KT-17483
exl-id: 9c3da83f-9e02-4a2e-9784-10213facf056
source-git-commit: 088615f28aa91dfd4ba119c11c4c9f8a89441d84
workflow-type: tm+mt
source-wordcount: '417'
ht-degree: 0%

---

# Adobe Admin Console으로의 Marketo 마이그레이션 - 사전 마이그레이션

Adobe 전문가와 함께 원활한 Marketo 마이그레이션에 참여하십시오!

이 유용한 웨비나에서 Adobe의 Customer Experience &amp; Identity 팀과 함께 Marketo 마이그레이션을 시작하십시오. Adobe Admin Console으로의 원활한 전환을 보장하기 위한 주요 단계, 모범 사례 및 일반적인 과제를 소개합니다.

배울 내용,

* 마이그레이션 전 프로세스를 위한 단계별 로드맵
* 전환을 단순화하고 위험을 방지하는 우수 사례
* 일반적인 마이그레이션 문제에 대한 전문가의 답변

마이그레이션을 시작하든 마지막 단계를 준비하든 상관없이 이 세션에서는 프로세스를 안심하고 탐색할 수 있는 지식과 도구를 제공합니다. 앞서서 Marketo 마이그레이션을 원활하게 수행할 수 있는 이번 기회를 놓치지 마십시오!

>[!VIDEO](https://video.tv.adobe.com/v/3449712/?learn=on&enablevpops)

## 주요 개선 사항

### 마이그레이션 목적 및 개요

Adobe은 향상된 사용자 관리 및 액세스를 위해 모든 제품을 하나의 허브로 통합하기 위해 Marketo Engage을 Admin Console으로 마이그레이션하고 있습니다.  Admin Console은 Adobe 제품, 사용자 역할, 권한 및 지원 액세스를 관리하기 위한 중앙 허브 역할을 합니다. Marketo Engage에 액세스하기 위한 URL이 Adobe의 Experience Cloud 플랫폼으로 변경됩니다.

### 마이그레이션 유형

* **자동 마이그레이션** 사용자 수가 75명 미만이고 SSL 설정이 없는 조직의 경우. Adobe이 마이그레이션을 처리합니다.
* SSL을 설정한 조직의 경우 **자체 마이그레이션**. 관리자는 마이그레이션 콘솔을 사용하여 마이그레이션 프로세스를 관리합니다.

### 마이그레이션 사전 요구 사항

* 시스템 관리자는 동의 이메일을 작성해야 합니다.
* SSL은 Marketo 인스턴스가 아닌 Admin Console에서 설정해야 합니다.

### 마이그레이션 후 변경 사항

* 사용자는 Adobe ID 또는 SSL(Federated ID)을 사용하여 로그인합니다.
* 관리자 역할 및 권한은 Admin Console의 액세스 수준을 결정합니다.

### 우수 사례

* 마이그레이션 전에 사용자 이메일을 확인하고 잠긴 계정을 해결하십시오.
* 적절한 관리자 역할이 할당되었는지 확인합니다.
* 로그인 문제를 방지하려면 광고 차단기를 비활성화하거나 시크릿 모드를 사용하십시오.

### 일반적인 함정

* 잘못된 관리자 권한으로 액세스가 제한될 수 있습니다.
* 브라우저 확장 및 광고 차단기가 액세스를 방해할 수 있습니다.
* 화이트리스트에 IP를 추가하는 작업은 Admin Console에서 아직 지원되지 않지만 개발 중입니다.

### 기능에 미치는 영향

* 자동화된 이메일, API 사용자 및 munchkin 코드는 마이그레이션의 영향을 받지 않습니다.
* 마이그레이션은 주로 사용자 인증 및 관리에 영향을 줍니다.

### 지원

* 문제가 발생하는 사용자는 Adobe 고객 지원 센터에서 지원 사례를 여십시오.
* 더 빠른 해결을 위해 지원 사례에 IMS 조직 ID를 포함하십시오.
