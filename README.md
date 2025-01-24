# Code typing speedtest.

### Общая задумка



Программа должна из себя представлять веб-сайт, на котором можно практиковаться в скорости написания програм, функций, и напоминать написание простых, рутинных задач.
В программе должно быть огромное количество решенных задач, решение которых будет перевводить пользователь
Сайт должен помогать в обучении алгоритмам, а также ускорять написание кода.
К каждой задаче должно быть описание самой задачи, а так же пояснение к решению.

---

## Содержание 

1. Функционал к реализации 
2. Описание реализованного функционала
3. Информация для участников проекта 

## Функционал проекта 
- [ ] Научить програму выводить текст, который затем пользователь введет, с постоянной проверкой на совпадения
- [ ] Таймер, кол-во введенных символов в минуту
- [ ] Подсветка синтаксиса
- [ ] Список базовых задач
- [ ] Список задач, с максимально оптимальным решением, взятые с LeetCode / CodeWars,
- [ ] Разделение задач на уровни сложности
- [ ] Возможность пользователю писать свои задачи, на которых можно будет практиковаться


---

## Реализованный функционал 

Ничего пока что не реализованно

---
## Инфа для контрибъютеров.

- Не пул реквестить в мейн
- Не комитить изменения развернутого описания
  решенной проблемы.
- Не пулреквестить без уважения


---

## Использованные технологии

- В разработке данного проекта учавствуют 2 языка: Golang, Javascript. 
  Go (backend) - выбран по причине хорошей оптимизации програм,
  также в следствии того, что язык изначально создавался для взаимодействия с сайтами, в нем есть множество библиотек способных помочь разработке и сделать ее более удобной.
  JavaScript(Frontend) - Является одним из трех языков, на которых разрабатывается frontend, выбран по причине потому что я не обладаю знаниями других языков в этой сфере

- Базы данных
  PostgreSql - Будет использоваться, как хранилище задач (Возможно что-то еще).
  Redis - Будет использоваться для хранения пользовательских данных, предполагается что скорость передачи данных поможет в оптимизации. 

 - Фреймворки

 - 

 - Для разработки используется Visual Studio Code, поскольку в нем поддерживается все, что нам нужно и он достаточно удобен.

# Для участников проекта

- Для лучшего взаимодействия между разработчиками пишите документацию к функциям
- Модель распределения веток **Git flow**
- git merge в main запрещен, допущен из ветки dev
- Новые фичи закидывать в test
- Для эксперементальных фич используется ветка experemental
- Шестое и последнее правило - Новичёк положит прод
