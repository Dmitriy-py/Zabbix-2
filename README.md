# Домашнее задание к занятию «Система мониторинга Zabbix. Часть 2»

# Климов Дмитрий

## Задание 1

Создайте свой шаблон, в котором будут элементы данных, мониторящие загрузку CPU и RAM хоста.

Процесс выполнения

1. Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.
2. В веб-интерфейсе Zabbix Servera в разделе Templates создайте новый шаблон
3. Создайте Item который будет собирать информацию об загрузке CPU в процентах
4. Создайте Item который будет собирать информацию об загрузке RAM в процентах

## Ответ:

![Снимок экрана (983)](https://github.com/user-attachments/assets/817dcf23-e9d2-4069-ad1a-cc2036b6e805)

![Снимок экрана (984)](https://github.com/user-attachments/assets/a21881b9-e776-44a2-b895-ad3af128e30a)

![Снимок экрана (985)](https://github.com/user-attachments/assets/7c0681b0-f5f9-43e6-8642-c1210fc51eed)

![Снимок экрана (986)](https://github.com/user-attachments/assets/024fc40b-695c-44af-9a48-26c08075d44d)

![Снимок экрана (988)](https://github.com/user-attachments/assets/9aa2fdd4-285e-41db-bd9f-c2467ced5c23)

![Снимок экрана (989)](https://github.com/user-attachments/assets/45695bd5-6a03-40be-99e8-fc481bd3b7c7)


## Задание 2

Добавьте в Zabbix два хоста и задайте им имена <фамилия и инициалы-1> и <фамилия и инициалы-2>. Например: ivanovii-1 и ivanovii-2.

Процесс выполнения

1. Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.
2. Установите Zabbix Agent на 2 виртмашины, одной из них может быть ваш Zabbix Server
3. Добавьте Zabbix Server в список разрешенных серверов ваших Zabbix Agentов
4. Добавьте Zabbix Agentов в раздел Configuration > Hosts вашего Zabbix Servera
5. Прикрепите за каждым хостом шаблон Linux by Zabbix Agent
6. Проверьте что в разделе Latest Data начали появляться данные с добавленных агентов

Результат данного задания сдавайте вместе с заданием 3

## Задание 3

Привяжите созданный шаблон к двум хостам. Также привяжите к обоим хостам шаблон Linux by Zabbix Agent.

1. Процесс выполнения
2. Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.
3. Зайдите в настройки каждого хоста и в разделе Templates прикрепите к этому хосту ваш шаблон
4. Так же к каждому хосту привяжите шаблон Linux by Zabbix Agent
5. Проверьте что в раздел Latest Data начали поступать необходимые данные из вашего шаблона

![Снимок экрана (998)](https://github.com/user-attachments/assets/a1460c90-e135-4001-9b53-e8d5e1fd69cf)

![Снимок экрана (990)](https://github.com/user-attachments/assets/bd7b0868-7cc9-4374-b02b-1df34d0c4814)

![Снимок экрана (991)](https://github.com/user-attachments/assets/36d21906-aa76-4ca1-8b4d-7a8b0d7453df)

![Снимок экрана (994)](https://github.com/user-attachments/assets/fd3e4090-98eb-48d9-b36f-435458cb5cc3)

![Снимок экрана (995)](https://github.com/user-attachments/assets/e052839b-f80a-47a5-a2b9-17ab953d142f)






