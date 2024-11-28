---
title: Adobe Experience Manager 신속한 개발 환경
description: DevOps Life 2024에 설명된 대로 Adobe의 새로운 SDK를 사용하여 클라우드 환경에서 신속한 개발 및 배포를 용이하게 하고 배포 시간을 크게 단축하며 빠른 업데이트, 라이브 로그 및 고급 구성 옵션을 지원합니다.
feature: Developer Tools
topic: Development
role: Developer
level: Beginner, Intermediate
doc-type: Event
duration: 2427
last-substantial-update: 2024-11-27T00:00:00Z
jira: KT-16570
source-git-commit: 07d4174b0d89ba2c417866e76ae72f015b91b03a
workflow-type: tm+mt
source-wordcount: '337'
ht-degree: 0%

---


# Adobe Experience Manager 신속한 개발 환경

RDE(신속한 개발 환경) 및 업데이트된 개발자 콘솔에 대한 모범 사례를 살펴봅니다. Adobe의 소프트웨어 개발 엔지니어인 Natalia Angulo Herrera와 Adobe의 소프트웨어 개발 엔지니어인 Remo Liechti가 마이그레이션 문제, AIO CLI 설정, 배포, 테스트, 로깅 및 구성 관리를 지원하여 보다 원활한 Adobe Experience Manager 워크플로를 구현합니다.

>[!VIDEO](https://video.tv.adobe.com/v/3440397/?learn=on&enablevpops)


## 커뮤니티 토론

Adobe Developers Live 커뮤니티 [토론](https://adobe.ly/3UJluDo)에서 대화를 계속합니다.

## 주요 개선 사항

* **DevOps Life 2024 소개** 세션은 빠른 개발 환경에 초점을 맞추어 Adobe의 Natalia와 Remo가 호스팅합니다.
* **문제 설명** 로컬 개발 환경이 로컬에서 잘 작동하지만 클라우드에 배포할 때 실패하는 문제입니다.
* **솔루션** 클라우드에서 새로운 SDK를 만들어 신속한 개발 및 배포를 용이하게 하여 시간을 30분에서 초 또는 몇 분으로 단축했습니다.
* **배포 프로세스** 새 환경을 사용하면 새로운 API 및 CLI 플러그인을 통해 빠른 업데이트와 유효성 검사를 수행할 수 있으므로 더 빠른 피드백과 배포를 가능하게 합니다.
* **인프라의 차이점** 클라우드 환경은 고가용성 없이 단일 작성자 및 게시 인스턴스를 사용하며 MongoDB를 사용하지 않습니다.
* **설치 및 사용** 개발자는 클라우드 인터페이스를 통해 설치 및 구성에 npm 및 Adobe IO CLI를 사용하여 신속한 개발 환경을 설정할 수 있습니다.
* **기본 명령** 주요 명령에는 io amd —help, io login, io status, io install, io history, io delete 및 io reset이 포함됩니다.
* **로깅 및 디버깅** 새 환경은 io am 또는 d 로그와 같은 명령을 사용하여 재배포 없이 라이브 로그 및 로그 수준 변경을 지원합니다.
* **고급 항목** 프론트엔드 패키지 및 구성 파이프라인을 지원하므로 빠른 배포와 반복이 가능합니다.
* **예정된 기능** 콘텐츠 손실 없이 보다 쉬운 환경 재설정 및 자동 업데이트를 위해 스냅샷 기능을 도입할 계획입니다.
* **Q&amp;A 및 피드백** 세션에서는 개발팀과의 실시간 상호 작용 및 피드백을 위해 참가자가 Discord 채널에 참여할 것을 권장합니다.