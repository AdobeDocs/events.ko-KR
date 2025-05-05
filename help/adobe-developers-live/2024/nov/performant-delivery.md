---
title: 성능 향상 전달에 대한 우수 사례
description: 적응형 스트리밍, 사용자 지정 비디오 프로필, SEO 모범 사례, 이미지 최적화, 벌크 콘텐츠 관리, 뷰어 사전 설정, 캐시 무효화 및 스마트 이미징을 활용하여 Dynamic Media에서 미디어 전달 및 성능을 최적화합니다.
feature: Dynamic Media, Video, SEO Optimization, Smart Imaging, Viewer Presets, Best Practices
topic: Content Management
solution: Experience Manager, Experience Manager Assets
role: Developer
level: Beginner, Intermediate
doc-type: Event
duration: 1596
last-substantial-update: 2024-11-26T00:00:00Z
jira: KT-16572
exl-id: a1920020-b9ce-43be-8f9e-e52aac68da7b
source-git-commit: 946d7cd484e8c5d4358d4099b3518705cab8d4a3
workflow-type: tm+mt
source-wordcount: '368'
ht-degree: 0%

---

# 성능 향상 전달에 대한 우수 사례

Adobe의 수석 제품 관리자인 Riya Midha와 함께 Adobe Experience Manager Assets Dynamic Media 설정을 위한 모범 사례를 살펴보십시오. 에셋 전달을 최적화하고, 비디오 스트리밍을 개선하고, 뷰어를 구성하고, 성능을 측정 및 개선하는 방법에 대해 알아봅니다.

>[!VIDEO](https://video.tv.adobe.com/v/3440424/?learn=on&enablevpops&captions=kor)

## 커뮤니티 토론

Adobe Developers Live 커뮤니티 [토론](https://adobe.ly/3YGedpb)에서 대화를 계속합니다.

## 주요 개선 사항

* **Dynamic Media 기능** Dynamic Media을 사용하면 장치 간에 고품질의 개인화된 미디어를 빠르고 유연하게 제공할 수 있으며, 연간 9조 건이 넘는 미디어 게재 및 최대 690억 개의 자산에 대한 일일 최대 처리 수량을 처리할 수 있습니다.
* **적응형 스트리밍** 비디오 게재에 적응형 스트리밍을 사용하면 버퍼링이 크게 줄어듭니다. 테스트는 5 Mbps의 제한된 대역폭을 사용하는 60초 비디오에서 버퍼 카운트가 50에서 5로 감소하는 것을 보여주었다.
* **비디오 프로필** 다양한 품질 인코딩으로 사용자 지정 비디오 프로필을 만들면 다양한 네트워크 조건에서 최적의 비디오 성능을 보장할 수 있습니다.
* **SEO 모범 사례**
   * 규칙 세트를 사용하여 더 나은 SEO를 위한 설명 URL을 만드십시오.
   * 이미지에 대체 텍스트 및 제목 속성을 추가합니다.
   * 스마트 이미징 및 WebP와 같은 최신 이미지 형식을 활용하여 검색 등급을 높일 수 있습니다.
* **이미지 최적화**
   * 배율 매개 변수를 사용하여 화면 크기에 따라 이미지 해상도를 조정합니다.
   * 이미지에는 100% 품질을 사용하지 마십시오. 대신 80-90% 범위를 사용하여 눈에 띄는 품질 손실 없이 파일 크기를 줄입니다.
   * 선명하게 하기 매개 변수를 적용하여 이미지의 텍스트 선명도를 향상시킵니다.
* **일괄 컨텐츠 관리**
   * Dynamic Media 전달을 위한 컨텐츠를 다른 컨텐츠와 분리합니다.
   * 선택적 동기화를 사용하여 처리 시간을 최적화하고 출시 시간을 향상시킵니다.
* **뷰어 사전 설정** 코드를 변경하지 않고 뷰어 사전 설정을 사용하여 뷰어 모양 및 동작을 사용자 지정합니다. 예를 들면 재생/일시 중지 단추 편집, 자동 재생 및 루프 활성화, 이미지 오버레이 추가 등이 있습니다.
* **캐시 무효화** 캐시 무효화를 사용하여 기본 10시간 TTL을 건너뛰고 이미 게시된 자산에 대한 변경 내용을 즉시 반영합니다.
* **모니터링 및 디버깅** AEM 데스크톱 앱 및 쿼리 디버거 페이지와 같은 도구를 사용하여 처리 작업을 추적하고 처리되지 않은 에셋을 식별합니다.
* **스마트 이미징** 스마트 이미징이 모든 도메인에서 기본적으로 활성화되어 이미지 파일 크기를 줄이고 로드 시간을 단축할 수 있습니다.
