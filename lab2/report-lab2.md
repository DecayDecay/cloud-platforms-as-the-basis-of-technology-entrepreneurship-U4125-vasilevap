University: ITMO University (https://itmo.ru/ru/) Faculty: FTMI

Course: Cloud Platforms as the basis of technology entrepreneurship Year: 2025/2026

Group: U4125

Author: Vasilev Anton

Lab: Lab1

Date of create: 05.05.2026

# Лабораторная работа №2

# Исследование Cloud Run


- Приступаем к созданию инстанса с demo сервисом hello. 
<img width="2177" height="1271" alt="Screenshot_7" src="https://github.com/user-attachments/assets/d26e3a2f-2252-482c-8eff-97429c2025cb" />

- Проверил что сервис корректно запущен по URL. 

<img width="2316" height="1249" alt="Screenshot_1" src="https://github.com/user-attachments/assets/33cfa05b-c7be-4a9e-aa8c-bf039d658a06" />

- Проверил метрики и логи. Тут мы можем видеть кол-во реквестов / нагрузку и задержки. 
В логах тоже все чисто, логируются подключения и браузер с которого законнектился.

<img width="2273" height="1067" alt="Screenshot_2" src="https://github.com/user-attachments/assets/13345d0c-7ca8-4a1f-be08-af05dd79df63" />

Дальше поменял в конфиге YAML порт на 8090. Создалась вторая ревизия. 

<img width="1650" height="1002" alt="Screenshot_3" src="https://github.com/user-attachments/assets/4512be11-a6c4-4122-a43a-ab41cce766b1" />

Следующим шагом провел распределение трафика по разным ревизиям и расписал проценты по трафику. 
<img width="2334" height="1221" alt="Screenshot_4" src="https://github.com/user-attachments/assets/39cff643-4fcc-4004-a221-029cd0c6b0b6" />

Последним шагом удалил за собой все сервисы Cloud Run. 

<img width="1972" height="957" alt="Screenshot_5" src="https://github.com/user-attachments/assets/357fca12-497c-4eb3-a169-bb9808d4699a" />

