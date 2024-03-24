https://school.programmers.co.kr/learn/courses/30/lessons/142086

## Problem Statement (Finding the Nearest Duplicate Character.)

Given a string `s`, find the index of the nearest occurrence of the same character that appeared before at each position in `s`.

For example, if `s="banana"`, the process proceeds as follows by reading each character from left to right:

- 'b' has no same character appearing before, so it's represented as -1.
- 'a' has no same character appearing before, so it's represented as -1.
- 'n' has no same character appearing before, so it's represented as -1.
- 'a' has another 'a' two positions before, so it's represented as 2.
- 'n' has another 'n' two positions before, so it's represented as 2.
- 'a' has 'a' two and four positions before, but the nearest occurrence is two positions before, so it's represented as 2.

Therefore, the final result would be `[-1, -1, -1, 2, 2, 2]`.

## Function Specification

Complete the function `solution` that performs the defined operation when given the string `s`.

---

https://school.programmers.co.kr/learn/courses/30/lessons/142086

## Problem Statement (문제 설명)

문자열 `s`가 주어졌을 때, `s`의 각 위치마다 자신보다 앞에 나왔으면서, 자신과 가장 가까운 곳에 있는 같은 글자가 어디 있는지 알고 싶습니다.

예를 들어, `s="banana"`라고 할 때, 각 글자들을 왼쪽부터 오른쪽으로 읽어 나가면서 다음과 같이 진행할 수 있습니다:

- 'b'는 처음 나왔기 때문에 자신의 앞에 같은 글자가 없습니다. 이는 -1로 표현합니다.
- 'a'는 처음 나왔기 때문에 자신의 앞에 같은 글자가 없습니다. 이는 -1로 표현합니다.
- 'n'은 처음 나왔기 때문에 자신의 앞에 같은 글자가 없습니다. 이는 -1로 표현합니다.
- 'a'는 자신보다 두 칸 앞에 'a'가 있습니다. 이는 2로 표현합니다.
- 'n'도 자신보다 두 칸 앞에 'n'이 있습니다. 이는 2로 표현합니다.
- 'a'는 자신보다 두 칸, 네 칸 앞에 'a'가 있습니다. 이 중 가까운 것은 두 칸 앞이고, 이는 2로 표현합니다.

따라서 최종 결과물은 `[-1, -1, -1, 2, 2, 2]`가 됩니다.

## Function Specification (함수 설명)

문자열 `s`이 주어질 때, 위와 같이 정의된 연산을 수행하는 함수 `solution`을 완성해주세요.

## Constraints (제한사항)

- 1 ≤ s의 길이 ≤ 10,000
- s은 영어 소문자로만 이루어져 있습니다.

## Example (예시)

| s       | result          |
|---------|-----------------|
| "banana" | [-1, -1, -1, 2, 2, 2] |
| "foobar" | [-1, -1, 1, -1, -1, -1] |
