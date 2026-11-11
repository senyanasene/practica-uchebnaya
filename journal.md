  ## <11.11.2026>  (отчёт №3)
  - Что сделал: установил Docker и Docker Compose на CTRL-01, IOT-01 и DB-01;
    проверил SSH между серверами и SCP файла с IOT-01 на CTRL-01; запустил Nginx
    на CTRL-01 через docker run и через Docker Compose (порт 8080); освободил
    порт 8080.
  - Как проверил: docker --version, docker compose version, hello-world;
    curl -I с IOT-01 вернул 200 в обоих случаях; страница Nginx открылась на WIN;
    ss -tlnp | grep 8080 пустой.