# Домашнее задание к занятию «Helm»


### Задание 1. Подготовить Helm-чарт для приложения

1. Необходимо упаковать приложение в чарт для деплоя в разные окружения. 
2. Каждый компонент приложения деплоится отдельным deployment’ом или statefulset’ом.
3. В переменных чарта измените образ приложения для изменения версии.

![IMG](https://github.com/SeNike/Study_24/blob/main/k8s/2.5/2.5.1.png)
![IMG](https://github.com/SeNike/Study_24/blob/main/k8s/2.5/2.5.2.png)
![IMG](https://github.com/SeNike/Study_24/blob/main/k8s/2.5/2.5.3.png)
![IMG](https://github.com/SeNike/Study_24/blob/main/k8s/2.5/2.5.4.png)
------
### Задание 2. Запустить две версии в разных неймспейсах

1. Подготовив чарт, необходимо его проверить. Запуститe несколько копий приложения.
2. Одну версию в namespace=app1, вторую версию в том же неймспейсе, третью версию в namespace=app2.
3. Продемонстрируйте результат.

![IMG](https://github.com/SeNike/Study_24/blob/main/k8s/2.5/2.5.5.png)
![IMG](https://github.com/SeNike/Study_24/blob/main/k8s/2.5/2.5.6.png)

### Правила приёма работы

1. Домашняя работа оформляется в своём Git репозитории в файле README.md. Выполненное домашнее задание пришлите ссылкой на .md-файл в вашем репозитории.
2. Файл README.md должен содержать скриншоты вывода необходимых команд `kubectl`, `helm`, а также скриншоты результатов.
3. Репозиторий должен содержать тексты манифестов или ссылки на них в файле README.md.

