### Лабораторная работа №4
#  1. Создание приложения и его запуск, создание контейнеров:
Создаю папки в которые помещу Dockerfile
![image](https://github.com/user-attachments/assets/2f9224e3-3102-4671-8c6a-52fd76515b5c)

В каждом файле пишу команды для указания операционной системы(первая строка), обновления пакетного менеджера, устанавливания aafire и ping.
![image](https://github.com/user-attachments/assets/8f4297e3-271b-4c87-bddb-044846aff750)

Прописываю команды, которые собирают образ с тегом aafire.
![image](https://github.com/user-attachments/assets/f11a80e9-e960-4c03-98df-fe0b5d1bc689)

Тестирую программы(прикладываю одну фотографию огня, так как не увидел смысла два раза показывать одно и то же изображение😉).


![image](https://github.com/user-attachments/assets/538513dc-8062-419c-8e4b-d3b7c12afd16)
![image](https://github.com/user-attachments/assets/342abd15-0b58-4faa-9ef3-879a20fe8a41)
![image](https://github.com/user-attachments/assets/aa2182d8-7bff-4bc5-88b4-34444968490c)<td><td>


#  2. Создание сети между контейнерами:
На данном этапе стал работать с terminator.
Создаю сеть, подключаю контейнеры к ней
![image](https://github.com/user-attachments/assets/683622ca-6563-411e-a029-05370ebd14cb)


Смотрю настройки созданной системы, в ней смотрю IPv4 контейнеров

![image](https://github.com/user-attachments/assets/d1ec8f43-3538-4028-a932-a76ecd5d57da)

Далее проверяю связь между контейнерами, она в обоих случаях произведена успешна, так как кол-во потери пакетов равно 0.

![image](https://github.com/user-attachments/assets/e557aeb0-8254-4983-9bd1-87aa59b12c03)
![image](https://github.com/user-attachments/assets/f51017c1-6607-4615-bd4c-c0cf3fa7fb3f)







