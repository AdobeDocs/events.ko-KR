---
title: Adobe Marketo Engage 챔피언 딥 다이브 - 웹후크를 사용하여 데이터 전송
description: Dashil Shah 및 Josh Arrington과 함께 Marketo에서 웹후크를 사용하여 데이터를 효율적으로 전송하는 방법에 대해 알아봅니다. 이 방법에서는 구조화된 데이터 처리, 오류 관리, 인증 방법, 그리고 John Grundy가 중재하는 CRM 통합 및 전자 상거래와 같은 실용적인 사용 사례를 다룹니다.
feature: Webhooks, Integrations
role: Admin, Developer, Leader, User
level: Beginner, Intermediate, Experienced
doc-type: Event
duration: 3185
last-substantial-update: 2024-04-25T00:00:00Z
jira: KT-15385
exl-id: d8e22e01-724a-4b0c-855b-0adb29e98d30
source-git-commit: 8da73b657295864a3bf6c64598b2fbd664a2379d
workflow-type: tm+mt
source-wordcount: '353'
ht-degree: 0%

---

# 웹후크를 사용하여 데이터 전송

경우에 따라 API를 만들고, 테스트하고, 배포하는 전체 과정이 필요하지 않습니다. 대신 웹후크를 사용하여 셀프서비스를 통해 CRM 또는 기타 통합 시스템으로 다양한 데이터 전송을 실행할 수 있습니다. 이 기능을 사용하는 방법을 배우고 효율성을 빠르게 향상시키려면 Darshil Shah와 Josh Arrington과 함께 하십시오! 존 그런디가 중재했습니다.

>[!VIDEO](https://video.tv.adobe.com/v/3428687/?learn=on)

이 이벤트는 Marketo의 웹후크에 대한 포괄적인 개요를 제공하고 웹후크를 효과적으로 사용하는 방법에 대한 실용적인 조언을 제공합니다. 스피커에서는 구조화된 방식으로 데이터를 보내고 받는 데 사용되는 웹후크의 사용을 설명하고 GET 및 POST 요청 사용을 권장하며 웹후크를 JSON 또는 XML 포맷과 함께 사용할 수 있다고 언급합니다. 이 섹션에서는 CRM 통합, 이벤트 관리, 전자 상거래 및 클라우드 스토리지를 포함하여 웹후크에 대한 다양한 사용 사례를 강조합니다. 오류를 처리하고, 복구를 자동화하고, 경고를 설정하는 방법에 대한 팁과 함께 오류 처리의 중요성이 강조됩니다. API 기반 인증, 기본 인증 및 OAuth 2.0 인증과 같은 인증 방법에 대해 논의하며, 보안 강화를 위해 OAuth 2.0을 사용할 것을 권장합니다.구현 세부 사항에는 30초 시간 제한 및 큰 데이터 세트를 신중하게 처리하는 것과 같은 제한 사항과 함께 트리거 캠페인 및 배치 캠페인에 웹후크 사용이 포함됩니다. 전체적으로 웨비나는 Marketo에서 웹후크를 효과적으로 사용하는 것에 대한 중요한 통찰력을 제공합니다.

## 주요 개선 사항

* Marketo의 Webhooks는 JSON 또는 XML 형식을 지원하는 데이터를 보내고 받는 구조화된 방법을 제공합니다.
* 웹후크에는 CRM 통합, 이벤트 관리, 전자상거래, 클라우드 스토리지 등 다양한 활용 사례가 있다.
* 오류 처리는 매우 중요하며 오류를 처리할 프로세스를 설정하고, 복구를 자동화하고, 예기치 않은 오류에 대한 경고를 설정하는 것이 중요합니다.
* 웹후크의 인증 방법에는 API 기반 인증, 기본 인증 및 OAuth 2.0 인증이 포함됩니다.
* 30초 시간 제한 및 대용량 데이터 세트를 신중하게 처리해야 하는 필요성과 같은 제한 사항을 고려하는 것이 중요합니다
