# Hash
Key-value쌍으로 데이터를 저장하는 자료구조    /   사용목적 : key를 이용하여 data를 빠른 속도로 찾을 때 사용   /   시간복잡도 : O(n)~O(1)



- 파이썬 : dictionary
    - stud = {'학번':2018, '이름':'홍길동','학과':'전정공'}
- c++ : hash_map
- java : hashcode(), HashMap, HashSet
    - HashTable 병렬 프로그래밍을 할 때 동기화를 지원해줌 / [출처](https://mangkyu.tistory.com/102)
    - 병렬 처리를 하면서 자원의 동기화를 고려해야하면 HashTable
    - public synchronized V put(K key, V value)
    - 병렬 처리를 하지 않거나 동기화를 고려하지 않는다면 HashMap
    - public V put(K key, V value)
