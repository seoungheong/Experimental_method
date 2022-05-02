# 독립 2표본 t검정 => ANOVA

> 독립적인 두 그룹의 평균에 대한 비교 => 둘 이상이라면?
>
> g개 그룹 간의 평균에 차이가 있는지를 통계적으로 검정하기 위해서 분산분석(analysis of variance, ANOVA)사용

# 분산 분석(analysis of variance, ANOVA)

> 그룹에 따라 반응변수의 평균이 차이가 나는지 알아보는 추론
>
> 일원배치 분산분석(One-way ANOVA): 그룹 변수 한 개
> >
> > 한개의 요인이 g개의 수준을 가질 때 수준 간 모평균 비교
> >
> > ex) 비료의 종류라는 한가지 요인에 의해 달라짐
>
> 이원 배치 분산분석(Two-way ANOVA): 그룹 변수가 두 개
> >
> > 
> >
> > ex) 비료와 농약의 종류라는 두 가지 요인에 의해 달라짐
>
> 삼원배치 분산분석(Three-way ANOVA): 그룹 변수가 세 개
> 
> > ex) 비료, 농약의 종류 및 일조량의 차이라는 세 가지 요인에 의해 달라짐  
>
> k-way ANOVA: 요인이 k개
> 요인(factor): 설명 변수
> 수준(level): 설명 변수의 각 범주인 그룹
>
> #### 제곱합의 분해
> >
> > g개 수준의 모평균 비교
> > 분산 분석표를 작성하여 수준 간 평균의 차이가 있는지 검정
> > 전체 자료 평균을 y로 i번째 그룹평균을 y_i로 표시하면
> > 자료 각각에서 전체 평균을 뺀 편차의 제곱을 구하여 이를 모두 합한 값
> > 자료의 전체 변동량
> > 
> > ![image](https://user-images.githubusercontent.com/65435447/166202224-52d6d147-0f6e-4f79-8330-f61e999eb503.png)
> >
> > <출처: https://m.blog.naver.com/PostView.naver?isHttpsRedirect=true&blogId=syj2755&logNo=220717448739>
> > 
> > SST ()
> > SSE(Sum of Squares Within) : 수준 내의 변동에 의해 생성되는 값
> > SSB (Sum of Squares Between) : 수준 내의 변동에 의해 생성되는 값
> > SSTrt(처리제곱합) : 값이 크다면 수준 간 차이가 크다고 볼 수 있으나 수준의 수가 많거나 원래 자료의 변동성이 클 경우, SSTrt가 크게 얻어지므로 이에 대한 보정이 필요함 -> 자유도를 사용하여 보정
> > 
>
> #### 자유도
> 
> > 전체 자료 수 N
> > SST의 자유도: N - 1
> > SSTrt의 자유도: g - 1
> > SSE의 자유도: N - g
> > SST의 자유도 = SSTrt의 자유도 + SSE의 자유도
> 
> #### 평균제곱
> 
> > 평균제곱합(Mean squares) : 제곱합을 해당 자유도로 나눈 것
> >
> > MSTrt(Mean Square Treatment) = SSTrt/(g - 1)
> > MSE(Mean Square Error) = SSE/(N - g)
> > * SST의 평균제곱은 분석에 사용하지 않음





















