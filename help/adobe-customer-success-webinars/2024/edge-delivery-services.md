---
title: 컨텐츠 전달 최적화 - Edge 서비스의 강력한 기능 잠금 해제
description: ATM Edge Delivery Services(EDS)는 컴포저블 서비스, 빠른 개발 주기, 높은 등대 점수를 통해 ATM 기능을 향상시켜 문서 기반 및 WYSIWYG 작성, 서버리스 아키텍처, 빠른 사이트 생성 및 광범위한 사용자 지정 옵션을 지원합니다.
solution: Experience Manager, Experience Manager as a Cloud Service
feature: Edge Delivery Services
role: Admin, Developer, Leader, User
level: Intermediate
doc-type: Event
duration: 3589
last-substantial-update: 2024-12-06T00:00:00Z
jira: KT-16631
source-git-commit: 47ae42d06ed311e60ebce194e0683bb95e8e5b69
workflow-type: tm+mt
source-wordcount: '410'
ht-degree: 0%

---


# 컨텐츠 전달 최적화: Edge 서비스의 강력한 기능 잠금 해제

이 세션에서는 EDS(Edge Delivery Services) 및 해당 아키텍처에 대한 개요를 제공합니다. EDS가 유니버설 편집기를 통해 문서 기반 작성 및 AEM 기반 작성과 어떻게 통합되는지 살펴보겠습니다. 라이브 데모에서는 EDS를 실제로 시연하며 이후 추가 탐색 및 Q&amp;A 세션을 위한 리소스를 소개합니다.

>[!VIDEO](https://video.tv.adobe.com/v/3440938/?learn=on&enablevpops)

## 주요 개선 사항

### EDS 소개

* EDS는 ATM의 기능을 향상시키도록 설계된 구성 가능한 서비스 세트입니다&#x200B;.
* 빠른 개발 주기와 100% 등대 점수로 참여와 전환을 이끄는 뛰어난 경험을 제공하는 것을 목표로 하고 있습니다. &#x200B;

### 작성 옵션

* **문서 기반 작성** 콘텐츠 작성을 위해 Microsoft Word 또는 Google Docs와 같은 익숙한 도구를 사용하므로 광범위한 교육 없이 빠른 콘텐츠 작성이 가능합니다. &#x200B;
* **범용 편집기**&#x200B;는 기존 ATM 사이트와 유사한 WYSIWYG 인터페이스를 제공하여 보다 상세하고 시각적인 콘텐츠 작성을 가능하게 합니다. &#x200B;

### 아키텍처

* EDS는 Amazon Cloud Service 프레임워크 내에서 통합됩니다. &#x200B;
* 서버리스 구현을 지원하며 기존 작성자 또는 게시자 인스턴스 없이 작업할 수 있습니다. &#x200B;
* 고객 인프라 수준과 EDS 수준에서는 두 가지 수준의 캐싱을 구현할 수 있습니다. &#x200B;

### 콘텐츠 관리

* 문서 기반 작성에는 GitHub 계정, Google Drive 또는 Microsoft SharePoint, 사이드 킥 플러그인 및 코드 동기화 도구가 필요합니다. &#x200B;
* IAM 작성을 사용하는 EDS에는 GitHub 계정, IAM as a cloud service 라이선스 및 코드 동기화 도구가 필요합니다.

### 개발 및 배포

* EDS를 사용하여 사이트를 만드는 프로세스는 빠르며, 종종 하루가 채 걸리지 않습니다. &#x200B;
* 로컬 개발은 aem up 명령을 사용하여 웹 사이트의 로컬 버전을 만들어 수행할 수 있습니다.
* 주 분기로 병합하기 전에 테스트를 위해 기능 분기에 변경 사항을 커밋할 수 있습니다. &#x200B;

### 사용자 정의 및 확장성

* 사용자 지정 구성 요소는 간단한 CSS와 JavaScript을 사용하여 만들 수 있습니다. &#x200B;
* 아키텍처를 통해 서드파티 통합 및 사용자 지정 작성 소스를 사용할 수 있습니다.

### 우수 사례

* 바닐라 JavaScript, CSS를 활용해 높은 등대 점수를 유지하는 것이 좋다.
* React와 같은 라이브러리의 도입은 성능 저하를 방지하기 위해 신중하게 고려하고 테스트해야 합니다.

### 지원 및 설명서

* 설정 및 사용자 지정 프로세스를 안내하는 포괄적인 설명서를 사용할 수 있습니다. &#x200B;
* 사용자는 해결되지 않은 문제에 대한 Adobe 지원에 문의하는 것이 좋습니다. &#x200B;