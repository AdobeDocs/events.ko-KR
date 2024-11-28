---
title: Adobe Experience Manager as a Cloud Service의 CDN 및 WAF 구성
description: Adobe 전문가가 공유하는 사용자 정의 CDN 규칙, WAF 보호 및 구성 파이프라인을 통해 Adobe Experience Manager as a Cloud Service 애플리케이션의 성능과 보안을 향상시킵니다.
feature: Security
topic: Performance, Security
role: Developer
level: Beginner, Intermediate
doc-type: Event
duration: 2211
last-substantial-update: 2024-11-26T00:00:00Z
jira: KT-16574
exl-id: a9f38e79-c707-443d-8b2f-e534ce4dd43d
source-git-commit: 946d7cd484e8c5d4358d4099b3518705cab8d4a3
workflow-type: tm+mt
source-wordcount: '366'
ht-degree: 0%

---

# Adobe Experience Manager as a Cloud Service의 CDN 및 WAF 구성

사용자 정의 가능한 CDN 규칙, WAF 보호 및 구성 파이프라인을 통해 Adobe Managed CDN의 모든 가능성을 최대한 활용하십시오. Adobe의 수석 컴퓨터 과학자 Marius Petria, Adobe의 소프트웨어 개발 엔지니어 Quentin Vecchio, Adobe의 소프트웨어 개발 엔지니어 Florian Froese는 Adobe Experience Manager as a Cloud Service 애플리케이션의 성능과 보안을 향상시키는 전략을 공유합니다.

>[!VIDEO](https://video.tv.adobe.com/v/3440401/?learn=on&enablevpops)

## 커뮤니티 토론

Adobe Developers Live 커뮤니티 [토론](https://adobe.ly/3O0TyYa)에서 대화를 계속합니다.

## 주요 사항

* **새로운 구성 기능 소개** 프레젠테이션에서는 다양한 사용 사례에 맞게 CDN을 구성하는 기능에 초점을 맞추어 클라우드 서비스의 CDN에 대한 새로운 구성 기능을 소개합니다.
* **CDN 구성 옵션** 새 옵션을 사용하면 헤더 추가/제거, 요청 경로 재작성, 트래픽 차단, 클라이언트 리디렉션 및 다른 원본으로의 프록시 지정과 같은 HTTP 요청 및 응답과의 상호 작용을 수행할 수 있습니다.
* **보안 개선 사항** 새로운 기능에는 요청 패턴에 따라 트래픽을 차단하거나 기록하는 트래픽 필터 규칙, SQL 삽입 및 XSS와 같은 웹 공격에 대한 고급 보호를 위한 M WAF의 도입이 포함됩니다.
* **선언적 구성** 구성은 YAML 파일을 사용하여 수행되고 Cloud Manager의 구성 파이프라인을 통해 배포되므로 빠르고 간단한 프로세스가 됩니다.
* **요청 및 응답 변환** 새로운 기능을 사용하면 요청 변환을 통해 URL을 정규화하고 불필요한 쿼리 매개 변수를 제거할 수 있으며, 응답 변환을 통해 클라이언트에 응답을 보내기 전에 헤더를 설정할 수 있습니다.
* **트래픽 필터 및 속도 제한** 트래픽 필터는 특정 IP 또는 국가를 차단하고 속도 제한을 구현하여 DDoS 공격으로부터 보호할 수 있습니다. 속도 제한은 클라이언트 IP, 사용자 에이전트 및 요청 경로와 같은 다양한 기준을 기반으로 구성할 수 있습니다.
* **모니터링 및 분석 도구** Adobe은 트래픽 및 사용을 분석할 수 있는 Elasticsearch/Kibana 및 Splunk 대시보드와 같은 도구를 제공하여 잠재적인 보안 위협을 식별하고 완화하는 데 도움이 됩니다.
* **실제 데모** 프레젠테이션에는 Cloud Manager을 사용하여 CDN 구성을 배포하는 방법과 AEM을 사용하여 오류를 처리하고 로컬에서 구성을 확인하는 방법을 보여 주는 데모가 포함되어 있습니다.
