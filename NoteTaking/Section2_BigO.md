# Big O
- 동일한 기능을 구현한 두개의 코드가 있다고 가정했을 시 수학적으로 어떤 코드가 효울적인지 비교하기 위한 것
- 코드를 평가하는데는 시간 복잡도와 공간 복잡도가 있음 (Time Complexity, Space Complexity)
- 코딩 인터뷰에서 Time Complexity와 Space Complexity 중 어느게 더 우선순위가 높은지 질문받을 수도 있음
- 지금 강의에서는 Time Complexity를 다룰 것임

# Worsr Case
- 오메가: best, 쎄타: average, 오미크론: worst
- Big O에 대해서 말하자는건 언제가 worst case에 대해 얘기하는 것
  
# Drop Constants and Non-Dominants
- O(const1 * n + const2) 에서 앞의 상수는 버린다.
- n^2 + n 은 그냥 n^2 이다.

# Squared
- Squared는 살림
- 효울이 아주 다르기 때문

# O(1)
- constant time
- the most efficient Big O

# O(log n)
- 숫자 8개를 정렬한다고 했을 때 1을 찾는다면 반씩 쪼개서 3번만에 찾아짐. 즉 2^3 이고 이건 log2의 8은 3임
- very flat, very efficient
- nlogn은 sorting 알고리즘 때 배울 예정