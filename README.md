# Collector Allods

Сверстанный одностраничный макет без функционала.

## Технологии

- HTML
- CSS
- WebPack

## Трудности и недостатки

При верстке возникли трудности с изображением центрального свечения в header, По какой-то причине при скачивании они более темного оттенка чем в макете, и не придумал нечего лучше, как добавить в его svg файл opacity: 0.6;
При создании таблицы я решил воспользоваться тегом table и из-за этого мне пришлось долго промучиться и я так и не смог сделать чтобы элементы таблицы находились на расстоянии друг от друга при то, чтобы borders также был бы на расстоянии. Я мог бы в этои случае воспользовался grid. Но у меня уже не было времени на это.
Также этот сайт не адаптирован под разренения экрана меньше 1500px, так как в макете про это ничего не было и я не стал адаптировать его под свой вкус. 

### Как установить и запустить проект:

- Клонировать репозиторий:

```console
    git clone https://github.com/endjoyer/collector-allods
```

- Установить зависимости:

```console
    npm install
```

- Собрать проект и выложить на github pages:

```console
    npm run build
```

- Запустить проект на локальном сервере:

```console
    npm run dev
```

### Ссылка на сайт:

https://endjoyer.github.io/collector-allods/

[Ссылка на макет в Figma](https://www.figma.com/file/osd6zziQmiUgnl2uDDZ1uP/a1-test?node-id=1%3A15&mode=dev)
