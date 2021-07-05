## 순차적 자료구조 (Sequential Structures)

1) array, list

- index로 임의의 원소 접근 가능
- 삽입(append, insert),  삭제(pop, remove)

2) stack, queue, dequeue

- stack : LIFO(Last IN First Out)
- queue : FIFO(First In First Out)
- dequeue : stack + queue

3) link list (연결 리스트)

- index 접근 불가능

---

## List (리스트)

- C언의 배열과 비슷한 개념
- 데이터를 연속적인 메모리 공간에 저장
- 저장된 곳의 주소를 통해 빠른 접근이 가능
- 리스트는 셀에 데이터가 아닌 데이터가 저장된 주소를 저장 (C언어 배열과 차이점)
- dynamic array(동적 배열)임
  - 필요에 따라 리스트 크기가 자동으로 증가/감소함
  - 메모리 낭비가 심함

