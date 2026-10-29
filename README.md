# Сайты Sogomonyan Tigran

- `portfolio/` — портфолио (одна страница + превью проектов)
- `diary/` — дневник с фото
- `deploy.sh` — выкладка обоих сайтов на сервер

## Выкладка (дома, на свободном сервере)

    ssh root@IP_СЕРВЕРА
    curl -fsSL https://raw.githubusercontent.com/TigranSogomonyan/portfolio/main/deploy.sh | bash

Обновление: та же команда ещё раз.
Когда купишь домены:

    PORTFOLIO_DOMAIN=example.com DIARY_DOMAIN=diary.example.com EMAIL=you@mail.com bash deploy.sh

Перед этим направь A-записи доменов на IP сервера.
