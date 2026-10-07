---
marp: true
theme: default
paginate: true
footer: 'Лабораторная работа №6 · НПИбд-03-25, Чжу Ино'
style: |
  section {
    font-family: "Times New Roman", serif;
    font-size: 24px;
    padding: 50px 70px;
    line-height: 1.5;
    color: #1a1a1a;
  }
  h1 {
    font-size: 38px;
    color: #003366;
    border-bottom: 3px solid #003366;
    padding-bottom: 10px;
    margin-bottom: 20px;
  }
  h2 {
    font-size: 30px;
    color: #003366;
    margin-bottom: 15px;
  }
  ul {
    margin-top: 10px;
  }
  li {
    margin-bottom: 8px;
  }
  section.lead {
    text-align: center;
    justify-content: center;
  }
  section.lead h1 {
    border: none;
    font-size: 46px;
    margin-bottom: 40px;
  }
  section.lead p {
    font-size: 26px;
    margin: 6px 0;
  }
  section.chapter {
    text-align: center;
    justify-content: center;
    background: #f4f7fb;
  }
  section.chapter h1 {
    border: none;
    font-size: 44px;
  }
  footer {
    font-size: 14px;
    color: #666;
  }
---

<!-- _class: lead -->

# Лабораторная работа №6. Основы работы с файловой системой Linux

НПИбд-03-25, Чжу Ино

---

# Содержание

1. Титульный слайд
2. Введение
3. Определение домашнего каталога
4. Работа с каталогом /tmp
5. Создание и удаление каталогов
6. История команд
7. Выполнение нескольких команд в одной строке
8. Заключение
9. Список литературы

---

<!-- _class: chapter -->

# 1. Титульный слайд

---

- Лабораторная работа №6
- Основы работы с файловой системой Linux
- НПИбд-03-25
- Чжу Ино

---

<!-- _class: chapter -->

# 2. Введение

---

- Изучение основных команд файловой системы Linux
- Работа с каталогами и историей команд
- Выполнение нескольких команд в одной строке

---

<!-- _class: chapter -->

# 3. Определение домашнего каталога

---

- Команда: `pwd`
- Результат: `/home/cedar`

---

<!-- _class: chapter -->

# 4. Работа с каталогом /tmp

---

- Переход в каталог: `cd /tmp`
- Просмотр содержимого: `ls`, `ls -l`, `ls -a`, `ls -la`
- Просмотр прав и владельцев файлов

---

<!-- _class: chapter -->

# 5. Создание и удаление каталогов

---

- Создание каталога: `mkdir ~/newdir`
- Создание вложенного каталога: `mkdir ~/newdir/morefun`
- Удаление пустого каталога: `rmdir ~/newdir/morefun`
- Удаление каталога: `rmdir ~/newdir`

---

<!-- _class: chapter -->

# 6. История команд

---

- Команда: `history`
- Просмотр последних выполненных команд

---

<!-- _class: chapter -->

# 7. Выполнение нескольких команд в одной строке

---

- Пример: `cd /tmp && ls && cd ~`
- Оператор `&&` — выполнение следующей команды только при успехе предыдущей

---

<!-- _class: chapter -->

# 8. Заключение

---

- Изучены команды `cd`, `pwd`, `ls`, `mkdir`, `rmdir`, `rm`
- Освоены операции с каталогами
- Изучены история команд и выполнение нескольких команд в одной строке

---

<!-- _class: chapter -->

# 9. Список литературы

---

1. Neil N. J. Learning CentOS: A Beginners Guide to Learning Linux. — CreateSpace Independent Publishing Platform, 2016.
2. Vugt S. van. Red Hat RHCSA/RHCE 7 cert guide. — Pearson IT Certification, 2016.
3. Unix и Linux: руководство системного администратора / Э. Немет и др. — 5-е изд. — СПб. : ООО «Диалектика», 2020.