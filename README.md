# Instagram Stream Script #
a very2 bad documentation XD

## What do u need ##
- a computer installed php or on Windows u can use XAMPP or WAMPP, WSL work too
- PHP Composer
- OBS App or another Stream App that support RTMP

## Authentication ##
- enter your username and password on config.php file

## How to use ##
- clone this repos
- extract and enter the directory with terminal
- don't forget to do ``` composer install  ``` and ``` composer update ```
- execute ``` php -S localhost:3000 server.php ```
- then execute ``` php live.php  ```
- enter stream URL on your stream app with custom stream
- enter stream key too with Authentication disable
- start stream
- recheck if your stream key entered correctly

## IMPORTANT ##
- Use 720x1280 resolution for phone output
- on OBS we can change it on canvas setting
- Then rotate your laptop display output

## Etc. ## 
We have web based  GUI to make stream more easier
- open localhost:3000 on your browser
- there's many options to show your stream info like Viewers, Likes, & Etc.
- you can also check your stram URL and stream key from browser when it was changed
