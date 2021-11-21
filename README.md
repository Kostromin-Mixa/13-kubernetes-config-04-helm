# 13.4 инструменты для упрощения написания конфигурационных файлов. Helm и Jsonnet   
Задание 1:  
Упаковать приложение в чарт для деплоя в разные окружения.   
- каждый компонент приложения деплоится отдельным deployment’ом/statefulset’ом    
[out_1.1.yaml](https://github.com/Kostromin-Mixa/13-kubernetes-config-04-helm/blob/main/out_1.1.yaml)   
- в переменных чарта измененный образ приложения для изменения версии.   
[out_1.2.yaml](https://github.com/Kostromin-Mixa/13-kubernetes-config-04-helm/blob/main/out_1.2.yaml)   
Задание 2: запустить 2 версии в разных неймспейсах:   
- одну версию в namespace=app1   
![v 1](https://user-images.githubusercontent.com/78191008/142755643-fa82e517-37aa-426e-b42d-c59382d5ed24.png)   

- вторую версию в том же неймспейсе   
![v 2](https://user-images.githubusercontent.com/78191008/142755659-24077986-117d-4755-8163-15d683e0ed6b.png)    

- третью версию в namespace=app2 
![v 3](https://user-images.githubusercontent.com/78191008/142755664-392705cc-c690-4420-ad34-357ba7f186cf.png)
