---
title: 전문가에게 문의 - Tags(Launch)의 유용한 확장 기능으로 Web SDK의 비용 절감
description: 구현을 새로운 Adobe Web SDK로 마이그레이션하시겠습니까?  Adobe 태그 라이브러리에서 데이터 수집을 한 단계 업그레이드하는 데 도움이 되는 자주 사용하는 확장 몇 가지를 살펴보겠습니다.
solution: Data Collection,Experience Platform
kt: 10528
thumbnail: https://video.tv.adobe.com/v/346610?format=jpeg
event-start-time: 2022-08-23 09:00-7
event-guests: Rudi Shumpert,Jeff Chasin,Eric Matisoff
exl-id: 5ef987f4-37f5-473f-b9f2-1598b7e655ba
duration: 3833
source-git-commit: 9a297cda953d4414131657f9ac84580aea0eabeb
workflow-type: tm+mt
source-wordcount: '675'
ht-degree: 0%

---

# 전문가에게 문의: Tag(Launch)의 유용한 확장 기능으로 Web SDK의 비용 절감

구현을 새로운 Adobe Web SDK로 마이그레이션하시겠습니까?  Adobe 태그 라이브러리에서 데이터 수집을 한 단계 업그레이드하는 데 도움이 되는 자주 사용하는 확장 몇 가지를 살펴보겠습니다.

>[!VIDEO](https://video.tv.adobe.com/v/346610/?quality=12&learn=on)

## 쇼의 질문 및 댓글

### Evolytics의 Data Element Assistant 확장

<br> 
**질문:** 데이터 보안의 관점에서 볼 때 Evolytics는 타사 확장이므로 안전하게 사용할 수 있습니까?

**답변:** 예. 원하는 경우 확장 코드를 검토할 수 있으며, 날짜를 저장하지 않고 변환만 수행합니다.

<br> 

**질문:** 이 캡처는 Adobe ECID도 캡처합니까?

**답변:** Adobe ECID는 해당 확장 내에서 캡처되지 않습니다. 이 확장은 (여러 가지 중에서) 추가 익명 식별자를 만들기 위한 것입니다.

**답변:** 그러나 Adobe ECID는 다른 방법으로 캡처할 수 있습니다. 여기에서 링크를 공유할 수 없으므로 ExL 노트와 Twitter을 통해 공유하겠습니다.

<br> 

**질문:** 해시 기능은 SHA-256과 같은 다양한 해시 기술을 제공하고 공개 및 개인 키를 제공합니까?

**답변:** 그래! SHA-256이 기본값입니다.

<br> 

### 일반적인 질문 및 의견:

<br> 

**질문:** 확장에 대한 소스 파일을 다운로드하려면 무엇을 클릭해야 합니까? &quot;3점 메뉴&quot;에 있는 건가요?

**답변:** 예! 점 3개를 선택한 다음 소스 다운로드(카탈로그 보기에서)

<br> 

**댓글:** 확장과 함께 정말 찾는 것 중 하나는 시간 절약적인 측면입니다. 많은 사람들이 당신 일을 합니다 *할 수 있음* 일부 사용자 지정 코드를 사용하지만 확장명을 사용하면 해당 코드를 작성할 필요가 없습니다.

**회신:** 맞습니다. 매번 바퀴를 다시 만들지 않아도 반복 가능합니다.

<br> 

**질문:** Analytics 플러그인은 어떻게 지원되거나 웹 SDK 구현으로 대체됩니까?

**답변:** 작업 영역과 Adobe 태그의 추가된 유연성 덕분에 요즘은 많은 분석 플러그인이 실제로 필요하지 않습니다. 그러나 그렇지 않은 항목은 Web SDK에서 사용하기 위해 적극적으로 마이그레이션되고 있습니다.

<br> 

**질문:** Web SDK를 사용한 Activity Map 추적에 대한 개발이 있습니까?

**답변:** Web SDK에서도 Activity Map이 지원을 위해 활발히 진행 중임을 알려 드립니다

<br> 

**질문:** 최종 대상으로 전송하기 전에 이벤트를 관리하기 위해 Adobe Edge 네트워크에 액세스할 수 있습니까? Launch에서도 할 수 있는 것으로 알고 있는데, 앞으로는 서버에서도 할 수 있을까요?

**답변:** 예! 이는 고객이 Real-Time CDP 제품(Real-Time CDP Connections, Prime 또는 Ultimate)을 통해 구매할 수 있는 이벤트 전달 기능을 통해 가능합니다.

**답변:** RTCDP 연결(이벤트 전달)은 adobe가 아닌 대상으로 전송하기 전에 더 많은 제어를 할 수 있는 기능을 제공합니다.

**답변:** 이에 대한 자세한 내용은 다른 ExL Live 비디오를 참조하십시오. [이 항목](exl-live-episode-06-23-22.md)).

<br> 

**댓글:** 즐겨 찾는 확장 중 하나에 대한 빠른 호출: 데이터 요소에 대한 테이블을 읽을 수 있는 매핑 테이블 확장이 있습니다. &quot;이 값이 이 값이면 이 값으로 설정합니다.&quot;

**회신:** 그들이 제공하는 유연성은 상당히 인상적이다. 또한 회사는 선택하는 경우 자체 비공개 확장을 만들 수도 있습니다.

<br> 

**질문:** 도시와 날씨 같은 CRM의 개별 데이터를 보여주셨는데, 개별 응답을 저장하는 곳은 어디입니까?

**답변:** 응답은 이벤트 전달 속성 내에서 규칙을 트리거하는 각 고유 이벤트에 저장되며 특정 이벤트에서만 사용됩니다.

<br> 

에서 이 주제에 대한 토론 계속 [Experience League 커뮤니티 토론](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-platform/experience-league-live-post-session-discussion-useful-extensions/m-p/542620#M240).
<br> 

## 이 데이터 수집 시리즈의 추가 Experience League 라이브 세션

* [전문가에게 문의 - Web SDK 기본 사항](exl-live-episode-05-26-22.md)
* [전문가에게 문의 - RTCDP Connections](exl-live-episode-06-23-22.md)
* [전문가에게 문의 - 데이터 스트림 및 데이터 준비](exl-live-episode-07-21-22.md)
