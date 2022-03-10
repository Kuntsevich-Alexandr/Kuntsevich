#Как создать SSH ключ
1. Вставить в терминал ssh-keygen -t ed25519 -C "your_email@example.com"
2. нажать 3 раза ентер
3. eval "$(ssh-agent -s)" (запускаем агент)
4. $ ssh-add ~/.ssh/id_ed25519
5. открыть паблик ключ в vsc и скопировать
6. profile picture-settings-ssh and gpg keys-new ssh key
7. вставить ключ и добавить описание
#Копирование репо
1. git clone "адрес репо с url ssh вместо https"
2. нажать yes