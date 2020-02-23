hello golang 뜯어보기. 한줄씩 냠냠
=============

<img src="https://drive.google.com/uc?export=view&id=1sReeHTeJkB0O7iKrcMZSMnoNAeBY480F"/>

Go의 가장 기본적인 코드이다. 한줄씩 분석해보자

1. __package 선언__
* main 함수가 포함된 페키지라는 의미임.
* 모든 go 프로그램은 main 패키지가 있어야하고, 모든 main 패키지는 main 함수를 포함해야한다.
* 이건 이름 짓기 나름임. 패키지 정의

2. __import 선언__
* 여기서는 패키지를 불러옴. 
* 다른 소스의 1줄에서 만든 패키지를 불러올 수 있고 표준 패키지를 불러올 수도 있음
* 해당 코드에서는 fmt 패키지를 가져왔는데, fmt는 format의 약자임. go 표준이다.  
* fmt는 C에서의 printf나 scanf와 유사한 기능의 I/O를 제공하는 패키지입니다. https://golang.org/pkg/fmt/#pkg-examples

3. __func main()__
* 함수 선언의 키워드는 func이고
* 그냥 평이한 print문인듯
