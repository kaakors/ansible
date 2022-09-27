# Самоконтроль выполненения задания

1. Где расположен файл с `some_fact` из второго пункта задания?  
		_/group_vars/all/examp.yml_
2. Какая команда нужна для запуска вашего `playbook` на окружении `test.yml`?
		_ansible-playbook -i inventory/test.yml site.yml_
3. Какой командой можно зашифровать файл?
		_ansible-vault encrypt file.yml_
4. Какой командой можно расшифровать файл?
		_ansible-vault decrypt file.yml_
5. Можно ли посмотреть содержимое зашифрованного файла без команды расшифровки файла? Если можно, то как?
		_ansible-vault view file.yml_
6. Как выглядит команда запуска `playbook`, если переменные зашифрованы?
		_ansible-playbook -i inventory/prod.yml site.yml --ask-vault-pass_
7. Как называется модуль подключения к host на windows?
		_winrm_
8. Приведите полный текст команды для поиска информации в документации ansible для модуля подключений ssh
		_ansible-doc -t connection ssh_
9. Какой параметр из модуля подключения `ssh` необходим для того, чтобы определить пользователя, под которым необходимо совершать подключение?
		_remote_user_
