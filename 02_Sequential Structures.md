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

---

## Stack (스택)

- LIFO (Last In First Out) 방식
- 가장 최근에 저장된 값 다음에 저장되며, 가장 최근에 저장된 값이 먼저 나감
- 연산 : push, pop, top, isEmpty, len

---

## Queue (큐)

- FIFO (Fist In Firsk Out) 방식
- 가장 최근에 저장된 값 다음에 저장되며, 가장 오래된 값이 먼저 나감
- 연산 : enqueue, dequeue, isEmpty, front, len
  - enqueue : 오른쪽에 값 추가
  - dequeue : 가장 왼쪽 값 삭제 후 반환
  - front : 가장 왼쪽에 저장된 값을 리턴 (실제로 삭제 X)

---

## Dequeue (디큐)

- stack + queue 2가지 기능을 조합된 방식
- 연산 : append, appendleft, pop, popleft

---

