Reverse Proxy Cacheable


1 . Start Nginx

nginx

2.	Stop Nginx


@taskkill /f /im nginx.exe


3. MockAPI

https://mockapi.io/projects/61fe0e54a58a4e00173c96fd








CURLS:

curl --location --request GET 'localhost/user'

![image](https://user-images.githubusercontent.com/34476524/152630882-f1e177f3-375a-4792-80ef-7faf56da0189.png)



curl --location --request GET 'https://61fe0e54a58a4e00173c96fc.mockapi.io/user' \
--header 'Cache-Control: no-cache'

![image](https://user-images.githubusercontent.com/34476524/152630897-2ff05783-e594-4ab5-9976-a4977624d7f4.png)
