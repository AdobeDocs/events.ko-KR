---
title: ID 그래프 사용 사례 및 문제 해결
description: Adobe Experience Platform Identity Service가 세분화, 활성화 및 프로필 병합 통찰력을 강화하여 실제 마케팅 문제를 해결하는 방법에 대해 알아봅니다.
feature: Identities, Profiles, Segments
solution: Experience Platform
role: Admin, Developer, User
level: Beginner, Intermediate, Experienced
doc-type: Event
duration: 3232
last-substantial-update: 2025-09-24T00:00:00Z
jira: KT-19286
source-git-commit: ae72352725cfb057cab771b08c4419c11e17e385
workflow-type: tm+mt
source-wordcount: '312'
ht-degree: 0%

---


# ID 그래프 사용 사례 및 문제 해결

이 웨비나는 Adobe Experience Platform ID 서비스가 디지털 마케팅 관리자에게 세그멘테이션 및 활성화 시나리오를 고안할 수 있는 지식을 제공하기 위해 작동하는 방식을 심층적으로 이해합니다. 다중 장치 및 기타 사용 사례의 작동 방식을 정확히 이해하면 현실적인 실제 솔루션이 가능합니다.

* 프로필 병합의 특성/제한 사항에 대한 이해 향상. 이를 통해 더 많은 이해 당사자들로 구성된 팀이 세분화 및 활성화 시나리오를 구상할 수 있습니다.
* 가능한 프로필 축소 문제의 첫 번째 라인 식별.
* ID 서비스와 실시간 고객 프로필 비교.

>[!VIDEO](https://video.tv.adobe.com/v/3475214/?learn=on&enablevpops)

## ID Graph Essentials

ID 그래프는 Adobe Experience Platform에서 고객 데이터를 통합하는 데 중추입니다. 여러 채널 및 장치에서 이메일, CRM ID, 로열티 카드, 쿠키 및 장치 ID와 같은 여러 식별자를 연결합니다.

* **ID 서비스** 데이터 수집 및 이벤트에서 식별자 쌍을 연결하여 그래프를 만듭니다.
* **프로필 서비스** 그래프를 사용하여 프로필 조각을 병합하고 특성, 동작 및 ID를 통합 고객 보기로 어셈블합니다.
* **병합 정책** 최신성(타임스탬프) 또는 데이터 세트 권한으로 데이터 충돌을 해결하는 방법을 결정합니다.
* **비즈니스 영향** 적절한 구성을 통해 정확한 보고, 마케팅 적격성 및 GDPR과 같은 규정 준수를 보장합니다.

## 고객 데이터 연결 잠금 해제

Adobe Experience Platform의 ID 그래프 규칙이 고객 데이터를 통합하여 보다 심층적인 통찰력과 더 나은 비즈니스 결과를 창출하는 방법을 살펴봅니다.

* **ID 그래프** 여러 장치와 채널에서 고객 상호 작용을 연결하여 포괄적인 프로필을 만듭니다.
* **네임스페이스 우선 순위** 비즈니스 기반 규칙은 프로필을 연결하고 충돌을 해결하는 식별자(이메일, CRM ID, 로열티 카드)를 결정합니다.
* **병합 정책** 타임스탬프 또는 데이터 집합 우선 순위를 사용하여 다른 원본의 데이터를 결합하는 방법을 제어합니다.
* **그래프 축소 및 수정** 공유 장치, 확인되지 않은 데이터 또는 구현 오류로 인해 프로필이 조각날 수 있습니다. 시뮬레이션 도구 및 복구 작업은 정확도를 복원하는 데 도움이 됩니다.

이러한 개념을 이해하면 조직은 데이터 가치를 극대화하고, 규정 준수를 보장하며, 개인화된 경험을 제공할 수 있습니다.

