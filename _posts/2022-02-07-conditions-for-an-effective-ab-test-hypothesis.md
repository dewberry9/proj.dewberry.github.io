---
title: 아마존, 쿠팡의 AB 테스트 성공 방정식, 가설의 5층 구조와 설정 프레임워크
layout: post
category: design-teatime
date: 2022-02-06 00:00:00 +0900
excerpt: AB 테스트의 영향력과 성공률을 동시에 높이면서, 동시에 실험 문화 확산까지 챙기는 전략이 있습니다. 바로 효과적인 가설이죠. 이런 가설은 어떻게 만들까요?
thumbnail: https://res.cloudinary.com/mag-epmat/image/upload/v1644125703/design/conditions-for-an-effective-ab-test-hypothesis/00_l1xzea.jpg
permalink: /conditions-for-an-effective-ab-test-hypothesis
topic: AB Test
stylecss: /assets/post.css
---

![AB Test Cycle](https://res.cloudinary.com/mag-epmat/image/upload/v1644115384/design/conditions-for-an-effective-ab-test-hypothesis/01_j6mfdh.jpg 'AB Test Cycle'){: loading='lazy'}
{: .normal-size}

매거진 입맛에서 가장 인기 있는 글 중 하나인 <a title='매거진 입맛 - 매출 만드는 AB 테스트, 시작이 막막한가요? 3단계 가이드' href='/3step-ab-test' target='_blank' rel='noopener'>AB 테스트 가이드</a>에서, AB 테스트를 가설 설정 → 실험 진행 → 결과 분석의 순서를 따르는 사이클로 설명한 적 있습니다. 가설을 세운 후 실험으로 증명하고, 여기서 얻은 인사이트가 다시 가설을 만드는 겁니다. 따라서 점차 핵심으로 파고드는 영향력 있는 실험을 하느냐, 아니면 빙빙 돌고 질질 끄는 실험을 하느냐는 초반의 가설 설정 단계에서 결정됩니다.

그렇다면 어떻게 영향력 있는 가설을 구상할 수 있을까요? 이번 글에서는 효과적인 AB 테스트 가설이 가진 5층 구조와 이런 가설을 만드는 3가지 방법론에 관해 알아보겠습니다.

## AB 테스트에 좋은 가설이 필요한 3가지 이유

![3 Reasons Why You Need a Good Hypothesis](https://res.cloudinary.com/mag-epmat/image/upload/v1644115384/design/conditions-for-an-effective-ab-test-hypothesis/02_v8aljz.jpg '3 Reasons Why You Need a Good Hypothesis'){: loading='lazy'}
{: .normal-size}

본론에 들어가기 전에, 좋은 가설의 구조와 방법론을 분석해야 하는 이유를 알아봅시다. 모든 제품과 조직은 각기 다른 환경에 처해 있습니다. 문제도 다르고 해결법도 다릅니다. 이상적 가설에 대한 지식이 내 제품, 내 조직에 도움을 줄 수 있을까요? 여기에는 3가지 이유가 있습니다.

**1. AB 테스트 문화를 조직 내 퍼뜨리는데 기여합니다.**  
<a title='매거진 입맛 - 따라쓰기만 하면 테스트 문화가 만들어진다. Growth Book' href='/growth-book-and-experiment-culture' target='_blank' rel='noopener'>Growth Book을 소개하는 글</a>에서 테스트 문화의 보급이 중요한 까닭을 설명한 적 있습니다. AB 테스트는 참여자가 많을수록 가치가 커지는 제품 성장 동력입니다. 서로 다른 직무를 맡은 조직원이 AB 테스트에 관여하면 할수록 제시하는 가설, 진행하는 실험, 도출하는 인사이트가 늘어납니다.

가설 설정은 AB 테스트의 시작입니다. 효과적인 가설 설정 방식을 이해하고 하나의 가이드로 확립한다면 그 자체로 훌륭한 테스트 문화가 됩니다. 일관된 접근 방식을 제공하여 AB 테스트의 허들을 낮추고 효율적인 협업을 만듭니다. 더 효과적인 AB 테스트가 더 많이 일어납니다. 더 많은 성과와 인사이트, 즉 가치로 이어집니다. 동료는 이 가치에 끌립니다. AB 테스트 참여자의 수는 늘어납니다. AB 테스트는 조직의 주요 의사결정 방식이 됩니다.

**2. AB 테스트의 방향이 명확해지고, 구성이 치밀해집니다.**  
대부분의 사람은 버튼이나 카피를 바꾸는 간단한 실험으로 AB 테스트를 시작합니다. 실험을 계속하면서 변수를 통제하고 데이터를 분석하는 일에 익숙해진 후에는 경쟁 제품이나 성공 사례에서 아이디어를 빌려 오기도 합니다. 처음에는 괜찮은 방법입니다. 이 시기에는 실험 과정을 온전히 내 것으로 만드는 게 중요한 과제입니다. 그러나 시간이 지나도 그 상태에 머물러 있다면 문제가 됩니다. 단편적인 부분만 건드리는 테스트를 하고, 도출한 인사이트를 다음 실험으로 발전시키지 못한다면 위에서 언급한 AB 테스트의 선순환이 작동하지 않습니다. 이런 AB 테스트는 한계가 금방 찾아옵니다. 제품의 성장 동력 역할도 할 수 없습니다.

![Tactical Experimentation VS Strategic Experimentation](https://res.cloudinary.com/mag-epmat/image/upload/v1644115384/design/conditions-for-an-effective-ab-test-hypothesis/03_x9kkri.jpg 'Tactical Experimentation VS Strategic Experimentation'){: loading='lazy'}
{: .normal-size}

CRO(전환율 최적화) 전문가 카일 헌쇼(Kyle Hearnshaw)는 위와 같은 AB 테스트를 전술적 실험(Tactical Experimentation)이라고 부릅니다. 또 효과적인 가설 설정 방식을 이해하여 전술적 실험을 <a title='Kyle Hearnshaw(Conversion.com), 2021 - How to build and experimentation, CRO or AB testing framework' href='https://conversion.com/blog/build-experimentation-cro-ab-testing-framework?refer=mag_epmat' target='_blank' rel='noopener'>전략적 실험(Strategic Experimentation)</a>으로 전환할 수 있다고 이야기합니다. 전략적 실험이란 제품 주요 지표와 조직 비전의 성취를 목적으로 하는 일련의 테스트입니다. 개별의 전략적 실험은 모두 목표를 달성하기 위한 과정입니다. 전략적 실험은 단일한 성과에 만족하고 끝나지 않습니다. 한 테스트가 만들어낸 인사이트는 다음 테스트로 연결됩니다. 무의미한 AB 테스트는 처음부터 기획되지 않습니다. 아이디어가 없어 구글만 뒤지고 있는 상황도 생기지 않습니다.

**3. AB 테스트의 영향력과 성공률이 커집니다.**  
앞서 설명한 두 가지 이유, 테스트 문화의 보급과 전략적 실험으로의 이행이 실험의 영향력과 성과를 키우는 것은 당연합니다.

테스트 문화 보급으로 AB 테스트 참여자가 늘어나면, 실험은 조직의 언어가 됩니다. 이 상황에서 대부분의 조직 구성원은 AB 테스트에 협조적입니다. 각자의 일을 하면서도 AB 테스트를 고려하거나 관련 전략을 적용하는 경우가 빈번해집니다. AB 테스트는 더 많은 성과를 내고, 실험에 대한 신뢰도는 높아집니다. 전략적 실험이라는 프레임워크는 이 상태를 극대화합니다. 모든 AB 테스트는 명료한 최상위 목표를 가집니다. 실험은 제품에 최대한 기여하는 방향으로 실행됩니다.

## 가설의 5층 구조

어떤 빌딩이라도 중간부터 튼튼할 수는 없습니다. 한 층의 안정성은 아래층의 안정성에서 나옵니다. 그다음 층도 마찬가지입니다. 건물의 단단함은 높은 첨탑 꼭대기에서 땅속에 박힌 기반에 이르기까지 꼬리에 꼬리를 무는 층간 관계에서 형성됩니다. 좋은 가설도 마찬가지 층위를 이루고 있습니다.

커머스 앱 하나를 운영한다고 가정하고 이 구조를 들여다보겠습니다.

**1. 목표**  
좋은 가설의 첫 번째 층은 목표입니다. 목표는 당면한 문제를 해결하는 것일 수도 있고, 특정 기능을 활성화하는 일일 수도 있습니다. 이 단계에서 무엇보다 중요한 점은 제품 주요 지표와 연관된 목표를 설정하는 것입니다.

우버(Uber)의 최고 제품 책임자, 아마존(Amazon)의 초창기 멤버였던 제프 홀든(Jeff Holden)은 <a title='Peter Diamandis, 2016 - Culture & Experimentation - with Uber’s Chief Product Officer' href='https://medium.com/abundance-insights/culture-experimentation-with-uber-s-chief-product-officer-520dc22cfcb4#.i9bh5xdie?refer=mag_epmat' target='_blank' rel='noopener'>목표 설정의 중요성에 관한 사례</a>를 이야기한 적 있습니다. 아마존은 모든 직원이 자유롭게 AB 테스트할 수 있는 사내용 플랫폼을 만들었습니다. 그 결과 단순한 호기심으로 만들어진 쓸모없는 AB 테스트가 무질서하게 진행되었습니다. 상반되는 실험이 생겼고, 꼭 필요한 실험이 무의미한 실험에 밀려났습니다. 아마존은 AB 테스트 진행 권한을 가진 팀을 만들어 문제를 해결했습니다. 누군가 AB 테스트를 기획하면, 팀은 실험의 가설과 해당 실험이 조직에 가져다줄 가치를 검토했습니다.

앞으로 한층 한층 오르며 하나의 목표에서 여러 방향성과 가설이 형성될 것입니다. 기껏 고도화한 가설이 모두 무익한 것으로 드러나고 싶지 않다면, 정말로 제품에 필요한 목표인지 확신할 수 있어야 합니다.

![Hypothesis Goals](https://res.cloudinary.com/mag-epmat/image/upload/v1644115384/design/conditions-for-an-effective-ab-test-hypothesis/04_jkspdb.jpg 'Hypothesis Goals'){: loading='lazy'}
{: .normal-size}

예시의 커머스 앱이 거래당 수수료를 기반으로 하는 비즈니스 모델을 갖고 있다고 가정하겠습니다. 주요 목표로 거래 횟수 늘리기, 반품률 줄이기, 고단가 제품 판매율 늘리기 등을 꼽을 수 있습니다.

**2. 문제/기회**  
목표를 설정했다면 이를 달성할 방법을 찾기 위해 정보를 모아야 합니다. 커머스 앱 유저의 사용 데이터를 분석한 외부 연구 조사 자료, 제품 사용 시 느꼈던 불편한 점을 묻는 고객 설문 조사 등 정보를 얻을 수 있는 출처는 많습니다. 특히 이전 AB 테스트의 결과로 도출된 인사이트, 내부 데이터 분석 자료처럼 제품과 조직 내부에서 얻은 정보는 영향력 있는 가설을 구축하는 데 큰 도움이 됩니다. 이에 대해서는 아래 방법론 부문에서 자세히 설명하겠습니다.

![Hypothesis Problem/Chance](https://res.cloudinary.com/mag-epmat/image/upload/v1644115384/design/conditions-for-an-effective-ab-test-hypothesis/05_e2qibd.jpg 'Hypothesis Problem/Chance'){: loading='lazy'}
{: .normal-size}

정리한 정보를 바탕으로 문제를 정의합니다. 예를 들어 장바구니에 상품을 등록한 고객 중 절반가량이 구매하지 않았다는 정보가 있다고 생각해봅시다. 상품 조회 → 장바구니 등록 → 구매에 이르는 상품 구매 퍼널에 문제가 있을 수도 있고, 장바구니를 의도한 것과 다르게 사용하는 고객 그룹이 있을 수도 있습니다. 이 문제들은 곧 해결책을 내는 실마리이기 때문에 기회라고도 말할 수 있습니다.

**3. 솔루션**

![Hypothesis Solution](https://res.cloudinary.com/mag-epmat/image/upload/v1644115384/design/conditions-for-an-effective-ab-test-hypothesis/06_dn4njs.jpg 'Hypothesis Solution'){: loading='lazy'}
{: .normal-size}

정의한 문제에 대한 해결책을 제시합니다. 장바구니에서 결제 단계로 넘어가는 버튼에 시인성 문제가 있다면 버튼 면적을 키우고 위치를 고정하는 솔루션을 생각해볼 수 있습니다.

영향력 있는 문제를 정확히 집어내는 것만큼이나 적절한 처방을 내리는 일도 중요합니다. <a title='Bryan Eisenberg(Buyer Legends), 2011 - The Conversion Trinity : The 3 Step Magic Formula to Increase Click Throughs & Conversions' href='https://www.bryaneisenberg.com/the-conversion-trinity-the-3-step-magic-formula-to-increase-click-throughs-conversions?refer=mag_epmat' target='_blank' rel='noopener'>좋은 솔루션의 조건</a>은 베테랑 CRO 컨설턴트 브라이언 아이젠버그(Bryan Eisenberg)가 정리한 바 있습니다.

1. 관련성 : 고객 니즈(정의한 문제)와 연관되어야 하며, 그 관계를 한눈에도 알 수 있어야 합니다.
2. 가치 증명 : 고객에게 적합한 해결법을 제시하고, 그 이유도 잘 설명합니다.
3. 행동 제안 : 고객에게 ‘필요한 행동’을 ‘매끄럽게’ 수행할 수 있도록 ‘분명’하게 제안합니다.

모든 조건에서 고객의 이해를 요점으로 꼽는다는 점을 눈치챘을 겁니다. 가설이 옳은지 그른지 명료하게 판단해야 하는 AB 테스트에서는 고객의 이해가 특히나 중요합니다.

**4. 예상 결과**

![Hypothesis Result Expect](https://res.cloudinary.com/mag-epmat/image/upload/v1644115384/design/conditions-for-an-effective-ab-test-hypothesis/07_s2ewri.jpg 'Hypothesis Result Expect'){: loading='lazy'}
{: .normal-size}

솔루션이 가져다줄 결과를 예상합니다. 장바구니에서 결제 단계로 이동하는 버튼을 키웠다면 이 화면 사이의 전환율과 구매율의 증가가 예상 결과가 됩니다. 이 단계에서는 측정지표를 알맞게 고르도록 주의해야 합니다. 솔루션이 영향을 주는 직접 지표를 특정하고, 상위 목표와 관련된 주요 지표를 포함합니다. 직접 지표와 주요 지표 사이에 다리를 놓는 지표가 따로 있다면 이 지표도 전부 예상합니다.

**5. 근거**

![Hypothesis Expect Evidence](https://res.cloudinary.com/mag-epmat/image/upload/v1644115384/design/conditions-for-an-effective-ab-test-hypothesis/08_v2hhhq.jpg 'Hypothesis Expect Evidence'){: loading='lazy'}
{: .normal-size}

근거는 예상 결과를 뒷받침해주는 이유입니다. 근거가 확실하지 않으면 결과가 성공적이더라도 부족한 AB 테스트가 될 수밖에 없습니다. 근거는 실험을 진행하는 이유이자, 결과 분석에 쓰이는 검사지입니다. 장바구니에서 결제 단계로 가는 버튼의 크기를 늘려, 시인성을 강화한 AB 테스트에서 화면 전환율과 구매율 상승을 예상했습니다. 그 근거는 구매를 원하는 고객이 장바구니에서 결제 단계로 넘어가는 버튼을 찾지 못하는 상황인데, 커서 잘 보이는 버튼은 이 문제를 해결할 것이기 때문입니다. 만약 이 AB 테스트가 성공하지 못했다면 어째서일까요? 설정한 근거로부터 몇 가지 상황을 추측해볼 수 있습니다.

- ‘구매를 원하지만, 장바구니에서 결제 단계로 넘어가지 못하는 고객’은 없다.
- 고객은 버튼이 잘 보이지만 다른 이유로 결제 단계로 이동하지 않는다.
- 버튼을 키웠지만, 여전히 잘 보이지 않는다. 혹은 특정 기종에서 솔루션이 제대로 적용되지 않았다.

이처럼 근거는 실험 결과에서 인사이트와 방향성을 만들어줍니다. 세밀한 근거는 완벽한 AB 테스트에 필수적입니다.

![5th Floors of Hypothesis](https://res.cloudinary.com/mag-epmat/image/upload/v1644115384/design/conditions-for-an-effective-ab-test-hypothesis/09_wn1xgh.jpg '5th Floors of Hypothesis'){: loading='lazy'}
{: .normal-size}

이제 가설이 실험에 뛰어들 준비를 마쳤습니다.

## 좋은 가설을 만드는 3가지 방법

![Three Strategies for Effective Hypothesis](https://res.cloudinary.com/mag-epmat/image/upload/v1644115384/design/conditions-for-an-effective-ab-test-hypothesis/10_ep7c98.jpg 'Three Strategies for Effective Hypothesis'){: loading='lazy'}
{: .normal-size}

효과적인 가설의 구조를 알아봤으니, 마지막으로 이러한 가설을 만드는데 유용한 3가지 방법론을 살펴보겠습니다.

**1. 과감한 가설로 크게 휘두르기**  
날아오는 공마다 온 힘으로 휘두르는 타자. 열에 아홉은 삼진아웃일 겁니다. 그러나 이런 선수에게는 구질을 살피면서 조심히 배트를 대는 타자에게서 찾아볼 수 없는 홈런의 가능성이 있습니다.

AB 테스트는 크게 휘둘러야 합니다. 가설 5층위 구조를 살펴보면서 각 단계에 이런저런 단서를 많이 붙였지만, 이에 위축되어 자잘한 실험만 해서는 안 됩니다. 최고로 영향력 있는 문제/기회를 골라, 기존에서 크게 변한 솔루션을 기획해야 합니다. 한두 군데씩 차근차근 검증하는 것보다 한번 크게 바꾼 후 디테일을 고치는 것이 시간과 비용 면에서 훨씬 효율적입니다.

위에서 언급한 사례에서 알 수 있듯 아마존은 강력한 실험 문화를 가진 기업입니다. 초창기 행보에서도 이런 특징이 두드러집니다. 아마존은 최초에 책을 팔았습니다. 카테고리는 어렵지 않게 늘렸지만 기본적으로 보유한 재고를 판매하는 방식이었습니다. 따라서 고객 규모를 키우는 속도에는 한계가 있었습니다. 아마존은 이베이(eBay)를 벤치마킹한 온라인 경매 플랫폼 아마존 옥션, 정찰제 경매 플랫폼 zShop를 실험했고 실패했습니다. 그다음으로는 외부 판매자가 아마존 웹페이지 내에서 상품을 판매할 수 있는 마켓 플레이스 방식을 테스트했습니다. 외부 판매자에게 밀려 아마존의 매출이 줄 것이라는 걱정도 있었지만 이 방식은 성공해 오늘날에 이르렀습니다.

9회로 끝나는 야구 경기에서는 분명 조심스러운 타자가 필요할 겁니다. 그러나 AB 테스트에는 끝이 없습니다.

**2. 확실한 정보로 단단한 가설 만들기**  
쿠팡 역시 아마존 못지않은 실험 문화를 가진 기업입니다. 쿠팡이 공유한 <a title='Coupang Design, 2021 - 쿠팡 UX Club 3. 테스트 결과가 예상과 다를 때' href='https://brunch.co.kr/@coupangdesign/73?refer=mag_epmat' target='_blank' rel='noopener'>패션 팀의 AB 테스트 경험 사례</a>에서도 이런 점이 충분히 드러납니다.

쿠팡 패션 팀은 리서치 팀과 함께 각종 설문조사, 인터뷰, 사용성 테스트를 진행했습니다. 거기서 표준화되지 않은 상품 사이즈 표의 부재가 구매 결정에 악영향을 미친다는 정보를 얻어냈습니다. 팀은 상단에 위치해 처음부터 노출되는 영역인 상품평 요약 우측에 사이즈 표로 연결되는 링크를 다는 AB 테스트를 진행했습니다. 그런데 전체적인 구매율이 나아지지 않았을 뿐더러, 링크 클릭률 자체도 무척 낮았습니다. 흥미로운 점은 링크를 1회 이상 눌러본 고객의 구매율은 2배였다는 것입니다. 추가로 진행한 사용성 테스트에서는 고객 대다수가 링크를 추가한 상단을 가격·결제 혜택을 보여주는 영역으로 여기고, 새로 넣은 링크를 발견하지 못한다는 사실을 알아냅니다. 팀은 링크를 사이즈 옵션 선택 영역으로 옮겨 다시 실험했습니다. 링크 클릭률과 구매율 모두 대폭 상승했습니다.

쿠팡은 다방면에서 수집한 정보로 가설에 확신을 하고 있었기 때문에 실패를 차분히 진단하고 정확한 문제를 짚어 해결할 수 있었습니다. 대부분의 AB 테스트는 실패로 끝납니다. 중요한 건 실패해서 포기하는 대신, 더 집요하게 파고들어 몰랐던 인사이트를 발굴해내는 일입니다. 이는 다음 성공의 밑거름이 될 것입니다.

**3. 준비성 있는 가설로 손해 없는 실험하기**  
AB 테스트의 결과는 크게 3가지로 나눌 수 있습니다. 성공, 실패, 변화 없음. 정말 명백하고 극적인 성공이나 실패는 매우 드뭅니다(앞서 설명한 크게 휘두르기 전략이 필요한 이유이기도 합니다). 결국 아무리 열심히 AB 테스트해도 돌아오는 건 변화 없는 실험 결과뿐입니다. 하지만 시야를 조금만 넓히는 것만으로 변화 없는 결과에서 인사이트를 만들어낼 수 있습니다. 위에서 살펴봤던 쿠팡의 사례에서도, 링크를 눌러본 고객의 구매 여부를 따로 파악하지 않았다면 후속 실험을 진행할 수 있었을까요? 모든 결과라도 대응할 수 있도록 데이터를 수집하고 다음 수를 계획해야 합니다. 그렇다고 실제로 상황별 후속 실험을 세세하게 기획할 필요까지는 없습니다. 이를 준비하는 과정에서 어떤 결과가 나와도 차분히 다음 단계를 밟을 수 있도록 계획하는 것으로 충분합니다.

## 정리

효과적인 AB 테스트 가설의 구조와 방법론은 다음과 같은 이유로 알 필요가 있습니다.

1. 조직 내  AB 테스트 확산에 기여합니다.
2. 전술적 실험에서 전략적 실험으로 전환할 수 있습니다.
3. AB 테스트의 영향력과 성공률을 키웁니다.

좋은 가설은 목표, 문제/기회, 솔루션, 예상 결과, 근거의 5층 구조로 구성되어 있습니다. 이러한 가설을 만드는 3가지 방법론은 아래와 같습니다.

1. 과감한 가설로 크게 휘두르기 
2. 확실한 정보로 단단한 가설 만들기
3. 준비성 있는 가설로 손해 없는 실험하기

가설은 중요합니다. 하지만 명심해야 할 점은 아무리 완벽한 가설이 있더라도 실행에 옮기지 않으면 무용하다는 것입니다. 준비가 끝났다면, 이제 행동할 시간입니다.