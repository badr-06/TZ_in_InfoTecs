## Библиотека для записи сообщений в журнал с разными уровнями важности и приложение, демонстрирующее работу библиотеки. 


### Как скомиплировать проект:

1. в корне дериктория вводим команду **mkdir build && cd build**
2. после того как мы оказались в дериктории *build* запускаме *cmake* командой **cmake ..** (по умолчанию стоит статческая сборка программы чтобы cборка была динамической нужно напсать **cmake -DBUILD_SHARED_LIBS=ON ..**)
3. и в конец прописываем **make**

### Как запустить проект

после сборки *make* должно появиться 2 файл *logger_app* и *logger_tests* в дериктории **src и tests**  первая запускает программу в вторая тесты