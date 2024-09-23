<div dir="ltr">

[**Русский 🇷🇺**](README_ru.md)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[**简体中文 🇨🇳**](README_cn.md)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[**日本語 🇯🇵**](README_ja.md)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

</div>

## 本项目源自 wyx2685 的 v2board，我将会对此分支进行维护

## 本分支支持的后端

- [Modified XrayR](https://github.com/wyx2685/XrayR)
- [Modified V2bX](https://github.com/wyx2685/V2bX)
- [V2bX](https://github.com/InazumaV/V2bX)

## 原版迁移步骤

按以下步骤进行面板文件迁移：

    git remote set-url origin https://github.com/EUForest/v2board  
    git checkout master  
    ./update.sh  


按以下步骤刷新设置缓存，重启队列:

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
