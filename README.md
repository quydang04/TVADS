Lệnh cài cho Ubuntu, Debian: 

````
apt update && apt install wget -y && wget https://raw.githubusercontent.com/quydang04/TVADS/main/start-no-venv && chmod +x start-no-venv && bash start-no-venv 
````

Bị lỗi error: externally-managed-environment thì xóa file start đi rồi cài bằng lệnh này:

```` 
apt update && apt install wget -y && wget https://raw.githubusercontent.com/quydang04/TVADS/main/start && chmod +x start && bash start
````
