---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "문과생의 좌충우돌 데이터 사이언스 도전기 (+커리큘럼)"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2019-12-08T02:07:41+09:00
lastmod: 2019-12-08T02:07:41+09:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
(지난 글 : 코딩 입문 쉽게 하기 / 머신러닝 입문 쉽게 하기)



안녕하세요, 오래간만에 데이터 사이언스를 주제로 글 씁니다.



정부나 기업 현직자가 현업에 결합하는 식이 아닌, 전업 데이터 애널리스트 혹은 사이언티스트를 목표로 공부한 과정 및 커리큘럼입니다. 모든 도전기/수기가 그렇듯 제가 겪은 시행착오를 위주로 작성했으며 사람마다 맞는 스타일, 교재 등등이 다르니 참고 정도만 하시면 좋겠습니다.



커리큘럼만 보실 분은 글 후반부로 바로 넘어가시길 추천합니다.







**I. 백그라운드**



1. 진로 탐색과 코딩 도전

이전 글 : 코딩 입문 쉽게 하기



상경계 학부생으로서 행시, 언론사에 발 담갔다가 적성에 안 맞음을 깨달았습니다. 방황하던 와중 좋은 팀원들을 만나 2017년 말부터 2018년 6월까지 안드로이드 앱 서버 개발을 전담했습니다.

직후 블록체인 업계에 한 번 덤볐다가 발을 빼고, 데이터 사이언스에 도전하기로 합니다. 코딩과 영어, 수학에는 거부감이 없었기 때문이지요.





2. 데이터 사이언스란?

이전 글 : 머신러닝 입문 쉽게 하기

추천 영상 : 머신러닝, 딥러닝, 빅데이터가 도대체 뭐야? ft. 스탠포드 박사



데이터 사이언스가 사용하는 방법론은 Computational statistics(계산 통계학)입니다. 인공지능 · 데이터 사이언스 · 빅데이터라는 용어는 구직자가 취업시장에서, 기업이 상품시장에서 사용하는 마케팅 용어로 보시는 게 맞을 듯 합니다.



결국 연구자들이 쌓아올린 성과물이며, 이러한 분과 학문을 어떻게 접근하고 또 공부해야 할까요? 한글 블로그나 국내 온오프라인 학원 강의에서 좋은 지식을 얻을 수 있을까요? 





3. 어디서 공부할까?

빅데이터가 핫해지면서 이를 내세운(마케팅) 저급 상품들이 시장에 넘쳐납니다. 올바른 자료와 강의를 만나기 어렵습니다. 한글 블로그나 국내 학원 강의는 보통 거르시는 게 맞고, 

영어 블로그 또한 구직자가 포트폴리오로 활용하기 위해 사용하는 경우가 많다보니 잘 취사선택해야 합니다.



한글 서적은 괜찮은 서적이 가끔 나오는 듯한데, 전공 수준의 통계 지식이 없는 사람이 쓴 책은 단순 지식 나열에 그칠 뿐입니다. 학문에 대한 이해가 있어야 지식의 나열이 아닌, 핵심 아이디어를 전달할 수 있고 이는 학습자 입장에서 암기가 아닌 이해를 하며 내공을 쌓을 수 있습니다.



더군다나 통계라는 학문은 수학처럼 누적되는 성질입니다. 사칙연산을 못하는데 미분을 배울 순 없지요. 따라서 여러 사람이 쓴 파편화된 정보를 블로그 등에서 그 때 그 때 찾기보다, 저자가 처음부터 끝까지 작성한 책을 공부하는 게 월등히 좋습니다. 단적인 예로 영문 위키피디아로 수학이나 통계를 공부하려면, 수많은 사람들이 각자 논리와 흐름으로 작성한 문서이기에 그 난이도는 헬입니다. 전공서로 배우고, 참조할 때나 써야할 녀석이지요.



결국 전문가가 쓴 영어 책이나, 전공 원서와 강의가 대부분 아주 좋은 자료입니다. 하지만 이렇게 공부하는 건 당연히 노력이 배로 들어갑니다. 예컨대 Asymptotic line, convergence 이런용어를 처음 접하면 '뭐지?' 싶습니다. 한글로는 점근선, 수렴이라는 간단한 개념이지만요.



전생의 기억을 되살리는 듯한 인고의 시간이지만, 학문의 언어 체계에 흠뻑 빠져들어야 학문을 잘할 수 있습니다. 데이터 사이언스니까요.







**II. 추천 커리큘럼**

(참고 : 서울대학교 통계학과 이수 표준형태 - 필수과목 위주로 보세요)



1. 입문 (Lv. 0)



**Brilliant.org**

웹사이트, 모바일 앱 모두 됩니다. 자연과학 전공자들이 모여 만든 교육 앱인데요, 필요한 수학을 짬짬이 공부하기 좋습니다.



추천 코스 : Linear Algebra, Multivariable Calculus





**3Blue1Brown**

(전설의 레전드)

애니메이션을 동원해 수학 개념들을 설명합니다. 기하적인 접근이므로 수학 개념에 대한 직관을 얻기 아주 좋습니다.



추천 코스 : Linear Algebra, Essence of calculus, Multivariable Calculus





**Statistics with R**

통계 원론격입니다. 통계학 교수님들이 강의하시고, 강의력 좋으십니다. (베이지안 통계 제외)







2. 초급 (Lv. 1)



**ISLR**

(교재를 pdf로 무료로 공개하신 멋진 분들)
머신러닝을 이 분들은 Statistical learning으로 부르십니다. 여하튼 머신러닝에서 사용하는 기법들을 익힐 수 있는 아주 좋은 교재입니다. 초급으로 분류해두었지만, 입문 단계에서 수학 공부하시면서 함께 보실만 할 겁니다.


**Hands on ML**

전직 구글러가 쓴 책입니다. 직접 코드를 사용하며 머신러닝 개념을 익히기 좋습니다.




**Linear Algebra (선형대수)**

대학 교과목인 만큼 양질의 전공서와 수업들이 있습니다. ISLR이나 Hands on ML 공부 중에 선형대수 개념 보충이 필요하다고 느끼시면, 읽으시길 추천합니다.



추천 교재 : Linear Algebra: Step by Step





**Mathematical statistics (수리통계)**

통계학을 수리적 엄밀함을 통해 접근합니다. 중급 레벨로 넘어가기 위해서는 필수적입니다.

추천 교재 : 아마존에서 'Mathematical statistics'로 검색하시고, 이 책 저 책 시도해보세요!



3. 중급 (Lv. 2)

*제가 목표로 하는 포지션은 데이터 사이언티스트 중에서도 통계 모델링을 위주로 하는 자리라 이 단계부터는 커리큘럼이 그 쪽으로 편중되어 있습니다*

**Brilliant.org**

(다시 돌아온 똑똑한 녀석)

이후 코스를 듣기 위해 필요한 수학 과목들이 있습니다. 대표적으로 시계열 분석에서 Fourier transform 등에 쓰이는 개념으로 Euler formula, Differential equation 등이 있습니다.



추천 코스 :

Complex numbers

(선후수과목 순서대로) Differential Equation I => Vector calculus => Differential Equation II




**Linear Algebra - Matrix Methods in Data Analysis, Signal Processing, and Machine Learning**

(갓 길버트 스트랭 교수님)

선형대수가 통계학 및 머신러닝, 딥러닝에서 어떻게 쓰이는지 알려주는 강의입니다. 강의력이 대단하십니다.


**Multivariate statistical analysis (다변량 분석)**

**Time series analysis (시계열 분석)**

요 두 녀석들은 각각 다변량 데이터를 다룰 때, 시계열 데이터를 다룰 때 고민해야 할 점을 알려줍니다. 특히 다변량 분석은 머신러닝 모델에 데이터를 Input 으로 넣어주기 전에 해야할 데이터 전처리와 고민을 알려주고, 시계열 분석은 시계열 데이터를 다루는 기법을 알려줍니다.

추천 교재 : Applied Multivariate Statistical Analysis, The Geometry of Multivariate Statistics
Time Series Analysis and Its Applications: With R Examples

더불어 아마존에서 'Multivariate statistical analysis', 'Time series analysis'로 검색하시고, 이 책 저 책 시도해보세요!


요기까지 하면 정말 간단하게 학부 통계학 전필과목 대부분 끝! + 머신러닝 맛보기도 완료!

*4. 고급 (Lv. 3)*

*제가 아직 중급이라.. 새해에는 고급까지 배우고 글 새로 쓰겠습니다 ㅎㅎ*


**스스로 공부하는 모든 비전공자를 응원합니다**