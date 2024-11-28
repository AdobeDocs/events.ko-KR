---
title: 200호 참호 이야기
description: 성능을 우선시하고, Google PageSpeed Insights를 사용하고, LCP 및 TBT와 같은 주요 지표를 최적화하고, 리소스를 효율적으로 관리하고, 개발 및 이미지 최적화를 위한 모범 사례를 따라 웹 프로젝트의 성공을 보장합니다.
solution: Experience Manager, Experience Manager Sites
feature: Edge Delivery Services
role: Developer
level: Beginner, Intermediate
doc-type: Event
duration: 1321
last-substantial-update: 2024-11-27T00:00:00Z
jira: KT-16541
source-git-commit: 07d4174b0d89ba2c417866e76ae72f015b91b03a
workflow-type: tm+mt
source-wordcount: '296'
ht-degree: 0%

---


# 200호 참호 이야기

200개 이상의 Edge Delivery Services 프로젝트가 완료됨에 따라 Adobe 수석 엔지니어인 Kiran Muruguulla와 Adobe Experience Manager Cloud의 설계자인 Varun Mitra는 학습한 주요 교훈을 공유합니다. 뛰어난 핵심 웹 바이탈을 통해 빠르고 높은 성과를 제공하는 비결에 대해 알아보십시오.


>[!VIDEO](https://video.tv.adobe.com/v/3439424/?learn=on&enablevpops)

## 커뮤니티 토론

Adobe Developers Live 커뮤니티 [토론](https://adobe.ly/4fwWvvi)에서 대화를 계속합니다.

## 주요 개선 사항

* **성능이 매우 중요합니다** 성능, 특히 웹 페이지의 속도가 성공적인 웹 프로젝트의 핵심 요소로 강조됩니다. 100의 성능 점수를 보장하는 것이 주요 목표입니다.
* **개발 사례**
   * 개발 중 지속적인 테스트를 위해 Google PageSpeed Insights 를 사용하십시오.
   * 이미 100점을 받는 표준 코드로 프로젝트를 시작하여 높은 성능을 유지합니다.
   * 병합하기 전에 가져오기 요청(PR)이 성능 표준을 충족하는지 확인하십시오.
* **주요 지표** 성능 점수에 큰 영향을 미치므로 LCP(최대 콘텐츠풀 페인트) 및 TBT(총 차단 시간)를 최적화하는 데 중점을 둡니다.
* **리소스 관리**
   * 프로젝트 소스 내에 글꼴 및 서드파티 스크립트와 같은 필수 리소스를 포함합니다.
   * 글꼴 폴백을 사용하여 로드 시간을 개선합니다.
   * 초기 로드 성능을 개선하기 위해 필수가 아닌 스크립트 로드를 지연합니다.
* **이미지 최적화** 접힌 것보다 높은 이미지 로딩의 우선 순위를 지정하고 중요한 이미지에 대해 우선 순위가 높은 가져오기 설정을 사용합니다.
* **사례 연구**
   * ***CNN.com*** 쿼리 인덱스를 최적화하고 Google 광고 로드를 지연하여 성능을 개선했습니다.
   * ***Herbert 홈*** 사용자가 스크롤할 때 Intersection Observer API를 사용하여 데이터를 로드하여 성능과 사용자 경험을 개선했습니다.
* **모범 사례**
   * 상용구 코드로 시작하여 잘 구성된 마크업을 사용합니다.
   * 고급 CSS 선택기를 활용하고 JavaScript 조작을 최소화합니다.
   * 모바일 우선 개발에 주력하십시오.
   * 작성자가 콘텐츠 구조를 직관적으로 이해할 수 있도록 합니다.
* **도구** 시간에 따른 사이트 성능 점수를 추적하는 데 Google Sheets 및 DSA와 같은 도구를 사용합니다.

