# Anna CV

Статична сторінка-резюме Анни Мирошниченко для відгуку на позицію у Службі турботи mono.
Оформлена як документ-резюме (не лендинг), з кнопкою завантаження оригінального PDF (`assets/anna-myroshnychenko-cv.pdf`).

## Deploy у Coolify

1. `New Resource` → `Application`.
2. Обрати GitHub repository `urs0v/annacv`.
3. Branch: `main`.
4. Build Pack: `Dockerfile`.
5. Port: `80`.
6. Додати домен у `Domains`.
7. Натиснути `Deploy`.

Додаткові build/start commands, env-змінні чи база даних не потрібні. Nginx роздає готовий статичний сайт.
