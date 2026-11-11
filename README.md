# TravelPenza — данные клуба

Открытые данные для приложения TravelPenza.

- `tracks.geojson` — все треки (FeatureCollection, у каждого трека линия LineString и свойства `name`, `distance_km`, `start_date`, `source_file`).
- `club.json` — настройки клуба, описания походов и анонсы.

## club.json

- `club`: `name`, `city`, `founded_year`, `chat_url`, `vk_group_url`.
- `trips`: описания походов. `track` — имя GPX-файла трека; дальше по желанию `title`, `date` (ГГГГ-ММ-ДД), `kind` (`hiking`, `water`, `bike`, `ski`, `other`), `difficulty`, `description`, `distance_km`, `cover` и `photos` (пути к фото в этом репозитории), `vk_album_url`.
- `announcements`: анонсы. `title`, `start_date`, `end_date`, `kind`, `distance_km`, `cover`, `signup_url`.
