## OOP_5_DZ_26.02.24.

Урок 5. От простого к практике

— Создать класс УчебнаяГруппа, содержащий в себе поля Преподаватель и список Студентов;

— Создать класс УчебнаяГруппаСервис, в котором реализована функция (входные параметры - (Teacher, List<Strudent>)) формирования из Студентов и Преподавателя УчебнойГруппы и возвращения его;

— Создать метод в Контроллере, в котором агрегируются функции получения списка студентов (их id) и преподавателя (его id) и формирования учебной группы, путём вызова метода из сервиса;

— Всё вышеуказанное создать согласно принципам ООП, пройдённым на семинаре.

Формат сдачи: ссылка на гитхаб проект

## Model

https://github.com/Nikolai-Nemkov/OOP_5_DZ_26.02.24./blob/main/Model/Student.java

https://github.com/Nikolai-Nemkov/OOP_5_DZ_26.02.24./blob/main/Model/Teacher.java

https://github.com/Nikolai-Nemkov/OOP_5_DZ_26.02.24./blob/main/Model/User.java

https://github.com/Nikolai-Nemkov/OOP_5_DZ_26.02.24./blob/main/Model/StudentGroup.java

## Service

https://github.com/Nikolai-Nemkov/OOP_5_DZ_26.02.24./blob/main/Service/DataService.java

https://github.com/Nikolai-Nemkov/OOP_5_DZ_26.02.24./blob/main/Service/GroupService.java

https://github.com/Nikolai-Nemkov/OOP_5_DZ_26.02.24./blob/main/Service/UserService.java


## Controller

https://github.com/Nikolai-Nemkov/OOP_5_DZ_26.02.24./blob/main/Controller/Controller.java

## View

https://github.com/Nikolai-Nemkov/OOP_5_DZ_26.02.24./blob/main/View/StudentView.java

## Main

https://github.com/Nikolai-Nemkov/OOP_5_DZ_26.02.24./blob/main/Main.java

## Result

Студенческая группа номер - 1, преподаватель в группе - Учитель: ID - '3', Имя - 'Наталья', Фамилия - 'Иванова', Год рождения - 35, стурднты в группе - [Студент: ID - '1', Имя - 'Иван', Фамилия - 'Иванов', Год рождения - 15, Студент: ID - '1', Имя - 'Ольга', Фамилия - 'Петрова', Год рождения - 16, Студент: ID - '1', Имя - 'Алексей', Фамилия - 'Сидоров', Год рождения - 14]

Студенческая группа номер - 2, преподаватель в группе - Учитель: ID - '7', Имя - 'Андрей', Фамилия - 'Петров', Год рождения - 40, стурднты в группе - [Студент: ID - '4', Имя - 'Екатерина', Фамилия - 'Михайлова', Год рождения - 16, Студент: ID - '4', Имя - 'Павел', Фамилия - 'Николаев', Год рождения - 17, Студент: ID - '4', Имя - 'Мария', Фамилия - 'Сергеева', Год рождения - 15]







