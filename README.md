# KSA_Clustering_Algorithm
SA(Simulated Annealing) + K-mean Clustering을 결합한 KSA Clustering Algorithm 구현 및 검증

# 1. K-means Clustering Algorithm 작동 과정

![image](https://github.com/user-attachments/assets/2587cd8e-eca6-4c29-91fa-a4aa287799c1)

# 2. SA Clustering Algorithm 작동 과정

![image](https://github.com/user-attachments/assets/adb6db52-e110-43d5-a8fd-2466553ee45b)

# 3. **KSA Clustering Algorithm**
   - K-means로 구한 해를 SA의 초기값으로 하는 Clustering 방법

## 실험 데이터
UCI example data
- iris.txt
- wine.txt
- glass.txt
- vowel.txt
- cloud.txt

## 실험결과 비교를 위한 데이터별 Hyperparameter 고정
- Iris(T = 1, △T = 0.05, t = 1500)
- Wine(T = 6, △T = 1, t = 1780)
- Glass(T = 1, △T = 0.03, t = 2140)
- Vowel(T = 100, △T = 10, t = 8710)
- Cloud(T= 15, △T = 0.025, t = 250)
