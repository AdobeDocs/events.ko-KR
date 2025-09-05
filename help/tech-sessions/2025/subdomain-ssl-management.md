---
title: 기술 세션 - Adobe Campaign 하위 도메인 및 Campaign 컨트롤 패널의 SSL 관리
description: Adobe Campaign의 Campaign 컨트롤 패널 내에서 하위 도메인을 위임 및 구성하고, SSL 인증서를 설정하고, 구성을 모니터링하여 안전한 이메일 전달성을 보장하는 방법을 알아봅니다.
solution: Campaign
feature: Subdomains and Certificates
role: Admin, Developer, Leader, User
level: Beginner, Intermediate, Experienced
doc-type: Event
duration: 3409
last-substantial-update: 2025-09-05T00:00:00Z
jira: KT-18866
source-git-commit: 18ce421793d97372198151afc92b24f3bed053a8
workflow-type: tm+mt
source-wordcount: '344'
ht-degree: 0%

---


# 기술 세션: Adobe Campaign 하위 도메인 및 Campaign 컨트롤 패널의 SSL 관리

이 세션에서는 보안 하위 도메인을 위한 SSL 인증서 설치를 포함하여 Adobe Campaign 내의 하위 도메인 위임 및 구성에 대한 개념을 살펴봅니다.

Adobe에서 하위 도메인을 효과적으로 사용할 수 있는 정의, 목적 및 위임 방법에 대해 알아봅니다. 또한 이 세션에서는 SSL 인증서를 통한 하위 도메인 보안의 원칙과 보안 환경을 유지 관리하기 위한 모범 사례를 다룹니다.

잠재적인 장애 요소와 해결 방법을 강조 표시하고 셀프서비스 Campaign 컨트롤 패널을 사용하여 하위 도메인을 구성하는 방법에 대한 단계별 지침을 제공합니다. 참가자는 하위 도메인을 원활하게 설정하고 안전하게 관리할 수 있는 실용적인 지식을 습득합니다.

관리자, 개발자 또는 플랫폼 소유자이든 이 세션은 Adobe Campaign에서 하위 도메인을 자신 있게 구성하고 보호하는 기술을 제공합니다.

>[!VIDEO](https://video.tv.adobe.com/v/3471391/?learn=on&enablevpops)

## Adobe Campaign에서 하위 도메인 관리 마스터링

Adobe Campaign 이메일 통신을 위한 하위 도메인 위임, 구성 및 보안에 대한 필수 사항 잠금 해제:

* **하위 도메인 위임** 전체 또는 CNAME 위임 중 선택하여 Adobe에서 DNS 및 이메일 게재 기능을 관리하는 방법을 제어합니다.
* **DNS 및 SSL 설정** 안전하고 신뢰할 수 있는 이메일 전송을 위해서는 MX, SPF, DKIM, DMARC 및 SSL 인증서의 적절한 구성이 중요합니다.
* **Campaign 컨트롤 패널** Adobe의 셀프서비스 도구를 사용하여 하위 도메인 설정을 간소화하고 레코드를 모니터링하며 SSL 인증서를 관리합니다.
* **일반적인 위험** 감사 타임라인, 레코드 요구 사항 및 문제 해결 단계를 이해하여 지연 및 오류를 방지합니다.

이러한 프로세스를 마스터하면 캠페인이 안전하고, 전달가능하며, 브랜드의 평판을 유지할 수 있습니다.

## 위임 방법** 전체 및 CNAME

* **전체 위임** Adobe은 하위 도메인에 대한 모든 DNS 레코드를 관리하여 최적의 전달성과 보안을 보장합니다. 대부분의 사용자에게 권장됩니다.
* **CNAME 위임** 고객과 Adobe이 DNS 책임을 공유합니다. 고객은 Adobe 관리 리소스를 가리키는 CNAME 레코드를 만듭니다.
* **주요 차이점:
* **전체** Adobe에 대한 모든 권한이 부여되어 있으므로 고객 유지 관리가 줄어듭니다.
* **CNAME** 공유 권한, 고객을 위한 더 많은 수동 단계.
* **팁** 루트 도메인을 위임하지 말고(하위 도메인만 위임하여 주 도메인을 제어하지 않도록 하십시오.
