---
title: 토스, 에어비앤비로 알아보는 디자인 시스템의 내일
layout: post
category: design-teatime
date: 2021-10-07 00:00:00 +0900
excerpt: 앞으로 디자인 시스템이 가야할 길은 어디일까요? 지원 툴, 코딩, 의사결정 민주화... 트렌드 분석을 통해 얻은 3가지 방향성을 설명하겠습니다.
thumbnail: /assets/images/design/future-of-design-system/00.jpg
permalink: /future-of-design-system
tag: 'ETC'
stylecss: /assets/post.css
---

![Design System]({{ '/assets/images/design/future-of-design-system/01.jpg' | relative_url }} 'Design System'){: loading='lazy'}
{: .normal-size}

디자인 시스템(Design System)은 일관성 있고 효과적인 제품을 만들기 위해 조직 내에서 공용으로 사용하는 도구입니다. 디자인 시스템은 모듈식 UI 컴포넌트, 색상, 서체, 여백과 같은 스타일 가이드, 보이스 톤까지 여러 범주에 속한 요소를 포함합니다. 디자인 시스템은 제품 만드는 과정에 일정한 규칙을 세워 조직 구성원 간 협업의 속도와 확실성을 끌어올립니다. 제품 개발에 필요한 노력은 줄지만 유사하거나 더 나은 품질의 제품이 나옵니다. 더 중요한 일, ‘제품으로 무엇을 하려는가’에 집중할 수 있도록 해줍니다.

재사용되는 UI 컴포넌트를 라이브러리로 만드는 일, 특정 디자인 규칙을 설계하고 적용하는 아이디어는 디자이너, 개발자, 기획자를 가리지 않고 광범위하게 활용되어 왔습니다. 하지만 그건 자기 일을 조금 편하게 하는 노하우의 영역에 머물러 있었고, 조직화되지 못한 채 흩뿌려져 있었습니다. 조직이 커질수록 한계가 보였습니다. UI 키트에서 컴포넌트를 꺼내 썼는데 구버전이었다던가, 수정된 리소스가 개발단에 넘어가지 않아 혼선이 생겼습니다. 분산된 라이브러리를 통합하려는 시도는 잘못된 구조로 실패하기 일쑤였습니다.

2013년 <a title='Brad Frost, 2013 - Atomic Design' href='https://bradfrost.com/blog/post/atomic-web-design?refer=mag_epmat' target='_blank' rel='noopener'>아토믹 디자인(Atomic Design)</a>이라는 개념이 디자인 업계에 등장했습니다. 원자로 비유되는 최소단위 디자인 요소들이 모여 버튼 그룹이, 내비게이션 바가, 랜딩 페이지가, 하나의 제품이 됩니다. 아토믹 디자인을 적극 차용한 구글의 <a title='Racheal Hooks, 2021 - The Evolution of Material Design' href='https://1brand.design/blog/the-evolution-of-material-design?refer=mag_epmat' target='_blank' rel='noopener'>머티리얼 디자인(Material Design)</a>이 2014년 발표되었을 때 반응은 뜨거웠습니다. 면과 그림자의 플랫 디자인으로 대표되는 머티리얼 디자인의 통일된 시각 언어는 수많은 디바이스와 플랫폼에서 활용하도록 만들어졌습니다. 마이크로소프트(Microsoft)의 Fluent Design, IBM의 Carbon Design System처럼 대기업은 물론이고 에어비앤비(Airbnb), 메일침프(Mailchimp), 트렐로(Trello) 등 여러 유니콘·스타트업도 그들만의 디자인 시스템을 만들어 공개했습니다. 찬양과 <a title='Pascal Barry, 2020 - Design System Are Bullsh*t' href='https://uxplanet.org/design-systems-are-bullsh-t-7ecdb795cc62?refer=mag_epmat' target='_blank' rel='noopener'>비판</a>, 2010년대 중후반 디자인 업계의 큰 화두는 단연 디자인 시스템이었습니다.

그렇다면 오늘날은 어떤가요? 트렌드 분석을 통해 디자인 시스템의 지금과 방향성을 3가지 포인트로 알아보겠습니다.

- 툴 안에서 디자인에 참견하는 시스템이 있다고요?
- 디자인 시스템으로 디자이너가 코딩을 배우게 된다고요?
- 디자인 시스템이 조직 내 의사결정 민주화에 관여한다고요?

## 거저 얻는 일관성 - 토스 보이스톤 메이커

![Design Lint]({{ '/assets/images/design/future-of-design-system/02.jpg' | relative_url }} 'Design Lint'){: loading='lazy'}
{: .normal-size}

토스의 디자인 컨퍼런스 Simplicity 21가 지난 8월 30일부터 9월 2일까지 나흘간 진행됐습니다. Simplicity 21의 마지막 날에 <a title='Simplicity 21 - 어느 날 토스가 말을 걸기 시작했다.' href='https://toss.im/simplicity-21/sessions/4-3' target='_blank' rel='noopener'>토스 보이스톤 메이커를 공개</a>했습니다.

보이스톤 메이커는 토스 내부에서 활용하는 UX 라이팅 도구입니다. <a title='김강령(Toss), 2021 - 토스가 보이스톤 메이커를 만들게 된 배경' href='https://brunch.co.kr/@thinkaboutlove/396?refer=mag_epmat' target='_blank' rel='noopener'>토스의 상황</a>을 알아보자면, 더 좋은 카피에 대한 고민은 모든 디자이너가 하고 있었지만 가진 경험은 제각각이었습니다. 송금 완료 상황에 사용한 문구만 해도 ‘송금을 완료했어요’, ‘송금합니다’, ‘송금했어요’, ‘보냈어요’ 등 뜻은 같아도 표현의 통일이 이뤄지지 않았습니다. 가이드와 인사이트가 산발적으로 만들어졌지만 공유되고 실제로 적용되는 일은 부족했습니다. 관리되지 않은 UX 라이팅은 제품의 일관성을 해칠 뿐만 아니라 어디선가 더 나은 카피가 쓰일 수 있다는 여지를 남겨두는 것이기도 합니다.

토스의 모든 프로덕트 디자이너는 현재의 UX 라이팅 상황에 일관성이 절실히 필요하다는 점을 인지했습니다. 처음에는 관련 인원이 해당 디자이너에게 시안을 받아 카피의 수정 제안과 그 수정안이 나올 수 있었던 원리를 설명하는 방법이 실행되었습니다. 그러나 이 방법은 실행자의 부담이 큰, 비영속적인 방식이었을 뿐만 아니라 카피 검수는 토스의 린(Lean)한 제품 개발 프로세스에 맞지 않았습니다.

두 번째로 디자이너에게 공통된 카피 선정 원칙을 교육, 검수 없이 처음부터 일관성 있는 UX 라이팅이 나오도록 했습니다. 하지만 이는 전 방식의 실행자가 지고 있던 부담을 디자이너에게 넘겨준 것에 불과했습니다.

제플린(Zeplin) 등에 공유된 디자인 시안을 직접 찾아가 수정 코멘트를 남기는 방법, 구체적 규칙이 명시된 가이드라인을 배포하는 방법도 시도되었으나 모두 특정 조직 구성원의 업무 부담을 키우는 단점을 극복하지 못했습니다.

방법은 ‘사람 디자이너의 일을 키우지 않는’ 방향으로 전환되었습니다. 디자인 툴 내부에서 실시간으로 카피를 체크해 가이드라인에 맞는 용어를 제안하는 보이스톤 메이커는 그렇게 채택되었습니다. 보이스톤 메이커는 템플릿을 통해 많은 부분을 자동으로 생성한 8천 개 이상의 규칙을 기반으로 작동합니다. 이 빠르고 직관적인 툴은 업무량이나 학습비용의 증가 없이 일관성 있는 제품을 만들도록 도왔습니다. 토스는 이렇게 짜인 일관성 위에서 개성 있고 효과적인 UX 라이팅을 도입할 수 있었습니다.

UX 라이팅보다 더 단순한 분야, 특정 속성값을 비교하는 수준에서는 이미 디자인 시스템을 적용 툴이 나와 있습니다. Figma의 <a title='Figma - Design Lint' href='https://www.figma.com/community/plugin/801195587640428208/Design-Lint' target='_blank' rel='noopener'>Design Lint</a>, Sketch의 <a title='Saransh Solanki, 2019 - Validate your designs against your defined design guidelines, within seconds' href='https://uxdesign.cc/sketch-lint-2f292ef87084?refer=mag_epmat' target='_blank' rel='noopener'>Lint for Sketch</a>가 그렇습니다. 디자인 툴 외부에서 독립되어 작동하는 <a title='Tanner Christensen, 2020 - What design system tools will look like in the future' href='https://tannerchristensen.com/blog/2020/4/9/what-design-system-tools-will-look-like?refer=mag_epmat' target='_blank' rel='noopener'>Superb</a>는 JSON으로 정리된 가이드라인과 각종 디자인 리소스를 주기적으로 최신화해서 디자이너가 디자인 시스템의 수정사항에 빠르게 대응할 수 있도록 합니다. Superb는 자체 사용 데이터를 축적해서 디자인 시스템을 개선하는데 필요한 유의미한 인사이트를 제공하기도 합니다.

이처럼 디자인 시스템의 무수한 **가이드라인을 그저 구성하는 데 그치지 않고 실무 적용 단계에서 적극적으로 지원하는 건 디자인 시스템의 명확한 발전 방향**입니다. 더 쉽고 빨라진 디자인 시스템의 실용은 제품 개발 속도를 극적으로 줄여주고 시스템 자체에 대한 학습도 빠르고 깊게 만들어줍니다.

## 디자이너와 개발자, 더 가깝게 - Airbnb React Sketch

![Code and Component]({{ '/assets/images/design/future-of-design-system/03.jpg' | relative_url }} 'Code and Component'){: loading='lazy'}
{: .normal-size}

오늘날 대부분의 디지털 프로덕트는 디자이너의 기획과 개발자의 구현으로 만들어집니다. 중요한 협업 관계나 하는 일이 다르기에 제품 개발을 보는 관점이 다른 두 직군의 조화는 어렵습니다.

디자인 시스템에서도 마찬가지입니다. 디자인 시스템의 주요 기능 중 하나는 동기화입니다. 조직의 디자이너와 개발자는 작업물에 포함된 리소스가 구형이라면 최신 버전으로 쉽게 갱신할 수 있어야 합니다. 이 부분은 세세한 설정을 다룰 수 있는 개발자가 더 유리했습니다. 어떤 디자인 툴에서 버튼 하나를 라이브러리로 만들어 공유했다고 가정합시다. 그다음 크기를 두 배쯤 키운 버전으로 업데이트합니다. 이 버튼이 들어간 카드, 리스트, 배너… 이런 컴포넌트의 레이아웃이 깨지지 않았을 확률이 얼마나 될까요? 보통 엉망진창이 되어있을 겁니다. 물론 세밀하게 상황을 나누어 각 상황에 맞는 컴포넌트를 제작하거나, 컴포넌트의 레이아웃을 자세하게 설정한다면 문제가 없을 수도 있습니다. 그러나 이런 조정이 계속해서 수정되고, 그때마다 개발자가 반영해야 한다면 업무량이 어마어마하게 커집니다. 디자이너와 개발자 모두 더 본질적인 작업에 집중할 시간이 필요합니다.

에어비앤비도 같은 고민에서 <a title='Jon Gold(Airbnb) - Painting with Code : Introducing our new open source library React Sketch.app' href='https://airbnb.design/painting-with-code?refer=mag_epmat' target='_blank' rel='noopener'>React Sketch.app</a>을 만들었습니다. 디자이너 팀이 합의해서 디자인 시스템을 Sketch 라이브러리로 만들면 개발자가 받아 제품에 반영했습니다. 2가지 문제점이 있었습니다.

1. Sketch에서 업데이트하는 것만으로는 실제 디자인 시스템 요소가 곳곳에 적용된 제품에 어떤 영향을 미칠지 쉽게 알 수 없었습니다.
2. 하나의 컴포넌트가 여러 상태를 가질 수 있는 디지털 프로덕트 특성상 Sketch의 컴포넌트는 실제로 개발된 컴포넌트를 직관적으로 반영하지 못했습니다.

위와 같은 문제는 에어비앤비가 커질수록 심각해졌습니다. 에어비앤비는 이 문제를 디자인 시스템의 원천을 바꾸는 것으로 해결했습니다. 기존에 디자인 시스템이 Sketch 설계를 바탕으로 구현되는 것이었다면, 이미 개발된 디자인 시스템을 바탕으로 Sketch에서 디자인하는 것입니다. 이제 디자이너는 실제 제품에서 사용 중인 컴포넌트를 실시간으로 가져다 디자인하고, 개발자는 수정된 디자인 시스템이 제품에서 완벽하게 작동한다는 확신 위에서 작업할 수 있게 되었습니다.

협업 효율을 위해 디자이너가 코딩을 배워야 한다는 이야기는 전부터 있었습니다. 디지털 시스템의 보편화로 디자이너의 개발 능력은 더 각별해졌습니다. 개발 지식은 디자이너가 디자인 시스템을 쓰고 고칠 것을 염두에 두며 작업하게 합니다. 이는 디자인 시스템과 협업 자체의 효율을 높입니다. **디자인 시스템의 기반이 개발로 넘어간 것은 이미 트렌드이고, 디자이너의 개발 작업 이해도는 더 중요해질 것**입니다.

## 결정은 앎에서 비롯하니까 - Storybook, 리소스 센터

디자인 시스템은 사용하고 개선하는 사람이 많아질수록 더 나아지고, 다시 더 많은 사용자를 불러오는 선순환을 가질 수 있습니다. 이를 위해서는 동료를 디자인 시스템에 온보딩하는 과정이 필요합니다. 디자인 시스템을 이해하고 활용하는 사람은 제품을 만들고 디자인 시스템을 개선하는데 더 효과적인 의사결정을 할 수 있게 됩니다. 개방적이고 투명한 디자인 시스템이 <a title='Jalita Aspelin(Columbia Road), 2018 - The future of design systems' href='https://www.columbiaroad.com/blog/the-future-of-design-systems?refer=mag_epmat' target='_blank' rel='noopener'>제품과 조직의 기량을 끌어올리는 것</a>입니다.

![SSOT]({{ '/assets/images/design/future-of-design-system/04.jpg' | relative_url }} 'SSOT'){: loading='lazy'}
{: .normal-size}

SSOT 구조가 위와 같은 디자인 시스템이 될 수 있습니다. <a title='Wikipedia - Single source of truth' href='https://en.wikipedia.org/wiki/Single_source_of_truth' target='_blank' rel='noopener'>SSOT(Single Source of Truth)</a>는 단일한 원천에서 모든 데이터가 참조되는 것을 의미합니다. 하나의 디자인 시스템 소스가 디자인 파일에, 마케팅 콘텐츠에, 제품 개발 코드에, 디자인 시스템 가이드 문서에 활용됩니다.


<a title='Storybook: UI component explorer for frontend developers' href='https://storybook.js.org?refer=mag_epmat' target='_blank' rel='noopener'>Storybook</a>은 디자인 시스템 가이드 문서를 기준으로 SSOT형 디자인 시스템을 구축하는 도구입니다. Storybook에 문서화된 UI는 실제 제품에서 작동하는 형태입니다. 디자이너, 개발자, 기획자, 제품을 만드는 모든 사람은 **공개된 디자인 시스템을 바탕으로 더 나은 의사결정을 할 기회를 평등하게 나눠 갖습니다.**

## 디자인 시스템의 내일

![Future of Design System]({{ '/assets/images/design/future-of-design-system/05.jpg' | relative_url }} 'Future of Design System'){: loading='lazy'}
{: .normal-size}

디자인 시스템은 일관성 있고 효과적인 제품을 만들기 위해 조직 내에서 공용으로 사용하는 도구로, 제품 만드는 과정에 일정한 규칙을 세워 조직 구성원 간 협업의 속도와 확실성을 끌어올립니다. 오늘날의 트렌드에서 확인할 수 있는 디자인 시스템의 발전 방향은 다음 3가지로 압축할 수 있습니다.

1. 디자인 시스템 실무 적용 지원 툴
2. 협업 효율 향상을 위한 코드 기반 디자인 시스템
3. 조직 구성원 전체의 효과적 의사결정을 위한 디자인 시스템 개방·투명화

고객과 시장이 변하듯 제품과 디자인 시스템도 바뀌고 있습니다. 디자인 시스템이 다음에는 어떤 모습을 가지게 될지 기대가 됩니다.

위시켓의 지원과 함께 제작된 콘텐츠입니다.
{: .right-infor}