# Домашнее задание к занятию "DevOps_Bondarev" - Бондарев Олег Николаевич


### Инструкция по выполнению домашнего задания

   1. Сделайте `fork` данного репозитория к себе в Github и переименуйте его по названию или номеру занятия, например, https://github.com/имя-вашего-репозитория/git-hw или  https://github.com/имя-вашего-репозитория/7-1-ansible-hw).
   2. Выполните клонирование данного репозитория к себе на ПК с помощью команды `git clone`.
   3. Выполните домашнее задание и заполните у себя локально этот файл README.md:
      - впишите вверху название занятия и вашу фамилию и имя
      - в каждом задании добавьте решение в требуемом виде (текст/код/скриншоты/ссылка)
      - для корректного добавления скриншотов воспользуйтесь [инструкцией "Как вставить скриншот в шаблон с решением](https://github.com/netology-code/sys-pattern-homework/blob/main/screen-instruction.md)
      - при оформлении используйте возможности языка разметки md (коротко об этом можно посмотреть в [инструкции  по MarkDown](https://github.com/netology-code/sys-pattern-homework/blob/main/md-instruction.md))
   4. После завершения работы над домашним заданием сделайте коммит (`git commit -m "comment"`) и отправьте его на Github (`git push origin`);
   5. Для проверки домашнего задания преподавателем в личном кабинете прикрепите и отправьте ссылку на решение в виде md-файла в вашем Github.
   6. Любые вопросы по выполнению заданий спрашивайте в чате учебной группы и/или в разделе “Вопросы по заданию” в личном кабинете.
   
Желаем успехов в выполнении домашнего задания!
   
### Дополнительные материалы, которые могут быть полезны для выполнения задания

1. [Руководство по оформлению Markdown файлов](https://gist.github.com/Jekins/2bf2d0638163f1294637#Code)

---

### Задание 1

`Что нужно сделать:`

1. `Установите себе jenkins по инструкции из лекции или любым другим способом из официальной документации. Использовать Docker в этом задании нежелательно.`
2. `Установите на машину с jenkins golang.`
3. `Используя свой аккаунт на GitHub, сделайте себе форк репозитория. В этом же репозитории находится дополнительный материал для выполнения ДЗ.`
4. `Создайте в jenkins Freestyle Project, подключите получившийся репозиторий к нему и произведите запуск тестов и сборку проекта go test . и docker build ..`


При необходимости прикрепитe сюда скриншоты

![image](https://github.com/user-attachments/assets/d2346da5-b916-4c3c-b6a0-0dd40eff859c)
![image](https://github.com/user-attachments/assets/5de52de6-1a24-4074-a3c0-b6ccef2ede63)
![image](https://github.com/user-attachments/assets/223b6a5a-6b68-4613-984b-28468e07f97b)
![image](https://github.com/user-attachments/assets/96a6e150-d745-4ebe-b90b-d63027a0062c)
![image](https://github.com/user-attachments/assets/a33c1d2c-0d0c-4c81-bea5-180c17e893cc)
![image](https://github.com/user-attachments/assets/9d2b7f02-5afb-4db5-8a75-9d2923702b57)


---

### Задание 2

`Что нужно сделать:`

1. Создайте новый проект pipeline.`
2. Перепишите сборку из задания 1 на declarative в виде кода.


При необходимости прикрепитe сюда скриншоты

![image](https://github.com/user-attachments/assets/47c4e33e-c967-475c-9137-dbbbec726d12)
![image](https://github.com/user-attachments/assets/7cdaf6b4-6234-4292-ac9d-ee4a9fdb50d9)
![image](https://github.com/user-attachments/assets/14d2835b-7267-4d82-82d0-a77f39087cc8)



---

### Задание 3

Что нужно сделать:

1. Установите на машину Nexus.
2. Создайте raw-hosted репозиторий.
3. Измените pipeline так, чтобы вместо Docker-образа собирался бинарный go-файл. Команду можно скопировать из Dockerfile.
4. Загрузите файл в репозиторий с помощью jenkins.


При необходимости прикрепитe сюда скриншоты

![image](https://github.com/user-attachments/assets/0cdc3621-5b81-4f3a-af16-4412f38f54e4)
![image](https://github.com/user-attachments/assets/cc6b32c4-ff4c-4deb-9942-235d3fd2ed9b)
![image](https://github.com/user-attachments/assets/3b7e3729-e5ab-42d6-98cc-d13c8ff3a747)


