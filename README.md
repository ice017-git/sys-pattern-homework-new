# Домашнее задание к занятию "`Система мониторинга Zabbix. Часть 2`" - `Леонов Алексей`

---

### Задание 1

Создайте свой шаблон, в котором будут элементы данных, мониторящие загрузку CPU и RAM хоста.

Процесс выполнения
Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.
В веб-интерфейсе Zabbix Servera в разделе Templates создал новый шаблон
![Создание_шаблона](https://github.com/ice017-git/sys-pattern-homework-new/blob/main/img/1_создание_шаблона.png)
Создал Item который будет собирать информацию об загрузке CPU в процентах
![Создание_item](https://github.com/ice017-git/sys-pattern-homework-new/blob/main/img/1_создание_item1.png)
Создал Item который будет собирать информацию об загрузке RAM в процентах
![Создание_item](https://github.com/ice017-git/sys-pattern-homework-new/blob/main/img/1_создание_item2.png)
Готовый шаблон:
![Создание_item](https://github.com/ice017-git/sys-pattern-homework-new/blob/main/img/1_готовый_шаблон.png)


---

### Задание 2 и Задание 3

Добавьте в Zabbix два хоста и задайте им имена <фамилия и инициалы-1> и <фамилия и инициалы-2>. Например: ivanovii-1 и ivanovii-2.
Привяжите созданный шаблон к двум хостам. Также привяжите к обоим хостам шаблон Linux by Zabbix Agent.

Создание 2 хостов с привязанными шаблонами:
![Создание_item](https://github.com/ice017-git/sys-pattern-homework-new/blob/main/img/2_1_host.png)
![Создание_item](https://github.com/ice017-git/sys-pattern-homework-new/blob/main/img/2_2_host.png)
![Создание_item](https://github.com/ice017-git/sys-pattern-homework-new/blob/main/img/3_hosts_templates.png)

### Задание 4

Создайте свой кастомный дашборд.
Мой дашборд:
![Создание_item](https://github.com/ice017-git/sys-pattern-homework-new/blob/main/img/dashboard.png)

### Задание 6

Создайте UserParameter на bash и прикрепите его к созданному вами ранее шаблону. Он должен вызывать скрипт, который:
при получении 1 будет возвращать ваши ФИО,
при получении 2 будет возвращать текущую дату.

**Скриншот Latest Data с Bash-скриптами:**

![код скрипта bash](https://github.com/ice017-git/sys-pattern-homework-new/blob/main/img/6_bash.png)
![latest data bash](https://github.com/ice017-git/sys-pattern-homework-new/blob/main/img/6_latest_data.png)

### Задание 7

Доработайте Python-скрипт из лекции, создайте для него UserParameter и прикрепите его к созданному вами ранее шаблону. Скрипт должен:

при получении 1 возвращать ваши ФИО,
при получении 2 возвращать текущую дату,
делать всё, что делал скрипт из лекции.

**Скриншот Latest Data с Python-скриптами:**

![код скрипта bash](https://github.com/ice017-git/sys-pattern-homework-new/blob/main/img/7_python.png)
![latest data bash](https://github.com/ice017-git/sys-pattern-homework-new/blob/main/img/7_latest_data.png)
