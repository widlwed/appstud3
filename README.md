# Лабораторная работа №3. Работа с базой данных в Android

**Выполнила:** Панфилова Евгения ИСП-212

**Язык приложения:** Java, используется Android SDK.

---

## Цель работы
Изучить работу Android-приложения с базой данных, используя SQLite. В ходе выполнения работы будет создано приложение, которое будет:

1. Создавать базу данных и таблицу при первом запуске.
2. Вносить данные в таблицу и отображать их.
3. Обновлять записи в таблице.

---

## Структура и внешний вид приложения
### 1. Класс DBHelper ###

Отвечает за создание и управление базой данных. В нем реализованы методы для:
- создания базы данных и таблицы;
- добавления новой записи;
- обновления последней записи;
- извлечения всех данных.
  
### 2. MainActivity ###
Главное активити приложения. Содержит три кнопки для взаимодействия с базой данных:

- Показать записи.
- Добавить запись.
- Обновить запись.

### 3. ShowRecordsActivity ###
Активити для отображения всех записей из таблицы «Одногруппники». Извлекает данные из базы и отображает их в формате: «ID, ФИО, Время добавления».
