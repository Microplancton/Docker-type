# Python Docker-type

Простое Python Flask приложение.

## Сборка и запуск

1.  Убедитесь, что у вас установлен Docker.
2.  Соберите образ:

    ```bash
    docker build -t python-app .
    ```

3.  Запустите контейнер:

    ```bash
    docker run -d -p 5000:5000 python-app
    ```

4.  Откройте в браузере `http://localhost:5000`.
