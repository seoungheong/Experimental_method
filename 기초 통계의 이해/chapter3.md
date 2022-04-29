# 일표본 모평균에 대한 추론
>
> 자료가 독립적으로 얻어지고 평균이 u, 분산이 o^2인 정규분포를 따른때 이를 확률 표본 X_1, X_2....X_n ~N(u,o^2)로 표현
>
> #### 추정
>
> > 모평균 u에 대한 점추정은 표본평균 X로 하며 모평균 u가 폼함될 수 있는 구간을 제시하는 모평균에 대한 100(1-a)% 신뢰구간은
> >
> >![image](https://user-images.githubusercontent.com/65435447/165915646-ea889008-841f-4490-a014-8b4cbc25a403.png)
> >
> ><출처 https://thebook.io/006723/ch07/07/01/>
> >
> >t_(n-1:a/2): 자유도 (n-1)인 t 분포의 제 100(1-a/2)% 백분위수
> >
> >a: 주로 0.05(95% 신뢰구간)을 많이 사용하며 가끔 0.01이나 0.1등도 사용 됨
>
> #### 가설검정
>
> > 일표본 검정은 모집단의 평균, 즉 모평균이 통계적으로 유의하게 u_0 보다 커졌는지, 작아졌는지, 달라졌는지를 통계적으로 검정하는 방법
> > 
> > 모평균 u가 특정한 값 U_0인지 검정하기 위한 가설
> > 
> > > 귀무가설: H_0:u=u_0
> > > 
> > > 대립가설: H_1:u>u_0 또는 H_1:u<u_0 또는 H_1:u<u_0 또는 H_1:u!=u_0
> > > 
> > > 검정통계량:
> > > 
> > > ![image](https://user-images.githubusercontent.com/65435447/165917917-8a05fe25-d847-48d5-bb71-429def7003a4.png)
>
> > 기각역은 각각의 대립가설에 대해서 다음과 같음
> > 
> > ![image](https://user-images.githubusercontent.com/65435447/165918464-ebaeda81-4d47-4178-bbd9-2357b27eef3f.png)
> >
> > <출처 : http://jangun.com/study/IntroductionStatistics.html>
> >
> > 일표본 t 검정(One sample t-test)
> > 
> > 통계 패키지 사용 시 유의확률을 계산해주므로 유의확률이 유의수준보다 작으면 귀무가설을 기각함
> > 

# 독립 이표본 평균차에 대한 추론
>
> #### 대조군과 처리군의 비교
> 
> > 두 모집단의 모평균 u_1과 u_2가 같은지 비교
> >
> > 두 모집단에서 독립적으로 얻은 자료
> > 
> > 두 그룹의 평균차 u_1 - u_2에 대한 추론
> > 
> 
> #### 독립 이표본 t검정(Independent samples t-test)
> >  
> > 두 그룹의 자료가 독립일 때 두 그룹 평균차에 대한 검정
> >
> > 두 그룹의 분산이 같을 때(v_1 = v_2) 
> >  
> > #### 신뢰구간
> >  
> > 두 그룹 평균차 u_1-u_2 에 대한 100(1-a)% 신뢰구간 
> >  
> > ![image](https://user-images.githubusercontent.com/65435447/165921228-77af3623-df62-46d3-9dc3-87fec9f064b7.png)
> >  
> > <출처 : http://jangun.com/study/StatisticsConceptProblem.html>
> >  
> >  ![image](https://user-images.githubusercontent.com/65435447/165921464-efad6710-4bf3-4ad2-9b8c-5099eb8be7ac.png)
> >
> > <출처 : http://jangun.com/study/IntroductionStatistics.html> 
> >  
> >  ![image](https://user-images.githubusercontent.com/65435447/165922055-91534033-e98f-4cd3-b1e9-2b95f456ec8b.png)
> >  
> >  <출처 : https://velog.io/@gggggeun1/%EC%B6%94%EB%A6%AC%ED%86%B5%EA%B3%84%EC%99%80-%EA%B0%80%EC%84%A4%EA%B2%80%EC%A0%95> 
> >  
> >  #### 검정
> >  
> >  두 그룹 모평균의 차가 o_0인지 검정하기 위한 가설
> >  
> >  귀무가설: H_0: u_1 - u_2 = o_0
> >  
> >  대립가설: H_0: u_1 - u_2 > o_0 또는 H_0: u_1 - u_2 < o_0 또는 H_0: u_1 - u_2 != o_0
> >  
> >  두 모집단 평균차이가 o_0 이며, 차이가 있는지 검정하는 경우가 많으므로 이 값은 0이 사용되는 경우가 많음
> >  
> >  ![image](https://user-images.githubusercontent.com/65435447/165923242-b917c306-e589-4d88-aec6-37e320b51dec.png)
> >
> > 위의 기각역에 해당하거나 유의확률이 유의수준보다 작으면 귀무가설을 기각함
> >    ㅇ
> ㅇ


# 대응 2 표본 추론(짝비교, 쌍체검정)






























