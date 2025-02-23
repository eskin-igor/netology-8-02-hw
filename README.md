## Решение на ДЗ "8.2 Что такое DevOps. СI/СD" - Еськин Игорь

### Задание 1
Что нужно сделать:

1. Установите себе jenkins по инструкции из лекции или любым другим способом из официальной документации. Использовать Docker в этом задании нежелательно.
2. Установите на машину с jenkins golang.
3. Используя свой аккаунт на GitHub, сделайте себе форк репозитория. В этом же репозитории находится дополнительный материал для выполнения ДЗ.
4. Создайте в jenkins Freestyle Project, подключите получившийся репозиторий к нему и произведите запуск тестов и сборку проекта go test . и docker build ..
В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

## Ответ:

1. Установите себе jenkins по инструкции из лекции или любым другим способом из официальной документации. Использовать Docker в этом задании нежелательно.
2. Установите на машину с jenkins golang.
3. Используя свой аккаунт на GitHub, сделайте себе форк репозитория. В этом же репозитории находится дополнительный материал для выполнения ДЗ.
4. Создайте в jenkins Freestyle Project, подключите получившийся репозиторий к нему и произведите запуск тестов и сборку проекта go test . и docker build ..

![](https://github.com/eskin-igor/netology-8-02-hw/blob/main/screenshots_8-02/1-1-1.png)

![](https://github.com/eskin-igor/netology-8-02-hw/blob/main/screenshots_8-02/1-1-2.png)

![](https://github.com/eskin-igor/netology-8-02-hw/blob/main/screenshots_8-02/1-2-1.png)

![](https://github.com/eskin-igor/netology-8-02-hw/blob/main/screenshots_8-02/1-3.png)

![](https://github.com/eskin-igor/netology-8-02-hw/blob/main/screenshots_8-02/1-4-1.png)

![](https://github.com/eskin-igor/netology-8-02-hw/blob/main/screenshots_8-02/1-4-2.png)

![](https://github.com/eskin-igor/netology-8-02-hw/blob/main/screenshots_8-02/1-4-3.png)

### Задание 2

Что нужно сделать:

1. Создайте новый проект pipeline.
2. Перепишите сборку из задания 1 на declarative в виде кода.
В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

## Ответ:

1. Создайте новый проект pipeline.
2. Перепишите сборку из задания 1 на declarative в виде кода.

![](https://github.com/eskin-igor/netology-8-02-hw/blob/main/screenshots_8-02/2-1.png)

![](https://github.com/eskin-igor/netology-8-02-hw/blob/main/screenshots_8-02/2-2.png)

![](https://github.com/eskin-igor/netology-8-02-hw/blob/main/screenshots_8-02/2-3.png)

![](https://github.com/eskin-igor/netology-8-02-hw/blob/main/screenshots_8-02/2-4.png)

### Задание 3

Что нужно сделать:

1. Установите на машину Nexus.
2. Создайте raw-hosted репозиторий.
3. Измените pipeline так, чтобы вместо Docker-образа собирался бинарный go-файл. Команду можно скопировать из Dockerfile.
4. Загрузите файл в репозиторий с помощью jenkins.
В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

## Ответ:

1. Установите на машину Nexus.
2. Создайте raw-hosted репозиторий.
3. Измените pipeline так, чтобы вместо Docker-образа собирался бинарный go-файл. Команду можно скопировать из Dockerfile.
4. Загрузите файл в репозиторий с помощью jenkins.

![](https://github.com/eskin-igor/netology-8-02-hw/blob/main/screenshots_8-02/3-1.png)

![](https://github.com/eskin-igor/netology-8-02-hw/blob/main/screenshots_8-02/3-2.png)

![](https://github.com/eskin-igor/netology-8-02-hw/blob/main/screenshots_8-02/3-3.png)

![](https://github.com/eskin-igor/netology-8-02-hw/blob/main/screenshots_8-02/3-4-1.png)

![](https://github.com/eskin-igor/netology-8-02-hw/blob/main/screenshots_8-02/3-4-2.png)

![](https://github.com/eskin-igor/netology-8-02-hw/blob/main/screenshots_8-02/3-4-3.png)

![](https://github.com/eskin-igor/netology-8-02-hw/blob/main/screenshots_8-02/3-4-4.png)
