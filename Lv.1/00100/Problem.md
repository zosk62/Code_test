https://school.programmers.co.kr/learn/courses/30/lessons/147355

# Substring Comparison

## Problem Statement

You are given two strings: 't' and 'p'. Your task is to write a function called 'solution' that counts the number of substrings in 't' that have the same length as 'p' and whose numerical representation is less than or equal to the numerical representation of 'p'.

### Example

If 't' equals "3141592" and 'p' equals "271", you should find all substrings of 't' that are of length 3 (matching the length of 'p'), such as "314", "141", "415", "159", and "592". Among these, "141" and "159" have numerical values less than or equal to the numerical value of 'p', which is 271. Therefore, the function should return 2 in this case.

## Usage

To use the `solution` function, pass two strings as arguments: 't' and 'p'. It will return the count of substrings in 't' that meet the specified condition.

python
count = solution("3141592", "271")
print(count)  # Output should be 2

------------------

https://school.programmers.co.kr/learn/courses/30/lessons/147355

# 숫자로 이루어진 문자열의 부분문자열 비교

## 문제 설명

숫자로 이루어진 문자열 t와 p가 주어질 때, t에서 p와 길이가 같은 부분문자열 중에서, 이 부분문자열이 나타내는 수가 p가 나타내는 수보다 작거나 같은 것이 나오는 횟수를 반환하는 함수 solution을 완성하세요.

### 예제

예를 들어, t="3141592"이고 p="271" 인 경우, t의 길이가 3인 부분 문자열은 314, 141, 415, 159, 592입니다. 이 문자열이 나타내는 수 중 271보다 작거나 같은 수는 141, 159 2개 입니다.

## 제한사항

- 1 ≤ p의 길이 ≤ 18
- p의 길이 ≤ t의 길이 ≤ 10,000
- t와 p는 숫자로만 이루어진 문자열이며, 0으로 시작하지 않습니다.

## 입출력 예

| t           | p   | 결과  |
|-------------|-----|------|
| "3141592"   | "271" | 2    |
| "500220839878" | "7" | 8   |
| "10203"     | "15" | 3    |

