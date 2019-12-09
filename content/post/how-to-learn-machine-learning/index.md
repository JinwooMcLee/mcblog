---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "머신러닝 입문 쉽게 하기"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2019-07-12T02:37:44+09:00
lastmod: 2019-07-12T02:37:44+09:00
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
(지난 글 : 코딩 입문 쉽게 하기)



머신러닝을 이야기하려면 데이터 사이언스가 빠질 수 없죠.



![Image of DS](https://snulife.com/files/attach/images/512/929/781/161/164dfeda0d8975e268602d801e5d8c3b.png)



데이터 사이언스는 "컴퓨터 공학 / 수학+통계학 / 업계 지식"을 결합해

데이터에서 비즈니스 인사이트를 뽑아내거나 (Data analyst)
고도화된 자동화 알고리즘으로 수리통계 예측 모델을 만듭니다 (Data scientist)


1번은 그나마 무슨 소린지 알겠는데.. 2번은 대체 무슨 소리냐고요?



빅스비나 시리 등 음성 인식 비서를 예로 들자면 얘네들은

수많은 음성 데이터를 기반으로
사람이 무슨 말을 하는지 학습하고
학습을 기반으로 예측 모델을 만들고
누군가 말을 걸면 모델을 통해 이 사람의 말을 이해하고자 합니다
![Image of AI](https://miro.medium.com/max/4200/1*GIPiAdQyOa8wUOkHaL-MJg.gif)






이러한 이해가 없이 머신러닝에 입문하면 길을 한참 잘못 들어서게 되죠.



컴퓨터에게 통계적 예측 모델을 만들도록 할 때는 종종

예측이 틀리면 많은 패널티를 
예측이 맞으면 적은 패널티를
주는 방법을 활용합니다.



예측이 얼마나 틀렸느냐를 Cost로 표현하고, Cost가 낮아지게끔 모델을 개선하게 하죠.

![Image of GD](https://blog.paperspace.com/content/images/2018/05/fastlr.png)




이 과정에서 Gradient descent 알고리즘을 활용할 때도 있습니다.



Gradient란 다변수 미적분 개념으로

![Image of Gradient](https://snulife.com/files/attach/images/512/929/781/161/419b26cf0dcc2b8dc71c7f72deeaec04.png)


특정 위치에서 다변수 함수값이 가장 빠르게 올라가는 방향,



등산한다고 치면 가장 가파르게 올라가는 방향을 나타냅니다.



Gradient에 마이너스 부호를 붙여주면, 함수값인 cost가 가파르게 내려가는 방향이겠지요?





한편 단순하게 예측하는 모델을 만들 때는



Linear regression을 활용할 수 있으며, 많은 상황에서



Untitled.png 

(X : 예측 모델 input / Y : 예측 모델 output / theta : X에 주는 가중치)



위와 같이 뚝딱 모델 Cost를 최소화하기도 합니다. (선형대수 개념)



이렇듯 한 번에 솔루션이 나오는 상황에서 Gradient descent를 쓰면 가까운 길을 놔두고 먼 길을 돌아가는 셈입니다.





결론은 입문을 하더라도 제대로 된 길로 들어서야 합니다.



맨 위 벤 다이어그램에서처럼, 수학과 통계는 머신러닝을 구성하는 거대한 축이지요.



시중에 있는 대다수 강의나 책은 대중성(이익)을 위해 단순히 코드 예제만 보고 따라하게끔만 합니다. 그런 식으로 하다가는 응용은 절대 불가합니다.



예측 모델을 만드려 Data input을 넣을 때만 해도

https://docs.scipy.org/doc/numpy/reference/routines.linalg.html

(inverse, inner (product), outer (product), eig(envalue), trace 등등.. 선형대수 개념들)



어떻게 데이터를 넣어줄지 하나도 모르는 불상사가 발생합니다.







결국 머신러닝 입문을 쉽게 하면 멀리 돌아가게 됩니다.



수학과 통계를 최소한도로, 직관 위주로 가르치는 강의 목록과 함께 마무리하겠습니다.

* 수학

3Blue1Brown Linear algebra
칸 아카데미 Multivariable calculus
(기초 미적분이 필요할 경우 3Blue1Brown - Essence of calculus)

* 통계

Coursera - Statistics with R

* 머신러닝

Coursera - Machine Learning

**Update : 본격적이고 구체적인 커리큘럼은 다음 글(http://jinwoomclee.github.io/post/curriculum/)을 참조해주세요**