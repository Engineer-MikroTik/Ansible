#
Готовые шаблона на все случаи жизни
#
Запуск:

ansible-playbook -i hosts install.yml -u ansible --ask-pass

Здесь:

Install_Nginx/hosts это файл inventory, -l ограничивает запуск хостом 10.254.251.100,
а install.yml это наш плейбук.
#
Обычная проверка:

С запросом пароля (просит поставить apt install sshpass)

ansible -i hosts all -m ping -u ansible --ask-pass

ansible -i Install_Nginx/hosts all -a "df -h" -u username --ask-pass

### git fetch && git pull
