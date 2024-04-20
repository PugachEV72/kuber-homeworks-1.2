# Домашнее задание к занятию `«Базовые объекты K8S»` - Пугач Евгений.


---

## `Задание 1. Создать Pod с именем hello-world`

1. Создать манифест (yaml-конфигурацию) Pod.
2. Использовать image - gcr.io/kubernetes-e2e-test-images/echoserver:2.2.
3. Подключиться локально к Pod с помощью kubectl port-forward и вывести значение (curl или в браузере).


### Ответ:

[Ссылка на манифест echoserver.yaml](https://github.com/PugachEV72/kuber-homeworks-1.2/blob/main/echoserver.yaml)

![Скриншот 1](https://github.com/PugachEV72/Images/blob/master/2024-04-20_21-00-59.png)

![Скриншот 2](https://github.com/PugachEV72/Images/blob/master/2024-04-20_21-08-42.png)

---

## `Задание 2. Создать Service и подключить его к Pod`

1. Создать Pod с именем netology-web.
2. Использовать image — gcr.io/kubernetes-e2e-test-images/echoserver:2.2.
3. Создать Service с именем netology-svc и подключить к netology-web.
4. Подключиться локально к Service с помощью kubectl port-forward и вывести значение (curl или в браузере).

### Ответ:

[Ссылка на манифест netology-web.yaml](https://github.com/PugachEV72/kuber-homeworks-1.2/blob/main/netology-web.yaml)

[Ссылка на манифест netology-svc.yaml](https://github.com/PugachEV72/kuber-homeworks-1.2/blob/main/netology-svc.yaml)

![Скриншот 3](https://github.com/PugachEV72/Images/blob/master/2024-04-20_21-42-31.png)

![Скриншот 4](https://github.com/PugachEV72/Images/blob/master/2024-04-20_21-38-01.png)

![Скриншот 5](https://github.com/PugachEV72/Images/blob/master/2024-04-20_22-22-33.png)

---
