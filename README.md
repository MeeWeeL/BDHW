# DB_Homework

Для работы с БД была использована MySQL

Всего 4 БД:

vehicles (Транспортные средства)
![image](https://github.com/user-attachments/assets/42800656-cabd-4caf-b9f6-5b0958063113)

racing (Автомобильные гонки)
![image](https://github.com/user-attachments/assets/d1aef9ba-a176-4050-9f52-1b9680f26981)

hotels (Бронирование отелей)
![image](https://github.com/user-attachments/assets/cc59335e-0825-475e-ae61-7d2985429592)

departments (Структура организации)
![image](https://github.com/user-attachments/assets/6e857e08-46a5-4f76-bc01-670942cf2817)


В репозитории для каждой БД своя папка. В каждой папке три файла:
1) Скрипт создания
2) Скрипт заполнения
3) Скрипт выполнения задач (С описанием самих задач)

Структура репозитория

├── vehicles/          # 1. Транспортные средства
│   ├── create_script  # Скрипт для создания таблиц
│   ├── fill_script    # Скрипт для заполнения таблиц тестовыми данными
│   └── tasks          # Описание задач и запросы для их решения
│
├── racing/            # 2. Автомобильные гонки
│   ├── create_script
│   ├── fill_script
│   └── tasks
│
├── hotels/            # 3. Бронирование отелей
│   ├── create_script
│   ├── fill_script
│   └── tasks
│
└── departments/       # 4. Структура организации
    ├── create_script
    ├── fill_script
    └── tasks

Все SQL-запросы готовы к непосредственному выполнению
Выполняйте скрипты в указанном порядке: create_script → fill_script → tasks
