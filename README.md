# Anna CV

Статичний сайт-резюме Анни Мирошниченко для відгуку на позицію у Службі турботи mono.

## Deploy у Coolify

1. `New Resource` → `Application`.
2. Обрати GitHub repository `urs0v/annacv`.
3. Branch: `main`.
4. Build Pack: `Dockerfile`.
5. Port: `80`.
6. Додати домен у `Domains`.
7. Натиснути `Deploy`.

Додаткові build/start commands, env-змінні чи база даних не потрібні. Nginx роздає готовий статичний сайт.
