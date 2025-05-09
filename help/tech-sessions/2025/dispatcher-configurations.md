---
title: Adobe Experience Manager as a Cloud Service의 Dispatcher 구성
description: AEM as a Cloud Service의 확장성과 효율성을 극대화하기 위한 캐싱, 보안 및 성능에 대한 AEM Dispatcher 모범 사례를 살펴봅니다.
solution: Experience Manager as a Cloud Service
version: Experience Manager as a Cloud Service
feature: Dispatcher
role: Developer, Leader, User
level: Beginner, Intermediate, Experienced
doc-type: Event
duration: 4200
last-substantial-update: 2025-05-07T00:00:00Z
jira: KT-17903
source-git-commit: cfc7b54ae4360779ca2c41f88fc08089bae99165
workflow-type: tm+mt
source-wordcount: '339'
ht-degree: 0%

---


# 기술 세션: Adobe Experience Manager as a Cloud Service의 Dispatcher 구성

**Adobe Experience Manager(AEM) as a Cloud Service**&#x200B;은(는) 최신 디지털 경험 플랫폼을 위한 확장성, 유연성 및 향상된 성능을 제공합니다. 이 아키텍처의 핵심은 캐싱, 보안 및 요청 관리를 담당하는 중요한 구성 요소인 **AEM Dispatcher**&#x200B;입니다. 올바르게 구성된 경우 Dispatcher은 컨텐츠 전달을 가속화하고 백엔드 시스템을 보호하며 전체 사이트 성능을 향상시킵니다.

이 개요에서는 캐싱 전략, 액세스 제어 메커니즘 및 요청 필터링을 포함한 주요 Dispatcher 설정을 강조 표시합니다. 또한 클라우드에서 안전하고 고성능 AEM 배포를 유지하기 위한 모범 사례에 대해 설명합니다. 개발자, 설계자 또는 비즈니스 의사 결정권자에 관계없이 Dispatcher 구성에 대한 확실한 이해는 AEM as a Cloud Service의 잠재력을 최대한 발휘하는 데 중요합니다.

>[!VIDEO](https://video.tv.adobe.com/v/3457891/?learn=on&enablevpops)

## 주요 학습 사항

* **유효성 검사를 위한 Dispatcher SDK** AEM Dispatcher SDK은 구성의 정적 분석을 위한 강력한 도구입니다. 구성을 신속하게 검증하고, 불변성을 확인하고, 오류를 식별하여 전체 파이프라인 배포에 비해 상당한 시간을 절약할 수 있습니다.

* **RDE(신속한 개발 환경)** RDE는 정적 분석 이상의 구성 테스트 및 디버깅을 위한 대화형 런타임 환경을 제공합니다. 신속한 유효성 검사와 디버깅을 지원하여 배포와 테스트에 필요한 시간을 단축합니다.

* **Mod 프록시를 사용한 고급 네트워킹** VPN 및 전용 이그레스 IP와 같은 고급 네트워킹 구성은 Cloud Manager을 사용하여 설정할 수 있습니다. mod 프록시 모듈을 사용하면 AEM에서 외부 서비스로 트랜잭션을 오프로드하여 성능을 최적화하고 JVM에 대한 로드를 줄일 수 있습니다.

* **Dispatcher 구성에 대한 우수 사례** 주요 권장 사항에는 상대 경로 사용, 고유한 x-vhost 헤더, 올바른 클라이언트 헤더, 캐시 제어 헤더를 활용하여 캐싱을 효과적으로 관리하는 것이 포함됩니다. 이러한 사례는 파이프라인 오류를 방지하고 디버깅 효율성을 개선하는 데 도움이 됩니다.

* **배포를 위한 웹 계층 파이프라인** 웹 계층 파이프라인은 격리된 Dispatcher 구성을 배포하는 유틸리티입니다. 여기에는 캐시 무효화와 같은 추가 테스트가 포함되어 있어 컨텐츠 업데이트가 프로덕션 환경에 빠르고 정확하게 반영되도록 합니다.