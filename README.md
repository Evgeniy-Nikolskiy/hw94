# HOMEWORK 9.4

Изначально условия ДЗ противоречат, что было выяснено в ходе лекции. Окончательные требования:
Создать [Jenkinsfile](https://github.com/Evgeniy-Nikolskiy/hw85/blob/main/roles/elastic_role/Jenkinsfile) 
который с помощью molecule test проверяет любую роль на свое усмотрене:[elstic_role](https://github.com/Evgeniy-Nikolskiy/hw85/tree/main/roles/elastic_role). 

А также создать [ScriptedJenkinsFile](https://github.com/Evgeniy-Nikolskiy/hw85/blob/main/ScriptedJenkinsFile)
который будет запускать [playbook](https://github.com/Evgeniy-Nikolskiy/hw85) и собирать весь стек ролей из предыдущиего ДЗ с ролями

Для решения задачи с --check --diff я выбрал параметризированную сборку присвоил имя prod_run 
и в stage описал условия 
![pic1](https://raw.githubusercontent.com/Evgeniy-Nikolskiy/hw94/master/assets/941.jpg)