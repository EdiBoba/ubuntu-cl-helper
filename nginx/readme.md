# Команды для работы с Nginx

**Запуск nginx:** 

    sudo systemctl start nginx

**Перезапуск nginx:** 

    sudo systemctl restart nginx
    
**Перезапуск nginx без закрытия соединений:**

    sudo systemctl reload nginx
    
**Остановка nginx:**

    sudo systemctl stop nginx

**Статус nginx:**

    sudo systemctl status nginx

**Не стартовать nginx при запуске системы:**

    sudo systemctl disable nginx

**Стартовать nginx при запуске системы:**

    sudo systemctl enable nginx

**Версия nginx**

    nginx -v