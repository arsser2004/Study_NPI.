## Практическая работа №1 "Знакомство с HTTP и HTTPS протоколами"
### Цель работы

Знакомство с различиями в работе HTTP и HTTPS протоколов при помощи анализатора пакетов Wireshark

### Ход работы:
1. Запускаю Wireshark

![Прикрепленное фото работы](https://s374vla.storage.yandex.net/rdisk/66ff9246418e1db40be58de8aa55edbc48aa586ed596539a7210976f36af661c/670f0807/0S5-avnlyGtePn4FbRxK9po31fR7NoVpJGUYa1pbeGD_pNQ4E19Pw9ibAbdr2SWVLf5M2GpB1Zm-leHZ4WbE0w==?uid=691504936&filename=Wireshark_iyccLv8dcf.png&disposition=inline&hash=&limit=0&content_type=image%2Fpng&owner_uid=691504936&fsize=75803&hid=81d9e97c7eaa9afc9367feb37d4531f4&media_type=image&tknv=v2&etag=81a234f9335a7d4e8892db666f011079&ts=6248d1c3ccfc0&s=d72eb6d38aa9a5f88af06c59a824496e1aed2e9edbcb00e0650a5f67da2e08d6&pb=U2FsdGVkX1_grGUy-q4czNuJOWZnp4h2WqJoBOBmtYqI6dRM59YpyMziJmEvIlX2Wsb_HP_yKeQWr7b1NeEkHgHDFfKAMemfAS_YrUgQpEw)

2. Запускаю перехват сетевых пакетов в Wireshark

![Прикрепленное фото работы](https://s733sas.storage.yandex.net/rdisk/52c25a691ee414d525c8824c5522750ecc4bce8079056e6893b3b2d539a06f0c/670f0995/0S5-avnlyGtePn4FbRxK9iqQmaRFJewE0BXpnnXSwnpcau0NzXAU3MDzdt3h5Q2-Nin5qzKyHfijuTivE2LZLg==?uid=691504936&filename=A1.png&disposition=inline&hash=&limit=0&content_type=image%2Fpng&owner_uid=691504936&fsize=241503&hid=df9a7a83a28f679095f2d7339d909181&media_type=image&tknv=v2&etag=b093badacf97eff8a79350842058c014&ts=6248d33f5cf40&s=b37ce5107080247449c38074c60c4645a9aea8d18b548efffac7b8dffbe96e2c&pb=U2FsdGVkX19IjlUgYlZe_tBQ6DIzI0OlmYjR3emUoZPZGYtqZ0vvyVzdCzyKB7NX1f4eQXBfCOth-W2FeO8RlwKorzlIzFIXS38dXpXzWZ4)

3. В интернет браузере перехожу на сайт, использующий протокол HTTP, я использовал [сайт Совета Федерации](http://council.gov.ru/users/login/?next=http%3A//pisma.council.gov.ru/cabinet/)

![Ожидаемый результат](https://s778sas.storage.yandex.net/rdisk/d2420b3b19e51f8a9c491b5270b030245311585c4f96155efdf068a1fcbc2640/670f0d75/0S5-avnlyGtePn4FbRxK9tT8-6T6jEE6ONMQegjg_6kHnaehkHawKTHZPUiUYqlP9iuVUvPuv0a2Z_5sm9bEAw==?uid=691504936&filename=А2.png&disposition=inline&hash=&limit=0&content_type=image%2Fpng&owner_uid=691504936&fsize=191530&hid=3a2c8f5be4b1c84232d8d2476074f201&media_type=image&tknv=v2&etag=2dc818bd3a2901590c50e0b83383aaf4&ts=6248d6f168740&s=e39fdcc69863cd89cb631335a372c8d90998910bc27f19f6215a4bcb134e4227&pb=U2FsdGVkX19io7z34H3oCSriIl2QBrgmvT8i-KOtLZknycwPLP7xrvCCkOLM2pJEm5D2DoerW89RKI0eDCsSKErmDsK8QGFxJZQSADRx6EU)

4. В Wireshark выполните перехват сетевых пакетов для заданного узла, при необходимости воспользовавшись утилитой `nslookup` для определения IP адреса

![Ожидаемый результат](https://storage.yandexcloud.net/shesterikov/CS_1_4.png)

5. Выберите HTTP пакет

![Ожидаемый результат](https://storage.yandexcloud.net/shesterikov/CS_1_5.png)

6. Откройте HTTP поток для просмотра
![Ожидаемый результат](https://storage.yandexcloud.net/shesterikov/CS_1_6.png)
7. Убедитесь, что заданный ресурс не использует шифрование, а содержимое пакетов представлено в открытом виде
![Ожидаемый результат](https://storage.yandexcloud.net/shesterikov/CS_1_7.png)
8. В интернет браузере перейдите на любой сайт, использующий протокол HTTP, к примеру [сайт расписание НПИ](https://schedule.npi-tu.ru/)
![Ожидаемый результат](https://storage.yandexcloud.net/shesterikov/CS_1_8.png)
9. В Wireshark выполните перехват сетевых пакетов для заданного узла, при необходимости воспользовавшись утилитой `nslookup` для определения IP адреса.
Убедитесь, что пакеты, передаеваемые между клиентом и сервером зашифрованы
![Ожидаемый результат](https://storage.yandexcloud.net/shesterikov/CS_1_9.png)

### Контрольные вопросы:
1. Что такое HTTP / HTTPS?
2. Какой порт по умолчанию используется протоколом HTTP?
3. Какой порт по умолчанию используется протоколом HTTPS?
4. Каким образом обеспечивается организация шифрованного соединения при использовании HTTPS протокола?
