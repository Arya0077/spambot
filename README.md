<h2 align="center">DiscordRaidMachine</h2> 

[RUSSIAN VERSION](https://github.com/TrueMajner/DiscordRaidSpamFloodBots/blob/master/README.md)  
[ENGLISH VERSION](https://github.com/TrueMajner/DiscordRaidSpamFloodBots/blob/master/README-EN.md)  
  
<h2 align="center">Зачем?🤔</h2> 

Если вам кто-то не нравится вы можете зарейдить его сервер и он будет страдать :)  
~~Я не призываю рейдить дискорд сервера, это карается DiscordTOS. Спасибо за внимание!~~  

<h2 align="center">Установка🔧</h2> 

##### Node.js
Если у вас уже установлена node.js переместитесь сюда [*клик*](https://github.com/TrueMajner/DiscordRaidSpamFloodBots/blob/master/README.md#git-clone).  
Начнём установку NodeJS  
1. Заходим на [сайт NodeJS](https://nodejs.org/en/)  
2. Скачиваем Current версию.  
3. Устанавливаем.  
Готово, вы установили NodeJS.  

##### Git Clone
Введите это в консоль. 
```cmd
git clone https://github.com/TrueMajner/DiscordRaidSpamFloodBots
cd DiscordRaidSpamFloodBots
npm install
```

<h2 align="center">Использование🏁</h2> 

Создайте файл tokens.txt в директории репозитория.  
Поместите в него токены аккаунтов для спама / флуда.  
Зайдите в файл config.json.  
  
В параметре "invite" укажите код приглашения (НЕ ССЫЛКУ) на сервер для атаки.  
В параметре "guildid" укажите ID сервера для атаки.  
В параменте "channel" укажите какой канал на сервере атаковать.  
В параметре "text" укажите текст сообщений.  
В параметре "tts" укажите использовать ли tts (true/false).  
В параметре "count" укажите максимальное кол-во ботов для атаки (0 - нет ограничений)  
В параметре "log" укажите логировать ли кол-во сообщений отправленное ботами (true/false)  
  
Запустите.  
```node
node main.js
```
Напишите что-либо в спам-канал и атака начнётся.  
Наслаждайтесь.  

<h2 align="center">Отблагодарить меня :)</h2> 
~~Завтра тут будет киви~~

