---
title: 로빈후드, 토스뱅크가 출시 전에 100만 고객을 모은 방법. 대기자 명단 바이럴
layout: post
category: design-teatime
date: 2021-11-04 00:00:00 +0900
excerpt: 어떻게 하면 고객이 다른 고객을 데려오도록 할 수 있을까요? 대기자 명단 바이럴(Waitlist Viral)의 3가지 핵심을 분석하며 알아봅니다.
thumbnail: /assets/images/design/waitlist-viral/00.jpg
permalink: /waitlist-viral
tag: '프로덕트'
stylecss: /assets/post.css
---

![Waitlist UI]({{ '/assets/images/design/waitlist-viral/01.jpg' | relative_url }} 'Waitlist UI'){: loading='lazy'}
{: .full-size}

몇 년 전 쉐이크쉑이 한국에 처음 들어온 때였습니다. 근처에 볼일이 있어 막 개장한 강남점을 지나간 적이 있습니다. 무척 더운 날이었습니다. 모퉁이 자리 쉐이크쉑 정문 앞 인도부터 코너를 돌아 길게 늘어진 줄이 멀리서도 보였습니다. 쉐이크쉑은 물론, 수제버거에 관해서는 아무런 흥미도 지식도 없었지만 자연히 관심이 생겼습니다. 언젠가 한 번 직접 줄을 서볼 정도였습니다. 여행지에서도 구태여 맛집을 찾지 않고 되는대로 밥을 먹는 저에게는 신기한 경험이었습니다. 더 묘한 것은, 오직 긴 대기 줄만 보고 쉐이크쉑에 가기로 마음먹었다는 점입니다.

본래 가게 앞에 늘어선 대기 줄은 자원 부족을 의미합니다. 조리에 쓰일 재료, 서빙에 필요한 일손, 손님이 자리할 시간과 공간이 부족할 때 서비스 제공에 지연이 생깁니다. 기존 고객이 이용을 마치고 자원의 여유분이 생길 때까지 다음 고객은 기다립니다. 대기 줄에 서는 행동은 기다리는 시간을 지불해서라도 해당 가게에서의 경험을 원한다는 부가적 의미를 낳습니다. 이런 점이 길게 줄을 선 가게, 그 많은 사람들이 선택한 경험의 매력도를 높입니다.

오프라인 매장과는 달리, 디지털 프로덕트에서 고객이 많다고 불만을 토로하는 경우는 보기 드뭅니다. 나날이 발전하는 기술 덕분에 디지털 프로덕트의 수용 능력은 그 어느 시대보다 거대한 상태입니다. 그러나 디지털 프로덕트에서 줄을 선 모습은 종종 눈에 띕니다. 대기 줄의 부가 효과 때문입니다. 최근에는 토스뱅크가 <a title='토스뱅크 - 토스뱅크 사전신청 사흘만에 50만명 돌파' href='https://blog.toss.im/article/tossbank-500k?refer=mag_epmat' target='_blank' rel='noopener'>사흘 만에 50만</a>, 한 달도 안되서 100만 명이 넘는 사전신청자를 유치한 적 있습니다. 어떻게 제품 정식 출시 전 이렇게 많은 잠재 고객을 모을 수 있었을까요? 배경에는 가게 앞에 선 줄, 대기자 명단(Waitlist) 바이럴 프로그램이 있었습니다.

- 그렇다면 대기자 명단 바이럴이 구체적으로 무엇이고 어떤 과정을 거쳐 지금의 역할에 이르게 되었을까요?
- 효과적인 대기자 명단 바이럴을 만드는데 필요한 3가지 핵심은 어떤 걸까요?
- 토스뱅크, 로빈후드(Robinhood) 등 실제 제품에서 대기자 명단 바이럴은 어떤 모습을 보였을까요?

## 윈도우, 드롭박스, 그리고 로빈후드의 대기 줄

오늘날 대기자 명단 바이럴은 제품 기능 혹은 제품 자체를 출시하기 전 **모집한 잠재고객이 또 다른 고객을 데려오는 핵심 메커니즘으로 작동하는 고객 유치 캠페인**이라고 정의할 수 있습니다. 대기자 명단 바이럴이 이와 같은 형태와 역할을 갖추게 된 것은 오래된 일이 아닙니다. 대기자 명단은 디지털 프로덕트 유통 과정의 진화에 따라 부수적 현상, 고객 니즈를 증명하는 역할, 핵심 바이럴 요소로 변화해왔습니다.

![Waiting Line in front of Windows 95 Sales Booth]({{ '/assets/images/design/waitlist-viral/02.jpg' | relative_url }} 'Waiting Line in front of Windows 95 Sales Booth'){: loading='lazy'}
{: .normal-size}  
사진출처 : Luis D'Orey(Reuters)
{: .infor}

상상조차 어렵지만, 과거의 디지털 프로덕트 구매는 인터넷과 간편 결제가 아니라 오프라인 매장과 지폐로 이뤄졌습니다. 마이크로소프트(Microsoft)의 히트작 중 하나인 윈도우 95(Windows 95) 역시 그렇습니다. 사람들은 CD에 담긴 윈도우 95를 사려고 밤새 줄을 섰습니다. 1995년 8월 24일 전 세계 의 윈도우 95 판매 부스 앞에서는 긴 줄이 늘어섰습니다. 윈도우 95는 혁신적이었습니다. 인터넷 익스플로러(Internet Explorer)의 조상 Internet Jumpstart Kit, 플러그 앤 플레이 지원, 화면 왼쪽 아래의 시작 버튼이 이때부터 들어갔습니다. 그러나 출시 5주간 <a title='Tom Warren(The Verge), 2020 - Windows 95 is 24 Years Old Today' href='https://www.theverge.com/21398999/windows-95-anniversary-release-date-history?refer=mag_epmat' target='_blank' rel='noopener'>7백만 개가 팔렸던 윈도우 95의 판매 기록</a>을 기술적 혁신만으로 설명하기는 어렵습니다. 1억 5천만여 달러라는 막대한 마케팅 비용도  윈도우 95의 실적에 크게 기여했습니다. 이는 당시 펩시(Pepsico)가 피자헛(Pizza Hut)이나 타코벨(Taco Bell)에 쓰는 <a title='Tim Stenovec(INSIDER), 2015 - People were unbelievably excited at the launch of Windows 95' href='https://www.businessinsider.com/windows-95-launch-20-years-ago-2015-8?refer=mag_epmat' target='_blank' rel='noopener'>1년 치 광고비와 맞먹는 금액</a>이었습니다. 마이크로소프트는 미국 최고의 심야 토크쇼 프로그램 더 투나잇 쇼(The Tonight Show)의 호스트까지 고용하면서 윈도우 95의 마케팅에 온 힘을 다했습니다. 윈도우 95 앞에 선 대기 줄은 이러한 노력이 만들어낸 부수적인 현상에 불과했습니다.

드롭박스(Dropbox)는 대표적인 파일 공유 클라우드 서비스입니다. 제품 개발과 마케팅에 이르기까지 드롭박스가 보여준 여러 모험은 <a title='매거진 입맛 - MVP가 실패하는 5가지 이유와 해답 - MVT(최소기능검증)' href='/why-mvp-as-a-product-fails-try-mvt' target='_blank' rel='noopener'>그로쓰 해킹의 표본</a>이 되었습니다. 이후 모든 스타트업의 제품 출시 방식을 바꿔버린 <a title='Drew Houston, 2010 - Dropbox Startup Lessons Learned' href='https://www.slideshare.net/gueste94e4c/dropbox-startup-lessons-learned-3836587?refer=mag_epmat' target='_blank' rel='noopener'>드롭박스의 제품 출시 과정</a>도 그중 하나입니다. 2006년, 드롭박스라는 아이디어를 처음으로 논의하기 시작했을 때 시장에는 이미 여러 파일 공유 서비스가 있었습니다. 하나 같이 불안정하고 불편한 서비스 사이에서 드롭박스는 차별화할 자신이 있었습니다. 그러나 이해시키기 어려운 기술적 기반에서 비롯한 자신감만으로 투자자를 설득할 수는 없었습니다. 드롭박스는 베타 제품을 사용하기를 원하는 고객을 모아 니즈를 증명하기로 합니다. 여기서 전설적인 MVP가 등장합니다. 드롭박스는 실제 작동하는 제품을 만드는 대신 작동하는 것처럼 보이는 데모 비디오를 커뮤니티에 공유했습니다. 베타 사용 신청자는 5천 명에서 7만 5천 명으로 하룻밤 새 15배 늘었습니다. 고객 니즈는 증명되었습니다. 폭발적인 반응을 보인 커뮤니티는 초기 제품에 꼭 필요한 구체적인 피드백을 수집하는 데도 효과적이었습니다. 대기자 명단은 출시 전의 드롭박스가 가진 잠재력을 증명했습니다. 이는 바이럴 실적을 확인하는 용도였지 바이럴 자체를 일으키는 주체는 아니었습니다.

![Waitlist Viral]({{ '/assets/images/design/waitlist-viral/03.jpg' | relative_url }} 'Waitlist Viral'){: loading='lazy'}
{: .normal-size}

대기자 명단이 본격적으로 바이럴 도구가 된 것은 <a title='Apostle Mengoulis(Viral Loops), 2018 - How Robinhood’s referral program brought 1 million users before launch' href='https://viral-loops.com/blog/robinhood-referral-got-1-million-users?refer=mag_epmat' target='_blank' rel='noopener'>로빈후드 때부터</a>입니다. 수수료 없는 주식 거래 서비스 로빈후드는 처음부터 커뮤니티에서 돌풍을 일으켰습니다. 2013년 말 <a title='Anna Mazarakis and Alyson Shontell(INSIDER), 2017 - The founders of Robinhood, a no-fee' href='https://www.businessinsider.com/robinhood-app-vlad-tenev-founder-free-stock-trading-valuation-2017-7?refer=mag_epmat' target='_blank' rel='noopener'>로빈후드가 등장했을 때</a> 첫날에 1만 명, 첫 주에는 5만 명이 넘는 잠재고객이 베타 사용 신청했습니다. 그러나 이후 한 해 동안 1백만 명으로 불어난 대기자 명단에서는 일시적인 화제성 이상의 추진력이 있었습니다. 로빈후드는 베타를 신청한 고객에게 자신보다 먼저 베타 신청한 사람이 몇 명인지, 더 늦게 신청한 사람은 몇 명인지 순위를 보여줬습니다. 동시에 개인화된 미디어 쿼리를 단 초대 URL를 줬습니다. 해당 URL를 통해 베타 신청한 사람이 생기면 순위를 올릴 수 있었습니다. 초대의 보상으로 ‘새치기’가 주어진 것입니다. 이 기능으로 로빈후드의 베타 신청자들은 경쟁적으로 바이럴했습니다. 앞에 길게 늘어선 대기 줄이 초대 한번으로 쑥쑥 줄어드는 경험은 거의 중독적이었습니다. 대기자 명단은 로빈후드의 초기 성장을 책임진, 강력한 바이럴 도구였습니다.

## 좋은 대기자 명단 바이럴을 만드는 3가지 포인트

![Three Points of Waitlist Viral]({{ '/assets/images/design/waitlist-viral/04.jpg' | relative_url }} 'Three Points of Waitlist Viral'){: loading='lazy'}
{: .normal-size}

로빈후드의 사례를 비롯한 대기자 명단 바이럴의 성공에는 3가지 특징이 있습니다.

1. 게이미피케이션(Gamification) 구조
2. 쉽고 효과적인 신청·초대 과정
3. 커뮤니티 타겟팅

초기 제품에서 실효성 있는 바이럴 효과를 일으키기 위해서는 각 특징이 대기자 명단 바이럴에서 작동하는 방식에 대해 이해하는 일이 중요합니다.

**게이미피케이션 구조 - 대기 순번**  
<a title='Alita Joyce(Nielson Norman Group), 2019 - Gamification in the User Experience' href='https://www.nngroup.com/videos/gamification-user-experience?refer=mag_epmat' target='_blank' rel='noopener'>게이미피케이션</a>은 게임 역학을 게임 바깥의 맥락에서 활용하는 것을 의미합니다. 게임 역학은 게임이 플레이어의 재미와 참여를 위해 게임의 규칙을 학습시키는 과정입니다. 학습은 플레이어의 동기와 관심을 연료 삼아 진행됩니다. 디지털 프로덕트에서 게이미피케이션은 비즈니스 목표를 달성하기 위한 제품 학습·사용 유도 과정에서 활용됩니다. 잘 설계된 게이미피케이션 구조에서 고객은 학습하고 제품을 사용하는데 충분한 동기를 갖게 됩니다. 일의 진행도를 알려주는 진행 표시줄(Progress Bar), 어떤 일을 성취했을 때 받는 뱃지, 나의 위치가 전체에서 어디쯤인지 알려줘 경쟁을 유도하는 순위표(Leaderboard) 등이 게이미피케이션 요소입니다.

<a title='매거진 입맛 - 고객 10명 중 6명은 한번 쓰고 버린다. 줄줄 새는 제품 온보딩 고치기' href='/product-led-growth-onboarding' target='_blank' rel='noopener'>제품 주도 성장(Product Led Growth) 방법론의 온보딩 개선 전략을 다룬 이전 글</a>에서 <a title='Stanford Behavior Design Lab - Fogg Behavior Model' href='https://behaviordesign.stanford.edu/fogg-behavior-model?refer=mag_epmat' target='_blank' rel='noopener'>포그 행동 모델(Fogg Behavior Model)</a>을 이야기한 적 있습니다. 포그 행동 모델은 어떤 행동이 발생하는데 필요한 3가지 요인을 설명합니다. 행동에 드는 힘, 난이도를 의미하는 능력(Ability), 행동 신호, 트리거를 뜻하는 계기(Prompts), 그리고 행동에 대한 의욕·의지를 나타내는 동기(Motivation)입니다. 어떤 행동에 대한 계기가 나타나면 대상이 되는 사람이 가지고 있는 동기와 행동의 난이도에 따라 행동의 실현 여부가 결정됩니다. 대기자 명단 바이럴의 게이미피케이션 구조는 포그 행동 모델의 3가지 요인 중 동기를 자극합니다.

![Robinhood Waitlist Viral]({{ '/assets/images/design/waitlist-viral/05.jpg' | relative_url }} 'Robinhood Waitlist Viral'){: loading='lazy'}
{: .normal-size}

대기자 명단 바이럴 속 게이미피케이션 구조의 중심에는 대기 순번이 있습니다. 많은 대기자 명단 바이럴 프로그램에는 로빈후드가 벤치마킹한 iOS 이메일 앱 메일박스(Mailbox)처럼 대기 줄에서 고객이 몇 번째인지 알려주는 2가지 숫자를 보여줍니다. 제품을 먼저 쓸 수 있는 사람이 몇 명인지,  자신이 몇 명보다 앞섰는지 알려줍니다. 기술적 한계에 의한 <a title='Ellis Hamburger(The Verge), 2013 - Inbox Unchained: Mailbox just fixed email on the iPhone' href='https://www.theverge.com/2013/2/7/3961544/mailbox-app-for-iphone-inbox-unchained?refer=mag_epmat' target='_blank' rel='noopener'>기약 없는 대기</a>라는 점에서 메일박스의 대기 줄은 오프라인 매장의 대기 줄과 비슷했습니다. 이 숫자는 로빈후드에서 철저히 게이미피케이션 요소가 되었습니다. 수많은 사람들이 관심을 보이기 때문에 제품 선택의 허들은 낮아집니다. 이게 바로 <a title='매거진 입맛 - 전환율 높이는 상세 페이지 디자인. 바로 써보는 3가지 방법' href='/product-page-tips' target='_blank' rel='noopener'>이전 글에서 언급한 적 있는 소셜 프루프(Social Proof)</a>입니다. 인간은 사회적 동물입니다. 작든 크든 인간의 선택에는 사회가 영향을 미칩니다.
그러나 대기 순번은 소셜 프루프보다 보상 대상으로서의 존재감이 더 큽니다. 초대하면 대기 순번을 앞당길 수 있습니다. 이 단순한 기능이 대기 순번을 게임의 점수로 만들었습니다.

![Robinhood Waitlist Viral]({{ '/assets/images/design/waitlist-viral/06.jpg' | relative_url }} 'Robinhood Waitlist Viral'){: loading='lazy'}
{: .normal-size}

토스뱅크는 이 기능을 ‘등수 올리기’라는 직관적인 카피로 제공했습니다. 빨리 신청할수록, 총 초대수가 많을수록 순번이 앞당겨집니다. 위에서 설명했듯 로빈후드도 마찬가지 기능을 제공했습니다. 8년 전 이 효과를 톡톡히 본 로빈후드는 최근 암호화폐 지갑 서비스에 대한 <a title='Robinhood, 2021 - Crypto Wallets Are Coming to Robinhood' href='https://blog.robinhood.com/news/2021/9/22/crypto-wallets-are-coming-to-robinhood?refer=mag_epmat' target='_blank' rel='noopener'>사전 사용 신청</a>을 받으면서 대기자 명단을 쓰고 있습니다. 토스뱅크와는 달리 한번 초대할 때마다 대기 순번이 절반씩 앞당겨집니다. 총 초대 수를 기준으로 하는 토스뱅크의 방식은 큰 차이의 상대를 만나게 되면 그 이상 순번을 올리기 어렵기에 단기간의 캠페인에 어울립니다. 반대로 로빈후드의 새 대기자 명단 바이럴 프로그램은 엎치락뒤치락하는 순번을 높이기 위해 꾸준한 초대가 필요하므로 장기간의 캠페인에 적당합니다. 어느 쪽이든 대기 순번 올리기가 제품을 쓰고 싶어 사전 신청한 고객에게 매력적인 보상인 것은 변함이 없습니다. 보상은 눈에 보이는 구체적인 숫자로 주어집니다. 이 모든 환경이, 잠재고객이 또 다른 고객을 데려오는 일로 경쟁하도록 부추깁니다.

**쉽고 효과적인 신청·초대 과정**  
포그 행동 모델에서 알 수 있듯, 난이도는 어떤 행동을 수행하는 데 있어서 중요한 요인입니다. 대기자 명단에 이름을 올리는 신청 과정과 다른 고객을 초대하는 일은 간단하고 쉬워야 합니다.

![Robinhood Early Access Landing Page]({{ '/assets/images/design/waitlist-viral/07.jpg' | relative_url }} 'Robinhood Early Access Landing Page'){: loading='lazy'}
{: .normal-size}

로빈후드는 ‘0달러 주식 거래’ 모토를 건 단순한 랜딩 페이지로 잠재 고객을 받았습니다. 신청에 필요한 정보는 제품 출시 때 안내할 용도로 받은 이메일 주소가 전부였습니다. 신청 후 대기 순번을 올릴 수 있는 화면에서는 고유 초대 URL을 각각 트위터, 페이스북, 이메일, 링크드인으로 공유할 수 있는 선택지가 주어졌습니다.

이미 기반이 확실한 토스에서 파생된 토스뱅크는 모든 과정이 좀 더 단순했습니다. 고객은 앱에서 터치 한번으로 사전 사용 신청을 끝낼 수 있었습니다. 신청 직후에는 지인 1명을 초대해서 올릴 수 있는 대기 순번을 보여줘 곧바로 초대 활동에 임하도록 설계했습니다.

두 금융 제품이 보여주는 신청·초대 과정의 간결함은 성공적인 대기자 명단 바이럴의 좋은 예시입니다.

**커뮤니티 타겟팅**  
![Viral]({{ '/assets/images/design/waitlist-viral/08.jpg' | relative_url }} 'Viral'){: loading='lazy'}
{: .normal-size}

게이미피케이션 구조는 고객이 고객을 불러오는 대기자 명단 바이럴의 핵심 사이클을 형성하고, 쉽고 효과적인 신청·초대 과정은 이 사이클을 부드럽게 돌아가도록 만드는 윤활유 역할을 합니다. 이 사이클이 얼마나 빨리, 오래 돌아갈지는 커뮤니티 타겟팅에 달렸습니다. 어떤 커뮤니티에서 바이럴을 시작할지 결정하는 일은 중요합니다. 대기자 명단 바이럴은 고객이 고객을 불러 결과적으로 기하급수적인 성장을 이끌어내는 바이럴 방식입니다. 고객 1명이 다른 고객 2명을 불러온다고 가정합시다. 처음 모집된 고객이 10명입니다. 첫 번째 초대에서 새 고객 20명이 생깁니다. 이들이 초대하면 또 다른 고객 40명이 생깁니다. 다음은 80명, 160명…. 새로 온 고객이 빠짐없이 초대한다고 했을 때, 네 번의 초대 사이클을 거쳤을 뿐인데 10명의 고객은 310명이 되었습니다. <a title='매거진 입맛 - 바이럴 없는 제품은 말라죽을 수밖에 없다' href='/product-led-growth-viral' target='_blank' rel='noopener'>바이럴 계수 K에 관해 이야기한 예전 글</a>에서 설명했듯, 이 숫자는 초기 고객의 수, 고객 1명이 초대하는 수, 그리고 각 초대의 전환율에 따라 달라집니다. 3가지 요인을 고려하여 적절한 커뮤니티를 선택해야 합니다. 개방적인 커뮤니티일수록 처음 모집되는 고객의 수는 많겠지만 고객 개개인의 열의는 크지 않아 1인당 초대 횟수가 낮을 수 있습니다. 반대로 폐쇄적인 커뮤니티라면 초기 고객 수가 적을 뿐만 아니라 바이럴 홍보부터가 어렵겠지만, 한번 제품의 효용성을 인정받고 나면 활발하게 바이럴하는 든든한 열성 고객을 얻을 수 있을 것입니다.

드롭박스와 로빈후드는 모두 IT 커뮤니티인 Hacker News에서 큰 반응을 얻은 바 있습니다. 혁신적인 제품을 가진 두 스타트업의 이야기는 Hacker News의 구성원이 관심을 끌 만한 것이었습니다.

토스뱅크의 경우는 좀 더 쉬웠습니다. 토스는 국내 금융 앱 중 가장 높은 MAU(월간 활성 유저 수)와 사용 시간을 가졌습니다. 매달 <a title='이형두(전자신문), 2021 - 토스, 카카오뱅크 제쳤다' href='https://m.etnews.com/20210928000045?obj=Tzo4OiJzdGRDbGFzcyI6Mjp7czo3OiJyZWZlcmVyIjtOO3M6NzoiZm9yd2FyZCI7czoxMzoid2ViIHRvIG1vYmlsZSI7fQ%3D%3D' target='_blank' rel='noopener'>1,412만 명이 넘는 고객</a>이 토스 앱을 사용합니다. 이미 브랜드와 제품을 알고 있는 토스 고객을 대상으로 시작하는 바이럴에서 좋은 성과를 기대하기란 어렵지 않습니다.

## 정리

가게 앞에 늘어선 대기 줄은 자원 부족을 의미하지만, 대기 줄에 서는 행동은 기다리는 시간을 지불하는 게 아깝지 않을 만큼 가게의 경험이 매력적임을 암시합니다. 디지털 프로덕트의 대기자 명단 바이럴은 이런 구도를 고객 유치에 활용합니다. 대기자 명단 바이럴은 디지털 프로덕트를 CD에 넣어 판매했던 시절부터 그 형태와 역할이 계속 변화해 왔습니다. 오늘날에는 제품 기능 혹은 제품 자체를 공개하기 전, 모집한 잠재고객이 또 다른 고객을 데려오는 핵심 메커니즘으로 작동하는 고객 유치 캠페인으로 정의 내릴 수 있습니다.

성공적인 대기자 명단 바이럴은 게이미피케이션 구조, 쉽고 효과적인 신청·초대 과정, 그리고 커뮤니티 타겟팅이라는 3가지 핵심이 있습니다.

여러 번 밝힌 것처럼, 고객을 데려와서 제품을 유지하는 비용은 점점 늘어나고 있습니다. 큰 잠재력을 가지고 있는 대기자 명단 바이럴은 앞으로 고객 획득 전략의 대세가 될 가능성이 충분해 보입니다.

위시켓의 지원과 함께 제작된 콘텐츠입니다.
{: .right-infor}