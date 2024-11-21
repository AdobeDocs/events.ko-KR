---
title: AEM Sites 효율성 - 성능 최적화, 구성 및 문제 해결
description: 이 세션에서는 성능 문제, 복잡한 구성 및 사용자 권한에 대한 실용적인 실습 솔루션에 중점을 둔 Adobe Experience Manager(AEM) Sites의 필수 문제 해결 기술을 다룹니다.
solution: Experience Manager
version: Cloud Service
role: Admin, Developer, Leader, User
level: Intermediate
doc-type: Event
duration: 3452
last-substantial-update: 2024-10-30T00:00:00Z
jira: KT-16353
exl-id: 55f7c1d8-7c2c-4392-894a-2aa9b3cc0e4a
source-git-commit: ef652eb09c33f11d69ec66f70013cd3e53537a95
workflow-type: tm+mt
source-wordcount: '235'
ht-degree: 0%

---

# AEM Sites 효율성: 성능 최적화, 구성 및 문제 해결

이 웨비나에서는 Adobe Experience Manager(AEM) Sites 문제 해결의 필수 사항에 대해 알아봅니다. 성능 문제에 직면하거나 복잡한 구성을 처리하는 경우 이 세션은 AEM 환경을 유지 관리하고 최적화하는 실용적인 기술을 제공합니다. 슬라이드보다는 라이브 데모를 우선시하며 실제 문제를 해결하는 데 실무 경험을 제공합니다&#x200B;.

>[!VIDEO](https://video.tv.adobe.com/v/3435114/?learn=on)

## 주요 사항

웨비나는 성능 최적화, 구성 및 문제 해결 등 AMP 사이트 효율성에 초점을 맞췄습니다.

### Dispatcher 구성

* 성능 좋은 웹 사이트를 제공하는 데 있어 Dispatcher의 중요성.
* Dispatcher 구성의 주요 측면: 가상 호스트 구성, 캐시 구조를 사용한 도메인 매핑, 정기적인 보고 및 리디렉션.

### Rights Management

* 모범 사례: 그룹에 권한을 적용하고, 거부 문을 방지하며, 과도한 참여를 방지합니다.
* Yaml 파일을 통해 권한을 관리하는 데 Netcentric ACL 도구를 사용하여 쉽게 배포하고 추적할 수 있습니다.

### 성능 문제

* 전체 캐시 플러시를 방지하기 위해 동기화 작업에서 델타를 식별하는 것이 중요합니다.
* 업무 시간 동안 대량의 페이지 작업을 피하십시오.
* 필요한 단계로 워크플로우를 간소화합니다.
* 특히 ImageMagick와 같은 도구를 사용하여 작성자 시스템의 서드파티 시스템 프로세스에 주의하십시오.
* 로드를 처리할 수 없는 서드파티 시스템에 동기화된 요청을 방지합니다.
* 성능 저하를 방지하려면 과중한 사용자 지정 구성 요소를 관리합니다.
* 장기 실행 세션을 모니터링하여 세그먼트를 찾을 수 없는 예외를 방지합니다.
