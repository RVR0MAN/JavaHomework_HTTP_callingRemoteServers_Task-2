# HTTP_callingRemoteServers_SecondTask
Чтение данных API NASA
### Решение задачи по условию - "Нужно воспользоваться публичным API NASA и скачать ежедневно выгружаемые им изображение или другой контент (например видео). Несмотря на то, что API публичный, доступ к нему предоставляется по ключу, который достаточно просто получить по адресу: https://api.nasa.gov/.

Перейдя по ссылке, заполняем личными данными поля: First Name, Last Name, Email и в ответ (а так же на почтовый адрес) будет выслан ключ. С этим ключом нужно делать запросы к API.

Итак, чтобы получить ссылку на картинку или другой контент, нужно:

Сделать запрос по адресу: https://api.nasa.gov/planetary/apod?api_key=ВАШ_КЛЮЧ
Разобрать полученный ответ
В ответе найти поле url - оно содержит адрес на изображение или другой контент (например видео), который нужно скачать и сохранить локально (на своем компьютере), имя сохраняемого файла нужно взять из части url (из примера ниже DSC1028_PetersNEOWISEAuroralSpike_800.jpg)
Проверить что сохраненный файл открывается."
