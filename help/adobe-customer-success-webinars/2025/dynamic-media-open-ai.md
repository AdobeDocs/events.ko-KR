---
title: Open API를 사용하여 Dynamic Media 마스터링
description: 기존 Dynamic Media와 Open API 모델 간의 주요 차이점을 이해하고, Open API를 사용하여 Dynamic Media Ultimate을 성공적으로 전환하고 구현하는 방법을 알아봅니다.
solution: Experience Manager as a Cloud Service, Experience Manager Assets
feature-set: Experience Manager Assets
feature: SDK/API
topic: Development, Content Management
role: Admin, Developer, User
level: Beginner, Intermediate
doc-type: Event
duration: 2757
last-substantial-update: 2025-08-08T00:00:00Z
jira: KT-18702
source-git-commit: ef1eacd73c5a4fb9cdfee730d40606ec65bab2a7
workflow-type: tm+mt
source-wordcount: '249'
ht-degree: 2%

---


# Open API를 사용하여 Dynamic Media 마스터링

이 웨비나는 기존 Dynamic Media에 익숙하고 Open API를 사용하여 [Dynamic Media Ultimate](https://experienceleague.adobe.com/ko/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-prime-ultimate)을(를) 이해하고 구현하려는 전문가를 위해 설계되었습니다.  Open API를 사용하는 Dynamic Media Ultimate의 높은 수준의 작업에 대해 살펴보고 기존 Dynamic Media와 비교합니다. Dynamic Media에 익숙한 참가자가 Open API 모델에 쉽게 적응할 수 있도록 이 두 접근 방식의 차이점을 포괄적으로 이해하는 것이 우리의 목표입니다.

>[!VIDEO](https://video.tv.adobe.com/v/3470620/?learn=on&enablevpops)

## 주요 기능 비교

| 기능 | Dynamic Media | OpenAPI를 사용하는 Dynamic Media |
|-----------------------------|------------------------|----------------------------|
| *가용성* | 온프레미스, AMS, Cloud | 클라우드만 |
| *수정자* | 리치 세트 사용 가능 | 제한적이지만 성장 |
| *액세스 제어* | 모든 사용자에게 열기 | 역할에 의해 제한됨 |
| *CDN TTL* | ~10시간 | ~10분 |
| *승인 적용* | 자동 게시됨 | 승인 필요 |
| *SEO에 친숙한* | 예 | 예 |

## 통합 시나리오

이러한 통합 시나리오는 다양한 엔터프라이즈 요구 사항을 위해 OpenAPI를 사용하는 Dynamic Media의 유연성과 확장성을 보여 줍니다.

* OpenAPI가 포함된 **AEM Sites 통합** 다이내믹 미디어는 AEM Sites과의 원활한 통합을 지원하므로 자산을 중복 없이 게재 계층에서 직접 가져올 수 있습니다.
* **타사 CMS** API 또는 마이크로 프런트 엔드 애플리케이션을 사용하여 Salesforce 및 Drupal과 같은 플랫폼과 통합할 수 있습니다.
* **API 기반 액세스**&#x200B;는 자산의 최적화된 렌디션을 검색, 검색 및 전달하기 위한 API를 제공합니다.
* **배달 계층 최적화** Assets은 Fastly를 통해 제공되므로 더 빠르고 효율적으로 배달할 수 있습니다.