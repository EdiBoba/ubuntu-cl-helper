# Команды для работы с Redis

**Запуск redis:** 

    redis-server /path/to/redis.conf

**Остановка redis:** 

    redis-cli shutdown
    
**Состояние redis:**

    redis-cli info
    
**Benchmark:** выполнит 100 000 запросов от 50 клиентов по 12 команд одновременно

    redis-benchmark -q -n 100000 -c 50 -P 12