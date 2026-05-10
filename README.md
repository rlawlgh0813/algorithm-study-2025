# Algorithm Study 2025

2025년 알고리즘 문제 풀이를 주제별로 정리한 study archive입니다.

이 저장소는 큰 프로젝트라기보다, 문제를 풀면서 사용한 접근 방식과 구현 패턴을 남겨 두는 용도입니다. 포트폴리오에서는 [algorithm-problem-solving](https://github.com/rlawlgh0813/algorithm-problem-solving)이 더 큰 풀이 모음이고, 이 레포는 2025년 학습 흐름을 작게 분리한 기록입니다.

## Structure

```text
algorithm-study-2025/
├── boj/
│   ├── greedy/
│   └── dynamic-programming/
├── docs/
│   └── compile.md
└── README.md
```

## Problems

| Category | Problem | File | Key idea |
| --- | --- | --- | --- |
| Greedy / Binary Search | [BOJ 2343 - 기타 레슨](https://www.acmicpc.net/problem/2343) | `boj/greedy/2343-guitar-lesson.cpp` | Parametric search |
| Dynamic Programming | [BOJ 1103 - 게임](https://www.acmicpc.net/problem/1103) | `boj/dynamic-programming/1103-game.cpp` | DFS + memoization + cycle detection |
| Dynamic Programming | [BOJ 2240 - 자두나무](https://www.acmicpc.net/problem/2240) | `boj/dynamic-programming/2240-plum-tree.cpp` | State DP with position and move count |
| Dynamic Programming | [BOJ 4811 - 알약](https://www.acmicpc.net/problem/4811) | `boj/dynamic-programming/4811-pill.cpp` | Counting DP |
| Dynamic Programming | [BOJ 12852 - 1로 만들기 2](https://www.acmicpc.net/problem/12852) | `boj/dynamic-programming/12852-make-one-2.cpp` | DP + path reconstruction |
| Dynamic Programming | [BOJ 2294 - 동전 2](https://www.acmicpc.net/problem/2294) | `boj/dynamic-programming/2294-coin-2.cpp` | Minimum coin DP |

## What This Shows

- C++ 기반 BOJ 문제 풀이
- greedy / binary search / dynamic programming 기초 패턴
- cycle detection, path reconstruction 같은 구현 디테일
- 풀이 후 짧은 회고를 코드 하단에 남기는 학습 방식

## Compile

```bash
g++ -std=c++17 -O2 -Wall boj/dynamic-programming/1103-game.cpp -o main.out
./main.out
```

자세한 컴파일 예시는 [docs/compile.md](docs/compile.md)에 정리했습니다.
