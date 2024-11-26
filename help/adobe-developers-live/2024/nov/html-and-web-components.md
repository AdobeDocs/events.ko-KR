---
title: 웹 구성 요소로 나만의 HTML 롤하기
description: 사용자 지정 요소, Shadow DOM, HTML 템플릿을 포함한 Adobe 수석 개발자 Raymond Camden과 함께 웹 구성 요소의 기본 사항에 대해 알아보고 PDF 포함, 정렬 가능한 테이블 작성 등 실용적인 사례를 들어 애플리케이션을 향상시킵니다.
topic: Development
role: Developer
level: Beginner, Intermediate
doc-type: Event
duration: 2580
last-substantial-update: 2024-11-26T00:00:00Z
jira: KT-16579
source-git-commit: 8770c8172ee90524079efc65aec7e129f1d1d031
workflow-type: tm+mt
source-wordcount: '343'
ht-degree: 0%

---


# 웹 구성 요소로 나만의 HTML 롤하기

Adobe 수석 개발자 전도사인 Raymond Camden과 함께 사용자 지정 요소, Shadow DOM 및 HTML 템플릿을 포함한 웹 구성 요소의 기본 사항에 대해 알아보십시오. 재사용 가능한 최신 솔루션으로 애플리케이션을 개선하기 위해 PDF 임베드 및 정렬 가능한 테이블 구축과 같은 실제 사례를 탐색합니다.

>[!VIDEO](https://video.tv.adobe.com/v/3440406/?learn=on&enablevpops)

## 커뮤니티 토론

Adobe Developers Live 커뮤니티 [토론](https://adobe.ly/48PRE63)에서 대화를 계속합니다.

## 주요 학습 사항

* **웹 구성 요소 소개** 웹 구성 요소를 통해 개발자는 JavaScript을 사용하여 정의된 대로 고유한 모양과 상호 작용성으로 사용자 지정 HTML 요소를 만들 수 있습니다.
* **핵심 기술** 웹 구성 요소는 사용자 지정 요소** 섀도 DOM 및 HTML 템플릿의 세 가지 핵심 기술을 사용하여 빌드되었습니다.
* **사용자 지정 요소** 사용자 지정 요소를 사용하여 새 HTML 태그를 만들 수 있습니다. Kebab-case를 사용하고 대시를 포함해야 합니다. JavaScript 클래스는 동작을 정의하는 데 사용됩니다.
* **섀도 DOM** 섀도 DOM은 구성 요소의 DOM 트리에 대한 캡슐화를 제공하여 CSS 누출을 방지하고 더 제어된 스타일을 허용합니다.
* **HTML 템플릿** HTML 템플릿을 통해 복제하여 DOM에 추가할 수 있는 HTML 및 CSS를 정의할 수 있습니다. 그러나 발표자는 더 나은 배포와 유연성을 위해 템플릿보다 슬롯을 사용하는 것을 선호합니다.
* **특성 및 이벤트** 사용자 지정 요소에는 DOM에서 추가하거나 제거할 때 동작을 관리하기 위한 connectedCallback 및 disconnectedCallback과 같은 특성 및 이벤트 처리기가 있을 수 있습니다.
* **슬롯** 슬롯을 사용하면 웹 구성 요소에 컨텐츠를 삽입할 수 있으므로 보다 유연한 컨텐츠 관리를 위해 기본 슬롯과 명명된 슬롯을 모두 지원합니다.
* **실제 예제** 예에는 웹 구성 요소의 실제 적용을 보여 주는 PDF 포함 뷰어, 이미지 자리 표시자 및 테이블 분류기가 포함됩니다.
* **점진적 개선** 웹 구성 요소는 JavaScript을 로드하지 못하는 경우 기능을 손상시키지 않고 기존 HTML을 개선할 수 있습니다.
* **다음 단계 및 리소스** 프레젠테이션에서는 양식 기여도, 선언적 섀도 DOM, 사용자 지정 HTML 특성 및 서버측 렌더링을 살펴볼 것을 제안합니다. 리소스에는 MDN, webcomponents.org 및 Ben Farrell의 &quot;Web Components in Action&quot; 책이 포함되어 있습니다.