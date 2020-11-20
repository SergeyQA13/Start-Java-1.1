# Отчет о тестировании приложение KeyValidator.
## Краткое описание
### 20.11.20 было проведено тестирование установки OpenJDK11 и Unit testing приложения KeyValidator
На тестирование затрачено: 1 часа

В результатет тестирования вявлены следующие дефект:
* [Bug report 1](https://github.com/SergeyQA13/Start-Java-1.1/issues/1#issue-745955752)
* [Bug report 2](https://github.com/SergeyQA13/Start-Java-1.1/issues/2#issuecomment-729920065)
* [Bug report 3](https://github.com/SergeyQA13/Start-Java-1.1/issues/3#issue-745971767)


## Описание процесса тестирования
### В процессе тестирования использовался следующий артефакт:
* [Тестовые данные для OpenJDK11 ](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md)
* [Тестовые данные для приложения Приложение KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)

### В качестве тестовых данных использовались данные из артефактов:

Данне для тестирования OpenJDK11:

Команда:

java -version

Ответ:
openjdk version "11.0.5" 2019-10-15
OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.5+10)
OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.5+10, mixed mode)

Данне для тестирования приложения KeyValidator:

Валидные ключи:

* 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998
* 80b427f8-92cd-3aae-ba04-3927fbe17c6
* b295bc63-9f03-3b4b-af80-969b39f8c262
* 387eedc6-12e9-3b32-9881-63b6b5e85317
* c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180

Невалидные ключи:

* 18252235-78e0-44a5-8720-556f0c7da17a
* e66075b6-ddad-445e-baf6-161b3289522b
* b6d53250-f07e-4352-a293-6102ddf7f1ca
* c2bc778a-1cb9-46c6-b435-0489649d2a42
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1

### Тестирование производилось в следующем окружении:
* 64 - разрядная ОС Window 7
* Java 11