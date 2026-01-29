# Как скачивать и загружать видео через браузер
Скачивание HTML страниц. Edge через [ПКМ] - «Сохранить как» - «Веб-страница, один файл (*.mhtml)». Открывается в любых браузерах + страница сохраняется одним файлом, без кучи доп. файлов в отдельной папке.

Скачивание видео. Если стоит ограничение «controlslist="nodownload"», просто скачать не получится.

Как скачать:
1. Открыть страницу с видео.
2. Открыть инструменты разработчика, вкладку [Network].
3. Запустить воспроизведение видео. Видео поступают в браузер «кусочками» в формате .ts (например, “index_00001.ts” и т.д.). Нужно кликнуть на index_00001.ts и скопировать содержимое Request URL. Далее необходимо скорректировать этот URL.

Было:
https://vktech.ispring.ru/proxy/longread/2/c3ed83c3-858b-11ef-8db8-26ee41bd5c73/eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiIsImtpZCI6ImtpZDEifQ.eyJhdSI6ImlzbHJ1LTEwMjE0OTAxIiwidXUiOiI1ZTFkOGY5Ni1kNDAyLTExZjAtYjc2YS1kMjg1ZjYzYTUzMzUiLCJjayI6IjEwMjE0OTAxLUZjb3BKLWZpdUJvLW53SmJlIiwiY2kiOiJjM2VkODNjMy04NThiLTExZWYtOGRiOC0yNmVlNDFiZDVjNzMiLCJhbSI6MSwiZXQiOjE3NjcxODI4MjZ9.xD0CCEnseyGUiIO3KnZhW2DvB_mHuWB6ZeMtEZmAPwM/data/islru-10214901/ccda20a8-d120-11f0-8df4-32f9cf23314a/hls/index_00004.ts

Стало:
https://vktech.ispring.ru/proxy/longread/2/c3ed83c3-858b-11ef-8db8-26ee41bd5c73/eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiIsImtpZCI6ImtpZDEifQ.eyJhdSI6ImlzbHJ1LTEwMjE0OTAxIiwidXUiOiI1ZTFkOGY5Ni1kNDAyLTExZjAtYjc2YS1kMjg1ZjYzYTUzMzUiLCJjayI6IjEwMjE0OTAxLUZjb3BKLWZpdUJvLW53SmJlIiwiY2kiOiJjM2VkODNjMy04NThiLTExZWYtOGRiOC0yNmVlNDFiZDVjNzMiLCJhbSI6MSwiZXQiOjE3NjcxODI4MjZ9.xD0CCEnseyGUiIO3KnZhW2DvB_mHuWB6ZeMtEZmAPwM/data/islru-10214901/ccda20a8-d120-11f0-8df4-32f9cf23314a.mp4

4. Вставляем скорректированный URL на новой вкладке браузера, нажимаем [Enter] – загрузка начнётся.
