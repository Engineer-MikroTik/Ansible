#
Готовые шаблона на все случаи жизни
#
Запуск:

ansible-playbook -i Install_Nginx/hosts -l 10.254.251.100 Install_Nginx/install.yml


ЗдесьInstall_Nginx/hosts это файл inventory, -l ограничивает запуск хостом 10.254.251.100,
а install.yml это наш плейбук.
#
