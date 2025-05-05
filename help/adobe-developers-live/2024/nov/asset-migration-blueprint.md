---
title: Assets 마이그레이션 블루프린트
description: 관련자 분석, 리소스 계획, 데이터 변환, 데이터 처리를 위한 CSV 파일 사용과 같은 모범 사례에 대한 Achim Koch의 통찰력을 통해 레거시 DAM을 Adobe Experience Manager Assets으로 마이그레이션하는 방법에 대해 알아봅니다.
feature: Migration
topic: Migration
solution: Experience Manager, Experience Manager Assets
role: Developer
level: Beginner, Intermediate
doc-type: Event
duration: 1690
last-substantial-update: 2024-11-26T00:00:00Z
jira: KT-16576
exl-id: f588055b-05c7-44df-be67-799a0e3ee1ed
source-git-commit: 946d7cd484e8c5d4358d4099b3518705cab8d4a3
workflow-type: tm+mt
source-wordcount: '338'
ht-degree: 0%

---

# Assets 마이그레이션 블루프린트

Adobe의 수석 기술 설계자 Achim Koch와 함께 이전 DAM을 Adobe Experience Manager Assets으로 마이그레이션하는 방법을 알아보십시오. 관련자 분석, 리소스 계획, 데이터 변환 및 데이터 처리를 위한 CSV 파일 사용과 같은 모범 사례에 대한 통찰력을 얻으십시오. 고유한 Adobe Experience Manager 마이그레이션 프로젝트에 대한 로드맵을 빌드합니다.

>[!VIDEO](https://video.tv.adobe.com/v/3440446/?learn=on&enablevpops&captions=kor)

## 커뮤니티 토론

Adobe Developers Live 커뮤니티 [토론](https://adobe.ly/4hKHpnF)에서 대화를 계속합니다.

## 주요 개선 사항

* **마이그레이션을 위한 기본 도구 없음** 제품 및 사용자 지정 솔루션의 다양성으로 인해 다양한 레거시 시스템에서 Adobe Experience Manager(AEM)로 마이그레이션할 수 있는 단일 도구가 없습니다.

* **마이그레이션 5단계**

   * 프로젝트 계획
   * 구현 계획
   * AEM 구현
   * 마이그레이션 스크립트 구현
   * 마이그레이션 실행

* **관련자 참여** 스폰서, 비즈니스 사용자, IT 시스템 관리자 및 레거시 시스템 지원과 같은 관련자를 확인하고 참여하는 것이 중요합니다.

* **리소스 및 타임라인 계획 수립** 리소스가 사용 가능한지 확인하고 휴일, 최대 업무 시간 및 제한 해제 기간에 대한 계획을 수립합니다.

* **기술 계획** 요구 사항 분석, 데이터 변환 및 인프라 계획이 포함됩니다.

* **반복 프로세스** 마이그레이션은 스크립트 실행, 분석, 피드백 및 적응을 여러 번 반복합니다.

* **CSV 파일 사용** CSV 파일은 마이그레이션 프로세스 중에 쉽게 사용하고 읽을 수 있도록 선호됩니다.

* **스크립팅 언어** Node.js는 CSV, AWS 및 HTTP를 지원하고 JavaScript을 학습할 수 있는 좋은 기회가 되도록 권장됩니다.

* **품질 및 반복 가능성** 고품질 데이터 마이그레이션을 보장하고 원본 데이터와 CSV 파일을 참조용으로 보관하며 프로세스를 반복 가능하게 만드십시오.

* **컨텐츠 고정** 마이그레이션 중에 컨텐츠 고정을 선언하여 스냅숏을 만든 후 새 데이터가 추가되지 않도록 합니다.

* **도구 및 팁** Rainbow CSV 확장명이 있는 VS 코드와 같은 도구를 사용하고 UTF-8 텍스트 파일에 대한 BOM(바이트 순서 표시)을 고려하십시오.

* **비즈니스 승인** 콘텐츠 동결을 해제하기 위해 마이그레이션 후 공식 비즈니스 승인을 테스트하고 가져올 시간을 예약합니다.
