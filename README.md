Проверял на ubuntu-server-22.04.4

1. Склонировать репозиторий git clone https://github.com/NomokonovD/NSFW.git -b docker

2. Добавить своего пользователя к группу docker sudo usermod -aG docker <username>

3. Сбилдить 3 образа: 

docker build -t bot_image .

docker build -t db_image .

docker build -t db_repl_image .

4. Запустить контейнер командой docker compose up -d
