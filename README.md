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

## Ответ:

![Снимок экрана (998)](https://github.com/user-attachments/assets/a1460c90-e135-4001-9b53-e8d5e1fd69cf)

![Снимок экрана (990)](https://github.com/user-attachments/assets/bd7b0868-7cc9-4374-b02b-1df34d0c4814)

![Снимок экрана (991)](https://github.com/user-attachments/assets/36d21906-aa76-4ca1-8b4d-7a8b0d7453df)

![Снимок экрана (994)](https://github.com/user-attachments/assets/fd3e4090-98eb-48d9-b36f-435458cb5cc3)

![Снимок экрана (995)](https://github.com/user-attachments/assets/e052839b-f80a-47a5-a2b9-17ab953d142f)

## Задание 4

Создайте свой кастомный дашборд.

Процесс выполнения

1. Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.
2. В разделе Dashboards создайте новый дашборд
3. Разместите на нём несколько графиков на ваше усмотрение.

## Ответ:

![Снимок экрана (999)](https://github.com/user-attachments/assets/1f7d4624-9213-4dc2-9b79-87e14752e945)

## Задание 5* со звёздочкой


Создайте карту и расположите на ней два своих хоста.

Процесс выполнения

1. Настройте между хостами линк.
2. Привяжите к линку триггер, связанный с agent.ping одного из хостов, и установите индикатором сработавшего триггера красную пунктирную линию.
3. Выключите хост, чей триггер добавлен в линк. Дождитесь срабатывания триггера.

## Ответ:

![Снимок экрана (1004)](https://github.com/user-attachments/assets/75c0cdd1-5624-41f8-a9c6-bc1137686a73)

![Снимок экрана (1002)](https://github.com/user-attachments/assets/ff3b7034-0266-486b-8955-a2e69683395d)

![Снимок экрана (1003)](https://github.com/user-attachments/assets/a8c1b44e-1531-40c4-bedf-8910cf046bcb)

![Снимок экрана (1001)](https://github.com/user-attachments/assets/d17d6400-ddc6-467f-977c-ade60c72d24f)

## Задание 6* со звёздочкой

Создайте UserParameter на bash и прикрепите его к созданному вами ранее шаблону. Он должен вызывать скрипт, который:

при получении 1 будет возвращать ваши ФИО,
при получении 2 будет возвращать текущую дату.

## Ответ:

![Снимок экрана (1010)](https://github.com/user-attachments/assets/c32727b4-3561-4771-b857-187b31469f76)

![Снимок экрана (1009)](https://github.com/user-attachments/assets/6e8c8019-7117-4598-99cd-6ac2b280ec62)

![Снимок экрана (1008)](https://github.com/user-attachments/assets/5c492894-8d96-4d1f-b3ce-3b8dcf6e7f12)

![Снимок экрана (1007)](https://github.com/user-attachments/assets/a9855a13-8878-430a-8c16-dee9df0e1876)

![Снимок экрана (1006)](https://github.com/user-attachments/assets/0118bc40-80d8-41a9-bcab-1a76abdad162)

## Задание 7* со звёздочкой

Доработайте Python-скрипт из лекции, создайте для него UserParameter и прикрепите его к созданному вами ранее шаблону. Скрипт должен:

при получении 1 возвращать ваши ФИО,

при получении 2 возвращать текущую дату,

делать всё, что делал скрипт из лекции.


## Ответ:


```

import sys
import os
import re

def get_info(arg):
    if arg == '1':
        return "Климов Дмитрий Геннадьевич"
    elif arg == '2':
        return os.popen("date +%Y-%m-%d").read().strip()
    else:
        if arg.startswith('-ping'):
            try:
                parts = arg.split()
                address = parts[1]
                result = os.popen("ping -c 1 " + address).read()
                result = re.findall(r"time=(.*) ms", result)
                return result[0]
            except Exception as e:
                return f"Error pinging {address}: {e}"

        elif arg.startswith('-simple_print'):
            parts = arg.split()
            text = parts[1]
            return text
        else:
            return f"unknown input: {arg}"

if __name__ == "__main__":
    if len(sys.argv) > 1:
        print(get_info(sys.argv[1]))
    else:
        print("No arguments provided.  Usage: script.py <argument>"

```
![Снимок экрана (1019)](https://github.com/user-attachments/assets/5815927a-1eb6-4b97-8dcc-230f24fd974e)

![Снимок экрана (1017)](https://github.com/user-attachments/assets/37954a32-d35d-4cf7-b4ce-3fd95cfafd72)

![Снимок экрана (1016)](https://github.com/user-attachments/assets/649ca9dd-26c5-4c7a-86d9-6863e4b38404)





