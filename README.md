# TraffStat

Лендинг TraffStat — global traffic & media buying infrastructure для Gambling, Betting и Crypto.

## Структура

```
Traffstat/
├── index.html          # главная страница
├── img/
│   ├── logo.png        # логотип в шапке
│   ├── logo-full.png   # полный логотип (запасной ассет)
│   └── watermarked_img_10434291128467773460.jpg  # фоновое изображение
├── README.md
└── .gitignore
```

## Локальный просмотр

Откройте `index.html` в браузере или поднимите простой сервер из корня проекта:

```bash
python3 -m http.server 8080
```

Сайт будет доступен по адресу `http://localhost:8080`.

## Публикация на GitHub Pages

1. Создайте репозиторий на GitHub и загрузите эту папку.
2. В Settings → Pages выберите ветку `main` и папку `/ (root)`.
3. После деплоя сайт откроется по адресу `https://<username>.github.io/<repo>/`.
