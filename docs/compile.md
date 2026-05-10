# Compile Notes

단일 C++ 풀이 파일을 빠르게 확인할 때 사용하는 기본 명령입니다.

```bash
g++ -std=c++17 -O2 -Wall boj/dynamic-programming/1103-game.cpp -o main.out
./main.out
```

다른 파일을 실행하려면 경로만 바꾸면 됩니다.

```bash
g++ -std=c++17 -O2 -Wall boj/greedy/2343-guitar-lesson.cpp -o main.out
./main.out
```

`main.out` 같은 실행 파일은 `.gitignore`에 포함되어 Git에 올라가지 않습니다.
