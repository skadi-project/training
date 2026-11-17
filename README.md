# training

Репозиторий который содержит 100 проектов на C и Rust.

Все проекты указаны в [100 projects.md](100_PROJECTS.md)

## Компиляция

### clang

Дебаг:
`clang -O0 -g -Wall -Wextra main.c -o main.exe`
-O0 -g -Wall -Wextra
Релиз:
`clang -O3 -march=native -flto -funroll-loops -DNDEBUG -Wall -Wextra main.c -o main.exe`