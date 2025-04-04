---
title: 인증 간소화 - 서비스 계정(JWT)에서 OAuth 서버 간 자격 증명으로 마이그레이션
description: 선임 현장 엔지니어인 Jeff Homequest와 Marco Lara가 이끄는 Adobe 웨비나는 프로세스에 대한 광범위한 지원과 설명서와 함께 서비스 계정 JWT에서 OAuth 서버 간 자격 증명으로 마이그레이션하는 데 중점을 두고, 2025년 1월 사용 중단 기한, 마이그레이션 단계, OAuth의 이점 및 AEM에 대한 특별 고려 사항을 강조했습니다.
role: Admin, Developer, Leader, User
level: Intermediate
doc-type: Event
duration: 3292
last-substantial-update: 2024-12-06T00:00:00Z
jira: KT-16629
source-git-commit: 47ae42d06ed311e60ebce194e0683bb95e8e5b69
workflow-type: tm+mt
source-wordcount: '404'
ht-degree: 0%

---


# 인증 간소화: 서비스 계정(JWT)에서 OAuth 서버 간 자격 증명으로 마이그레이션

이 웨비나는 더 이상 사용되지 않는 서비스 계정(JWT) 자격 증명에서 새 OAuth 서버 간 자격 증명으로 마이그레이션하는 과정을 안내합니다. 서비스 계정(JWT) 자격 증명은 2025년 1월 27일 이후로 더 이상 작동하지 않으므로, 개발자와 조직은 잠재적인 서비스 중단을 방지하기 위해 마이그레이션 프로세스를 이해하는 것이 중요합니다. 또한 이 웨비나에서는 OAuth 서버 간 자격 증명의 장점과 무중단 마이그레이션을 보장하는 방법을 중점적으로 다룹니다.

>[!VIDEO](https://video.tv.adobe.com/v/3440936/?learn=on&enablevpops)

## 주요 개선 사항

* **모임 녹음/녹화 및 슬라이드** 모임이 녹음되었으며 녹음/녹화에 대한 링크는 마지막에 사용할 수 있습니다.
* **발표자 소개** Adobe의 현장 선임 엔지니어인 Jeff Homequest와 Marco Lara가 웨비나를 이끌었습니다.
* **웨비나 포커스** 웨비나는 서비스 계정 JWT에서 OAuth 서버 간 자격 증명으로 마이그레이션하는 데 중점을 둡니다.
* **사용 중단 기한** Adobe이 JWT 자격 증명을 사용하지 않고 있으므로 2025년 1월 말까지 마이그레이션해야 합니다.
* **대상 타기팅** 웨비나는 Adobe 응용 프로그램에서 JWT 자격 증명을 사용하는 응용 프로그램 개발자, 기술 리더 및 통합 설계자를 대상으로 했습니다.
* **마이그레이션 단계** 웨비나에는 단계별 마이그레이션 안내서와 데모가 포함되어 있습니다.
* 회의 내내 **Q&amp;A 세션** 질문이 수행되었으며 끝에 전용 Q&amp;A 세션이 있습니다.
* **OAuth의 이점** OAuth는 JWT에 비해 개발을 단순화하고, 보안을 강화하고, 유지 관리를 간소화합니다.
* **마이그레이션 타임라인**
   * 2023년 5월 1일 - 향후 사용 중단 발표.
   * 2024년 6월 2일 - 새 서비스 계정 자격 증명을 만드는 마지막 날짜.
   * 2025년 1월 27일 - 서비스 계정의 수명 종료 및 이를 사용하는 API의 작동이 중단됩니다.
* **&#x200B;AEM에 대한 특수 고려 사항** 웨비나에서는 특정 인증 패턴 및 구성을 포함하여 마이그레이션이 AEM cloud 및 온프레미스 고객에게 미치는 영향을 해결했습니다.
* **자동 생성된 통합** 자동 생성된 통합은 기한 전에 Adobe에 의해 자동으로 마이그레이션됩니다.
* **지원 및 설명서** Adobe은 마이그레이션 프로세스에 대한 광범위한 설명서와 지원을 제공합니다. 고객은 Adobe 담당자 또는 전문 서비스에 연락하여 도움을 받을 수 있습니다.
* **테스트 및 유효성 검사** 마이그레이션 후 이전 JWT 자격 증명을 삭제하기 전에 통합을 철저히 테스트하는 것이 좋습니다.
* **사용자 지정 통합** 사용자 지정 통합을 사용하는 고객은 가능한 한 빨리 마이그레이션을 식별하고 계획해야 합니다(특히 서드파티 공급업체가 관련된 경우).