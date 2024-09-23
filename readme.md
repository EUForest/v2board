<img src="https://avatars.githubusercontent.com/u/56885001?s=200&v=4" alt="logo" width="130" height="130" align="right"/>
<div dir="ltr">

[**Русский 🇷🇺**](README_ru.md)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[**简体中文 🇨🇳**](README_cn.md)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[**日本語 🇯🇵**](README_ja.md)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

</div>

## This project is derived from wyx2685's v2board

## Backends supported in this branch
 
 - [Modified XrayR](https://github.com/wyx2685/XrayR)
 - [Modified V2bX](https://github.com/wyx2685/V2bX)
 - [V2bX](https://github.com/InazumaV/V2bX)

## Original migration steps

Follow these steps for panel file migration：

    git remote set-url origin https://github.com/EUForest/v2board  
    git checkout master  
    ./update.sh  


Flush the settings cache and restart the queue as follows:

    php artisan config:clear
    php artisan config:cache
    php artisan horizon:terminate


# **V2Board**

- PHP7.3+
- Composer
- MySQL5.5+
- Redis
- Laravel

## Demo
[Demo](https://demo.v2board.com)

## Document
[Click](https://v2board.com)

## Sponsors
Thanks to the open source project license provided by [Jetbrains](https://www.jetbrains.com/)

## Community
🔔Telegram : [Group](https://t.me/+-Nld4TL4mUZiMWRk)  

## How to Feedback
Follow the template in the issue to submit your question correctly, and we will have someone follow up with you.
