# Containerization_1
## Контейнеризация (семинары)
### Урок 1. Механизмы пространства имен

Задание: необходимо продемонстрировать изоляцию одного и того же приложения (как решено на семинаре - командного интерпретатора) в различных пространствах имен.

Формат сдачи ДЗ: предоставить доказательства выполнения задания посредством ссылки на google-документ с правами на комментирование/редактирование.
Результатом работы будет: текст объяснения, логи выполнения, история команд и скриншоты (важно придерживаться такой последовательности).
В названии работы должны быть указаны ФИ, номер группы и номер урока.

### Создаём изолированное пространство посредствам изменения корневого каталога для запущенного процесса и всех его "дочек":
![make_chroot](https://github.com/Andymarch83/Containerization_1/assets/122732408/d4751e6b-10ad-4c52-a1f7-1f26c82219da)
![make_chroot1](https://github.com/Andymarch83/Containerization_1/assets/122732408/d364b77a-0887-4433-b4c8-123edf8153e7)


### Создаём изолирование по сети:
![make_nets](https://github.com/Andymarch83/Containerization_1/assets/122732408/10e12c8f-a8e8-482f-813b-d42c28ea3fe0)


## Изолируем одно и то же приложение (как решено на семинаре - командного интерпретатора) в различных пространствах имен и сравниваем процессы в контейнере и в операционной системе:
### Изолирование процессов в контейнере:
![compare processes inside container](https://github.com/Andymarch83/Containerization_1/assets/122732408/4a18283d-c377-4fe3-b1f9-bf5827c707a8)
![compare processes inside container1](https://github.com/Andymarch83/Containerization_1/assets/122732408/372fbaa5-6e71-4851-8186-ff99457d23a2)
![compare processes inside container2](https://github.com/Andymarch83/Containerization_1/assets/122732408/185d08c5-bb5a-4287-9f65-4537fea54952)


### Изолирование сети:
![compare processes net isolation](https://github.com/Andymarch83/Containerization_1/assets/122732408/2380e18c-6b2b-42ef-a553-9be7ca24bb2b)

Подготовил студент Столяр Андрей, Containerization_1
https://github.com/Andymarch83/Containerization_1
