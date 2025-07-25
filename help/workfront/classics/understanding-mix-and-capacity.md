---
title: 전문가에게 문의 - 혼합 및 용량 이해
description: 기업 내 혼합 및 용량을 측정하는 방법에 대해 알아봅니다. 이 웨비나는 2019년 10월 2일에 녹화되었습니다.
doc-type: feature video
team: Technical Marketing
kt: 9913
exl-id: 49cce53f-457b-4973-a0d9-1b5ce2272884
duration: 4239
source-git-commit: 91f20c3e9ee5ae5b259d5cb3da476974acdc6585
workflow-type: tm+mt
source-wordcount: '2229'
ht-degree: 0%

---

# 전문가에게 문의 - 혼합 및 용량 이해

기업 내 혼합 및 용량을 측정하는 방법에 대해 알아봅니다. 이 웨비나는 2019년 10월 2일에 녹화되었습니다.

>[!VIDEO](https://video.tv.adobe.com/v/341119/?quality=12)

## Q&amp;A

**질문**

%s을(를) 어떻게 세로 막대형 차트에 표시합니까?

**답변**

차트 탭에서 &quot;그룹 열&quot; 및 &quot;100%로 스택&quot;을 선택했기 때문에 혼합 보고서에 % 값이 표시되었습니다. &quot;누적됨&quot;을 선택하면 백분율이 아닌 계획된 시간 합계가 표시됩니다.

**질문**

부서/조직 워크로드에 프로젝트/작업 및 문제/요청이 혼재되어 있는 경우, WPI에 대해 Workfront 보고서에서 높은 수준의 검토를 받는 것이 좋습니까?

**답변**

프로젝트, 작업 및 문제는 각각 고유한 사용자 정의 양식이 있는 자체 보고서를 가져야 합니다. 그러나 각 사용자는 동일한 작업 유형 필드를 사용할 수 있습니다. 한 대시보드에 세 개의 보고서를 표시할 수 있습니다.

**질문**

작업을 운영하거나 전략적으로 만들기 위해 작업을 일괄 편집해야 합니까?

**답변**

제안하는 기법은 작동 중인 작업 목록을 가져올 수 있는 보고서를 만드는 것입니다. 모든 작업을 한 번에 선택하고 일괄 편집한 다음 작업 유형이 있는 사용자 정의 양식을 첨부하고 한 번에 모든 작업에 대해 작업 유형을 [작동]으로 설정할 수 있습니다. 동일한 절차에 따라 전략 작업 목록을 수집하고, 일괄 편집하고, 사용자 정의 양식을 추가하는 등의 작업을 수행합니다.

작업 이름, 프로젝트 소유자, 포트폴리오 또는 할당된 사용자의 특정 단어를 확인하는 것과 같이 목록을 얻는 데 도움이 될 수 있는 사용자 지정 프롬프트에 대한 몇 가지 아이디어가 웨비나에 언급되어 있습니다. 이건 그냥 아이디어일 뿐이야 자신의 상황에 가장 적합한 보고서를 작성해야 합니다.

**질문**

내 조합에 4개의 범주가 있는 경우 각각에 대한 목표를 생성한 다음 예측과 계획 및 실제 간의 델타에 대해 보고할 수 있습니까? (4가지 카테고리: Campaign, Business Unit, Web 및 제품). 사용자 정의 양식/필드에 프로젝트 수준의 범주가 있습니다. 목표는 분기별 예측(예산/예측)을 만든 다음 해당 예측을 위한 계획된 시간과 궁극적으로 실제 시간을 추적하는 것입니다.

**답변**

하나의 사용자 정의 필드에 모든 범주가 있는 경우(지금은 작업 유형이라고 함) 계획된 시간 및 작업 유형에 대한 프로젝트 보고서 그룹화를 먼저 만들면 됩니다. 프로젝트 보고서를 필터링하여 원하는 날짜 범위 내에서 Planning에 프로젝트를 표시합니다. 백분율을 보려면 그룹화된 열 또는 막대가 100%로 스택된 차트를 사용합니다. Forecast Report 일 수 있습니다.

보고서를 복사하고 편집하여 현재 프로젝트를 기반으로 보고서를 만들 수 있으며 계획된 시간을 기반으로 한 혼합을 계속 표시할 수 있습니다.

보고서를 다시 복사하고, 계획된 시간 대신 실제 시간별로 그룹화하고, 원하는 날짜 범위 내에 완료된 프로젝트만 표시할 수 있습니다. 실제 시간을 기반으로 한 퍼센트 혼합이 표시됩니다.

**질문**

프로젝트나 작업에 여러 개의 범주 ID가 있는 경우 이것이 작동합니까?

**답변**

예. 여러 ID가 있는 경우 다음과 같이 탭으로 구분해야 합니다.

```
EXISTS:1:$$EXISTSMOD=NOTEXISTS
EXISTS:1:$$OBJCODE=OBJCAT
EXISTS:1:categoryID=5d76d82600e7926bb51eeb1e0886810e 5d54288d01034619f2eb2c74f6472f18
EXISTS:1:objID=FIELD:ID
```

탭 문자로 구분하는 가장 좋은 방법은 빌더에서 카테고리 목록을 먼저 만드는 것입니다. 여러 사용자 정의 양식 이름을 입력하고 텍스트 모드로 전환하면 탭으로 구분된 ID로 표시됩니다.

여러 ID는 OR로 처리되므로 이 중 하나가 작업에 첨부되면 보고서에 표시되지 않습니다.

**질문**

보고서 프롬프트가 &#39;ANDed&#39;입니까? 아니면 &#39;ORed&#39;입니까?

**답변**

개별 사용자 정의 프롬프트는 &#39;ANDed&#39;입니다. 따라서 Pam을 프로젝트 소유자로 지정하고 Bill을 작업에 할당된 것으로 지정하면 Pam이 프로젝트 소유자인 프로젝트에 있는 Bill에 할당된 작업만 표시됩니다.

**질문**

특정 열로만 정렬할 수 있는 이유는 무엇입니까? 즉, 할당별로 정렬할 수 없습니다.

**답변**

&quot;할당&quot;은 목록이며 항목 목록에서 정렬 또는 그룹화할 수 없습니다. 개별 항목에서만 정렬 또는 그룹화할 수 있습니다.

요점을 설명하기 위해 한 작업에서 이와 같은 할당 목록을 상상하십시오.

```
Jane
Bill
Dan
```

다른 작업에 대한 다음과 같은 할당 목록:

```
Bill
Jane
Helen
```

정렬에서 어떤 작업이 먼저 표시되어야 합니까? &quot;목록의 이름별로 정렬&quot;이라고 할 수 있지만 순서를 제어할 수 없으므로 이 작업은 필수로 유용하지 않습니다. Workfront에서는 목록을 기준으로 정렬할 수 없으므로 문제를 방지할 수 있습니다.

목록별로 그룹화하는 것은 어떻습니까? 이름 목록으로 그룹화할 수 있는 경우 Jane, Bill, Dan에게 지정된 모든 태스크와 Jane, Dan, Bill에게 지정된 모든 태스크(동일한 목록이지만 순서가 다른)를 다른 그룹화에서 찾을 수 있습니다. 또한 Workfront에서는 목록별로 그룹화할 수 없으므로 문제가 발생하지 않습니다.

**질문**

전략 작업에 계획된 시간과 실제 운영 시간이 사용됩니까?

**답변**

아니요. 이 예제에서는 계획된 시간을 사용하여 전략 및 운영 작업 모두에 대해 계획된 작업 수준을 표시합니다. 이를 통해 과거든 현재든 미래든 쉽게 비교할 수 있다. 실제 시간을 사용하여 전략 및 운영 작업을 비교할 수도 있지만 실제 시간이 작업에 실제로 소요된 시간으로 보고된 시간이므로 과거의 작업에만 해당됩니다.

**질문**

리소스 플래너에서 과거에 계획되었지만 완료되지 않은 작업을 어떻게 처리합니까? 계획된 시간은 차츰 당겨지지 않을 것 같으므로 향후 몇 주에는 리소스가 필요한 작업/시간으로 표시되지 않습니다.

**답변**

완료되지 않은 작업에는 &quot;자동&quot; 롤포워드 기능이 없습니다. 이 경우 프로젝트를 다시 계획해야 합니다. 원래 특정 작업에 할당한 리소스를 새 일정에서 사용할 수 없는 경우가 있을 수 있으므로 프로젝트 관리자는 이를 살펴보고 가장 적합한 재계획 방법을 결정해야 합니다. 이해 당사자가 참여하고 계획 변경 사항에 대한 승인을 받는 것을 의미할 수 있습니다.

**질문**

이메일, 휴식 시간을 확인하기 위해 2시간/일을 입력하는 대신 FTE를 조정하는 것이 좋습니까?

**답변**

예. FTE를 .75로 설정하면 리소스 플래너에서 사용자가 하루에 6시간을 사용할 수 있는 것으로 표시됩니다. 이는 매일 이용 가능해집니다. 각 분기의 마지막 날을 사용할 수 없음 등 날짜에 따라 다른 기간에 대해 사용할 수 없음으로 표시하려는 경우, 오버헤드 프로젝트가 이 작업을 수행하는 방법입니다.

일부 사용자는 오버헤드 프로젝트를 직접 빌드하고 원하는 대로 변경할 수 있으므로 선호하지만 자체 FTE를 편집할 권한이 없을 수도 있습니다.

**질문**

작업에 대한 권한에 관계없이 보고서를 공유하는 모든 사용자가 팀 수용작업량 대시보드의 데이터를 사용할 수 있습니까?

**답변**

사용자에게 개체를 볼 수 있는 권한이 없는 경우에는 보고서/대시보드 내에 개체를 볼 수 없습니다. 그러나 모든 사람이 동일한 결과를 보기를 원하는 경우 보고서 작업 > 편집 > 보고서 설정으로 이동하여 필드에 이름을 입력하고 &quot;의 액세스 권한으로 이 보고서 실행&quot;을 할 수 있습니다. 이렇게 하면 이 보고서에 공유된 사용자가 표시되는 정확한 결과를 볼 수 있습니다. 결과 자체에 대한 추가 액세스 권한을 부여하지 않으므로 일부 결과는 클릭 가능하거나 클릭하지 않을 수 있습니다.

**질문**

프로젝트에 할당된 모든 직원(작업 수준이 아님)을 전체적으로 표시하는 보고서를 어떻게 만들 수 있습니까?

**답변**

프로젝트 보고서 내에 직원 탭(프로젝트 팀)의 일부로 나열된 모든 사용자를 표시하는 열을 만들 수 있습니다. 다음 텍스트 모드를 사용합니다.

```
displayname=Project Team
listdelimiter=<p>
listmethod=nested(projectUsers).lists
textmode=true
type=iterate
valuefield=user:name
valueformat=HTML
```

**질문**

내 팀의 작업 방식을 통합하는 보고서/대시보드를 원합니다. 특히 다음 시나리오: - 내가 소유한 프로젝트 / 나를 위해 생성된 프로젝트 / 타인에게 할당한 작업 / 나에게 할당된 작업

**답변**

내가 소유한 프로젝트

모든 현재 프로젝트를 보여 주는 &quot;현재 프로젝트&quot;라는 기본 제공 보고서가 있습니다. 이 프로젝트를 편집하고 필터 규칙 :Project > 소유자 ID > 같음 > $$USER.IDT를 추가한 다음 보고서를 저장하고 이름을 &quot;내가 소유한 프로젝트&quot;로 바꿀 수 있습니다.

나를 위해 만들어진 프로젝트

이름이 &quot;내 프로젝트&quot;인 기본 제공 보고서가 있으며 이 보고서는 프로젝트 팀에 있는 모든 현재 프로젝트(사용자가 소유자, 스폰서 또는 작업에 할당되었음을 의미함)를 보여 줍니다. 요청하신 내용인지 확실하지 않지만, 귀하를 프로젝트 소유자, 스폰서 또는 작업에 할당하는 것 외에 누군가가 귀하를 위해 프로젝트를 만들었는지 여부를 알 수 있는 다른 방법은 없습니다.

내가 다른 사람에게 할당한 작업

원하는 필터로 작업 보고서를 만든 다음 필터 탭으로 이동하여 텍스트 모드로 전환을 클릭합니다. 이미 있는 항목에 이 코드를 추가합니다.

```
EXISTS:1:$$OBJCODE=ASSGN
EXISTS:1:taskID=FIELD:ID
EXISTS:1:assignedByID=$$USER.ID
```

이렇게 하면 로그인한 사용자가 현재 할당자 중 하나 이상을 할당한 모든 작업이 표시됩니다. 피할당자가 여러 사람에 의해 할당된 경우 사용자를 처음 할당한 사람의 이름만 작업 랜딩 페이지에 &quot;요청자&quot;로 표시됩니다. 할당된 모든 사람과 각 사람을 할당한 사람을 보려면 보기에 열을 추가하고 텍스트 모드로 전환한 후 현재 있는 모든 항목을 다음과 같이 바꿀 수 있습니다.

```
displayname=All Assignees and Requesters
listdelimiter=<p>
listmethod=nested(assignments).lists
textmode=true
type=iterate
valueexpression=CONCAT("Assigned To: ",{assignedTo}.{name},"; Requested By: ",{assignedBy}.{name})
valueformat=HTML
```

나에게 할당된 작업

작업 소유자인 현재 프로젝트에 대한 모든 미완료 작업을 보여 주는 &quot;내 작업&quot;이라는 기본 제공 보고서가 있습니다. 작업 소유자뿐만 아니라 할당되었을 수 있는 여러 사용자 중 하나인 모든 작업을 표시하도록 필터를 변경하는 것이 좋습니다. 필터 규칙을 제거하여 이 작업을 수행합니다

```
Task > Assigned To ID > Equal > $$USER.ID 
```

및 을 로 교체

```
Assignment Users > ID > Equal > $$USER.ID
```

**질문**

차트에서 레이블을 사용자 정의할 수 있는 방법이 있습니까? 프로젝트 상태를 반영하도록 차트를 만들 때 홈 그룹의 이름이 레이블에 포함되는 것을 발견했습니다.

**답변**

차트의 레이블은 그룹화하는 항목의 필드 이름을 사용합니다. 따라서 레이블을 변경할 수 있는 유일한 방법은 원하는 이름으로 계산된 사용자 정의 필드를 사용하는 것입니다. 필드의 계산 섹션에 그룹화할 기본 필드의 필드 이름을 입력합니다.

**질문**

척의 팀 할당에 있는 보고서 표시줄에 어떻게 색깔을 입히세요? 예, 뒤는 앰버, 늦은 시간은 레드, 정시는 그린? 또한 순서를 좀 더 논리적인 (예: 빨간색/주황색/녹색) 또는 반대로 변경할 수 있습니까?

**답변**

진행 상태 옵션에 대해 보고서에 사용된 색상을 변경하려면 보고서를 편집하고 차트 탭을 클릭합니다. &quot;사용자 정의 색상 >&quot; 드롭다운을 찾습니다. 열 또는 막대를 그룹화할지 여부에 따라 &quot;왼쪽(Y) 축&quot; 상자 또는 &quot;데이터 그룹화 기준&quot; 상자 옆에 표시됩니다. 해당 드롭다운에서 색상을 선택할 수 있습니다. 색상 옵션의 오른쪽 하단에 있는 숫자를 클릭하면 더 큰 팔레트에서 색상을 선택할 수 있습니다.

안타깝게도 이 제품들은 순서 변경이 불가능합니다.

**질문**

작업자가 작업 내에 할당받은 프로젝트 수를 가리키는 차트를 만들 수 있습니까?

**답변**

예, 방법은 다음과 같습니다.

* 프로젝트 보고서 만들기
* 해당 사용자가 로그인한 사용자인 경우 필터에 다음 행을 포함해야 합니다.

```
   Project Users > ID > Equal >$$USER.ID 
```

* 그렇지 않으면 [!DNL $$USER.ID] 대신 사용자 이름을 지정합니다. 이 사용자에게 작업이 할당되거나 소유자 또는 스폰서가 있는 모든 프로젝트가 표시됩니다. 작업이 할당된 프로젝트만 보려면 다음 두 개의 필터 규칙을 추가해야 합니다.

```
   Project > Owner ID > Not Equal > $$USERID
   Project > Sponsor ID > Not Equal > $$USERID
```

* 차트를 만들 수 있도록 그룹화를 하나 이상 만드십시오. 회사와 같은 모든 것에 대해 그룹화하십시오. 그런 다음 차트 탭을 클릭하고 차트를 선택합니다. &quot;레코드 수&quot;가 한 축의 기본값이 됩니다. 사용자가 할당한 프로젝트 수입니다.

사용자에게 프로젝트에 대한 할당(작업 또는 프로젝트 소유자 또는 프로젝트 스폰서에 할당됨)이 주어지면 해당 개인이 프로젝트 팀에 추가되고 인력 하위 탭의 스태핑 탭에서 볼 수 있습니다. 사용자가 프로젝트 소유자, 스폰서 또는 작업 할당에서 제거된 경우 해당 이름은 여전히 프로젝트 팀에 있습니다. 제거하려면 수동으로 제거해야 합니다. 이 경우 보고서 결과의 정확성에 영향을 줄 수 있습니다. 프로젝트 팀에서 사용자를 제거하려면 직원 > 인력으로 이동하여 해당 사용자를 선택한 다음 목록 위에 나타나는 제거 단추를 누릅니다.

**질문**

텍스트 모드(그룹화)에서 열의 내림차순을 변경하려면 어떻게 합니까?

**답변**

보고서를 작성할 때 열(보기) 탭에서 대부분의 열을 정렬하도록 선택할 수 있습니다. 그룹화가 없는 경우 전체 목록 보고서가 정렬됩니다. 그룹화가 있는 경우 각 그룹화 내에서 해당 선택에 따라 정렬됩니다.

**질문**

승인 단계에 할당된 팀원을 식별하는 열을 어떻게 만들 수 있습니까?

**답변**

작업 또는 문제/요청 보고서를 실행 중인 경우 Report Builder 내에서 &quot;승인자 및 상태&quot;라는 열을 사용할 수 있으며 이 열은 이 정보를 가져옵니다.
