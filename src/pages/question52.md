- info
    - lv0
    - 그리디

# 아이스크림 잔돈 계산
## 문제 설명
라이캣은 편의점에서 1만원으로 아이스크림을 살 예정입니다. 모든 아이스크림은 7백원입니다. 아이스크림 사는 갯수에 따라 최소 갯수의 잔돈을 리스트로 출력하세요.

예를 들어, 아이스크림을 2개 산다면 1,400원이므로 8,600원의 거스름돈을 주어야 합니다. 이럴 경우 5,000원 1개, 1,000원 3개, 500원 1개, 100원 1개의 거스름돈이 나가야 합니다. 리스트로는 [0, 1, 3, 1, 1]이 출력되어야 합니다.

리스트는 차례대로 만원, 오천원, 천원, 오백원, 백원을 가리킵니다.
---

## 제한 사항

- 외상은 없습니다. 있는 돈 안에서 아이스크림을 구매합니다.
- 라이캣은 항상 1만원을 가지고 있습니다.
- 리스트는 만원이 없어도 항상 만원부터 출력해야 합니다.

---

## 입출력 예

|   입력 (아이스크림 개수) | 출력 (거스름돈 리스트: [만원, 오천원, 천원, 오백원, 백원]) |
| --------------------- | ------------------------------------------------------- |
| 2                     | [0, 1, 3, 1, 1]                                         |
| 3                     | [0, 1, 2, 1, 4]                                         |
| 10                    | [0, 0, 3, 0, 0]                                         |

---

## 입출력 설명
- 첫 번째 예시에서 아이스크림 2개의 가격은 1,400원이며, 라이캣이 10,000원에서 거슬러 받아야 할 금액은 8,600원입니다. 이 금액을 거슬러 주기 위한 최소 잔돈은 5,000원 1개, 1,000원 3개, 500원 1개, 100원 1개이므로, 리스트는 [0, 1, 3, 1, 1]이 됩니다.
- 두 번째 예시에서 아이스크림 3개의 가격은 2,100원이며, 거슬러 받을 금액은 7,900원입니다. 이를 위한 최소 잔돈은 5,000원 1개, 1,000원 2개, 500원 1개, 100원 4개이므로, 리스트는 [0, 1, 2, 1, 4]가 됩니다.
- 세 번째 예시에서 아이스크림 10개의 가격은 7,000원이므로, 거슬러 받을 금액은 3,000원입니다. 이를 위한 최소 잔돈은 1,000원 3개이므로, 리스트는 [0, 0, 3, 0, 0]이 됩니다.