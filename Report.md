# Отчет о тестировании KeyValidator

# KeyValidator - приложение, проверяющее лицензионные ключи,
написано на языке Java, работает из командной строки.

24.10.2020 проведено тестирование установки, совместимости и функционала KeyValidator.

На тестирование затрачено: 2 часа

В результате тестирования выявлены следующие дефекты:
* Приложение не запускается при вводе валидного ключа https://github.com/marosi13/KeyValidator/issues/1
* Приложение запускается при вводе невалидного ключа https://github.com/marosi13/KeyValidator/issues/3

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md
* https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md

В качестве тестовых данных использовались данные https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md:
* Result for 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998: OK
* Result for 80b427f8-92cd-3aae-ba04-3927fbe17c6: OK
* Result for b295bc63-9f03-3b4b-af80-969b39f8c262: OK
* Result for 387eedc6-12e9-3b32-9881-63b6b5e85317: OK
* Result for c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180: OK

* Result for 18252235-78e0-44a5-8720-556f0c7da17a: FAIL
* Result for e66075b6-ddad-445e-baf6-161b3289522b: FAIL
* Result for b6d53250-f07e-4352-a293-6102ddf7f1ca: FAIL
* Result for c2bc778a-1cb9-46c6-b435-0489649d2a42: FAIL
* Result for 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1: FAIL

Тестирование производилось в следующем окружении:
* Win7 Professional 64-bit OS
* Java: openjdk version "11.0.9"
