#Algorithm

# STL
: Standard Template Library의 약자로서, 알고리즘, 컨테이너, 함수, 이터레이터 등으로 이루어져있다.

----------------------------------------------------------------------------------------------------------------------------------


1. vector
	* Vector 
		 - 길이를 변경할 수 있는 배열
		 - array 처럼 배열의 길이가 바뀔 때마다 바뀌는 메모리를 신경 쓸 필요가 없다
	* Pair
		- 두 자료형을 하나의 쌍(pair)으로 묶는다
		- 첫번째 데이터는 first, 두번째 데이터는 second로 접근 가능
		- vector, algorithm 의 헤더파일에 include 하고 있기 때문에 별도로 utility 헤더를 물릴 필요가 없다
		
2. set
	* Set
		- Associative 컨테이너
		- 균형 이진 트리로 구현되어있다
		- Key라 불리는 원소들의 집합으로 이루어져 있다
		- Key값은 중복되지 않는다
		- insert를 통해 입력하면 자동 정렬된다
		- 즉, 중복을 피하면서 정렬까지 사용하고 싶으면 매우 유용

3. map
	* Map
		- Associative 컨테이너
		- set은 원소값으로 key 하나만을 저장하지만, map은 <key, value>의 쌍(pair)으로 저장
		- 중복 저장되지 않는다
		- set처럼 컨테이너에 원소 (key, value의 쌍)를 삽입하는 멤버 함수 insert()를 제공
		- map은 [] 연산자를 제공하여 key에 해당하는 원소의 value에 쉽게 접근하거나 변경할 수 있다
		
4. stack
	* Stack
		- 스택은 자주 사용되는 자료구조 중 하나
		- LIFO(Last In, First Out)의 특징
		- 컴퓨터의 기본 아키텍쳐도 스택의 구조
		
5. queue
	* Queue
		- FIFO (First in, First Out)의 특징
		- BFS(넓이 우선 탐색)을 할 때 많이 사용하게 된다
	* Priority Queue
		- 들어간 순서와 상관없이 우선순위가 높은 데이터가 먼저 나온다
		- 내부적으로 의 heap 과 관련된 함수들을 사용하여 구현

 
  
  
6. 출처 : https://purduecho.github.io/stl/	 
