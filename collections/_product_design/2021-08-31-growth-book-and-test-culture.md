---
title: 따라쓰기만 하면 테스트 문화가 만들어진다. Growth Book
layout: post
category: design-teatime
date: 2021-08-30 00:00:00 +0900
excerpt: AB 테스트는 조직에 함께하는 문화가 자리잡을 때 곱절의 성능을 발휘합니다. 테스트 문화 구현에 적합한 오픈소스 AB 테스트 플랫폼을 소개합니다.
thumbnail: /assets/images/design/growth-book-and-experiment-culture/00.jpg
permalink: /growth-book-and-experiment-culture
topic: AB Test
stylecss: /assets/post.css
---

![Growth Book]({{ '/assets/images/design/growth-book-and-experiment-culture/01.jpg' | relative_url }} 'Growth Book'){: loading='lazy'}
{: .full-size}

AB 테스트는 제품과 조직에 성장을 안겨다 주는 확실한 전략 중 하나입니다. 그러나 AB 테스트를 한번이라도 직접 해본 사람을 찾는다면 의외로 손에 꼽을 것입니다. 이전에 연재한 <a title='매거진 입맛 - 매출 만드는 AB 테스트, 시작이 막막한가요? 3단계 가이드' href='/3step-ab-test' target='_blank' rel='noopener'>AB 테스트 가이드</a>에서 이야기했듯 AB 테스트는 단 1명이라도 올바른 추진 방법을 알고 실행에 옮길 행동력을 가지고 있다면 할 수 있는 일입니다. 하지만 AB 테스트로 피운 성장 동력이라는 불을 지키고 키우려면 여러 사람이 함께 참여해야 합니다. 참여자의 수가 늘수록 제시되는 가설, 진행되는 실험, 도출되는 인사이트, 그리고 성장량이 같이 커집니다.

어떤 조직의 구성원이라면 자신이 어느 직무에 있던 데이터에 따라서 의사결정하고, 가설을 내며, 실험을 설계하고, 결과를 분석하는 것. 이와 같은 일련의 과정이 조직 내에 자연스럽게 녹아 있는 모습을 보고 테스트 문화가 잘 자리 잡았다고 말합니다. 테스트 문화의 구조는 조직의 상황에 따라 다른 모양을 가집니다. 테스트 문화로 유명한 조직은 독립적인 그로쓰 해킹 팀이 주도적으로 테스트 문화를 적용하고 개선하는 경우가 많습니다. 조직이 크든 작든 테스트 문화를 만드는데 겪어야 하는 시행착오의 양은 비슷합니다. 테스트 문화를 만드는 업무에 힘을 쏟을 여유가 부족한 소규모 팀이라면 테스트 문화가 자리 잡는데 더 오랜 기간이 걸릴 것입니다.

잠깐 다른 이야기로, 한 도구는 사람의 행동방식을 바꿀 힘을 가지고 있습니다. 자동차가 보급된 후 얼마나 많은 식당, 집, 도로, 직장, 그리고 도시가 바뀌었습니까? 먹는 법, 쉬는 법, 다른 사람을 만나는 방법은 자동차 등장 전후로 큰 변화를 겪었습니다. 사람이 만든 도구는 사람을 바꿉니다. 조직 내 테스트 문화 보급도 마찬가지 맥락에서 볼 수 있습니다. **어떤 툴은 단지 쓰는 것만으로 테스트 문화를 만들 수 있습니다.** 이번 글에서 소개하려는 <a title='Growth Book' href='https://www.growthbook.io/?ref=매거진입맛' target='_blank' rel='noopener'>AB 플랫폼 Growth Book</a>이 바로 그 툴입니다.

- Growth Book은 어떤 구조길래 테스트 문화를 만들까요?
- Growth Book은 어떻게 사용할까요?
- 무료로 쓸 수 있나요? 쉬운가요? 😅

## AB 테스트와 시행착오
 
AB 테스트는 가설 수립 → 실험 진행 → 결과 분석으로 구분되는 연속적 사이클 위에서 작동합니다. 단순해 보이지만 실제 업무에서는 훨씬 많은 작업이 필요합니다.

1. 가설 수립을 위한 리서치
2. 실험 계획별 우선순위 지정
3. 실험 구현, 지표 추적
4. 결과 분석, 시각화 등 분석자료 공유 작업
5. 결과 문서화, 아카이빙

당장 중요하다 싶은 일만 해도 위와 같이 꼽을 수 있습니다. 이런 업무에는 몇 가지 공통점이 있습니다.

1. 여러 직군을 아우르는 팀원의 협력·의견·타협 필요
2. 산출되는 결과물에 있어서 표준적인 형식 없음
3. 각 업무가 균등한 중요도를 가짐(선택과 집중 어려움)

AB 테스트는 조직의 일입니다. 제품을 가지고 고객을 상대로 벌이는 작업입니다. 어떤 실험을 먼저 혹은 나중에 실행할지, 어떤 방향으로 구현할지, 심지어 실험 결과를 어떤 쪽으로 분석할지까지 조직 구성원 간의 협업과 합의가 요구됩니다. 이런 특성 때문에 AB 테스트 의사결정은 관련된 조직 구성원은 실험에 대해 같은 수준의 이해도를 보여야 합니다. AB 테스트 진행자가 실험 설계, 분석자료, 결과 문서 등의 공유 작업에 공을 들여야 하는 이유가 여기 있습니다. 문제는 이와 같은 공유 자료는 그 형식이 제품·시장·조직의 환경을 많이 타기에 AB 테스트 초보자 처지에서 난감하다는 것입니다. 앞서 언급한 <a title='매거진 입맛 - 매출 만드는 AB 테스트, 시작이 막막한가요? 3단계 가이드' href='/3step-ab-test' target='_blank' rel='noopener'>AB 테스트 가이드</a>에서 <a title='AB 테스트 리포트 템플릿' href='https://www.notion.so/dewberry9/AB-bd3ad2cfce654938b50e4e04f915c0c7' target='_blank' rel='noopener'>노션(Notion)으로 만든 테스트 리포트 템플릿`</a>을 제공한 것도 이런 문제에 대해 도움을 줄 수 있을 것이라 여겼기 때문입니다. 해당 테스트 리포트 템플릿은 <a title='Paul(Market Fit Lab), 2020 - Culture of Experimentation: 클래스101은 어떻게 AB테스트를 한 달에 100개씩 돌리게 되었나?' href='https://mfitlab.com/blog/culture-of-experimentation/?ref=매거진입맛' target='_blank' rel='noopener'>클래스 101의 테스트 리포트</a>를 참고하여 설계한 것으로, 실험 기획 배경, 가설, 실험 목표, 구현 모습과 결과 분석 항목으로 구성되어 있습니다.

여러 동료와의 협업, 이를 위한 실험 관련 자료 처리. 이런 업무가 진짜 어려운 이유는 번뜩이는 가설을 내놓고 획기적인 인사이트를 뽑아내는 것과 비교해도 중요도가 떨어지지 않는 데 있습니다. AB 테스트를 하늘의 뜬구름 같은 위치에서 진짜로 하는 어떤 일, 현실로 끌어내리는 실무적인 작업이기 때문입니다.

**피할 수 없는 시행착오**. 테스트 문화를 만드는 일의 핵심이 여기 있습니다. 그럼 Growth Book은 이를 어떻게 해결할까요?

## Growth Book 온보딩 : 데이터 소스 연결, 지표 설정

Growth Book은 AB 테스트 가설·계획 기록, 실험 제어와 결과 분석·문서화를 중심으로 조직의 테스트를 관리하는 협업 플랫폼입니다. Growth Book은 위와 같은 작업에 필요한 유연한 형식을 제공하여, 툴이 지원하는 기능을 따라 쓰기만 해도 일정 수준 이상의 테스트 문화가 작동하도록 만들어줍니다.

이제 온보딩부터 Growth Book의 구조를 살펴보겠습니다.

![Growth Book Plan]({{ '/assets/images/design/growth-book-and-experiment-culture/02.jpg' | relative_url }} 'Growth Book Plan'){: loading='lazy'}
{: .full-size}

기본적으로 오픈소스이기 때문에 제공되는 Docker를 내려받아 직접 호스팅 할 수 있습니다. 이게 어렵다면 계정만 만들고 Growth Book에서 호스팅하는 서비스를 사용할 수 있습니다. (10개 계정까지 무료) 적은 사용 비용은 Growth Book 입문의 허들을 낮춰줍니다.

![Growth Book Onboarding]({{ '/assets/images/design/growth-book-and-experiment-culture/03.jpg' | relative_url }} 'Growth Book Onboarding'){: loading='lazy'}
{: .full-size}

Growth Book을 시작하면 처음으로 볼 수 있는 온보딩 화면입니다. 데이터 소스 연결 → 지표 설정 → 실험 진행 순으로 사용법을 안내하고 있습니다. 현시점에서 Growth Book이 지원하는 데이터 소스는 Redshift, Snowflake, BigQuery, ClickHouse, AWS Athena, Postgres, MySQL/MariaDB, PrestoDB/Trino, Mixpanel, Google Analytics로 총 10개입니다. <a title='Growth Book Docs - Data Sources' href='https://docs.growthbook.io/app/datasources?ref=매거진입맛' target='_blank' rel='noopener'>공식 문서</a>에서 데이터 소스별 연동 방법을 찾아볼 수 있습니다.

![Growth Book Metric]({{ '/assets/images/design/growth-book-and-experiment-culture/04.jpg' | relative_url }} 'Growth Book Metric'){: loading='lazy'}
{: .full-size}

이렇게 연동한 데이터는 지표를 설정할 때 활용합니다. Growth Book에서 지표는 비율(Binomial), 횟수(Count), 시간(Duration), 수익(Revenue)의 4가지 형식으로 만들 수 있습니다. 지표는 아래에서 설명할 실험 진행에 활용됩니다. 특히 지표에 대한 설명을 적고 코멘트를 달 수 있으며 수정 내역이 기록되는 기능은 유용합니다. AB 테스트를 진행하다 보면 연관성을 가진 여러 지표를 다루게 되는데 다소 비직관적인 지표로 분석 결과를 설명해야 할 때도 생깁니다. 지표의 정의와 각종 변동 사항을 편하게 문서화하여 남길 수 있는 기능은 테스트 문화가 기능하는 데 큰 영향을 줍니다.

## 아이디어

사이드바 가장 상단에 있는 페이지입니다. 기능 자체는 단순합니다. 실험 가설을 써서 올릴 수 있습니다. 그러나 다음 3가지 특징 덕분에 아이디어는 강력한 기능이 되었습니다.

1. 마크다운 형식
2. 댓글 기능
3. 태그 기능

![Growth Book Ideas Content]({{ '/assets/images/design/growth-book-and-experiment-culture/05.jpg' | relative_url }} 'Growth Book Ideas Content'){: loading='lazy'}
{: .full-size}

Growth Book의 아이디어는 노션처럼 마크다운 형식으로 각 항목을 작성합니다. 제목, 볼드체, 목록, 표, 이미지, 링크 등 마크다운에서 활용하는 여러 요소로 누구나 직관적으로 이해할 수 있는 풍부한 실험 가설 문서를 만들 수 있습니다.

댓글 기능으로는 각 실험 가설에 대한 개선안, 보충안, 반대안과 같은 여러 논의를 독립적으로 보존할 수 있습니다. 예전에 이야기했던 회원가입 퍼널 실험에 대한 우선순위 논의를 찾기 위해 한 달 전 슬랙(Slack)를 뒤질 필요가 없다는 의미입니다.

![Growth Book Ideas List]({{ '/assets/images/design/growth-book-and-experiment-culture/06.jpg' | relative_url }} 'Growth Book Ideas List'){: loading='lazy'}
{: .full-size}

Growth Book에서 태그는 아이디어, 실험, 지표 등 모든 항목에서 아울러 활용할 수 있는 기능입니다. 실험이 적용되는 페이지, 기능, 관련 지표, 작업자, 우선순위, 실험 여부…. 높은 자유도로 무엇이든 유형화해서 아이디어, 실험, 지표를 관리할 수 있습니다.

상기한 특징은 실험 가설을 효과적으로 보존하고 조직 구성원의 참여도를 높이는 데 긍정적인 힘을 미칠 것입니다.

## 실험 진행·문서화

아이디어 페이지에서 특정 실험 가설을 바탕으로, 아니면 그냥 실험 화면에서 버튼을 눌러 실험 초안을 만들 수 있습니다. Growth Book에서 실험은 다음 3단계 상태 중 하나를 가집니다.

1. 초안(Draft)
2. 실험 중(Running)
3. 실험 종료(Stopped)

![Growth Book Create Test]({{ '/assets/images/design/growth-book-and-experiment-culture/07.jpg' | relative_url }} 'Growth Book Create Test'){: loading='lazy'}
{: .full-size}

실험 초안은 가설과 데이터 소스, 원본 및 대안에 대한 설명과 목표 지표, 참고 지표, 활성화 조건, 실험을 진행할 페이지의 URL 등을 입력해 생성합니다. 실험은 종료할 때 원본과 비교해서 대안이 개선에 성공했는지, 실패했는지, 비등비등했는지 선택할 수 있습니다. 이때 분석한 결과도 기록할 수 있습니다. 많은 요소가 한데 어우러져 다소 복잡할 수 있기 때문에 Growth Book에서는 종료 실험을 살펴볼 수 있게 샘플 데이터 추가 기능을 제공합니다.

![Growth Book Experiment Info]({{ '/assets/images/design/growth-book-and-experiment-culture/08.jpg' | relative_url }} 'Growth Book Experiment Info'){: loading='lazy'}
{: .full-size}

아이디어를 입력했을 때와 마찬가지 자유도로 실험을 꾸릴 수 있습니다. 가설과 목표 지표, 원본과 대안의 설명 등 실험을 구성하는 항목을 성실하게 채우는 것만으로 보기 좋은 실험 문서가 만들어집니다. 필수적인 항목만 제공하면서도 입력 자체는 최대한의 자유로움을 보장하는 **Growth Book은 상황에 맞게 다룰 수 있는 유연함과 초보자를 위한 가이드 역할까지 부족함 없이 지니고 있습니다.**

![Growth Book Experiment Results]({{ '/assets/images/design/growth-book-and-experiment-culture/09.jpg' | relative_url }} 'Growth Book Experiment Results'){: loading='lazy'}
{: .full-size}

실험 결과 페이지에서는 목표 지표별로 그 값과, 특정 대안을 선택했을 때의 위험도, 원본보다 나을 확률, 그리고 바이올린 플롯으로 시각화된 전환율 분포도를 확인할 수 있습니다. 일반적으로 위험도는 1% 미만, 원본보다 나을 확률은 95% 이상에 도달할 때 실험 결과가 의미 있다고 할 수 있습니다. 특히 Growth Book은 원본보다 대안이 나을 확률을 산정할 때 웹상에서 찾을 수 있는 많은 AB 테스트 결과 신뢰 구간 계산기처럼 빈도주의적 통계를 사용하지 않고 <a title='Jeremy Dorn(Growth Book), 2021 - Growth Book Bayesian Statistics Engine' href='https://www.growthbook.io/docs/GrowthBookStatsEngine.pdf' target='_blank' rel='noopener'>베이지안 통계 방식을 활용</a>합니다. AB 테스트 결과 통계 해석에 대해서는 차후 다른 글에서 자세히 이야기해보겠습니다. 결론은 Growth Book이 훨씬 받아들이기 자연스러운 통계를 제공한다는 것입니다.

아이디어와 마찬가지로 각 실험 문서에 대한 의견, 수정 기록은 독립적으로 보존됩니다.

## 정리

AB 테스트 가설·계획 기록, 실험 제어와 결과 분석·문서화를 중심으로 조직의 테스트를 관리하는 오픈소스 협업 플랫폼, Growth Book은 다방면의 데이터 소스를 쉽게 연동하여 지표를 설정할 수 있습니다. 이는 여러 조직 구성원이 함께 실험 가설을 제시하고 실험을 설계하는데 단단한 기반이 됩니다. 협업하는데 필수적인 항목을 제공해 초보자에게도 문제없는 테스트 문화를 형성하고, 한편으로 그 안에서 최대한의 자유도를 보장하는 유연함을 갖췄습니다.

AB 테스트는 시작했지만 아직 이렇다 할 문화가 자리 잡지 못했다면 Growth Book은 좋은 선택이 될 것입니다.

위시켓의 지원과 함께 제작된 콘텐츠입니다.
{: .right-infor}