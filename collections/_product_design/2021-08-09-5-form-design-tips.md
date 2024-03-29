---
title: 통계로 알아보는, 성과 내는 5가지 폼(Form) 설계 팁
layout: post
category: design-teatime
date: 2021-08-08 00:00:00 +0900
excerpt: 디자이너의 오랜 고민거리 폼. 통계 데이터를 바탕으로 폼 전환율을 개선할 수 있는 5가지 팁을 준비했습니다.
thumbnail: /assets/images/design/5-form-design-tips/00.jpg
permalink: /5-form-design-tips
tag: 'UX'
stylecss: /assets/post.css
---

디지털 프로덕트에서 폼(Form)이란 고객이 제품 사용에 필요한 정보를 제공하는 도구입니다. 폼은 그 자체로 온보딩 과정이 되기도 하고, 결제라는 결정적인 순간에 등장하기도 합니다. 폼은 고객의 제품 경험뿐만 아니라 제품의 주요 지표에도 큰 영향력을 미칩니다. 한 명이라도 더 전환시키는 폼 설계가 디자이너 사이에서 오랫동안 논의의 주제가 된 것은 당연한 일입니다. 이번 글에서는 실제적인 데이터, 즉 통계를 가지고 폼 전환율을 개선할 수 있는 5가지 팁을 소개하겠습니다.

## 페이지 나누기

폼에서 요구하는 정보의 개수를 줄이는 것이 전환율에 도움이 된다는 사실은 상식입니다. 하지만 같은 개수의 입력란이 있다면 페이지를 늘리는 것은 오히려 전환율을 높일 것입니다.

![Single Page vs Multi Page]({{ '/assets/images/design/5-form-design-tips/01.jpg' | relative_url }} '단일 페이지 vs 다중 페이지'){: loading='lazy'}
{: .normal-size}

66만 5천 명이 넘는 디지털 프로덕트 사용자에게 모바일 폼 경험을 <a title='formstack, 2015 - The Form Conversion Report' href='https://www.formstack.com/resources/report-form-conversion' target='_blank' rel='noopener'>설문한 조사</a>에 따르면, 단일 페이지로 구성된 폼의 평균 전환율은 4.53%, 다중 페이지는 13.85%로 3배 이상 높았습니다.

폼을 여러 페이지에 나누어 배치하면 개별 입력란이 받는 고객의 집중도가 단일 페이지에 몰아놓았을 때보다 높습니다. 이 특성은 페이지 분리로 입력란의 시인성과 조작성을 개선하고 입력을 유도하는 추가적인 정보를 실을 수 있는 화면이 늘어나면서 강화됩니다.

하지만 다중 페이지로 구성한 폼에도 여전히 주의할 점이 있습니다. 첫번째는 진행 표시줄(Progress Bar)이나 페이지 번호를 표기하여 폼의 전체 분량을 명시해야 한다는 점입니다. 다중 페이지 폼은 단일 페이지 폼보다 폼의 분량을 직관적으로 느끼기 어렵습니다. 하염없이 계속되는 폼은 고객의 의지를 앗아갈 것입니다. 둘째로 페이지 이동 간 이전에 입력했던 정보가 초기화되지 않도록 기술적 조치를 해야 합니다. 다중 페이지 폼에서 일어나는 입력란 사이의 이동과 수정은 페이지 이동이라는 추가적인 행동을 요구합니다. 거기에 이미 한 번 이상 입력했던 정보가 사라져 다시 입력해야 하는 상황이 닥친다면? 말할 것도 없습니다.

잘 설계된 폼은 고객의 행동에 부담과 장애가 생기지 않도록 최대한 배려합니다.

## 적은 입력란

입력란의 개수가 적을 수록 해결하기도 쉽고 따라서 전환율도 나을 것이다. 직관적으로 떠올릴 수 있는 생각입니다. 이는 데이터도 증명하는 사실입니다.

![Imaginary Landscape AB Test]({{ '/assets/images/design/5-form-design-tips/02.jpg' | relative_url }} 'Imaginary Landscape AB 테스트'){: loading='lazy'}
{: .full-size}

이 분야의 가장 고전적인 통계는 웹 에이전시 <a title='Brian Moloney(Imaginary Landscape), 2008 - Fewer fields in a contact form sharply increases conversions' href='https://www.imagescape.com/media/filer_public/06/94/0694c7f4-8914-4598-8871-b857fbc12737/form_case_study.pdf' target='_blank' rel='noopener'>Imaginary Landscape의 AB 테스트</a>에서 확인할 수 있습니다. 이 테스트에서 주소, Fax, 유입 채널을 묻는 설문 등 11개짜리 입력란으로 구성된 문의하기 폼은 이름, 전화번호, 이메일 주소, 코멘트의 4가지 항목으로 개편되었습니다. 그 결과 전환율은 5.4%에서 11.9%로 2배 이상 증가했습니다.

![Form Conversion Rate by Number of Fields]({{ '/assets/images/design/5-form-design-tips/03.jpg' | relative_url }} '입력란 개수별 폼 전환율'){: loading='lazy'}
{: .full-size}

B2B 마케팅 자동화 솔루션 기업 <a title='Egan Cheung(Eloqua), 2011 - How Many Fields Belong On Your Landing Pages? [Chart]' href='https://blogs.oracle.com/marketingcloud/post/how-many-fields-belong-on-your-landing-pages-chart' target='_blank' rel='noopener'>Oracle Eloqua의 조사</a>도 적은 입력란의 효과를 증명합니다. 1,500여개의 폼을 검토한 이 조사는 입력란의 수가 늘어날 수록 전환율이 떨어지는 추세를 보여주고 있습니다. 이전에 소개한 <a title='매거진 입맛 - 당장 활용하는 12가지 AB 테스트 사례' href='/12-ab-test-cases' target='_blank' rel='noopener'>Netflix 랜딩 페이지의 비밀번호 입력란 추가 AB 테스트</a>가 실패한 이유도 여기 있습니다.

폼을 구성하는 입력란의 개수를 줄이는 일은 전환율을 개선하는 확실한 방법 중 하나입니다. 그러나 분별없이 개수만 줄이는 행동은 제품에 도움이 되지 않습니다. 제품의 특성과 특정 폼의 제출로 실행할 수 있는 기능에 따라 필요한 입력란은 다를 수 있습니다. 앞서 언급한 Eloqua의 조사도 이런 점을 설명하고 있습니다. 조사에 따르면 무료 체험판을 받는 과정에서 폼을 입력하는 경우에는 입력란이 8개에 이르러도 전환율이 크게 감소하지 않습니다. 어떤 리소스를 다운로드 받는 경우에는 11개까지도 가능합니다. 하지만 웨비나(Webinar) 이벤트에 등록하는 폼이라면 5개만 넘어도 전환율이 쭉 떨어지기 시작합니다. 제품의 특성과 상황을 고려해서 필수적인 입력란으로만 폼을 구성해야 합니다. 이를 위해서는 폼을 구성하는 각 입력란을 중요도에 따라 줄세울 수 있어야 합니다.

## 전환율을 떨어뜨리는 텍스트 박스, 드롭다운 피하기

한 줄짜리 텍스트 입력란, 여러 줄을 쓸 수 있는 텍스트 박스, 체크 박스, 라디오 버튼, 드롭다운, 날짜 선택기…. 입력란에는 여러 종류가 있습니다. 그리고 특정 종류의 입력란은 전환율을 떨어뜨릴 수 있습니다.

![Form Conversion Rate by Field Types]({{ '/assets/images/design/5-form-design-tips/04.jpg' | relative_url }} '입력란 종류별 폼 전환율'){: loading='lazy'}
{: .full-size}

CRM 솔루션 기업 HubSpot은 4만 개가 넘는 <a title='Dan Zarrella(HubSpot), 2021 - Which Types of Form Fields Lower Landing Page Conversions?' href='https://blog.hubspot.com/blog/tabid/6307/bid/6746/Which-Types-of-Form-Fields-Lower-Landing-Page-Conversions.aspx' target='_blank' rel='noopener'>랜딩 페이지를 분석</a>하여 전환율에 악영향을 주는 형태의 입력란을 찾아냈습니다. 주로 이름, 이메일 주소 등을 받는 데 사용되는 한 줄짜리 텍스트 입력란보다 여러 줄을 입력받는 텍스트 박스 형태 입력란은 개수가 늘어남에 따라 전환율이 감소하는 정도가 큽니다. 드롭다운이 포함된 폼은 기본적으로 전환율이 낮습니다.

여러 줄을 쓸 수 있는 텍스트 박스는 입력받을 텍스트가 많은 경우에 사용하는 UI로 한 줄짜리 텍스트 입력란보다 크게 구성하는 것이 일반적입니다. 텍스트 박스는 한 줄짜리 텍스트 입력란보다 요구하는 수고가 큽니다. 그 자체로 2~3개의 한 줄짜리 텍스트 입력란의 부담감을 줍니다.

드롭다운은 제시된 목록 중에 하나를 선택할 수 있는 UI입니다. 라디오 버튼과 같은 방식이지만, 제시된 항목이 많아 제한된 화면에 라디오 버튼처럼 펼쳐놓을 수 없는 경우에 사용합니다. 드롭다운의 태생에서 알 수 있듯 드롭다운은 초기 상태에서 정보를 숨기는 특성이 있습니다. 이런 비직관성에, 제시된 목록 중 선택하는 기능을 수행하기 위해 정보의 숨김-노출 상태를 조작해야 하는 수고까지 요구합니다. 드롭다운이 포함된 폼의 전환율이 낮은 것은 당연해 보입니다.

이처럼 전환율을 떨어뜨리는 입력란의 형태는 존재합니다. 이와 같은 형태의 입력란을 사용할 때에는 대체할 방법이 있지는 않은지, 꼭 필요한지 검토하는 과정이 필요합니다.

## 소셜 프루프로 불안감 없애기

![Reasons for Giving Up Filling Out the Form]({{ '/assets/images/design/5-form-design-tips/05.jpg' | relative_url }} '폼 입력 포기 사유'){: loading='lazy'}
{: .full-size}

<a title='Michelle Delgado(THE MANIFEST), 2018 - 6 Steps for Avoiding Online Form Abandonment' href='https://themanifest.com/web-design/6-steps-avoiding-online-form-abandonment' target='_blank' rel='noopener'>한 조사</a>에 따르면 폼 입력을 포기하는 이유는 보안에 대한 불안(29%), 너무 긴 폼의 길이(27%), 광고에 활용될 것 같은 예상(11%), 정보 수집 이유가 불분명한 항목(10%) 때문입니다.

보안에 대한 불안이 폼 입력 포기 사유 1순위라는 것은 놀라운 사실이 아닙니다. 디지털 프로덕트의 고객은 오랫동안 버벅대는 온라인 환경을 경험했습니다. 보안 문제는 폼뿐만 아니라 디지털 프로덕트의 어떤 분야에도 빠지지 않고 등장하는 이슈입니다.

소셜 프루프(Social Proof)는 한 개인이 어떤 것을 결정할 때 사회적인 정보에 의존하는 경향과, 이를 활용하여 고객의 결정에 영향력을 미치는 방법입니다. 대표적인 소셜 프루프로는 상품 후기를 꼽을 수 있습니다. 고객은 다른 고객의 후기를 참고하여 구매를 결정합니다. 이와 관련해서는 <a title='매거진 입맛 - 전환율 높이는 상세 페이지 디자인. 바로 써보는 3가지 방법' href='/product-page-tips' target='_blank' rel='noopener'>상세 페이지 개선법을 다룬 이전 글</a>에서 자세히 설명한 적이 있습니다. 이미 몇 명이 폼을 입력했다든지 다른 고객이 문제없이 폼을 처리했다는 정보를 보여주는 것은 고객의 불안감을 씻어주는 솔직한 소셜 프루프 해결책 중 하나입니다. 혹은 폼 입력 자체를 한정된 기회로 만들어 고객의 FOMO(Fear Of Missing Out)를 자극하는 것도 방법이 될 수 있습니다.

## 리타게팅 광고 활용하기

![Actions after Giving Up Filling Out the Form]({{ '/assets/images/design/5-form-design-tips/06.jpg' | relative_url }} '폼 입력 포기 후 행동'){: loading='lazy'}
{: .full-size}

바로 위의 조사 자료에서 이어지는 내용입니다. 폼 입력을 포기한 고객 중 67%는 떠나서는 다시 돌아오지 않습니다. 이는 돌아와 폼 입력을 마치거나(13%), 다른 유사 제품을 찾아가거나(10%), 고객 지원 센터에 연락하는 경우(7%)보다 압도적으로 큰 비중을 차지합니다. 이 통계는 폼 입력 도중 문제가 생긴 고객이 문제를 해결하는데 얼마나 수동적인지 보여주는 사례입니다. 하지만 조금만 더 깊게 들어가 보면 새로운 기회가 보일 겁니다. 폼 입력 포기 고객의 사후 관리, 리타겟팅 광고가 바로 그것입니다.

리타겟팅(Retargeting) 광고는 제품에서 이탈한 고객을 대상으로 하는 마케팅 전략입니다. 고객은 다양한 이유로 제품에서 이탈합니다. 원하는 선택지를 받지 못했을 수도 있고, 더 나은 제품을 찾아 떠나거나 단지 무관심해졌을 수도 있습니다. 중요한 건 그렇게 떠난 고객이 생각보다 쉽게 돌아온다는 점입니다. 방문 고객 4명 중 3명은 리타겟팅 광고를 인지하며, 26%는 리타겟팅 광고로 인해 제품으로 돌아옵니다. 리타겟팅 광고로 돌아온 고객은 그렇지 않은 고객보다 전환율이 상대적으로 70% 더 높습니다. 폼 입력 포기 고객을 대상으로 하는 리타겟팅 광고는 전환율을 늘리는 가장 효과적인 방법이 될 수 있습니다.

## 정리

지금까지 데이터가 증명하는 폼 설계 개선안 5가지를 알아보았습니다.

1. 폼을 다중 페이지로 구성
2. 폼을 구성하는 입력란 줄이기
3. 여러 줄을 쓸 수 있는 텍스트 박스, 드롭다운 피하기
4. 소셜 프루프 요소로 불안감 해소하기
5. 폼 입력 포기 고객 대상으로 리타겟팅 광고 집행하기

위 팁을 바탕으로 자신의 제품에 맞는 테스트를 진행한다면 또 다른 인사이트를 얻을 수 있을 것입니다.

위시켓의 지원과 함께 제작된 콘텐츠입니다.
{: .right-infor}