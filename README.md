# smirnov-otus_platform
smirnov-otus Platform repository

kubernetes-intro

в kubernetes-intro/web добавил Dockerfile 
в kubernetes-intro/ добавлен манифест web-pod и исправленный манифест для frontend-pod
причины восстановления pods после удаления,написал комментарий в PR

kubernetes-controllers

созданы манифесты вида: Replicaset и Deployment
проверил сценарии обновления/откат версии используя blue-green и rollout
выполнил сценарий blue-green(Развертывание трех новых pod && Удаление трех старых pod)
                  rollout(Удаление одного старого pod && Создание одного нового pod)
выолнил Probes ( readinessProbe, livenessProbe) Daemonset и пробы добавлены в манифесты
nodeexporter-daemonset.yaml