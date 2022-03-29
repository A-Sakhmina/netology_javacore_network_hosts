# netology_javacore_network_hosts
Working with hosts file, client-server application with 3-5 steps 
## Задача "Клиент-сервер с рюшечками"
Код по [ссылке](https://github.com/A-Sakhmina/netology_javacore_network_hosts/tree/master/src/main/java)
### Задание 
В серверной и клиентской части сделайте последовательность вызовов в рамках одной сессии таким образом, 
чтобы получился некий **диалог между клиентом и сервером**, содержащий от 3 до 5 (или больше) шагов. 

Например,
* при подключении сервер спрашивает: `Write your name`. Клиент читает это сообщение и отправляет ему имя.
* Сервер читает имя, запоминает его, и задает следующий вопрос: `Are you child? (yes/no)`. Клиент отвечает `yes` или `no`.
* На что сервер, если увидел `yes`, отвечает `Welcome to the kids area, %username%! Let's play!`, 
* а если `no`, то `Welcome to the adult zone, %username%! Have a good rest, or a good working day!` 
(где %username% - имя клиента из предыдущего шага)