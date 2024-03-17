- info
    - lv1
    - 탐색, 슬라이딩 윈도우

# 작은 길이 부분 배열 찾기
## 문제 설명
정수 배열과 타겟 합 S가 주어집니다. 배열 내 연속된 부분 배열 중에서 그 합이 S 이상이 되는 가장 작은 길이의 부분 배열을 찾아, 그 길이를 반환하는 코드를 작성해주세요. 만약 그러한 부분 배열이 존재하지 않으면 0을 반환합니다.

---

## 제한 사항

- 배열의 각 요소는 양의 정수입니다.
- 배열의 길이는 최소 1에서 최대 100까지입니다.
- 타겟 합 S는 양의 정수입니다.

---

## 입출력 예

|   입력 (배열, 타겟 합 S)   | 출력 (최소 길이) |
| -------------------------- | ---------------- |
| ([2, 1, 5, 2, 3, 2], 7)    | 2                |
| ([1, 1, 1, 1, 1, 1, 1], 11) | 0                |

---

## 입출력 설명
첫 번째 예시에서 배열 [2, 1, 5, 2, 3, 2] 내에서 합이 7 이상이 되는 가장 작은 길이의 부분 배열은 [5, 2]로 길이가 2입니다. 두 번째 예시에서는 합이 11 이상이 되는 부분 배열이 존재하지 않으므로 0을 반환합니다.