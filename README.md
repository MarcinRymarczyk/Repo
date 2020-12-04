

Projekt polegał na stworzeniu serwerów : PHP, APACHE, MySQL

Projekt trzeba w pierwszej kolejności zbudować następującą komendą:
    sudo docker-compose build

Następnie uruchamiamy za pomocą następującej komendy:
    sudo docker-compose up

Za pomocą następującej komendy jesteśmy w stanie sprawdzić działanie skryptu index.php :
    curl localhost:6666

Następująca komenda jest komendą która wyświetli zawartość naszego pliku index.html:
    curl localhost:6666/index.html

