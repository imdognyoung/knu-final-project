     
## 역할

### 1.1. 사용할 Data 구상
  1.1.1
     - 조원들과의 회의를 통해 사용할 데이터 정한 뒤, 어떤 방식으로 데이터베이스를 구축할 것인가. -> 데이터가 많이 필요하다 -> 크롤링  
       
  1.1.2. 크롤링  
     - 조원들과 스탯티즈 사이트에서 특정한 값을 긁어오는 크롤링 프로그램을 구성한 뒤에, 타자 데이터를 수집하여 데이터베이스를 구축하는 역할을 맡게되었습니다. 
     
  1.1.3. 데이터 정제
     - 데이터 분석에 앞서 전처리가 완료된 데이터에 대해 빈값(결측치)이나 정상 범위를 벗어난 값(이상치)들을 제거하거나 다른 값으로 대체하는 처리 등 데이터 정제 역할을 맡게 되었습니다.    
  
## 배운점  

      1) 프로젝트를 진행하기전에는, 딥러닝하면 그냥 네트워크에 데이터 때려 넣고 하이퍼 패러미터만 바꿔되면 되는줄 알았습니다. 
      하지만 공부하면 할수록, 깊은 수학적 이해와 이를 효과적으로 구현 할수 있는 코딩능력이 필요하다는걸 깨달았습니다. 
      특히 딥러닝의 수학적 이해가 필수라는 것을 점점 느낍니다. 진행이 잘 되지 않으면 데이터 더 집어넣고 더 깊게 만들고가 끝이 아니라,
      왜 이런 결과가 나오는지, 내가 사용하는 모델이 이 목적에 맞고 잘 구현했는지, 또한 내 데이터에 이 모델이 어떤 식으로 영향을 미치고 
      이걸 해결하려면 어떤 방향으로 접근해야 하는지 정확히 알아야 한다는걸 깨달았습니다. 
      그리고 또 발견한 문제를 해결하기 위해선 데이터를 더 만드는것 뿐 아니라 loss가 적합한지 보고 아니라면
      어떤 custom loss를 구현할지 또 이 loss의 gradient가 바뀌는 거에 따라 정규화는 어떻게 해야하는지 등등 상당히 어려웠지만,
      조원들과 함께 정확도 82%의 결과값을 내는 프로그램을 만들 수 있게 되어 보람을 느끼고 있습니다.
 
