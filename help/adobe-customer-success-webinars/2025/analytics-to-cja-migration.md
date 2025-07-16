---
title: Adobe Analytics에서 Adobe Customer Journey Analytics으로 마이그레이션하는 우수 사례
description: XDM 스키마 디자인, 데이터 매핑 및 데이터 보기 설정을 포함하여 Adobe Analytics에서 Customer Journey Analytics(CJA)로 마이그레이션하기 위한 필수 단계 및 모범 사례에 대해 알아봅니다.
solution: Analytics, Customer Journey Analytics
topic: Migration
role: Developer
level: Beginner, Intermediate
doc-type: Event
duration: 3654
last-substantial-update: 2025-07-16T00:00:00Z
jira: KT-18535
source-git-commit: 90eb4a9d2cf445c58fde776092fb047f820fa207
workflow-type: tm+mt
source-wordcount: '298'
ht-degree: 0%

---


# Adobe Analytics에서 Adobe Customer Journey Analytics으로 마이그레이션하는 우수 사례

Adobe Analytics에서 Customer Journey Analytics(CJA)로의 마이그레이션에 대해 알아봅니다. Adobe의 Ultimate Success 팀에서 Nicolina Picone 및 Maurizio Corò가 주최한 이 세션은 CJA과 의 기능 및 마이그레이션에 대한 심도 있는 개요를 제공합니다.

## 논의된 주요 항목

* analytics와 CJA의 차이점
* 강력한 id 식별자, 데이터 구조 정렬 및 사용자 지정 가능한 데이터 보기 만들기의 중요성
* 내역 데이터 가져오기, 마케팅 채널 속성 관리 및 CJA의 유연성을 활용하여 맞춤형 보고를 수행하는 전략을 다룹니다

>[!VIDEO](https://video.tv.adobe.com/v/3464911/?learn=on&enablevpops)

## 주요 방법

* **Customer Journey Analytics(CJA) 개요** CJA은 단일 트랙 이벤트가 아닌 여러 접점(예: 모바일, 웹, CRM, 콜 센터)에서 전체 고객 여정에 중점을 둔 Adobe Analytics의 발전된 기능입니다. 실시간 데이터 처리 및 조작이 가능합니다.

* **마이그레이션 준비** Adobe Analytics에서 CJA으로 마이그레이션하는 주요 단계에는 강력한 ID 식별자(예: 개인 ID) 확인, 변수 및 차원 정렬, XDM 스키마에 데이터 매핑 등이 있습니다. 유효성 검사 단계를 통해 이전 데이터를 가져올 수 있습니다.

* **데이터 보기 및 유연성** CJA을 사용하면 조정 가능한 세션 기간, 세그먼테이션 필터 및 속성 설정을 통해 사용자 지정 가능한 데이터 보기를 만들 수 있습니다. 이러한 유연성으로 맞춤형 보고 및 분석이 가능합니다.

* **이전 데이터 마이그레이션에 대한 우수 사례** 허용 범위(예: 10% 차이) 내에서 CJA 데이터와 비교하여 Adobe Analytics 데이터의 유효성을 검사합니다. 짧은 채우기 기간(예: 1개월)으로 시작하여 점진적으로 확대하십시오.

* **마케팅 채널 속성** CJA에서는 마케팅 채널 속성에 대해 향상된 기능을 제공하므로 &quot;첫 방문 페이지&quot; 기능과 같은 제한을 없애고 보다 동적 세션 구성을 사용할 수 있습니다.
