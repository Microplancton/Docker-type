# Java Docker Example

Простое Java Maven приложение.

## Сборка и запуск

1.  Убедитесь, что у вас установлен Docker.
2.  Соберите образ:

    ```bash
    docker build -t java-app .
    ```

3.  Запустите контейнер:

    ```bash
    docker run -d -p 8080:8080 java-app
    ```

4.  Откройте в браузере `http://localhost:8080`.
