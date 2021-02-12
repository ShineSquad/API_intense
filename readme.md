# Заметки на картах

Для работы с Yandex.map JS API, необходимо получить
ключ на сайте: https://developer.tech.yandex.ru/keys/:

1) Кнопка "Подключить API", в правой части
2) Выбрать "JavaScript API и HTTP Геокодер"
3) Заполнить анкету  
	3) Обязательно указать использование API в открытой системе
	3.2) Также, обязательно отметить использование "в бесплатном проекте"
	3.3) Ну и последнее - "буду отображать данные на карте"
	3.4) В качестве сайта, укажите https://shinesquad.ru/
	3.5) Остальное по Вашему усмотрению
4) Перейти к API
5) Скопировать и сохранить ключ для API в нижней части
	5.1) ключ вида: 0a0b0c0d-1e1f-2g2h-3i3j-4k4l4m4n4o4p4
6) Для использования ключа, его необходимо вставить на страницу
```html
<script 
    src="https://api-maps.yandex.ru/2.1/?lang=ru_RU&amp;apikey=<ваш API-ключ>"
    type="text/javascript">
</script>
```
```html
<script 
    src="https://api-maps.yandex.ru/2.1/?lang=ru_RU&amp;apikey=0a0b0c0d-1e1f-2g2h-3i3j-4k4l4m4n4o4p4"
    type="text/javascript">
</script>
```

### Все примеры взяты с официального сайта:

https://yandex.ru/dev/maps/jsbox/2.1/

### Официальная документация Yandex JS API:

https://yandex.ru/dev/maps/jsapi/doc/2.1/ref/concepts/About.html

### Документация localStorage:

https://developer.mozilla.org/ru/docs/Web/API/Window/localStorage