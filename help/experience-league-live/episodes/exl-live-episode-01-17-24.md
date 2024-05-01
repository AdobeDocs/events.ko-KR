---
title: Adobe Analytics 데이터 및 분석을 Customer Journey Analytics으로 가져오기
description: 새로운 자동화된 프로세스를 통해 분석 및 데이터를 Adobe Analytics에서 Adobe Customer Journey Analytics으로 이동하는 데 어떻게 도움이 되는지에 대해 알아봅니다.
jira: KT-14746
solution: Analytics,Customer Journey Analytics
feature: Experience Cloud Integration
event-cta-url-live: https://www.youtube.com/watch?v=BkAjaMPgpgE
event-cta-url-reg: https://engage.adobe.com/ExpLeagueLive-240117.html
event-start-time: 2024-01-17 10:00-7
event-guests: Doug Moore,Eric Matisoff,Bryan Skelton
exl-id: 2c2136a9-0b40-4a0a-907d-5af181568073
duration: 3655
source-git-commit: 0b2f63198af8767f24783dbafd244c9398c24f33
workflow-type: tm+mt
source-wordcount: '394'
ht-degree: 0%

---

# Adobe Analytics 데이터 및 분석을 Customer Journey Analytics으로 가져오기

Bryan, Eric 및 Doug와 함께 CJA(Customer Journey Analytics)를 사용하여 빠르게 전환하는 방법에 대해 논의합니다. 자동화된 프로세스를 사용하여 Adobe Analytics에서 CJA로 데이터 및 분석을 이동하는 방법과 프로세스 중에 고려해야 할 사항에 대해 알아봅니다. 그리고 물론, 그들은 그 과정에서 건강한 양의 재미있는 팁과 요령을 가질 것입니다.

>[!VIDEO](https://video.tv.adobe.com/v/3426778/?quality=12&learn=on)

>[!BEGINSHADEBOX 질문이 있습니까?]

다음에 대한 토론 계속 [Experience League 커뮤니티 포럼 토론](https://experienceleaguecommunities.adobe.com/t5/adobe-analytics-discussions/experience-league-live-post-session-discussion-bringing-your/m-p/646093#M3582).

>[!ENDSHADEBOX]

## 핵심 사항

* Adobe Analytics에서 Customer Journey Analytics으로 데이터를 가져오는 방법에는 ADC(Analytics Data Connector)와 웹 SDK의 두 가지가 있습니다.
* ADC를 사용하면 보고서 세트의 데이터를 분석을 위해 Adobe Experience Platform에 복사할 수 있지만, Web SDK는 데이터를 Adobe Experience Platform으로 직접 전송합니다.
* Customer Journey Analytics의 데이터 보기 는 플랫폼으로 가져오는 데이터를 사용자 정의하고 분석하는 방법을 제공합니다.
* 데이터 보기는 소급 변경 사항, 사용자 지정을 위한 파생 필드, 세분화된 수준에서 데이터를 필터링하고 분석하는 기능과 같은 강력한 기능을 제공합니다.
* Customer Journey Analytics의 연결을 사용하면 서로 다른 데이터 세트를 통합하여 한 곳에서 여러 데이터 소스를 분석할 수 있습니다.
* 데이터 보기 및 연결은 데이터 액세스 및 분석에 대한 적절한 거버넌스 및 제어를 보장하기 위해 전략적이고 신중하게 사용해야 합니다.
* Adobe Analytics 관리자가 프로젝트를 CGA로 마이그레이션할 수 있는 새로운 도구 &quot;구성 요소 마이그레이션&quot;이 있습니다.
* 프로젝트를 마이그레이션할 때 적용된 세그먼트 또는 계산된 지표는 물론 테이블의 모든 구성 요소가 CGA로 이동됩니다.
* CGA에 존재하지 않는 구성 요소를 catch-all 또는 파생 필드를 사용하여 매핑할 수 있는 매핑 프로세스가 있습니다.
* CGA에 존재하지 않는 요소에 대해 다목적 캐치(catch-all)를 만든 다음 대상 프로젝트에서 편집하는 것이 좋습니다.
* 이전에는 CGA로 마이그레이션할 때 계산된 지표와 세그먼트를 다시 만들어야 했지만, 이제는 마이그레이션할 수 있는 옵션이 있습니다.
* 계산된 지표 및 세그먼트가 마이그레이션에 포함되도록 하려면 Adobe Analytics의 테이블 또는 시각화에 적용되어야 합니다.

