---
title: 확장성을 위한 PMCF 필드 활용
description: Adobe Marketo Engage Champion Deep Dive 비디오에서 설명한 대로 데이터 관리, 개인화된 커뮤니케이션 및 정확한 보고를 위한 모범 사례를 포함하여 확장성을 위해 Marketo의 PMCF(Program Member Custom Field)를 활용하는 방법에 대해 알아봅니다.
solution: Marketo Engage
feature-set: Marketo Engage
feature: Field Management
role: Admin, Developer, User
level: Intermediate, Experienced
doc-type: Event
duration: 3059
last-substantial-update: 2024-06-28T00:00:00Z
jira: KT-15784
exl-id: 9fd094c3-d6ad-410e-aeae-1b6bf3f012bd
source-git-commit: 8da73b657295864a3bf6c64598b2fbd664a2379d
workflow-type: tm+mt
source-wordcount: '281'
ht-degree: 0%

---

# 확장성을 위한 PMCF 필드 활용

&quot;Adobe Marketo Engage 챔피언 딥 다이브&quot; 비디오에서 발표자는 확장성을 위해 Marketo의 PMCF(Program Member Custom Field)를 사용하는 방법에 대해 설명합니다. 이 세션에서는 PMCF의 정의, 목적, 규칙 및 사용 사례를 다룹니다. PMCF를 사용하여 데이터를 변경하고, 정보를 참조하며, 웨비나에 대한 UTM 매개 변수와 같은 고유한 이벤트 데이터를 추적하는 모범 사례입니다. 전반적으로 PMCF는 Marketo에서 복잡한 마케팅 프로그램을 관리하고 확장하려는 마케터에게 유용한 도구입니다.

>[!VIDEO](https://video.tv.adobe.com/v/3430531/?learn=on)

## 주요 개선 사항

**프로그램 구성원 사용자 지정 필드(PMC)**

* 프로그램에 대한 고유 데이터 필드.
* 프로그램 수준에서 컨텍스트 데이터를 허용합니다.
* 프로그램당 20개의 사용자 정의 필드 생성 제한.
* 데이터 가져오기 방법: 목록 가져오기, 양식 채우기, 흐름 단계.
* 데이터 일관성을 위해 Salesforce 캠페인 멤버와 동기화합니다.
* 개인화된 커뮤니케이션을 위한 이메일, 랜딩 페이지 및 경고에서 을(를) 사용합니다.
* 프로그램별 데이터의 추적, 분석 및 보고 기능을 향상시킵니다.

**Marketo의 PMC 사용률**

* 프로그램 내에서 정보를 캡처하고 공유하는 데 중요합니다.
* 필드 및 수집된 정보를 나열하는 데 적합한 프로그램 설명.
* 개인화된 정보를 이메일에 통합.
* 정확한 참여 정보를 위한 타임스탬프 사용자 지정 필드.
* 정확한 보고 및 속성을 위해 참여 날짜를 수정합니다.
* 오류를 방지하기 위해 사용자 정의 필드의 신중하게 계획 및 유효성 검사
* 각 프로그램에 필요한 필드를 감사하고 우선 순위를 지정합니다.

**사용자 지정 필드 계획 및 구현**

* 변경 또는 새 필드 만들기 전에 개념 테스트 및 증명.
* 효과적인 현장 활용을 위해 마케팅 팀과 영업 팀 간의 Collaboration.
* 개인화된 지원 및 잠재 고객과의 참여를 위한 맞춤형 웨비나 참여 데이터입니다.
