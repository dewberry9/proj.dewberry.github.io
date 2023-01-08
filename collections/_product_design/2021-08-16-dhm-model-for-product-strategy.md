---
title: 전략을 결정하는 전략. 넷플릭스 DHM 모델
layout: post
category: design-teatime
date: 2021-08-15 00:00:00 +0900
excerpt: 좋은 제품은 좋은 전략으로부터 나옵니다. 그럼 좋은 전략은? 넷플릭스 전 부사장의 제품 전략 수립·평가 방법론 DHM 모델을 알아봅니다.
thumbnail: /assets/images/design/dhm-model-for-product-strategy/00.jpg
permalink: /dhm-model-for-product-strategy
tag: '프로덕트'
stylecss: /assets/post.css
---

**DHM 모델 시리즈**  
1부 - 전략을 결정하는 전략. 넷플릭스 DHM 모델  
2부 - <a title='매거진 입맛 - DHM 모델로 제품 전략에서 AB 테스트 실무까지' href='/dhm-model-strategy-to-ab-test' rel='noopener'>DHM 모델로 제품 전략에서 AB 테스트 실무까지</a>
{: .infor}

오늘날의 디지털 프로덕트 시장은 결과물이라고 할 수 있는 제품에서부터 조직의 제품 개발 이론에 이르기까지 다양한 아이디어가 활발하게 제안되고 있습니다. 그중에서도 북극성 지표(North Star Metric)와 그로쓰 해킹의 기반이 되는 가설 - 실험 방법론, 이 둘은 수많은 조직에서 제품 개발의 방향을 결정하는 데 활용되고 있습니다.

<a title='Sean Ellis, 2017 - What is a North Star Metric?' href='https://blog.growthhackers.com/what-is-a-north-star-metric-b31a8512923f' target='_blank' rel='noopener'>북극성 지표는 제품이 고객에게 주는 핵심적 가치를 재는 척도</a>입니다. 북극성 지표를 개선하려는 노력은 곧 <a title='매거진 입맛 - 알아서 팔리는 제품을 만드는 제품 주도 성장(Product-led Growth) 방법론' href='/introduce-product-led-growth' target='_blank' rel='noopener'>제품 주도 성장(Product-led Growth) 방법론</a>으로 이어집니다. 이는 마케팅과 영업 활동에 의존하는 대신 제품 자체로 자신의 몸집을 불리는 성장 엔진을 만듭니다. 제품 개발자는 북극성 지표로 제품의 비전을 다룰 수 있게 되었습니다.

<a title='매거진 입맛 - 매출 만드는 AB 테스트, 시작이 막막한가요? 3단계 가이드' href='/3step-ab-test' target='_blank' rel='noopener'>AB 테스트</a>로 대표되는 그로쓰 해킹의 가설 - 실험 방법론은 데이터 기반 의사결정 전략을 만능키로 만들었습니다. 수익보다 훨씬 직접적인 지표가 제품의 기능과 모습을 결정합니다. 제품 개발자가 세심하게 설정한 실험 환경에서 고객은 저도 모르는 사이 제품을 개발합니다.

![DHM Model is Bridge Between North Star and AB Test]({{ '/assets/images/design/dhm-model-for-product-strategy/01.jpg' | relative_url }} 'DHM 모델은 다리이다.'){: loading='lazy'}
{: .normal-size}

한편 북극성 지표와 가설 - 실험 방법론 사이는 상당히 떨어져 있습니다. 북극성 지표는 제품이 가야 하는 방향을 표시하는 큰 롤러 붓이지만 가설 - 실험 방법론은 작은 버튼 하나에도 쓰일 수 있는 얇은 붓입니다. 그 때문에 이 둘의 방향이 상충하기라도 하면 까다로워집니다. 하지만 이 둘 사이에 다리가 되는 무언가가 있다면 문제는 해결되겠죠. 제품 전략 수립·평가 방법론 DHM 모델이 그 다리가 될 것입니다.

- 그렇다면 DHM 모델이 뭘까요?
- DHM의 구성요소는 뭐가 있고, 어떤 걸 뜻할까요?
- 넷플릭스, 쿠팡 등에서 발견할 수 있는 DHM 모델의 요소는 뭐가 있을까요?

## 깁슨의 DHM 모델

깁슨 비들(Gibson Biddle)은 2005년부터 2010년까지 넷플릭스의 제품 부사장(VP of Product)이었습니다. 아직 DVD 대여 사업을 유지하고 있던 때부터 2007년 본격적으로 스트리밍 사업에 뛰어든 후, 2010년 캐나다로 첫 해외 진출할 때까지 넷플릭스라는 제품을 설계하고, 뜯고, 고쳤다는 뜻입니다. 직후에는 교육 기술 기업 Chegg에서 회사가 상장할 때까지 CPO(최고 제품 책임자) 자리를 맡았습니다.

깁슨은 오랫동안 리더의 자리에서 제품 개발을 지휘했던 경험을 바탕으로 제품이 어떤 방향으로 발전할지 결정하는 <a title='Gibson Biddle, 2019 - #1 The DHM Model' href='https://gibsonbiddle.medium.com/2-the-dhm-model-6ea5dfd80792' target='_blank' rel='noopener'>제품 전략의 수립과 평가를 위한 모델</a>을 만들었습니다. DHM 모델입니다.

![Three Points of DHM Model]({{ '/assets/images/design/dhm-model-for-product-strategy/02.jpg' | relative_url }} 'DHM 모델 3요소'){: loading='lazy'}
{: .normal-size}

DHM 모델은 특정 제품 전략을 설계하고 평가하는 데 쓰이는, 전략을 위한 전략입니다. DHM 모델은 다음 3개 질문으로 제품 전략을 수립합니다.

1. Delight Customers - 무엇이 고객에게 만족 혹은 효용을 가져다주는가?
2. Hard to Copy - 무엇이 제품을 복제하기 어렵게, 즉 독보적으로 만드는가?
3. Margin Enhancing - 무엇이 수익성을 개선하는가?
   
이제 각 항목을 좀 더 세부적으로 알아보겠습니다.

## Delight Customers

오늘날 아마존(Amazon)이라는 거대 IT 기업은 20년 전 제프 베조스(Jeff Bezos)가 냅킨 위에 그린 <a title='Ryan Faist(Channel Key), 2021 - Amazon Flywheel: The Secret to Success for Earth’s Most Customer-Centric Company' href='https://channelkey.com/amazon-flywheel-the-secret-to-success-for-earths-most-customer-centric-company/' target='_blank' rel='noopener'>아마존 플라이휠(Flywheel)</a>에서 시작되었습니다. 아마존 플라이휠은 제품 성장 구조로 낮은 가격, 상품 다양화가 고객을 만족시켜 더 많은 트래픽과 제품 성장을 불러오고, 다시 더 낮은 가격과 더 다양한 상품으로 이어지는 구조입니다. 이 무서우리만큼 단순하고 연속적인 제품 전략은 다시 없을 변화를 일으켰습니다. 고객 만족은 모든 제품의 기준이 되었습니다. 고객이 만족하고 효용을 느끼는 요소는 특정 제품을 찾는 이유가 됩니다. 좋은 제품 전략은 고객을 만족시킵니다.

그럼 실제 제품에서 해당하는 제품 전략을 찾아보겠습니다.

![Delight Points of Netflix, Coupang, and Beamin]({{ '/assets/images/design/dhm-model-for-product-strategy/03.jpg' | relative_url }} '넷플릭스, 쿠팡, 배달의민족의 고객 만족 제품 전략'){: loading='lazy'}
{: .full-size}

**넷플릭스**

1. 오리지널 콘텐츠
2. 고화질 비디오·사운드
3. 인터랙티브 콘텐츠
4. 여러 기기에서 사용 가능
   
**배달의민족**

1. 식당 후기
2. 자체 결제수단을 통한 포인트 적립(배민페이)
3. 전용 상품권 선물 기능
4. 대리 결제(가족계정)

**쿠팡**

1. 당일·익일 무료 배송 상품(로켓 배송)
2. 적립, 무료반품, 신선식품 구매 혜택, OTT 등을 포함한 멤버십(와우 멤버십)
3. 동일 상품 최저가 우선 노출
4. PB(자체 브랜드) 상품

## Hard to Copy

좋은 제품은 많지만, 살아남는 제품은 적습니다. 고객은 좋기만 한 제품에 남아 있지 않습니다. 살아남는 제품은 독보적이기 때문에 다른 제품과의 경쟁에서 이길 수 있습니다. <a title='매거진 입맛 - MVP는 방향이 아닌 속도다. MLP로 성장하는 제품 만들기(1/2)' href='/mlp-for-growing-product' target='_blank' rel='noopener'>MLP(Minimum Lovable Product) 개념을 소개한 글</a>에서도 ‘먹히는 어떤 것’이 '내 제품'만을 써야하는 이유가 되기 어렵다고 관련된 내용을 다룬 적 있습니다. 깁슨은 넷플릭스, 스포티파이(Spotify) 등 여러 IT 기업의 고문(Adviser)이자 헤지펀드 Strategy Capital의 매니징 파트너인 해밀턴 할머(Hamilton Helmer)의 책 <a title='Hamilton Helmer - 7 Powers: The Foundations of Business Strategy' href='https://7powers.com/' target='_blank' rel='noopener'>&lt;7 Powers : 비즈니스 전략의 본질&gt;</a>을 인용하며 제품을 복제하기 어렵게 만드는 전략의 7가지 핵심에 관해 설명합니다.

![7 Powers for Hrad-to-Copy]({{ '/assets/images/design/dhm-model-for-product-strategy/04.jpg' | relative_url }} '복제를 어렵게 만드는 7가지 힘'){: loading='lazy'}
{: .normal-size}

**1. 규모의 경제(Scale Economies)**
생산량이 늘면 개당 생산비용이 주는 현상을 규모의 경제라고 합니다. 규모의 경제는 이미 250여 년 전에 <a title='Adam Smith Institute - The Wealth of Nations' href='https://www.adamsmith.org/the-wealth-of-nations/' target='_blank' rel='noopener'>애덤 스미스(Adam Smith)가 그의 저서 국부론</a>에서 언급했습니다. 일단 초기 시장 진출, 지출 구조 개선 등으로 규모의 경제를 이루고 나면, 경쟁사가 같은 방식으로 규모의 경제를 이루기 위해 점유율을 늘릴 때 경쟁사는 상대적으로 더 높은 가치 혹은 더 낮은 가격을 제공해야 합니다. 규모의 경제를 이미 이룬 기업은 경쟁사에 맞춰 가치와 가격을 조정하며 쉽게 방어할 수 있습니다. 시간이 흐를수록 규모의 경제를 이룬 기업과 그렇지 않은 기업의 차이는 벌어집니다.

**2. 네트워크 효과(Network Effect)**
제품 사용 고객이 늘어날수록 제품이 제공하는 가치가 커지는 현상을 말합니다. 네트워크 효과를 이룬 기업의 경쟁사는 고객을 유치하기 위해 엄청난 비용을 지불해야 합니다. 규모의 경제와 마찬가지로 시장에는 네트워크 효과를 이룬 기업의 독식 체계가 형성됩니다.

**3. 카운터 포지셔닝(Counter Positioning)**
카운터 포지셔닝은 다윗이 골리앗을 이기는 방법입니다. 기성 대기업은 기민하지 못하고 위험을 회피하는 성향이 있기 때문에 아직 증명되지 않고 더 나은 비즈니스 모델이 등장했을 때 금방 활용하지 못합니다. 스타트업과 같은 신규 기업은 이를 적극적으로 채용하여 시장을 전복합니다.
넷플릭스가 아직 DVD 대여 사업을 하던 시절, 시장의 주도권을 가진 기업은 블록버스터(Blockbuster)였습니다. 블록버스터의 주요 수익원은 DVD 대여 연체료였습니다. 넷플릭스는 DVD 익일 배송과 더불어 연체료를 받지 않는 정책을 펼쳤고 시장의 판도는 바뀌었습니다.

**4. 전환 비용(Switching Costs)**
아이폰 사용자는 다음 휴대폰도 아이폰으로 고르는 경우가 많습니다. 다른 스마트폰과 아이폰의 사용 경험은 상당한 차이가 있어 익히는 데 시간이 들기 때문입니다.

넷플릭스의 네트워크 효과로 유치한 수많은 고객에게서 나온 데이터를 바탕으로 독보적인 개인화 경험을 제공합니다. 다른 OTT 제품도 저마다의 개인화 경험을 제공하겠지만 새 제품에서 이미 넷플릭스를 사용하고 있는 고객이 제공받는 수준의 개인화 경험이 이륙 되려면 오랜 시간이 필요합니다. 이 비용 때문에 고객은 넷플릭스에서 이탈하지 않습니다.

**5. 브랜드**
명품이 값비싼 것은 명품 브랜드가 제공하는 신뢰도, 스토리텔링, 제품의 가치를 다수가 공인한 까닭입니다. 이 과정은 아주 오랜 기간 고객과 브랜드 사이의 긍정적 경험이 누적되면서 이뤄집니다.

**6. 고유한 리소스**
특허로 독자적인 기술 사용권을 얻거나, 다른 조직에는 이식하기 어려운 유일무이한 업무 문화가 있다면 이는 모두 고유한 리소스라고 볼 수 있습니다. 고유한 리소스는 제품 개발에 사용되며 복제하기 어려운 제품을 만드는 데 도움을 주곤 합니다.

**7. 프로세스**
제품이 고도화될수록 제품과 조직에는 고유한 프로세스가 생기기 시작합니다. 이러한 프로세스는 개발, 고객 획득, 기업 문화 등 제품과 조직의 성장에 전반적으로 영향을 줍니다.

## Margin Enhancing

수익은 제품이라는 로켓이 비전이라는 별에 도달하기 위해 필요한 연료입니다. 제품으로 벌어들인 수익은 제품에 재투자되며 성장은 가속도가 붙습니다. 수익성 개선의 핵심은 가치 창출 경로를 찾아내고 시장에서 인정되는 가격으로 제공하는 것입니다.

넷플릭스 가격 정책의 간략한 역사를 본다면 완벽한 수익화 모델이란 없으며 대신 한없이 완전에 가까워지는 길만 있다는 사실을 알게 될 것입니다.

1. DVD 대여 사업 초기, 디스크 1개당 4달러의 가격 정책은 월 25달러에 3개를 대여하는 구독 방식으로 개편되었습니다.
2. 디스크 1개에 10달러, 2개에 17달러, 3개의 23달러 등 여러 요금제가 실험되었습니다. 곧 규모의 경제가 발생했고 가격은 절반 이하로 감소했습니다.
3. 2007년 처음 월 23달러 구독료를 내는 스트리밍 서비스가 출시되었을 때 한 달 시청 가능 시간은 23시간이었습니다. 시청 시간은 실험 후 무제한으로 변경되었습니다.
4. 오늘날 넷플릭스는 영상 품질, 동시 시청 기기 수 같은 요소에 차등이 있는 3가지 멤버십을 운영합니다. 좀 더 저렴한 모바일 전용 요금제가 실험 중입니다.

## DHM 모델로 확인하는 좋은 제품 전략

한 제품 전략은 DHM 모델의 3가지 방향성을 모두 지니고 있을 수도 있고, 반대로 하나도 없을 수도 있습니다. 정확한 것은 제품 전략을 실천하는 단계에서 알게 되겠지만 DHM 모델은 실행 이전 단계에서 제품 전략 아이디어를 평가하는 데 부족함이 없습니다.

![DHM Model Evaluation of Netflix, Coupang, and Beamin Product Strategies]({{ '/assets/images/design/dhm-model-for-product-strategy/05.jpg' | relative_url }} '넷플릭스, 쿠팡, 배달의민족 DHM 모델 평가'){: loading='lazy'}
{: .full-size}

이를테면 넷플릭스 오리지널 콘텐츠 전략은 새 콘텐츠에 목말라 있는 고객을 만족시킵니다. 오리지널 콘텐츠는 고객 데이터를 바탕으로 시장에서 먹힐 만하다고 특정된 요소를 포함합니다. 이러한 데이터는 넷플릭스 정도 되는 규모의 제품에서 효과적으로 활용할 수 있습니다. 오리지널 콘텐츠는 넷플릭스 고유의 특색이 되고 고객이 유입시킬 수 있습니다. 게다가 콘텐츠 제작비를 직접 관리하여 콘텐츠 단가를 낮출 수도 있습니다. 반면 쿠팡의 최저가 노출 전략은 이미 다른 제품에서도 흔하게 볼 수 있는 전략입니다. 단기적으로 봤을 때는 수익에도 큰 도움이 되지 않습니다. 대신 최저가 노출 전략은 경쟁사로 빠져나가는 고객을 방어합니다.

이렇듯 특정 전략이 DHM 모델의 몇 가지 방향성을 가졌는지 검토하면 각 전략의 효과와 우선순위에 대해 참고할 만한 인사이트를 얻게 됩니다.

## 정리

이번 편에서는 제품 전략을 수립하는 전략인 DHM의 개념과 구성, 즉 고객 만족, 복제의 어려움, 수익성에 대해 실제 제품 사례와 함께 알아보았습니다. <a title='매거진 입맛 - DHM 모델로 제품 전략에서 AB 테스트 실무까지' href='/dhm-model-strategy-to-ab-test' target='_blank' rel='noopener'>이어지는 글</a>에서는 DHM 모델로 수립된 제품 전략이 어떤 과정을 통해 실무 단계까지 내려와 작동하는지 살펴보겠습니다.

위시켓의 지원과 함께 제작된 콘텐츠입니다.
{: .right-infor}