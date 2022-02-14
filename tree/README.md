# tree
### ✅ 트리란?
node와 link로 구성된 비선형 자료구조

ex. windows 디렉토리 구조


### ➰ 특징
- Root가 하나 존재
- Root를 제외한 모든 node는 하나의 부모 가져야 함
- node는 여러 개의 자식을 가질 수 있음
- 한 node에서 다른 node로 가는 경로는 유일함


### 용어
- node : data
- link : node의 연결관계
- Root node : 최상위 노드
- leaf node : 최하위 노드 (terminal / external node)
- internal node : leaf node가 아닌 노드
- subtree : 트리의 부분집합
- path : 한 node에서 다른 node로 가는 경로
- 최소 공통 선조 : 두 노드의 공통적인 선조 중 가장 레벨이 높은 선조 노드
- 자식 노드 : 자신의 아래로 연결된 노드
- 부모 노드 : 자신의 위로 연결된 노드
- 조부모 노드 : 자신의 부모의 부모 노드
- 레벨 : root에서 특정 노드로 가는 경로의 노드 수
- 높이 : 가장 높은 레벨


### ✅ 이진트리란?
모든 internal node가 두개 이하의 자식을 갖는 트리 (left child / right child)

ex.
- parse tree : 수식 계산에 사용
- heap : 정렬에 사용
- binary search tree : 검색에 사용


### 용어
- Full Binary Tree : 마지막 레벨을 제외한 모든 레벨에 노드가 꽉 차 있는 것
- Complete Binary Tree : 모든 레벨에 노드가 꽉 차 있는 것


### 레벨과 노드의 수 관계
- d(레벨) / N(트리의 노드수)
- 2^(d-1) <= N <= 2^d - 1
- d = log2N +1 


