# Домашнее задание к занятию "Система мониторинга Zabbix. Часть 2" - `Щербатых А.Е.`
## Задание 1
Создайте свой шаблон, в котором будут элементы данных, мониторящие загрузку CPU и RAM хоста.
1. Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.
2. В веб-интерфейсе Zabbix Servera в разделе Templates создайте новый шаблон
    ![alt text](https://github.com/Anton-Shcherbatykh/FOPS-32_5/blob/main/images/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5_1_1.jpg)
    ![alt text](https://github.com/Anton-Shcherbatykh/FOPS-32_5/blob/main/images/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5_1_2.jpg)
   
3. Создайте Item который будет собирать информацию об загрузке CPU в процентах
   ![alt text](https://github.com/Anton-Shcherbatykh/FOPS-32_5/blob/main/images/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5_1_3.jpg)
   ![alt text](https://github.com/Anton-Shcherbatykh/FOPS-32_5/blob/main/images/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5_1_4.jpg)
5. Создайте Item который будет собирать информацию об загрузке RAM в процентах
![alt text](https://github.com/Anton-Shcherbatykh/FOPS-32_5/blob/main/images/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5_1_3.jpg)
![alt text](https://github.com/Anton-Shcherbatykh/FOPS-32_5/blob/main/images/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5_1_5.jpg)
## Задание 2
Добавьте в Zabbix два хоста и задайте им имена <фамилия и инициалы-1> и <фамилия и инициалы-2>. Например: ivanovii-1 и ivanovii-2.

*данное задание перекликается с заданием из первой части темы по Zabbix, поэтому скрины с созданием ВМ и установкой на них Zabbix-агентов, а также с добавлением их в раздел Configuration > Hosts моего Zabbix Servera в данном задании не прикреплял, т.к. данные работы по этим ВМ были уже проведены ранее*

1. Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.
2. Установите Zabbix Agent на 2 виртмашины, одной из них может быть ваш Zabbix Server
3. Добавьте Zabbix Server в список разрешенных серверов ваших Zabbix Agentов
4. Добавьте Zabbix Agentов в раздел Configuration > Hosts вашего Zabbix Servera
5. Прикрепите за каждым хостом шаблон Linux by Zabbix Agent
 ![alt text](https://github.com/Anton-Shcherbatykh/FOPS-32_5/blob/main/images/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5_2_1.jpg)
6. Проверьте что в разделе Latest Data начали появляться данные с добавленных агентов
 ![alt text](https://github.com/Anton-Shcherbatykh/FOPS-32_5/blob/main/images/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5_2_2.jpg)
  ![alt text](https://github.com/Anton-Shcherbatykh/FOPS-32_5/blob/main/images/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5_2_3.jpg)
   ![alt text](https://github.com/Anton-Shcherbatykh/FOPS-32_5/blob/main/images/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5_2_4.jpg)

## Задание 3
Привяжите созданный шаблон к двум хостам. Также привяжите к обоим хостам шаблон Linux by Zabbix Agent.

1. Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.
2. Зайдите в настройки каждого хоста и в разделе Templates прикрепите к этому хосту ваш шаблон
3. Так же к каждому хосту привяжите шаблон Linux by Zabbix Agent
    ![alt text](https://github.com/Anton-Shcherbatykh/FOPS-32_5/blob/main/images/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5_3_1.jpg)
4. Проверьте что в раздел Latest Data начали поступать необходимые данные из вашего шаблона
   ![alt text](https://github.com/Anton-Shcherbatykh/FOPS-32_5/blob/main/images/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5_3_2.jpg)

## Задание 4
Создайте свой кастомный дашборд.

1. Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.
2. В разделе Dashboards создайте новый дашборд
3. Разместите на нём несколько графиков на ваше усмотрение.
    ![alt text](https://github.com/Anton-Shcherbatykh/FOPS-32_5/blob/main/images/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5_4_1.jpg)
   

