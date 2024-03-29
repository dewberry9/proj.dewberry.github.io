---
title: '프라이버시 트렌드 정리 : 이제 개인 정보는 관리해야 할 리스크입니다.'
layout: post
category: design-teatime
date: 2021-07-08 00:00:00 +0900
excerpt: Apple의 앱 추적 투명성, EU 쿠키 법, Google의 FLoC... 사용자가, 시장의 규칙이 바뀌고 있습니다. 프라이버시 트렌드에 대해 정리합니다.
thumbnail: /assets/images/design/privacy-trend/00.jpg
permalink: /privacy-trend
tag: 'ETC'
stylecss: /assets/post.css
---

**프라이버시 트렌드 시리즈**  
1부 - 프라이버시 트렌드 정리 : 이제 개인 정보는 관리해야 할 리스크입니다.  
2부 - <a title='매거진 입맛 - 이루다의 논란이 넷플릭스에 없는 이유. 프라이버시 리스크 관리의 3가지 포인트' href='/three-points-of-privacy-risk-management' rel='noopener'>이루다의 논란이 넷플릭스에 없는 이유. 프라이버시 리스크 관리의 3가지 포인트</a>
{: .infor}

하나의 유령이 디지털 프로덕트 마켓을 배회하고 있습니다. 프라이버시라는 유령이.

데이터 중심 의사결정은 작은 스타트업이라는 다윗이 기성 대기업이라는 골리앗과 싸워 유니콘으로 성장하는 데 크게 기여한 전략입니다. 데이터 중심 의사결정은 쉽게 말해 결정권자 개인의 주관 대신 실제 제품과 시장의 데이터가 특정 의사결정의 근거가 되는 구조입니다. 딱히 새로운 방법론이라고 할 수는 없습니다. 그런데 이 낡은 전략은 디지털 프로덕트에 도입되면서 차원이 다른 성능을 내기 시작합니다.

![Characteristics of digital products in data-driven decision-making]({{ '/assets/images/design/privacy-trend/01.jpg' | relative_url }} '데이터 중심 의사결정에 있어서 디지털 프로덕트의 특징'){: loading='lazy'}
{: .normal-size}

디지털 프로덕트에서는 이전의 제품보다 더 많은 데이터를 정확하고, 빠르고, 저렴하게 뽑아낼 수 있습니다. 이는 자연히 더 많고, 정확하고, 영향력 있는 인사이트로 이어집니다. 디지털 프로덕트에 있어서 이러한 데이터 중심 의사결정 전략의 특성은, 그로쓰 해킹의 유행 그리고 제품 자체가 자신을 작동시키고 성장시키는 <a title='매거진 입맛 - 알아서 팔리는 제품을 만드는 제품 주도 성장(Product-led Growth) 방법론' href='/introduce-product-led-growth' target='_blank' rel='noopener'>제품 주도 성장 방법론</a>을 개발하는데 이르렀습니다.

데이터의 위치가 굳건한 이 상황에, 첫 줄에서 언급한 프라이버시라는 유령은 허황한 이야기로 들릴 겁니다. 하지만 변화는 생각 이상으로 빠르고 확실하게 일어나고 있습니다. 이미 우리는 하루에도 몇 번씩이고 쿠키 허용 배너와 앱 추적 허용 팝업을 만납니다. 점점 몸집이 커지고 있는 이 유령을 보자면 지금의 데이터 중심 의사결정이 그대로 작동할 수 있을 지 의문이 듭니다. 그 전에 살아남을 수나 있을까요?

- Apple의 앱 추적 투명성, EU 쿠키 법, Google의 FLoC가 정확히 뭘까요?
- 위와 같은 정책이 시장에, 제품을 만드는데 어떤 영향을 줄까요?
- 데이터 중심 마케팅(Data-Driven Marketing)은 이제 정말 끝난 걸까요? 💀

## 애플의 앱 추적 투명성, 페이스북과의 대결

2020년 애플은 iOS 14와 함께 앱 추적 투명성(ATT; App Tracking Transparency) 정책을 발표합니다. 준비 시간이 필요한 앱 개발사의 요청으로 앱 추적 투명성 정책은 2021년 iOS 14.5 업데이트와 함께 본격적으로 실행됩니다.

앱 추적 투명성은 제품이 IDFA(Identifier for Advertisers)를 비롯한 사용자 식별자를 설정하여 사용 데이터를 수집하기 전에 명시적인 동의를 받는 등, 사용 데이터를 수집하는 제품의 행위에 대해 <a title='Apple Developer - 사용자 개인정보 보호 및 데이터 사용' href='https://developer.apple.com/kr/app-store/user-privacy-and-data-use/' target='_blank' rel='noopener'>사용자의 권한을 늘려주는 데 초점을 맞춘 정책</a>입니다.

IDFA, AdID(안드로이드 앱의 광고 식별자) 등의 광고 식별자는 사용자가 볼 수 없는 앱 생태계의 속살 밑에서 흐르는 피 같은 존재입니다. 광고 식별자는 본래 말 그대로 광고 성과 측정을 위해 만들어졌습니다. 어떤 사용자가 한 앱의 광고를 보고 설치하기 위해 광고에 포함된 링크를 클릭합니다. 이때 사용자가 쓰고 있는 디바이스 ID와 매칭되는 광고 식별자가 발급되고 광고 플랫폼의 광고 네트워크에 이 데이터를 전송합니다. 설치된 앱이 실행될 때 앱에 포함된 SDK가 이 광고 식별자를 확인하면서 이 사용자가 광고를 보고 앱을 설치했다는 사실을 알아냅니다. 사용자가 어떤 광고를 봤는지 알아야 하고, 또 광고의 성과로 보는 행위가 앱 설치나 실행이 아닌 다른 행동일 수도 있기 때문에 광고 식별자는 사용자의 사용 기록을 담기 시작했습니다.

![Structure of Advertising Identifier]({{ '/assets/images/design/privacy-trend/02.jpg' | relative_url }} '광고 식별자의 구조'){: loading='lazy'}
{: .normal-size}

광고 식별자는 일단은 사용자가 수정할 수 있지만 그럴 일은 거의 없는 디바이스 ID를 기준으로 생성되기 때문에 웹브라우저의 쿠키보다 수명이 깁니다. 광고 식별자는 동일한 광고 플랫폼을 사용하는 여러 앱과 웹사이트를 넘나들며 사용 데이터를 수집합니다. 사용자에게 개인 정보를 요청한 적은 없지만, 이렇게 데이터가 모이면 개인을 식별하기에 충분한 고유성을 지닌 프로필을 만들 수 있게 됩니다. 이렇게 만든 프로필은 데이터 브로커에게 판매되거나 맞춤 광고에 사용됩니다.

구체적인 특징을 구분할 수 있는 사용자 프로필 데이터를 가지고 있는 것이 데이터 중심 의사결정에 얼마나 큰 도움을 줄 수 있는지는, 또 얼마나 큰 마케팅 비용을 절감하는 강조할 필요가 없어 보입니다. 꾸준한 업데이트를 제공하는 AppsFlyer의 <a title='AppsFlyer - The impact of iOS 14 & ATT on the mobile app economy' href='https://www.appsflyer.com/ios-14-att-dashboard/' target='_blank' rel='noopener'>iOS 앱 추적 투명성 분석 자료</a>에 따르면, iOS 앱에서 앱 추적을 허용하겠느냐고 묻는 팝업이 노출됐을 때 동의한 경우는 42%입니다. 예상보다는 높다고는 해도 사용자 프로필을 구성하는 데이터가 절반 넘게 빈약해졌다는 사실은 여전합니다.

![Value Beneficiaries: Advertising Platforms vs. App Market Operators]({{ '/assets/images/design/privacy-trend/03.jpg' | relative_url }} '가치 수혜자 : 광고 플랫폼 vs 앱 마켓 운영사'){: loading='lazy'}
{: .normal-size}

페이스북은 이러한 애플의 정책이 고효율 광고 덕분에 저렴한 비용으로 서비스를 제공해왔던 <a title='Dan Levy(Facebook), 2021 - Speaking Up for Small Businesses' href='https://about.fb.com/news/2020/12/speaking-up-for-small-businesses/' target='_blank' rel='noopener'>중소기업에 피해를 줄 것이라는 입장</a>을 밝힌 적 있습니다. 페이스북에 따르면 비개인화된 모바일 앱 설치 광고를 운영했을 때, 개인화된 광고를 운영했을 때보다 <a title='Facebook For Developers, 2020 - The Value of Personalized Ads to a Thriving App Ecosystem' href='https://developers.facebook.com/blog/post/2020/06/18/value-of-personalized-ads-thriving-app-ecosystem/' target='_blank' rel='noopener'>수익이 50% 감소</a>합니다. 이를 중소기업을 위한 페이스북의 정의로운 분투로 보기보다는 앱 생태계의 주도권을 놓고 벌이는 앱 마켓 운영사와 광고 플랫폼의 마찰로 보는 게 자연스러울 듯합니다. 지금까지 사용자는 개인 정보를 지불하고 무료 앱을 사용했습니다. 이 과정에서 앱이 창출한 가치는 광고 플랫폼에 돌아갔습니다. 앱 마켓 운영사는 이 가치를 가져오고자 합니다. 인앱 결제에서 오는 15~30%의 수수료가 그 가치가 움직이는 통로입니다. 길도 뚫렸으니 가져오기만 하면 됩니다. 프라이버시 정책으로 광고 효율은 낮아지고 무료 앱은 유료가 됩니다. 사용자는 개인 정보 대신 현금을 지불합니다. 이 구조에서 광고 플랫폼으로 들어갔던 가치는 앱 마켓 운영사로 들어갑니다.

이 상황을 제품 개발사와는 무관한 큰 회사 간의 분쟁 정도로 생각하고 있으면 안 됩니다. 앱 마켓 운영사가 확실한 주도권을 가질 때까지 제품에 영향을 미치는 프라이버시 정책은 언제든 바뀔 가능성이 있습니다. 앱 생태계에서의 데이터 중심 의사결정에서 얻었던 이점을 유지하고 싶다면 한 발자국 먼저 움직여야 합니다.

## EU 쿠키 법과 투명해지는 웹 사용자

어느 순간부터 쿠키 수집 허용 여부를 묻는 배너가 외국 웹사이트에서 많이 보이기 시작했을 겁니다. 조금만 웹서핑해도 사이트마다 노출되는 배너 때문에 귀찮게 느꼈을지도 모르겠습니다. 사이트 제공자들도 별로 넣고 싶지는 않을 겁니다. 그대로 어쩔 수 없습니다. 법이니까요.

쿠키에 대한 규정 중 가장 유명한 건 아무래도 EU의 ePrivacy Directive, 일명 쿠키 법이 아닐까 싶습니다. EU는 쿠키 법과 GDPR(일반 개인 정보 보호법)로 웹사이트의 쿠키, 로컬 스토리지(Local Storage) 등을 이용한 <a title='Richie Koch(GDPR EU), 2019 - Cookies, the GDPR, and the ePrivacy Directive' href='https://gdpr.eu/cookies/' target='_blank' rel='noopener'>개인 정보 수집 정책을 규제</a>합니다. 제품 사용에 필수적인 쿠키 외 다른 쿠키를 사용할 시 사용자 동의 필요하며, 이에 동의하지 않더라도 제품을 사용할 수 있도록 허용하는 등의 내용을 담고 있습니다. EU 국가는 이 지침에 따라 자국법을 개정해야 합니다. 지침이라고 해서 가벼운 규칙이라고 여기면 안 됩니다. 2014년 쿠키 법을 어겨 <a title="Nuria Pastor(fieldfisher), 2014 - History in the making: the first 'cookie rule' fines in Europe" href='https://www.fieldfisher.com/en/services/privacy-security-and-information/privacy-security-and-information-law-blog/history-in-the-making-the-first-cookie-rule-fines-in-europe' target='_blank' rel='noopener'>벌금형을 선고받은 최초의 기업이 스페인에서 나왔습니다.</a> 2018년 7월부터 2021년 6월까지 집행된 누적 벌금은 공개된 것만  <a title='GDPR Enforcement Tracker - Fines Statistics' href='https://www.enforcementtracker.com/?insights' target='_blank' rel='noopener'>290,430,902유로</a>(한화 약 3천 9백억 원)입니다. 최근에는 아마존(Amazon)이 7억 4,600만 유로(한화 약 1조 202억 원)의 <a title='Stephanie Bodoni(Bloomberg), 2021 - Amazon Gets Record $888 Million EU Fine Over Data Violations' href='https://www.bloomberg.com/news/articles/2021-07-30/amazon-given-record-888-million-eu-fine-for-data-privacy-breach' target='_blank' rel='noopener'>역대 최고액 벌금을 선고</a>받았습니다. EU 7개국에서 200개 이상의 뉴스 웹사이트를 <a title='Timothy Libert, Lucas Graves and Rasmus Kleis Nielsen(Reuters Institute), 2018 - Changes in Third-Party Content on European News Websites after GDPR' href='https://reutersinstitute.politics.ox.ac.uk/our-research/changes-third-party-content-european-news-websites-after-gdpr' target='_blank' rel='noopener'>조사한 결과</a>에 따르면, 2018년 GDPR이 발효된 후 서드파티(Third-Party) 쿠키의 양은 22% 감소했습니다. 대체 무엇 때문에 이런 규제가 생긴 걸까요?

![Structure of Third-party Cookies]({{ '/assets/images/design/privacy-trend/04.jpg' | relative_url }} '서드파티 쿠키의 구조'){: loading='lazy'}
{: .normal-size}

쿠키(Cookie)는 브라우저 등에 웹사이트 사용에 필요한 데이터를 저장하는 기술입니다. 새로 고침을 해도 웹사이트의 로그인 상태가 유지되는 것은 쿠키를 활용한 덕분입니다. 그런데 제품에 포함된 쿠키는 제품을 만들고 제공하는 기업만 설정할 수 있는 것이 아니라 다른 기업이 설정할 수도 있습니다. 이를 서드파티 쿠키라고 합니다. 구글 애널리틱스와 같은 분석 도구, SNS의 공유 버튼, 유튜브에서 동영상을 공유하며 딸려온 비디오 플레이어를 웹사이트에 설치할 때, 설치 코드에 관련 기능이 포함되어 있다면 서드파티 쿠키가 설정됩니다. 서드파티 쿠키는 여러 웹사이트에 걸쳐 작동하면서 웹서핑하는 사용자의 사용 데이터를 추적할 수 있습니다. 이를테면 웹사이트 A, B, C에 모두 페이스북 공유 버튼이 들어가 있다면 페이스북은 사용자의 A, B, C 사용 데이터를 수집할 수 있습니다. 이렇게 수집된 데이터는 데이터 브로커에게 판매되거나 맞춤형 광고에 활용됩니다. 선풍기에 대해 구글링하다가 페이스북에 들어가면 선풍기 광고를 볼 수 있는 이유는 여기에 있습니다. 이런 기술 덕분에 구글과 페이스북 등은 기존 광고 매체보다 월등한 광고 효율을 낼 수 있었습니다. 수많은 디지털 프로덕트는 서드파티 쿠키의 혜택을 받으면서 성장했습니다.

하지만 상황이 바뀌었습니다. 이 마법의 기술을 남용한 탓일까요, 사용자는 서드파티 쿠키를 통한 사용 데이터의 추적에 이점이 아니라 피로와 공포를 느끼기 시작했습니다. 3만 명의 인터넷 사용자를 대상으로 한 <a title='Mozilla, 2017 - Hackers, Trackers and Snoops: Our Privacy Survey Results' href='https://medium.com/mozilla-internet-citizen/hackers-trackers-and-snoops-our-privacy-survey-results-1bfa0a728bd5' target='_blank' rel='noopener'>Mozilla 재단의 설문</a>에 따르면, 응답자 1/3이 온라인에서 자신의 개인 정보를 전혀 통제할 수 없다고 여깁니다. 응답자 **61%는 온라인에서 가장 두려운 경험으로 광고주에 의한 데이터 추적을 꼽았습니다.** 이는 해킹 당하는 경험(80%)에 이어 2번째며, 심지어 온라인상의 괴롭힘(40%)보다 높은 수치입니다. 이제 브라우저는 개인 정보 보호 기능을 제품 홍보의 주안점으로 삼습니다. 웹사이트에 사용 데이터를 추적하지 말아 달라는 의사를 표명하는 기능인 DNT(Do Not Track)는 파이어폭스(Firefox)에서 시작해서 이제 대부분의 주요 브라우저에서 확인할 수 있습니다. 실제 효용성은 둘째치고, 사용자의 인식이 기존의 데이터 수집·활용 환경에 부정적이라는 것을 알 수 있습니다.

웹 생태계에서의 데이터 중심 의사결정 환경은 변하고 있으며, 다시는 예전으로 돌아가지 않을 겁니다.

## 서드파티 쿠키의 죽음과 구글 FLoC

서드파티 쿠키는 죽었습니다. 파이어폭스와 사파리(Safari) 브라우저는 이미 서드파티 쿠키를 지원하지 않습니다. 하지만 웹브라우저 시장의 점유율 과반을 차지하고 있는 크롬(Chrome)은 상황이 약간 다릅니다. 물론 크롬도 서드파티 쿠키를 배제할 것입니다. 2022년으로 예정되어 있던 서드파티 쿠키 제거 계획은 얼마 전 <a title='Google, 2021 -  프라이버시 샌드박스 타임라인 업데이트' href='https://korea.googleblog.com/2021/07/updated-timeline-privacy-sandbox-milestones.html' target='_blank' rel='noopener'>2023년 후반기로 연기</a>되었습니다. 이 일에 대해 이해하려면 먼저 FLoC를 알아야 합니다.

구글은 크롬의 운영사고, 2020년 미국 디지털 광고 시장에서 <a title='eMarketer, 2020 - Google’s US Ad Revenues to Drop for the First Time' href='https://www.emarketer.com/newsroom/index.php/google-ad-revenues-to-drop-for-the-first-time/' target='_blank' rel='noopener'>29.4%의 점유율</a>을 가지고 있는 광고 플랫폼 회사이기도 합니다. 또한 구글은 유튜브 등 많은 사용자를 지닌 유명 제품을 다수 운영하고 있습니다. 구글의 <a title='동아닷컴, 2020 - “역시 유튜브 천하” 구글 트래픽 비중 23.5% 달해…네이버·카카오 1~2%' href='https://www.donga.com/news/It/article/all/20200909/102851001/1' target='_blank' rel='noopener'>국내 일평균 트래픽 비중은 23.5%</a>입니다. 서드파티 쿠키로 가장 많은 데이터를 모을 수 있었던 곳은 구글이고, 가장 효율적인 광고를 운영할 수 있었던 곳도 구글입니다. 서드파티 쿠키의 규제가 제도상으로 확실해지니 전과 같은 광고 효율을 유지하려면 다른 방법이 필요했습니다.

FLoC(Federated Learning of Cohorts)는 서드파티 쿠키 이후의 웹 생태계에서 주도권을 확보하려는 구글의 시도입니다. FLoC는 사실상 개인을 특정할 수 있었던 서드파티 쿠키와는 다르게, 브라우저(크롬)가 주도해서 데이터를 수집하고 유사한 특징을 띄는 사용자끼리 그룹을 지어 광고주에게 제공합니다. 구글의 실험에 따르면 FLoC 방식 광고는 서드파티 쿠키 광고와 비교해 달러당 전환율을 <a title='Chetna Bindra(Google Ads & Commerce), 2021 - Building a privacy-first future for web advertising' href='https://blog.google/products/ads-commerce/2021-01-privacy-sandbox/' target='_blank' rel='noopener'>최소 95%로 지킬 수 있습니다.</a> 고객 획득 전략의 뾰족한 전환점 없이 서드파티 쿠키에 의존하고 있던 기업으로서는 만족할 만한 대체제입니다. 그러나 구글이 서드파티 쿠키 이후의 웹 세계를 지배하도록 놔두지 않는 회사가 있습니다. 아마존(Amazon)은 물론, 자포스(Zappos)를 비롯한 아마존 계열 웹사이트에는 이미 <a title="Kate Kaye(DIGIDAY), 2021 - Amazon is blocking Google's FLoC — and that could seriously weaken the system" href='https://digiday.com/media/amazon-is-blocking-googles-floc-and-that-could-seriously-weaken-the-fledgling-tracking-system/' target='_blank' rel='noopener'>FLoC 차단 코드가 삽입</a>되었습니다. 마이크로소프트(Microsoft)의 Github에서 운영하는 웹 호스트 서비스 Github Pages는 기본 제공 도메인인 github.io를 사용하는 모든 Github Pages 사이트에 <a title='Github, 2021 - GitHub Pages: Permissions-Policy: interest-cohort=() Header added to all pages sites' href='https://github.blog/changelog/2021-04-27-github-pages-permissions-policy-interest-cohort-header-added-to-all-pages-sites/' target='_blank' rel='noopener'>FLoC 차단 코드를 삽입</a>했다고 발표했습니다. 이런 상황에서 크롬의 서드파티 쿠키 제거 계획이 연기된 것입니다.

## 관리해야 할 리스크, 프라이버시

지금까지 오늘날의 프라이버시 트렌드를 알아보았습니다. 사용자는 개인 정보 보호에 더욱 민감해졌고, 빅 테크 기업은 그것을 이용해 시장에서의 영향력을 키우려고 합니다. 데이터에 기반하여 마케팅의 성과를 판단하고 광고 집행 방향성을 결정하는 전략, 데이터 중심 마케팅은 이런 상황에서도 살아남을 것입니다. 빅 테크 기업이 바꿔놓은 규칙에 적응하며 나름의 방법을 찾을 것입니다. 문제는 제품입니다. 이제 제품 개발은 거대 기업이 정해놓은 규칙에 정신없이 끌려다닐 미래밖에 남지 않은 걸까요? 프라이버시 이슈를 관리해야 할 리스크로 보고, 한 수 앞서 움직인다면 그렇지 않아도 됩니다. 구체적인 전략에 대해서는 <a title='매거진 입맛 - 이루다의 논란이 넷플릭스에 없는 이유. 프라이버시 리스크 관리의 3가지 포인트' href='/three-points-of-privacy-risk-management' target='_blank' rel='noopener'>다음 2부</a>에서 알아보겠습니다.

위시켓의 지원과 함께 제작된 콘텐츠입니다.
{: .right-infor}