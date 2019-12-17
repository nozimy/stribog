# stribog
Реализация алгоритма хеширования "Стрибог" по ГОСТ 34.11 - 2012. Статья в журнале "Хакер": https://xakep.ru/2016/07/20/hash-gost-34-11-2012/.

### Build

- ` cmake -G "CodeBlocks - Unix Makefiles" ../`

### Run

- `./cmake-build-debug/stribog -d 64 -s YOUR_STRING`
- example `./cmake-build-debug/stribog -d 64 -s 001`