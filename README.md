Модифицируйте код сервера таким образом, чтобы он читал строки в цикле до тех пор, пока клиент не введет “exit”. Можно считать, что это команда разрыва соединения со стороны клиента: 
![image](https://user-images.githubusercontent.com/90459151/146971714-eebd36f2-66b6-4125-b082-56b5e3ce1976.png)

Модифицируйте код сервера таким образом, чтобы при разрыве соединения клиентом он продолжал слушать данный порт и, таким образом, был доступен для повторного подключения:
![image](https://user-images.githubusercontent.com/90459151/146972318-cef8884c-ffa4-4fe7-b427-7bf36ba4980c.png)

Модифицируйте код клиента и сервера таким образом, чтобы номер порта и имя хоста (для клиента) они спрашивали у пользователя. Реализовать безопасный ввод данных и значения по умолчанию:
![image](https://user-images.githubusercontent.com/90459151/146971880-9faccebe-b88c-43bb-a850-b5dfa22a1e58.png)

Модифицировать код сервера таким образом, чтобы все служебные сообщения выводились не в консоль, а в специальный лог-файл:
![image](https://user-images.githubusercontent.com/90459151/146972601-c5e77ddf-d83e-454d-991b-a6cf34030523.png)

Реализовать сервер идентификации. Сервер должен принимать соединения от клиента и проверять, известен ли ему уже этот клиент (по IP-адресу). Если известен, то поприветствовать его по имени. Если неизвестен, то запросить у пользователя имя и записать его в файл. Файл хранить в произвольном формате:
![image](https://user-images.githubusercontent.com/90459151/146972860-22654217-eb67-40f8-8d94-0e22f6a2b070.png)

Реализовать сервер аутентификации. Похоже на предыдущее задание, но вместе с именем пользователя сервер отслеживает и проверяет пароли. Дополнительные баллы за безопасное хранение паролей. Дополнительные баллы за поддержание сессии на основе токена наподобие cookies: 
![image](https://user-images.githubusercontent.com/90459151/146973065-87143fc2-76f5-422d-be51-2cfe55443e9b.png)
