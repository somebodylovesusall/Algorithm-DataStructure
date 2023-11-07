# Bubble Sort

## ❔
주어진 배열에 대하여 버블 정렬을 수행하는 `bubbleSort` 함수 구현

## ✔️
이중 `for` 반복문을 사용하여 배열에서 인접 요소끼리 비교  

## ❕
- 처음 `for` 반복문은 회전 반복을 수행하며 다음 `for` 반복문은 매회전마다 인접한 모든 요소들을 비교
- 변수 `j`는 `arr.length - i - 1`까지 증가하여 배열에서 해당 요소와 다음 요소를 비교
- 왼쪽 요소가 오른쪽 요소보다 작으면 맞교환하여 정렬하고 같은 방식으로 매회전을 반복

## 💡
버블 정렬은 매회전마다 마지막 요소부터 역순으로 요소를 확정하며 회전을 반복할수록 비교 횟수 감소  
시간복잡도: `O(n^2)`