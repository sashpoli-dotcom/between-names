# Between Names — landing page

## Что в этой папке

```
between-names/
├── index.html                  ← главный файл, открой в браузере
├── images/
│   ├── audio-disc.png          ← диск, центр hero
│   ├── lp1.png                 ← обложка LP 1
│   ├── lp2.png                 ← обложка LP 2 (gatefold inner)
│   ├── photo-01.jpg            ← портретная полоса 1 (Алекс за роялем)
│   ├── photo-02.jpg            ← портретная полоса 2 (Алекс портрет)
│   ├── photo-03.jpg            ← Алекс в two-col Artist
│   ├── composer-rachmaninoff.jpg  ← ВРЕМЕННО, заменить на public domain
│   ├── composer-ornstein.jpg      ← ВРЕМЕННО, заменить на public domain
│   └── composer-bloch.jpg         ← ВРЕМЕННО, заменить на public domain
├── audio/
│   ├── between-names-preview.mp3  ← НЕТ В АРХИВЕ, положи свой файл
│   └── README.txt
└── README.md (этот файл)
```

## Что добавить локально

1. Положи MP3-превью в `audio/between-names-preview.mp3` (30–90 сек, ~128–192 kbps).
   Если файла нет — диск всё равно крутится и кликается, просто звука не будет.
2. Замени `composer-*.jpg` на public-domain фотографии (см. ниже).

## Где взять фото композиторов в public domain

- **Рахманинов** (умер 1943, в EU PD с 2014; в US — все фото до 1929 free):
  - Library of Congress: loc.gov/pictures/?q=Rachmaninoff (фильтр "no known restrictions")
  - Wikimedia Commons: search "Sergei Rachmaninoff" → файлы с лицензией PD
- **Орнштейн** (умер 2002, в EU всё ещё под копирайтом до 2073;
  в US — фото до 1929 free):
  - Wikimedia Commons: search "Leo Ornstein" → найди файлы с пометкой "PD-US-expired"
    (тот, который сейчас стоит как заглушка, скорее всего и есть он)
- **Блох** (умер 1959, в EU PD с 2030; в US — фото до 1929 free):
  - Wikimedia Commons: search "Ernest Bloch" → ранние портреты 1916–1925
  - Ernest Bloch Society (ernestblochsociety.org) — для запроса разрешения

## Языки

Сайт собран как двуязычный на одной странице.
Переключатель RU/EN — в правом верхнем углу.
Выбор языка сохраняется в localStorage.

## Ритм страницы (цвета блоков)

ТЁМНЫЙ: hero, morph + archive card, object, portrait bands, artist, support, contact, footer
СВЕТЛЫЙ (бумажный #ebe1d0): concept, three composers, program, beyond the record

## Что осталось

- Заменить временные фото композиторов на public domain
- Уточнить имя первого педагога Алекса в России (сейчас стоит "Владимир Шаклеин — имя нужно подтвердить")
- Положить MP3 превью
- Решить: оставлять ли "архивную карточку" под морфом имени или упростить
