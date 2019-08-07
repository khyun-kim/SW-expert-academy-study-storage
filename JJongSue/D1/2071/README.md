# 2072 홀수만 더하기

[링크](https://www.swexpertacademy.com/main/code/problem/problemDetail.do?contestProbId=AV5QRnJqA5cDFAUq&categoryId=AV5QRnJqA5cDFAUq&categoryType=CODE)
- 시간 : 3개 테스트케이스를 합쳐서 C++의 경우 30초 / Java의 경우 30초 / Python의 경우 30초
- 메모리 : 힙, 정적 메모리 합쳐서 256MB 이내, 스택 메모리 1MB 이내 

### 문제 설명
10개의 수를 입력 받아, 평균값을 출력하는 프로그램을 작성하라.

(소수점 첫째 자리에서 반올림한 정수를 출력한다.)


### 제약 사항
- 각 수는 0 이상 10000 이하의 정수이다.

-------------------------------------------
### 입출력 예

[입력]

가장 첫 줄에는 테스트 케이스의 개수 T가 주어지고, 그 아래로 각 테스트 케이스가 주어진다.

각 테스트 케이스의 첫 번째 줄에는 10개의 수가 주어진다.


[출력]

출력의 각 줄은 '#t'로 시작하고, 공백을 한 칸 둔 다음 정답을 출력한다.

(t는 테스트 케이스의 번호를 의미하며 1부터 시작한다.) 

| 입력 | 출력 |
|--------|--------|
|3 | |
|3 17 1 39 8 41 2 32 99 2 |#1 24 |
|22 8 5 123 7 2 63 7 3 46 |#2 29 |
|6 63 2 3 58 76 21 33 8 1 |#3 27 |


### 입출력 예 설명
..

-------------------------------------------
### 풀이
- 정수 N을 입력 받고, for문을 통해 N번 반복 후, 10개의 수를 입력 받고  sum에 넣고, 반올림을 위해 끝자리가 5이상일 경우 10으로 나눈 후 1을 더했다.
