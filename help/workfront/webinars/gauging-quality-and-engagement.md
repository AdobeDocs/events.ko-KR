---
title: 전문가에게 문의 - 품질 및 참여 평가
description: 품질 및 참여 질문에 대한 답변을 제공하는 보고서를 작성하는 방법을 알아봅니다. 이 웨비나는 2019년 11월 13일에 녹화되었습니다.
activity: use
doc-type: feature video
team: Technical Marketing
kt: 9914
exl-id: 76a8e418-71c7-414a-9938-e64e4e73c184
source-git-commit: 1792dc318643aec2c12613f621361d72a7a918b1
workflow-type: tm+mt
source-wordcount: '1211'
ht-degree: 1%

---

# 전문가에게 문의 - 품질 및 참여 평가

품질 및 참여 질문에 대한 답변을 제공하는 보고서를 작성하는 방법을 알아봅니다. 이 웨비나는 2019년 11월 13일에 녹화되었습니다.

>[!VIDEO](https://video.tv.adobe.com/v/341120/?quality=12)

## Q&amp;A

**질문**

필터링 기준으로 사용할 수 있는 일부 필드가 있지만 그룹화하려고 할 때는 사용할 수 없습니다. 일관된 옵션을 만들기 위해 노력하고 있습니까?

**답변**

보고 도구를 사용하면 동적 필드로 그룹화하거나 확인란 필드처럼 한 번에 여러 개의 선택을 할 수 있는 필드로 그룹화할 수 없습니다. 선택 항목이 많을 수 있지만 단일 값이 있는 필드에서만 그룹화할 수 있습니다.

확인란을 기준으로 필터링하고 볼 수 있으며, 확인란에 대해 그룹화할 수 없습니다.

**질문**

작업 역할 의 반복에서 기본 역할을 굵게 표시할 수 있습니까?

**답변**

반복에서 기본 작업 역할을 식별할 수 있습니다. valueexpression에서 이를 수행해야 하지만 HTML 코드는 valueexpression에서 인식되지 않습니다. 그래서 우리는 그 역할을 1차적인 것으로 파악하는 다른 방법을 생각해내야 한다. 이 코드에서 기본 역할 이름 앞과 뒤에 &quot;**&quot;을 넣습니다. 한 번 시도해보고 어떤지 봐보세요.

```
displayname=All Job Roles 
listdelimiter=<p> 
listmethod=nested(userRoles).lists 
textmode=true
type=iterate 
valueexpression=IF({user}.{roleID}={role}.{ID},CONCAT("**",{role}.{name},"**"),{role}. {name})
valueformat=HTML
```

이렇게 하면 다음과 같은 목록이 제공됩니다.

```
Support Engineer 
QA Engineer 
**Designer**
```

여기서 Designer는 이 사용자의 기본 역할입니다.

**질문**

안녕하세요! 기사의 라이프사이클(초기 작성 —> 부서 검토 —> 최종 편집 —> 게시) 위치를 추적하는 편집 팀의 워크플로우를 준비하고 있습니다. 마일스톤 또는 현재 작업이 있는 위치를 쉽게 확인할 수 있습니다. 내가 받는 피드백은 표준 이정표 보기(빨간색 또는 녹색 음영 사용)가 너무 &quot;바쁘고 복잡함&quot;이라는 것입니다. 테이블 또는 그리드에 &quot;프로젝트 이름&quot;과 &quot;현재 마일스톤&quot;만 표시하는 방법이 있습니까?

**답변**

예. 현재 작업 중인 마일스톤 작업과 연결된 작업을 표시하는 작업 보고서를 만들 수 있습니다. 이 작업은 표 또는 목록 보고서에서 수행할 수 있습니다.

**질문**

보고서에서 프로젝트 정보와 증명 정보를 결합할 수 있습니까?

**답변**

증명 승인 보고서를 만든 경우 프로젝트 정보를 텍스트 모드를 사용하여 열로 가져올 수 있습니다. 예를 들어 열에서 프로젝트 이름을 참조하려는 경우 다음을 사용할 수 있습니다.

```
displayname=Project Name
textmode=true 
valuefield=documentVersion:document:project:name 
valueformat=HTML
```

**질문**

또한 프로젝트와 관련된 증명 데이터 보고에 대한 자세한 정보가 필요합니다. 예를 들어 증명 결정 및 댓글이 포함된 프로젝트 보고서입니다.

**답변**

단일 보고서에서 프로젝트 정보 및 증명 정보를 참조하기 위해 증명 승인 보고서를 만들 수 있습니다. 현재 증명의 주석을 이 보고서로 가져올 수 없지만 각 증명 승인자 결정은 승인자 결정 열 아래의 해당 라인 항목에서 찾을 수 있습니다.

**질문**

단일 페이지 상태(많은 열)를 만들기 위해 sharecol을 자주 사용합니다. 그러나 보고서를 만든 후 페이지 맨 위에 열을 추가하려는 경우 돌아가서 수정하는 데 매우 시간이 오래 걸립니다. 이런 종류의 변화를 만들 수 있는 팁이나 요령이 있나요?

**답변**

텍스트 모드 열 목록의 맨 위에 열을 배치하는 것을 말하는 경우 열 번호를 수동으로 다시 지정해야 합니다.

그러나 첫 번째 열이 일부 공유 열인 보고서를 이미 만든 경우 다른 공유 열을 목록의 맨 위에 추가하려는 경우 이 작업이 더 쉽습니다.

보고서 편집기에서 새 열 두 개를 추가하고 열(보기) 화면의 맨 왼쪽으로 드래그하면 됩니다. 이렇게 하면 왼쪽 열에 사용된 항목이 표시되고 텍스트 모드 열 번호가 모두 증가함을 알 수 있습니다. 빈 열을 필요한 만큼 끌어서 놓습니다. 저장하기 전에 반드시 빈 칸에 무언가를 넣어 두십시오. 그렇지 않으면 그것들이 제거될 것입니다.

**질문**

안녕하세요 - 최종 버그 보고서와 관련하여 - 여러 프로젝트에 대해 버그가 발생하는 경우 여러 프로젝트에 대해 보고서를 어떻게 수행할 수 있습니까??

**답변**

작업을 구성한 방법에 따라 포트폴리오 또는 프로젝트별로 필터링할 수 있습니다.

요청 대기열을 필터링할 수도 있습니다. 공유한 요청 대기열에 직접 로그인하고 티켓을 제출할 수 있는 검토자로 고객 사용자를 만들 수 있는 각 프로젝트에 대한 요청 대기열을 설정할 수 있습니다.

**질문**

첫 번째 보고서는 프로젝트/프로젝트 이름을 기반으로 했습니다. 작업에 대해서도 이 작업을 수행할 수 있으며, 작업 이름이 자주 다를 수 있으므로 가장 좋은 방법으로 그룹화할 수 있습니다. 감사합니다!

**답변**

이러한 모든 보고서는 항목을 추적하는 방법에 따라 작업, 문제 또는 프로젝트 보고서로 수행할 수 있습니다.

작업을 그룹화하는 일반적인 방법은 먼저 해당 프로젝트 이름으로 그룹화한 다음 각 프로젝트 내에서 작업 이름으로 그룹화하는 것입니다. 이렇게 하면 이름이 같은 두 개의 작업이 있는 경우 해당 작업의 프로젝트를 쉽게 볼 수 있습니다.

**질문**

어떤 증명이 미결인지, 어떤 작업과 프로젝트에 연결되어 있는지, 언제 라우팅되었는지, 마감일은 언제인지, 누가 중재자와 승인자인지 알고 싶습니다.

**답변**

처리되지 않은 증명은 증명 승인 보고서 내에서 결정 대기 > 같음 > 참으로 필터링할 수 있습니다. 아직 결정하지 않은 사용자를 설명하는 승인자 열이 있습니다.

텍스트 모드를 사용하여 증명이 연결된 작업 또는 프로젝트를 참조할 수 있습니다(아래 예 참조).

```
displayname=Task Name
textmode=true 
valuefield=documentVersion:document:task:name 
valueformat=HTML
```

```
displayname=Project Name
textmode=true 
valuefield=documentVersion:document:project:name
valueformat=HTML
```

라우팅 날짜, 기한 및 중재자의 경우 이러한 필드를 현재 Workfront의 보고서로 가져올 수 없으므로 증명을 직접 클릭하여 해당 정보를 확인해야 합니다.

**질문**

요청이 완료되면 요청자에게 자동으로 보내도록 사용자 정의 양식을 설정할 수 있습니까? 고객 만족도 조사처럼?

**답변**

여러분의 필요를 충족시킬 수 있는 한 가지 방법이 있습니다. 실제 완료 일자를 입력한 후 &quot;입력자&quot;에게 이메일을 보내는 문제에 미리 알림 을 첨부할 수 있습니다. 입력한 사람 은 문제를 만든 사람입니다.

리마인더 알림은 &quot;AAR(After Action Review)&quot; 웨비나에서 수행한 것처럼 만듭니다. 단, 이것이 문제 리마인더일 수 있습니다. 설문 조사 링크를 제공하기 위해 이메일 템플릿도 만들 수 있습니다. 각 문제에 미리 알림을 수동으로 적용(또는 벌크 편집 사용)해야 합니다.

통합하면 수동 단계를 자동화할 수 있으므로 더 좋지만 미리 알림을 즉시 수행할 수 있습니다.

**질문**

템플릿 유형별 프로젝트를 보여 주는 보고서를 만들었습니다. 프로젝트 소유자는 나열할 수 있지만 프로젝트에 할당된 사람은 나열할 수 없습니다.

**답변**

프로젝트 팀(스태핑 탭)을 프로젝트 보고서의 열로 가져오려면 텍스트 모드를 통해 만들어야 합니다. 텍스트 모드는 다음과 같습니다.

```
displayname=Staffing 
listdelimiter=<p> 
listmethod=nested(projectUsers).lists 
textmode=true
type=iterate 
valuefield=user:name 
valueformat=HTML
```

## AAR 참여 보고서에 대한 텍스트 모드 코드

```
column.0.displayname=Task Details
column.0.value=<b>Project Name:</b>&nbsp;
column.0.valueformat=HTML
column.0.sharecol=true
column.1.valuefield=project:name
column.1.valueformat=HTML
column.1.sharecol=true
column.2.value=<br>
column.2.valueformat=HTML
column.2.sharecol=true
column.3.value=<b>Task Name:</b>&nbsp;
column.3.valueformat=HTML
column.3.sharecol=true
column.4.valuefield=name
column.4.valueformat=HTML
column.4.sharecol=true
column.5.value=<br>
column.5.valueformat=HTML
column.5.sharecol=true
column.6.value=<b>Task Owner:</b>&nbsp;
column.6.valueformat=HTML
column.6.sharecol=true
column.7.valuefield=assignedTo:name
column.7.valueformat=HTML
column.7.sharecol=true
column.8.value=<br>
column.8.valueformat=HTML
column.8.sharecol=true
column.9.value=<b>Actual Completion Date:</b>&nbsp;
column.9.valueformat=HTML
column.9.sharecol=true
column.10.valuefield=actualCompletionDate
column.10.valueformat=HTML
column.11.displayname=Name of Reviewer
column.11.linkedname=Name of Reviewer
column.11.namekey=view.relatedcolumn
column.11.namekeyargkey.0=Name of Reviewer
column.11.namekeyargkey.1=name
column.11.querysort=DE:Name of Reviewer:name
column.11.valuefield=Name of Reviewer:name
column.11.valueformat=customReferenceObjectAsString
column.12.displayname=AAR 1
column.12.description=In your view, does the work match stakeholders’ expectations? Did we achieve the intended results?
column.12.value=<b>AAR 1 Score:</b>&nbsp;
column.12.valueformat=HTML
column.12.sharecol=true
column.13.valuefield=AAR 1 - In your view, does the work match stakeholders’ expectations? Did we achieve the intended results?
column.13.valueformat=customDataLabelsAsString
column.13.sharecol=true
column.14.value=<br>
column.14.valueformat=HTML
column.14.sharecol=true
column.15.value=<br><b>AAR 1 User Comment:</b>&nbsp;
column.15.valueformat=HTML
column.15.sharecol=true
column.16.valuefield=AAR 1 User Comment
column.16.valueformat=customDataLabelsAsString
column.17.linkedname=direct
column.17.namekey=AAR 1 Reviewer Comment
column.17.querysort=DE:AAR 1 Reviewer Comment
column.17.valuefield=AAR 1 Reviewer Comment
column.17.valueformat=customDataLabelsAsString
column.18.linkedname=direct
column.18.displayname=AAR 1 Needs Attn
column.18.querysort=DE:AAR 1 Needs Attention
column.18.valuefield=AAR 1 Needs Attention
column.18.valueformat=customDataLabelsAsString
column.19.linkedname=direct
column.19.displayname=AAR 1 Needs Attn Notes
column.19.querysort=DE:AAR 1 Needs Attention Notes
column.19.valuefield=AAR 1 Needs Attention Notes
column.19.valueformat=customDataLabelsAsString
column.20.displayname=AAR 2
column.20.description=Do You Believe This Work Will Make an Impact?
column.20.value=<b>AAR 2 Score:</b>&nbsp;
column.20.valueformat=HTML
column.20.sharecol=true
column.21.valuefield=AAR 2 - Do You Believe This Work Will Make an Impact?
column.21.valueformat=customDataLabelsAsString
column.21.sharecol=true
column.22.value=<br>
column.22.valueformat=HTML
column.22.sharecol=true
column.23.value=<br><b>AAR 2 User Comment:</b>&nbsp;
column.23.valueformat=HTML
column.23.sharecol=true
column.24.valuefield=AAR 2 User Comment
column.24.valueformat=customDataLabelsAsString
column.25.linkedname=direct
column.25.namekey=AAR 2 Reviewer Comment
column.25.querysort=DE:AAR 2 Reviewer Comment
column.25.valuefield=AAR 2 Reviewer Comment
column.25.valueformat=customDataLabelsAsString
column.26.linkedname=direct
column.26.displayname=AAR 2 Needs Attn
column.26.querysort=DE:AAR 2 Needs Attention
column.26.valuefield=AAR 2 Needs Attention
column.26.valueformat=customDataLabelsAsString
column.27.linkedname=direct
column.27.displayname=AAR 2 Needs Attn Notes
column.27.querysort=DE:AAR 2 Needs Attention Notes
column.27.valuefield=AAR 2 Needs Attention Notes
column.27.valueformat=customDataLabelsAsString
column.28.displayname=AAR 3
column.28.description=Are you proud of the work you did on this?
column.28.value=<b>AAR 3 Score:</b>&nbsp;
column.28.valueformat=HTML
column.28.sharecol=true
column.29.valuefield=AAR 3 - Are you proud of the work you did on this?
column.29.valueformat=customDataLabelsAsString
column.29.sharecol=true
column.30.value=<br>
column.30.valueformat=HTML
column.30.sharecol=true
column.31.value=<br><b>AAR 3 User Comment:</b>&nbsp;
column.31.valueformat=HTML
column.31.sharecol=true
column.32.valuefield=AAR 3 User Comment
column.32.valueformat=customDataLabelsAsString
column.33.linkedname=direct
column.33.namekey=AAR 3 Reviewer Comment
column.33.querysort=DE:AAR 3 Reviewer Comment
column.33.valuefield=AAR 3 Reviewer Comment
column.33.valueformat=customDataLabelsAsString
column.34.linkedname=direct
column.34.displayname=AAR 3 Needs Attn
column.34.querysort=DE:AAR 3 Needs Attention
column.34.valuefield=AAR 3 Needs Attention
column.34.valueformat=customDataLabelsAsString
column.35.linkedname=direct
column.35.displayname=AAR 3 Needs Attn Notes
column.35.querysort=DE:AAR 3 Needs Attention Notes
column.35.valuefield=AAR 3 Needs Attention Notes
column.35.valueformat=customDataLabelsAsString
column.36.displayname=Done
column.36.valuefield=Review Complete
column.36.valueformat=customDataLabelsAsString
```
