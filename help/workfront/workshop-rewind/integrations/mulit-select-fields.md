---
title: 다중 선택 필드를 위한 Workfront API 및 Fusion 변경 사항을 쉽게 탐색
description: 다중 선택 필드 업데이트, 이벤트 구독 버전 관리 및 변경 내용 손상 방지 전략을 포함하여 예정된 Adobe Workfront API 및 Fusion 변경 사항에 대해 알아봅니다.
feature: Workfront API, Workfront Fusion, Workfront Integrations and Apps
topic: Integrations
role: Admin, Developer, Leader, User
level: Beginner, Intermediate, Experienced
doc-type: Event
duration: 3172
last-substantial-update: 2025-08-08T00:00:00Z
jira: KT-18631
source-git-commit: 6225f36c5d26ecca5ebc2aca24a2d592a3279570
workflow-type: tm+mt
source-wordcount: '340'
ht-degree: 0%

---


# 다중 선택 필드를 위한 Workfront API 및 Fusion 변경 사항을 쉽게 탐색

이 워크숍은 2025년 6월 25일에 기록되었으며 Andy Hess가 참여하여 Workfront API 및 Fusion에 대한 향후 변경 사항을 공유했습니다.

>[!VIDEO](https://video.tv.adobe.com/v/3469978/?learn=on&enablevpops)

## 리소스

온디맨드 녹화와 함께 슬라이드 데크와 추가 리소스가 포함되어 있습니다.
* [슬라이드 데크 PDF](https://workfront-experience.s3.us-west-2.amazonaws.com/Training/Guides/Customer+Success+at+Scale/Navigating+the+API+and+Fusion+Changes+for+Multi-Select+Fields+with+Ease+062425.pdf)
* 특정 영역, [[이벤트 후속 작업] 이벤트 구독 V2 업그레이드 동안 Fusion 시나리오 보존](https://experienceleaguecommunities.adobe.com/t5/workfront-discussions/event-follow-up-preserving-your-fusion-scenarios-during-the/m-p/754182?profile.language=ko#M4041)에 대해 자세히 알아보려면 Adobe 소프트웨어 개발 팀과 함께 호스팅된 이벤트가 이벤트 구독 변경 사항에 대해 5월 초에 전달되었습니다.

## 주요 개선 사항 및 리소스

* Workfront API 다중 선택 필드에 대한 변경 사항은 혼합 문자열/배열 응답 대신 일관된 JSON 배열 형식을 보장하기 위해 버전 21(2025년 10월)에 제공됩니다
* 이벤트 구독 버전 관리가 도입됩니다. 버전 2는 항상 다중 선택 필드를 배열로 반환하지만 버전 1은 현재 일관되지 않은 동작을 유지합니다.
* 새 이벤트 구독은 자동으로 버전 2로 설정되고, 모든 구독은 2026년 1월 중순에 버전 2로 자동 업그레이드됩니다
* 모듈 매핑을 보존하고 변경 사항을 방지하기 위해 수동 업그레이드 프로세스를 통해 새로운 Workfront 커넥터 버전이 올해 말 출시될 예정입니다
* Fusion AI Assistant는 현재 사용할 수 있지만 서명된 AI 계약과 적절한 라이선스 설정이 필요합니다. 질문이 있거나 자세한 내용을 알고 싶은 경우 계정 관리자에게 문의하십시오. [Fusion에서 AI 사용에 대한 추가 정보](https://experienceleague.adobe.com/ko/docs/workfront-fusion/using/manage-scenarios/fusion-ai-assistant)
* [현재 사용 가능한 Workfront Fusion 템플릿](https://experienceleague.adobe.com/ko/docs/workfront-fusion/using/create-and-manage-templates/currently-available-fusion-templates)
* [Fusion 템플릿 호출](https://experienceleaguecommunities.adobe.com/t5/workfront-discussions/call-for-fusion-template-ideas/m-p/732085?profile.language=ko#M3686)- 새 Fusion 템플릿에 대한 제안이 있는 경우 여기에 추가하십시오. 여기에서 팀이 아이디어를 가져옵니다.  

추가 질문이 있는 경우 이 [Experience League 커뮤니티 게시물](https://experienceleaguecommunities.adobe.com/t5/workfront-discussions/event-follow-up-navigating-the-workfront-api-and-fusion-changes/td-p/761253?profile.language=ko)에 회신하십시오! 

향후 고객 성공 워크숍에서 여러분을 볼 수 있기를 바랍니다!  전체 목록을 보려면 Experience League에서 [Workfront 이벤트](https://experienceleague.adobe.com/events/?lang=ko&filters=Workfront)를 확인하고 등록하십시오.