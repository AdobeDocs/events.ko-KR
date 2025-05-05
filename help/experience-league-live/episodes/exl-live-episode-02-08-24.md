---
title: 사용 사례 플레이북과 셀프서비스 템플릿을 통해 전자 상거래 참여를 강화하여 몇 번의 클릭으로 전자 상거래 사용 사례를 배포할 수 있습니다
description: Adobe Real-Time CDP 및 Adobe Journey Optimizer의 사용 사례 플레이북을 손쉽게 배포하고 잠재적인 기능을 잠금 해제하여 전자 상거래 고객 참여를 개선하는 방법에 대해 알아봅니다.
jira: KT-14791
solution: Experience Platform, Real-Time Customer Data Platform
feature: Playbooks
event-cta-url-live: https://www.youtube.com/watch?v=EZGQ--J2M9I
event-start-time: 2024-02-08 09:00-7
event-guests: Daniel Wright,Josée Monette-Healey,Rohit Basuri
duration: 25
exl-id: 8e820234-2c73-46dc-aa85-f1f089e4ae8e
source-git-commit: 0b2f63198af8767f24783dbafd244c9398c24f33
workflow-type: tm+mt
source-wordcount: '662'
ht-degree: 0%

---

# 사용 사례 플레이북, 셀프서비스 템플릿을 사용하여 몇 번의 클릭으로 사용 사례를 배포할 수 있습니다.

사용 사례 플레이북 소개 - Real-Time CDP 및 Journey Optimizer의 산업별 사용 사례 플레이북에 대한 실용적인 카탈로그입니다. 사용 사례 플레이북과 마케팅 목표를 구현 개체로 변환하는 방법에 대해 알아봅니다. 비즈니스 영향 및 공동 작업 가속화를 위해 일반적으로 알려진 사용 사례를 구축하고 배포하는 데 있어 조직을 빠르게 시작하는 방법을 보여 드리겠습니다.

>[!VIDEO](https://video.tv.adobe.com/v/3426930/?quality=12&learn=on)

>[!BEGINSHADEBOX &quot;질문이 있습니까?&quot;]

Adobe Experience League [커뮤니티 게시물](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-platform/experience-league-live-post-session-discussion-use-case/m-p/651643?profile.language=ko#M488)에서 이 주제에 대한 토론을 계속합니다.

>[!ENDSHADEBOX]

사용 사례 플레이북은 두 가지 주요 문제를 해결하기 위해 빌드되었습니다.

1. **빈 페이지 증후군** - 많은 고객, 특히 새로운 고객은 처음 Adobe Experience 플랫폼에 액세스할 때 압도감을 느끼고 어디서부터 시작해야 할지 또는 기능을 활용하는 방법을 알지 못합니다. 사용 사례 플레이북은 고객이 특정 마케팅 목표를 구현하는 프로세스를 안내하는 선별된 사용 사례 템플릿을 제공하여 이 초기 장애를 극복하는 데 도움이 됩니다.

1. **더 나은 채택과 참여** - 플레이북은 고객이 사전 제작된 템플릿과 기술 지침을 제공하여 Adobe 제품에 대한 투자 속도를 높이고 속도를 높이는 데 도움을 주는 것을 목표로 합니다.  이를 통해 고객은 사용 사례를 보다 신속하게 구현하고, 이해 당사자에게 가치를 입증하며, IT 팀과 마케팅 팀 간의 협업을 강화할 수 있습니다.  궁극적으로 이 플레이북은 고객이 Adobe 경험 플랫폼에서 얻을 수 있는 채택과 가치를 극대화하는 것을 목표로 합니다.

이 세션에서 논의되는 사용 사례의 예는 구매하지 않은 브라우징 및 상품 사용 사례입니다. 이 사용 사례는 고객이 구매하기 전에 탐색 세션을 포기하는 문제를 해결하는 데 목적이 있습니다. 이 사용 사례의 결과 대상 세그먼트는 구매를 완료하지 않고 브라우징 세션을 포기한 고객입니다. 그런 다음 이 세그먼트를 개인화된 메시지 또는 오퍼로 타겟팅하여 재구매를 유도할 수 있습니다.

## 주요 개선 사항

* 사용 사례 플레이북은 고객이 Adobe Experience 플랫폼의 기능을 활용하고 발견할 수 있도록 도와주는 선별된 사용 사례 템플릿 세트입니다.
* 사용 사례 플레이북이 해결하고자 하는 주요 과제는 &quot;빈 페이지 신드롬&quot;과 도구 전반에서 더 많은 채택과 참여의 필요성입니다.
* 사용 사례 플레이북은 업계 및 애플리케이션별로 정렬되므로 고객이 자신의 요구 사항에 맞는 특정 플레이북을 선택할 수 있습니다.
* 고객은 개발 샌드박스에서 플레이북의 인스턴스를 만들고 비즈니스 요구 사항에 맞게 이를 맞춤화한 다음 프로덕션 샌드박스로 이동할 수 있습니다.
* 호환성을 보장하려면 사용 사례 플레이북의 스키마를 고객의 개발 샌드박스 스키마에 매핑하는 것이 중요합니다.
* 여정, 세그먼트 및 메시지 수정을 포함하여 개발 샌드박스에서 플레이북을 추가로 사용자 정의할 수 있습니다.
* 사용 사례 플레이북 기능은 특정 제품 라이선스에 따라 달라지지 않지만 특정 기능에는 Journey Optimizer 또는 Real-time CDP에 대한 라이선스가 필요할 수 있습니다.
* 앞으로 고객이 직접 플레이북을 만들 수 있도록 할 계획이다.
* 고객 피드백 및 제안을 기반으로 사용 사례 플레이북 기능이 지속적으로 개선되고 있습니다.
* Experience League 커뮤니티는 사용 사례 플레이북 기능에 대한 질문을 하고, 아이디어를 공유하고, 피드백을 제공할 수 있는 좋은 공간입니다.

## 추가 리소스

* **[사용 사례 플레이북 개요](https://experienceleague.adobe.com/docs/experience-platform/use-case-playbooks/playbooks/overview.html?lang=ko){target="_blank"}**
  *사용 사례 플레이북을 통해 Real-Time CDP 또는 Adobe Journey Optimizer을 시작할 때 원하는 사용 사례를 달성하기 위해 무엇을 시작해야 하는지 또는 올바른 자산을 만드는 방법을 정확히 알 수 없는 경우 문제를 해결할 수 있습니다.*

* **[사용 사례 플레이북 시작](https://experienceleague.adobe.com/docs/experience-platform/use-case-playbooks/playbooks/get-started.html?lang=ko){target="_blank"}**
  *Real-time Customer Data Platform 및 Adobe Journey Optimizer용으로 설계된 사용 사례 플레이북에 대한 계정을 설정하는 방법을 알아봅니다.*

* **[사용 사례 플레이북](https://experienceleague.adobe.com/docs/experience-platform/use-case-playbooks/playbooks/playbooks-list.html?lang=ko){target="_blank"}**
  *이 페이지를 읽고 Real-time Customer Data Platform 및 Adobe Journey Optimizer에서 검색하고 사용할 수 있는 모든 플레이북에 대한 개요를 살펴보십시오.*
