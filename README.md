## Практическая работа №1 "Знакомство с HTTP и HTTPS протоколами"
### Цель работы

Знакомство с различиями в работе HTTP и HTTPS протоколов при помощи анализатора пакетов Wireshark

### Ход работы:
1. Запускаю Wireshark

![Прикрепленное фото работы](https://s374vla.storage.yandex.net/rdisk/66ff9246418e1db40be58de8aa55edbc48aa586ed596539a7210976f36af661c/670f0807/0S5-avnlyGtePn4FbRxK9po31fR7NoVpJGUYa1pbeGD_pNQ4E19Pw9ibAbdr2SWVLf5M2GpB1Zm-leHZ4WbE0w==?uid=691504936&filename=Wireshark_iyccLv8dcf.png&disposition=inline&hash=&limit=0&content_type=image%2Fpng&owner_uid=691504936&fsize=75803&hid=81d9e97c7eaa9afc9367feb37d4531f4&media_type=image&tknv=v2&etag=81a234f9335a7d4e8892db666f011079&ts=6248d1c3ccfc0&s=d72eb6d38aa9a5f88af06c59a824496e1aed2e9edbcb00e0650a5f67da2e08d6&pb=U2FsdGVkX1_grGUy-q4czNuJOWZnp4h2WqJoBOBmtYqI6dRM59YpyMziJmEvIlX2Wsb_HP_yKeQWr7b1NeEkHgHDFfKAMemfAS_YrUgQpEw)

2. Запускаю перехват сетевых пакетов в Wireshark

![Прикрепленное фото работы](https://s733sas.storage.yandex.net/rdisk/52c25a691ee414d525c8824c5522750ecc4bce8079056e6893b3b2d539a06f0c/670f0995/0S5-avnlyGtePn4FbRxK9iqQmaRFJewE0BXpnnXSwnpcau0NzXAU3MDzdt3h5Q2-Nin5qzKyHfijuTivE2LZLg==?uid=691504936&filename=A1.png&disposition=inline&hash=&limit=0&content_type=image%2Fpng&owner_uid=691504936&fsize=241503&hid=df9a7a83a28f679095f2d7339d909181&media_type=image&tknv=v2&etag=b093badacf97eff8a79350842058c014&ts=6248d33f5cf40&s=b37ce5107080247449c38074c60c4645a9aea8d18b548efffac7b8dffbe96e2c&pb=U2FsdGVkX19IjlUgYlZe_tBQ6DIzI0OlmYjR3emUoZPZGYtqZ0vvyVzdCzyKB7NX1f4eQXBfCOth-W2FeO8RlwKorzlIzFIXS38dXpXzWZ4)

3. В интернет браузере перехожу на сайт, использующий протокол HTTP, я использовал [сайт правительства РФ](http://government.ru/)

![Прикрепленное фото работы](https://s332vla.storage.yandex.net/rdisk/4f3cf9b7cc87c587472435bde51c0c2ee112a4df698a78879a5db8994ab39311/670f0fae/0S5-avnlyGtePn4FbRxK9sOP6B9ZsKnX_gZpZtGOWCgeB5B1xblcdsIb1kp_XSmoXYjctYK0yuJx16_sg-GbIg==?uid=691504936&filename=browser_3YikN0io2i.png&disposition=inline&hash=&limit=0&content_type=image%2Fpng&owner_uid=691504936&fsize=1579678&hid=750d73ee5086f2421946d4be0033ac4c&media_type=image&tknv=v2&etag=6dee5da5af98f5113bda5c5f560a332f&ts=6248d9100c780&s=7f2882f90a4ded9f32abde56e5f67096832d0d186ef121a9d3450bdc33b1f264&pb=U2FsdGVkX18wNmXOOmQVy8HIHaRnCBlDxlg-i1Z7GUmN240o8zQPRxjGR4Dc_x9SLtuE7322GgHPqUiUImpYt4HEadPG2GXlQsPSK_c1yOw)

4. В Wireshark перехватываю сетевые пакеты для заданного узла

![Прикрепленное фото работы](https://s142vla.storage.yandex.net/rdisk/e383ea2c7e63232adbf2993e35d2580319b6d0806ec1b32f8e589ba7173d52fb/670f11cb/0S5-avnlyGtePn4FbRxK9gElYNb2wQGxdxTsak_A4uwFlbktnoQ42n85BPuq9-3QLh7IJ7y63sgQl9V09WtfKA==?uid=691504936&filename=А3.png&disposition=inline&hash=&limit=0&content_type=image%2Fpng&owner_uid=691504936&fsize=266929&hid=9a2854b0b0f1d60614f613cced09db49&media_type=image&tknv=v2&etag=8ae8e31af54dfaf006dbbfe93a6a484b&ts=6248db13fc8c0&s=a71e536e87eeed527e7c7629acd66d42cf85efde548264e987eabd845c7e294d&pb=U2FsdGVkX19QR3fgfNJkxTgNE6m9vkE1_H0472NkO95IEONZlZsyPeeQ1MFJL8VUDPCSAG-flMlbmJ_PpdBACTQX_-cB2oRGFo20psyj89c)

5. Выбираем HTTP пакет

![Прикрепленное фото работы](https://s54sas.storage.yandex.net/rdisk/afe81286794f6a3cc453e2024e933d97dd50008111fe155fbf147a82319018ee/670f1114/0S5-avnlyGtePn4FbRxK9nq-rHGeaYaRGyohnUuwaGAEjAFBWgILLFDHisCGxzcoXB6j8a1LKuCTPBh_r792Zg==?uid=691504936&filename=А4.png&disposition=inline&hash=&limit=0&content_type=image%2Fpng&owner_uid=691504936&fsize=297454&hid=facbdcce8f374f47bfea18b4deae3dfd&media_type=image&tknv=v2&etag=3be19f6f66614330b766f95e1ea05c67&ts=6248da6576d00&s=0b3c9c2818729b9e8c7ab91a4cf2520bdc60dbb07b61e246ec2246f6423f350a&pb=U2FsdGVkX18yrMq4tDxbqFtBTmbhowrC4brLe9kZO8f_jBkrDmyAl2XpKN6mDyZTIc93DRg8V09Uk_P7Ld9r1_kkCxhmjxkWOEUum3hiD9A)

6. Открываю HTTP поток для просмотра

![Прикрепленное фото работы](https://s303vla.storage.yandex.net/rdisk/c985d37e0750bf52863a6140fceb40201c2e7492a30207f92341e1c1f4602b74/670f128b/0S5-avnlyGtePn4FbRxK9oZ_E7G7W8iXIp2lDLDVGxIYVhIDiAav8ZaUdu0EHCixW7Cy4jP_uTVfI-TJc20Cmg==?uid=691504936&filename=А5.png&disposition=inline&hash=&limit=0&content_type=image%2Fpng&owner_uid=691504936&fsize=283075&hid=c84a323b6347872a6d545077aacf7036&media_type=image&tknv=v2&etag=b4f7d17ffc8872b55e695e79f1aa40c1&ts=6248dbcb178c0&s=9aa204a81d9c35808285b25e91e911e879880dc68eff59e35a1ce7c972474903&pb=U2FsdGVkX1_eYgQiHrxZa697QzJ8UfCGZpOcR83sV3jFKpxIeFyp7cxuyR0yJSZB6CmTPlaifCgfjogIs-4QhWM7VLtxpba5M6Z8nWI2-5s)

7. Показываю то, что заданный ресурс не использует шифрование, а содержимое пакетов представлено в открытом виде

![Прикрепленное фото работы](https://s884sas.storage.yandex.net/rdisk/ef7808785eaedf1f5f299d9220550d446b7bca920dfa08acc47af27c2ca3fa19/670f135e/0S5-avnlyGtePn4FbRxK9vu_Bt2ihXdeHeJZGDPZVkibZt_JeqZetCBNAWJ4S3QE04BAwLFaGEMrXI5YqqExzA==?uid=691504936&filename=А6.png&disposition=inline&hash=&limit=0&content_type=image%2Fpng&owner_uid=691504936&fsize=90848&hid=bcf01f2c0269d4c37ccc65e9c8dabf21&media_type=image&tknv=v2&etag=1545dafb80aeb61e0932d713d2556cdd&ts=6248dc9451380&s=c4164efe1d3ceb36d60dba12bf99408095dd930194c9410b6c5300017fd4782e&pb=U2FsdGVkX1-EgDUbIuzeOv0-qEhKCw7dpuK5kbAeJVtFl502NXD1nS7LbQkO6bj5swkOruqSIjDhcVnnEyPuYyMKrqIAmR4R2kTfILI_zQw)

8. В интернет браузере перехожу на сайт, использующий протокол HTTPS, к примеру [сайт расписание НПИ](https://schedule.npi-tu.ru/)

![Прикрепленное фото работы](https://s85vla.storage.yandex.net/rdisk/91e775e420eff0bcb75acfc57972839a8f086e3c3e0b4bf8c33042d2051c47f7/670f13e8/0S5-avnlyGtePn4FbRxK9p3TB4AYr2xbr6kKNGuGyX42ck4NL73Yt_UeTydWcwKmeeVpz2VLMjdoTk2dFa7IfQ==?uid=691504936&filename=А7.png&disposition=inline&hash=&limit=0&content_type=image%2Fpng&owner_uid=691504936&fsize=721080&hid=6c3ee8e4d332d08e1ceaa28b115c030b&media_type=image&tknv=v2&etag=65ed51437e26a58b34617558e6daac88&ts=6248dd17eca00&s=addd0d74d6265d33936c32d04e9fffd5374877c38afb46efe8cb0eb34aafaff8&pb=U2FsdGVkX18dLhZKAxvDnPgM92HnqYVgdPKNgVjNJ78_Oy0t4tpQ3PjHD09tgEPJZG-4SQrMM67lx4pbqcc0C-lK7OGouE6OLPTd8Gfd_9I)

9. В Wireshark перехватываю сетевые пакеты для заданного узла и проверяю то что они представлены в зашифрованном виде

![Прикрепленное фото работы](https://s913sas.storage.yandex.net/rdisk/65bb55b8190c44e3b59da482fddc591df5a26b799638a52907a78d4a818c70f3/670f17c5/0S5-avnlyGtePn4FbRxK9to5d8u0Ox9zGcf-zuZqPUgJIlP2YNsgylyU7zLDAOD1CNfongMHLkeCVdr4Ot9cOw==?uid=691504936&filename=QpFJQBafR0.png&disposition=inline&hash=&limit=0&content_type=image%2Fpng&owner_uid=691504936&fsize=307846&hid=7e726176dc38e6ad5738752ee67432c1&media_type=image&tknv=v2&etag=80335e362cdc9a1ec071c1e8d2bbb025&ts=6248e0c71bb40&s=4918480b272ca89bff191d3982f46b105c5a9a5cf1f95931f05c6a95895a904c&pb=U2FsdGVkX18v3Z0MIfJEYgfobNIZZFTa6mmZuPzfC-Dtu3KXP93p2GASmZTB-5ymX9CZYPj4HpHyV3gXzmBx5o255hqdBo6NL4wuXtOTwxQ)

### Контрольные вопросы:
1. Что такое HTTP / HTTPS?

Ответ: HTTP (HyperText Transfer Protocol) — это протокол передачи гипертекста, который предназначен для передачи информации между клиентом и сервером. По протоколу HTTP данные передаются в незашифрованном виде, поэтому он не является безопасным. HTTPS (HyperText Transfer Protocol Secure) — это защищённый протокол передачи данных. Его отличие от HTTP в том, что по нему информация передаётся в зашифрованном виде. Это обеспечивает безопасную передачу данных.

2. Какой порт по умолчанию используется протоколом HTTP?

Ответ: По умолчанию для протокола HTTP используется порт 80. Однако вместо него может быть выбран и любой другой порт, это зависит от конфигурации конкретного веб-сервера. 

3. Какой порт по умолчанию используется протоколом HTTPS?

Ответ: По умолчанию протоколом HTTPS используется порт 443.

4. Каким образом обеспечивается организация шифрованного соединения при использовании HTTPS протокола?
   Ответ:
   Организация шифрованного соединения при использовании HTTPS протокола обеспечивается благодаря SSL/TLS-сертификату — цифровой подписи сайта, которая подтверждает его подлинность. 

  Пользователь через браузер отправляет запрос на соединение с сайтом. 
  Браузер спрашивает у сайта данные SSL-сертификата. 
  Сайт отправляет запрошенную информацию. 
  Браузер проверяет подлинность документа безопасности через центр сертификации. 
  После проверки браузер и веб-ресурс генерируют симметричный ключ, с помощью которого в дальнейшем шифруется вся передаваемая информация.

