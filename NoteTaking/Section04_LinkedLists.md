# Linked Lists
- Linked Lists에서 맨 앞, 끝 노드 넣었다 빼는건 O(1)
- 중간에 있는 노드 넣었다 빼는건 O(n)
- pop이랑 look up by index는 일반 lists가 더 좋고, prepend랑 pop first는 linked lists가 더 좋음

# Node
- node에는 value와 next의 값이 있음
- 이를 dictionary 형태로 관리
- pop을 할 때 고려해야할 케이스는 3가지로
  - 노드가 1개도 없음
  - 노드가 1개만 있음
  - 노드가 2개 이상 있음
- prepend를 할 때 고려할 케이스는 2가지
  - 노드가 1개도 없음
  - 노드가 2개 이상 있음