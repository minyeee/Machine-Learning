# 1.1 Introduction

## 1.1.1 what is Machine Learning?

>기계학습이란 컴퓨터가 명시적으로 프로그래밍 되지 않아도, 배울 수 있도록 하는 과학이다.
>
>우리는 하루에 수십번씩 기계학습을 사옹하고 있다. 구글이나 빙에서 인터넷 검색을 할때나 페이스북이나 애플의 사진 어플리케이션이 나의 친구를 사진에서 구분하는것은 기계학습이 잘 동작하고 있다는 것이다. 또한 우리의 이메일이 스펨메일을 구분할 수 있는 것도 우리의 컴퓨터가 스팸메일을 구분해 낼 수 있는 방법을 찾아냈기 때문이다. 
>
>많은 과학자들은, 사람의 뇌를 모사하는 컴퓨터 신경망이라고 부르는 학습 알고리즘이 이러한 진전을 가져올 수 있는 가장 좋은 방법이라고 생각한다. 



### 왜 기계학습이 오늘날에 사용되고 있는 것일까?

* Grew out of work in AI
* New capability for computers

>기계학습은 컴퓨터의 새로운 능력을 불어넣어 향상 시켜주기 때문에 오늘날 기초과학과 산업의 여러 분야에서 사용되고 있다.

### Examples

* Database mining 

  > Large datasets from growth of automation/web. 
  >
  > E.g.,Web click data, medical record, biology, engineering 

* Applications can't program by hand.

  >E.g., Autonomous helicopter, handwriting recognition, most of Natural Language Processing(NLP), Computer Vision.

* Self-customizing programs

  > E.g., Amazon, Netflix product recommendations

* Understanding Human learning (brain, real AI)

### Machine Learning Definition

* Arthur Samuel(1959). Machine Learning :  "내용을 분명하게 프로그램하지 않으면서 컴퓨터에게 학습할 능력을 주는 학문분야" 라고 정의 

* Tom Mitchell(1998). Well-posed Learning problem : '어떤 과제 T에 대한 성능이 P라고 측정되고 경험 E를 통해 향상된다면 프로그램은 과제 T에 대해 경험 E로부터 성능 기준 P에 따라 학습한다고 할 수 있다 '

  > Example : playing checkers 
  >
  > E = 체스게임을 많이 해본 경험
  >
  > T = 체스를 하는 일 
  >
  > P = 프로그램이 다음 게임에서 이길 확률  

## 1.1.2 Supervised Learning

>우리가 알고리즘에게 정확한 답을 알고있는 데이터(data set)를 준다는 데서 유래한다. 예를 들면 우리가 알고리즘에 집들에 대한 데이터를 주고 그 데이터의 모든 예시들에 대해서, 이게 맞는 가격이고 실제로 집이 팔린 가격이 얼만지 알려주게 되면 알고리즘은 이 'right answers' 들을 더 만들어 내는 것이다. 

* Regression problem : 우리가 연속적인 값을 예측하는 것. 집값으로 예를 들자면 연속적인 값이란 가격이 됨. Regression 이라는 용어는 어떤 연속적인 속성 값을 예측하려는 것을 말함

## 1.1.3 Unsupervised Learning

> efinition : dataset이 주어지고 그 data가 무슨 의미인지 알려주지 않는다. 그냥 data set이 주어질 뿐. 알고리즘이 data로부터 모든 것을 찾도록 해야한다

+ E.g, ORaganize computing clusters, Social network analysis, Market segmentation, Astronomical data analysis
+ Cocktail party problem : 두명이 동시에 말을하거나 음악이 들리는 배경에서 한사람이 말을 할 때 그 소리를 구분해 내는 알고리즘. 두명이 서로 다른 언어로 1부터 10까지 말을 한다면 언어별로 ouput 만들어 내며, 음악이 들리는 배경에서 한사람이 말을 할 때 음악소리와 사람의 목소리로 각각의 output을 만들어낸다.



