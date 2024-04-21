pod - элемент kubernetes, 
абстрация над контейнером, 
имеют свои ip,
минимальная единица развертки

container - docker conteiner

service - обеспечивает постоянный доступ к контейнеру

NodePort - дополнительный доступ из вне  

Node - виртуальная машина или сервер  

Master Node: 
- Api Server слушает запросы к себе вызывает cubectl, авторизация
- Scheduler планирует что размещать на нодах, дает задания другим нодам
- Controller Manager, под упал его нужно переподнять, перераспределение нод, если какая-то вышла из строя
- ETCD key-value storage

Node:
- Pod
- Kubelet

Node:
- Pod
- Kubelet

Императивный подход - что нужно сделать 

kubectl run nginx --image=nginx --restart=Never


Декларативный подход - какой должен быть результат?


# kubernetes-lessons
