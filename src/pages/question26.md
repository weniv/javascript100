- info
    - lv0
    - 탐색, 슬라이딩 윈도우

# 최대 합계 배열 찾기
## 문제 설명
정수로 이루어진 배열과 'k' 길이의 윈도우가 주어집니다. 윈도우를 배열 전체에 슬라이드 시켜가며 얻을 수 있는 최대 합계를 갖는 연속 부분 배열의 합을 찾는 코드를 작성해주세요.

---

## 제한 사항

- 배열의 길이는 최소 k 이상입니다.
- 배열의 요소는 정수이며, 음수일 수도 있습니다.
- k는 1 이상 배열의 길이 이하인 정수입니다.

---

## 입출력 예

|   입력 (배열, k)   | 출력 (최대 합계) |
| ------------------ | ---------------- |
| [[1, 3, 2, 6, -1, 4, 1, 8, 2], 5] | 18 |
| [[4, 2, 1, 7, 8, 1, 2, 8, 1, 0], 3] | 16 |

---

## 입출력 설명
첫 번째 예시에서 배열 [1, 3, 2, 6, -1, 4, 1, 8, 2]에 대해 길이가 5인 윈도우를 사용하여 얻을 수 있는 최대 합계는 [2, 6, -1, 4, 1, 8] 부분 배열의 합 17입니다. 두 번째 예시에서는 [7, 8, 1] 부분 배열의 합이 16으로 최대 합계입니다.
