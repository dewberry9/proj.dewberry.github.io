---
title: 당장 활용하는 12가지 AB 테스트 사례
layout: post
category: design-teatime
date: 2021-08-01 00:00:00 +0900
excerpt: Booking.com, 넷플릭스, Etsy 등, 직관적이고 어렵지 않은 난이도의 AB 테스트 사례 12가지를 보고 인사이트를 가져가세요.
thumbnail: /assets/images/design/12-ab-test-cases/00.jpg
permalink: /12-ab-test-cases
topic: AB Test
stylecss: /assets/post.css
---

AB 테스트는 <a title='매거진 입맛 - 매출 만드는 AB 테스트, 시작이 막막한가요? 3단계 가이드' href='/3step-ab-test' target='_blank' rel='noopener'>가설 수립, 실험 진행, 결과 분석의 3단계로 진행되는 그로쓰 해킹 방법론</a>입니다. AB 테스트는 제품과 조직의 확실한 성장 엔진으로, 그랩(Grab), 넷플릭스(Netflix), 에어비앤비(Airbnb) 등 데이터 좀 다룬다 싶은 기업은 모두 AB 테스트 성공담 하나는 가지고 있습니다. <a title='매거진 입맛 - 매출 만드는 AB 테스트, 시작이 막막한가요? 3단계 가이드' href='/3step-ab-test' target='_blank' rel='noopener'>이전 글</a>에서 말씀드렸다시피 큰 그로쓰 해킹 팀이나 테스트 문화, 맞춤 툴이 전혀 없는 상황이라도 AB 테스트를 시작하는 데는 아무런 문제가 없습니다. 나름의 가설을 세우고, 동료와 함께 구성하고, 지표를 추적하고, 시행착오를 겪다 보면 어느 정도 요령이 생깁니다.

하지만 AB 테스트 문화를 조직 전반에 퍼뜨리는 것은 또 다른 일입니다. 1명이 제시할 수 있는 아이디어에는 한계가 명확합니다. 더 많은 조직 구성원이 AB 테스트에 참여할수록 만들 수 있는 가설이 늘어납니다. 이는 더 많은 실험, 인사이트, 성장으로 직결됩니다.

이번 글에서는 다양한 AB 테스트 사례를 소개합니다. 동료가 AB 테스트에 익숙해질 수 있도록 직관적이고, 바로 테스트에 적용할 수 있을 만큼 어렵지 않은 난이도의 사례로 모아봤습니다.

## 기능보다 가치 - Booking.com 온보딩 팝업 카피
{: #bookingcom}

세계 최대의 온라인 숙박 플랫폼 중 하나인 Booking.com은 <a title='Stefan Thomke, 2020 - Building a Culture of Experimentation' href='https://hbr.org/2020/03/building-a-culture-of-experimentation' target='_blank' rel='noopener'>연간 2만 5천 개가 넘는 AB 테스트를 실행</a>하는 데이터 기업이기도 합니다. 숙소를 등록하려고 가입한 숙박업소주가 첫 3개월 동안 크게 이탈하는 데이터를 확인한 Booking.com은 숙박업소주를 대상으로 한 온보딩 과정에서 제품을 설명하는 둘러보기 단계에서 대부분이 건너뛰는 선택지를 고른다는 것을 알아냅니다. 둘러보기 단계를 시작하는 팝업은 둘러보기 계속, 건너뛰기, 닫기의 3가지 기능으로 구성되어 있었습니다.

![Booking.com Onboarding Popup Test]({{ '/assets/images/design/12-ab-test-cases/01.jpg' | relative_url }} 'Booking.com 온보딩 팝업 테스트'){: loading='lazy'}
{: .full-size}

Booking.com은 처음에 건너뛰기 기능을 없애고 계속하기와 닫기 기능만 남겨 실험을 진행했습니다. 이는 둘러보기를 진행하는 고객을 13% 늘렸습니다.
두 번째 실험에서는 기능 변경 없이 팝업의 문구를 수정했습니다. 이 대안에서 고객은 제품이 어떤 일을 할 수 있는지가 아니라, 나에게 어떤 도움이 되는지를 설명 받습니다. 이는 둘러보기를 진행하는 고객을 50% 늘렸습니다.

<a title='Alex Muñoz, 2019 - What we learned onboarding 2 million home and apartment owners on Booking.com' href='https://booking.design/what-we-learned-onboarding-2-million-hosts-on-booking-com-99412c03fa3a' target='_blank' rel='noopener'>Booking.com의 AB 테스트</a>가 말하는 바는 <a title='매거진 입맛 - 고객 10명 중 6명은 한번 쓰고 버린다. 줄줄 새는 제품 온보딩 고치기' href='/product-led-growth-onboarding' target='_blank' rel='noopener'>제품 주도 성장 온보딩 전략</a>을 다룬 글에서 이야기한 것과 같습니다. 제품을 설명하는 것도 중요하지만 제품이 고객에게 어떤 가치를 제공할지 설명하는 게 더 중요합니다.

## 입구는 단순하게 - 넷플릭스 랜딩 페이지

넷플릭스는 제품 개선의 방향 자체를 AB 테스트에 의존하고 있는 기업입니다. 재생, 대기열 추가 버튼과 같은 UI는 물론, 시청 데이터를 이용한 개인화 기능, 페이지 로드 시간, 인코딩 품질 등 제품의 <a title='Quora - What types of things does Netflix A/B test, aside from member sign-up?' href='https://www.quora.com/What-types-of-things-does-Netflix-A-B-test-aside-from-member-sign-up' target='_blank' rel='noopener'>거의 모든 부분을 AB 테스트</a>하고 있습니다.

넷플릭스 경험의 시작, 랜딩 페이지 역시 AB 테스트 중심적 제품 개선 정책에서 벗어나지 않습니다.

![Netflix Landing Page Main Copy Test]({{ '/assets/images/design/12-ab-test-cases/02.jpg' | relative_url }} '넷플릭스 랜딩 페이지 메인 카피 테스트'){: loading='lazy'}
{: .full-size}

CTA(Click to Action) 버튼 카피 수정 테스트는 간단하게 생각할 수 있는 테스트이지만 상황에 따라서는 큰 영향력을 끼치기도 합니다. 넷플릭스는 랜딩 페이지 상단 중앙에 가입 단계로 이어지는 CTA 버튼 하나를 놓고 여러 카피를 실험했습니다. ‘JOIN NETFLIX’, ‘JOIN NOW’, ‘GET NETFLIX’, ‘TRY IT NOW’의 <a title='GoodUI, 2019 - Netflix A/B Tested These 4 Button Labels With “Try It Now” Possibly Leading' href='https://goodui.org/leaks/netflix-a-b-tested-these-4-button-labels-with-join-now-possibly-leading/' target='_blank' rel='noopener'>MVT(다변수 실험)</a>와 30일, 14일, 7일로 설정된 <a title='Good UI, 2019 - Netflix A/B Tests And Rejects Free Trials' href='https://goodui.org/leaks/netflix-a-b-tests-and-rejects-free-trials/' target='_blank' rel='noopener'>무료체험 기간을 명시한 MVT</a>가 대표적입니다.

접두사 ‘TRY’는 ‘JOIN’, ‘GET’에 비해 시험 삼아 가볍게 눌러 볼만한 카피로 후자와 비교해 성과가 좋았을 것으로 추정됩니다.(한국어 사이트에서는 ‘시작하기’를 사용) 같은 이유로 무료체험 기간을 알려주는 카피는 기간에 상관없이 성과가 낮을 겁니다. ‘TRY IT NOW’는 버튼을 누르는 고객의 **심리적 허들을 최소화하는 가장 단순한 카피**입니다.

![Netflix Landing Page Two Buttons Test]({{ '/assets/images/design/12-ab-test-cases/03.jpg' | relative_url }} '넷플릭스 랜딩 페이지 투 버튼 테스트'){: loading='lazy'}
{: .full-size}

**CTA 버튼은 1개일 때 가장 큰 영향력을 발휘**합니다. 고객을 제품 사용으로 인도해야 하는 랜딩 페이지에서는 특히 더 그렇습니다. 넷플릭스 랜딩 페이지에서 <a title='GoodUI, 2019 - Netflix A/B Tests And Rejects Secondary Sign-in And Sign-up Calls To Action' href='https://goodui.org/leaks/netflix-a-b-tests-and-rejects-secondary-sign-in-and-sign-up-calls-to-action/' target='_blank' rel='noopener'>가입 버튼 아래 로그인 옵션</a>이나 <a title='GoodUI, 2020 - Netflix A/B Tests 4 Secondary Choices - All of Which Get Rejected' href='https://goodui.org/leaks/netflix-a-b-tests-4-secondary-choices-all-of-which-get-rejected/' target='_blank' rel='noopener'>‘더 알아보기’에 해당하는 다른 버튼을 추가하는 대안</a>은 모두 취소되었습니다. 로그인 기능이나 넷플릭스에 대한 정보 제공이 고객 편의나 전환에 도움이 될 수는 있지만, 가입률이라는 1순위 지표를 해칠 만큼 중요한 것은 아니기 때문입니다.

![Netflix Landing Page Email Field Test]({{ '/assets/images/design/12-ab-test-cases/04.jpg' | relative_url }} '넷플릭스 랜딩 페이지 이메일 주소 입력란 테스트'){: loading='lazy'}
{: .full-size}

그런 의미에서 가입 버튼 옆에 <a title='GoodUI, 2020 - Netflix A/B Tests Upfront Email Capture At The Start Of Their Signup Flow And It Succeeds' href='https://goodui.org/leaks/netflix-a-b-tests-early-email-capture-at-the-start-of-their-signup-flow-and-it-succeeds/' target='_blank' rel='noopener'>이메일 주소 입력란을 붙인 테스트</a>는 조금 이상하게 보일 수 있습니다. 그러나 이메일 주소 입력란은 새로 추가된 요소가 아닙니다. 기존 회원가입 과정에서도 이메일 주소를 받는 단계는 존재했습니다. 이 단계를 가입 퍼널 맨 앞으로 가져옴으로써 전체적인 퍼널의 단계 수를 줄이고, 아무런 사전 정보 없이 이메일 주소 입력란을 마주치게 했던 당혹스러운 경험을 입력란을 처음부터 제시하는 방식으로  해소했습니다.

하지만 전체적인 퍼널의 단계 수를 줄인다고 한 화면에 많은 입력란을 두는 건 좋은 선택이 아닙니다. 고객은 처리해야 할 일이 너무 많다고 느낄 수 있습니다. 따라서 이메일 주소에 비밀번호까지 처음부터 입력받으려고 했던 <a title='GoodUI, 2020 - Netflix A/B Tests Displaying A Password Field Which Fails And Gets Rejected' href='https://goodui.org/leaks/netflix-a-b-tests-displaying-a-password-field-which-fails-and-gets-rejected/' target='_blank' rel='noopener'>넷플릭스의 대안</a>이 실패한 이유는 어렵지 않게 어림짐작할 수 있습니다.

## 100의 법칙 - 코드카데미(Codecademy) 플랜 가격 할인율

100의 법칙(Rule of 100)은 고객의 처지에서 어떤 상품의 가격이 100달러 미만이라면 할인가가 얼마인지 표시하는 것보다 할인율이 몇 퍼센트인지 보여주는 게 할인 폭을 더 크게 실감한다는 이론입니다.

![Codecademy Plan Page Test]({{ '/assets/images/design/12-ab-test-cases/05.jpg' | relative_url }} '코드카데미 플랜 가격 할인율 테스트'){: loading='lazy'}
{: .full-size}

프로그래밍 학습 플랫폼 코드카데미는 <a title='Daniel Layfield, 2020 - How Codecademy Saw 5X Growth with Strategic Testing' href='https://cxl.com/blog/codecademy-strategic-testing/' target='_blank' rel='noopener'>이 이론을 플랜 선택 페이지에 적용</a>했습니다. 연간 결제 플랜으로 전환하는 비율이 28% 늘었고 전체적인 페이지 전환율도 개선되었습니다.

## CTA 버튼 추가 - OFLARA

UX 리서치를 하다 보면 도무지 상상할 수 없었던 방법으로 제품을 사용하는 고객이 있는 반면, 대체 왜 이 사용법을 모르는지 알 수 없는 고객이 보이기도 합니다. 리스트·그리드 UI의 각 항목에 붙인 CTA 버튼은 후자를 위한 UI입니다. 리스트·그리드 UI는 거의 모든 디지털 프로덕트에서 활용되고 있습니다. 이 관습성 때문에 디자이너는 별도의 CTA 버튼이 없어도 고객이 사용하는데 무리가 없을 것으로 생각하는 경우가 많습니다. 이런 생략이 고객의 제품 사용을 불안하게 만든다는 점을 간과해서는 안 됩니다.

![OFLARA CTA Button Test]({{ '/assets/images/design/12-ab-test-cases/06.jpg' | relative_url }} 'OFLARA CTA 버튼 테스트'){: loading='lazy'}
{: .full-size}

온라인 주얼리 커머스 OFLARA에서는 상품을 보여주는 그리드 UI에 <a title='BrillMark - Case Study: How an A/B Test Improved Oflara’s Conversion Rate by 60%' href='https://www.brillmark.com/how-an-a-b-test-improved-the-conversion-rate-by-60/' target='_blank' rel='noopener'>장바구니 추가 버튼을 추가</a>했습니다. 이 실험으로 매출이 60% 증가했습니다.

## 인기 항목을 빠르게 필터링 - TELE2

필터는 고객이 원하는 조건에 맞는 항목만을 드러내 탐색에 드는 비용을 줄여주는 UI입니다. 필터에는 취급하는 항목이 가지고 있는 속성에 따라 적게는 두세 개에서 많게는 수백 가지까지 구성할 수 있습니다. 그러나 이런 세부성이 탐색 비용을 줄인다는 필터 UI의 본래 목적을 해칠 수 있습니다. 이를테면 브랜드 필터링 옵션이 있는데 고를 수 있는 브랜드가 수십 가지라면 고객은 필터 목록에서 브랜드를 찾기보다는 차라리 검색 기능을 사용할 겁니다.

![TELE2 Quick Fillter Test]({{ '/assets/images/design/12-ab-test-cases/07.jpg' | relative_url }} 'TELE2 빠른 필터링 테스트'){: loading='lazy'}
{: .full-size}

유럽 통신사 TELE2는 휴대전화 목록에서 인기 있는 브랜드를 바로 선택할 수 있는 <a title='ISM eCompany, 2020 - Conversie verhogen zonder A/B-testen? De top 5 beste methoden!' href='https://www.slideshare.net/ISMeCompany/conversie-verhogen-zonder-abtesten-de-top-5-beste-methoden#12' target='_blank' rel='noopener'>빠른 필터 UI를 추가</a>했습니다. 이는 필터 클릭률을 19% 개선했습니다.

## 양날의 검, 무한 스크롤 - Etsy

내용물이 많아 한 화면을 넘어가게 되는 리스트·그리드 UI를 처리하는 방법은 크게 2가지입니다.

1. 페이지네이션(Pagination) : 페이지와 함께 내용물을 나누어 표시합니다.
2. 무한 스크롤 : 내용물이 스크롤하는 만큼 제한 없이 표시됩니다.

무한 스크롤 방식은 작은 노력으로 많은 항목을 탐색할 수 있다는 장점이 있습니다. 구글 이미지 검색과 핀터레스트는 무한 스크롤을 잘 활용한 제품으로 유명합니다. 그러나 꼭 많은 탐색이 많은 전환으로 이어지는 것은 아닙니다. 제품에 따라 다를 수 있습니다.

![Etsy Infinity Scroll Test]({{ '/assets/images/design/12-ab-test-cases/08.jpg' | relative_url }} 'Etsy 무한 스크롤 테스트'){: loading='lazy'}
{: .full-size}

수공예 마켓플레이스 <a title='AB Test Cases, 2020 - Changing pagination to infinite scrolling on the listing page' href='https://www.abtestcases.com/testcases/changing-pagination-to-infinite-scrolling-on-the-listing-page/' target='_blank' rel='noopener'>Etsy의 실험</a>은 무한 스크롤 방식이 양날의 검이라는 것을 알려주는 대표적인 사례입니다. Etsy는 검색 결과 페이지의 그리드 UI를 무한 스크롤 방식으로 바꿨지만 조회율, 클릭률, 장바구니에 담는 비율, 구매율까지 모두 낮아졌습니다. 특히 구매율은 22.6%, 조회율은 50%나 감소했습니다.

## 콘텐츠 발행일 숨기기

같은 주제라고 해도 10년 전에 만들어진 콘텐츠보다 한 달 전에 만들어진 것이 더 정확하고, 오늘날에 알맞다고 여기는 심리는 자연스러운 것입니다. 전자를 구식으로 여기고 꺼리는 것 역시 자연스럽습니다.

벨기에의 UX 디자이너 Paul Olyslager는 자신의 블로그에서 <a title='Paul Olyslager, 2017 - How to Improve the Bounce Rate with a Simple A/B Test' href='https://www.paulolyslager.com/how-to-improve-bounce-rate-simple-ab-test/' target='_blank' rel='noopener'>위의 사실을 실험</a>했습니다. 그 결과 콘텐츠의 이탈률은 84%에서 72%로 감소했습니다.

## 정리

이번 글에서 소개한 AB 테스트 사례로 얻을 수 있는 인사이트를 정리하면 다음과 같습니다.

1. 기능보다 가치 전달에 초점을 맞춘 카피
2. 랜딩 페이지에 심리적 허들을 낮추는 가벼운 카피 사용
3. 랜딩 페이지에 제품 사용을 복잡하게 느껴지는 카피 회피
4. 랜딩 페이지를 비가입 고객 친화적으로 구성
5. CTA 버튼의 수 최소화하여 우선순위 높은 기능에 집중
6. 전체 퍼널의 단계 수를 고려한 디자인
7. 한 화면에 많지 않은 입력란
8. 100의 법칙 - 액수가 낮다면 할인가 말고 할인율 노출
9. 리스트·그리드 UI에 CTA 버튼 추가
10. 인기 항목은 빠르게 필터링할 수 있도록 디자인
11. 무한 스크롤은 양날의 검 - 많은 항목을 쉽게 탐색하는 것이 꼭 전환으로 이어지지 않음
12. 이탈률 감소를 위한 콘텐츠 발행일 숨김

AB 테스트 사례를 통해서 실험이 어떤 방식으로 인사이트를 도출하는지 알 수 있고, 이는 조직 내의 AB 테스트 문화 확산에 도움이 될 것입니다.

위시켓의 지원과 함께 제작된 콘텐츠입니다.
{: .right-infor}