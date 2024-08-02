# Домашнее задание к занятию «Базовые объекты K8S» - Подус Сергей

### Задание 1. Создать Pod с именем hello-world

1. Создать манифест (yaml-конфигурацию) Pod.
2. Использовать image - gcr.io/kubernetes-e2e-test-images/echoserver:2.2.
3. Подключиться локально к Pod с помощью `kubectl port-forward` и вывести значение (curl или в браузере).

------

### Задание 2. Создать Service и подключить его к Pod

1. Создать Pod с именем netology-web.
2. Использовать image — gcr.io/kubernetes-e2e-test-images/echoserver:2.2.
3. Создать Service с именем netology-svc и подключить к netology-web.
4. Подключиться локально к Service с помощью `kubectl port-forward` и вывести значение (curl или в браузере).

## Ответ:

1. Манифест находится в папке src

![Scrinshot 1](https://github.com/Wanderwille/scrinshot/blob/scrin2/kube_2/pod1.png)

![Scrinshot 2](https://github.com/Wanderwille/scrinshot/blob/scrin2/kube_2/pod1-2.png)

![Scrinshot 3](https://github.com/Wanderwille/scrinshot/blob/scrin2/kube_2/pod1-3.png)

2. Манифест находится в папке src

![Scrinshot 4](https://github.com/Wanderwille/scrinshot/blob/scrin2/kube_2/pod2.png)

![Scrinshot 5](https://github.com/Wanderwille/scrinshot/blob/scrin2/kube_2/pod3.png)

![Scrinshot 6](https://github.com/Wanderwille/scrinshot/blob/scrin2/kube_2/pod3-1.png)

