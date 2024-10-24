## Практическая работа №1 "Знакомство с HTTP и HTTPS протоколами"
### Цель работы

Знакомство с различиями в работе HTTP и HTTPS протоколов при помощи анализатора пакетов Wireshark

### Ход работы:
1. Запускаю Wireshark

![Прикрепленное фото работы](https://s374vla.storage.yandex.net/rdisk/66ff9246418e1db40be58de8aa55edbc48aa586ed596539a7210976f36af661c/670f0807/0S5-avnlyGtePn4FbRxK9po31fR7NoVpJGUYa1pbeGD_pNQ4E19Pw9ibAbdr2SWVLf5M2GpB1Zm-leHZ4WbE0w==?uid=691504936&filename=Wireshark_iyccLv8dcf.png&disposition=inline&hash=&limit=0&content_type=image%2Fpng&owner_uid=691504936&fsize=75803&hid=81d9e97c7eaa9afc9367feb37d4531f4&media_type=image&tknv=v2&etag=81a234f9335a7d4e8892db666f011079&ts=6248d1c3ccfc0&s=d72eb6d38aa9a5f88af06c59a824496e1aed2e9edbcb00e0650a5f67da2e08d6&pb=U2FsdGVkX1_grGUy-q4czNuJOWZnp4h2WqJoBOBmtYqI6dRM59YpyMziJmEvIlX2Wsb_HP_yKeQWr7b1NeEkHgHDFfKAMemfAS_YrUgQpEw)

2. Запускаю перехват сетевых пакетов в Wireshark

![Прикрепленное фото работы](https://s733sas.storage.yandex.net/rdisk/52c25a691ee414d525c8824c5522750ecc4bce8079056e6893b3b2d539a06f0c/670f0995/0S5-avnlyGtePn4FbRxK9iqQmaRFJewE0BXpnnXSwnpcau0NzXAU3MDzdt3h5Q2-Nin5qzKyHfijuTivE2LZLg==?uid=691504936&filename=A1.png&disposition=inline&hash=&limit=0&content_type=image%2Fpng&owner_uid=691504936&fsize=241503&hid=df9a7a83a28f679095f2d7339d909181&media_type=image&tknv=v2&etag=b093badacf97eff8a79350842058c014&ts=6248d33f5cf40&s=b37ce5107080247449c38074c60c4645a9aea8d18b548efffac7b8dffbe96e2c&pb=U2FsdGVkX19IjlUgYlZe_tBQ6DIzI0OlmYjR3emUoZPZGYtqZ0vvyVzdCzyKB7NX1f4eQXBfCOth-W2FeO8RlwKorzlIzFIXS38dXpXzWZ4)

3. В интернет браузере перехожу на сайт, использующий протокол HTTP, я использовал [сайт правительства РФ](http://government.ru/)

![Прикрепленное фото работы](https://s959sas.storage.yandex.net/rdisk/bce78a882d809b853227eecfe9f050a10b8144912ff4828ef455d20927ed59a7/671a584c/0S5-avnlyGtePn4FbRxK9sOP6B9ZsKnX_gZpZtGOWCgeB5B1xblcdsIb1kp_XSmoXYjctYK0yuJx16_sg-GbIg==?uid=691504936&filename=browser_3YikN0io2i.png&disposition=inline&hash=&limit=0&content_type=image%2Fpng&owner_uid=691504936&fsize=1579678&hid=750d73ee5086f2421946d4be0033ac4c&media_type=image&tknv=v2&etag=6dee5da5af98f5113bda5c5f560a332f&ts=62539bdcdab00&s=ca7d58ead7800ab02ddec25e1deaf094ebfd976df1f14c42dd18db6c1b4a408c&pb=U2FsdGVkX18D--azcLUSmLrZ0iSAh43AjabRs206DzHjfcxXqwfQX5l2d0IND7wEtsjBTxyKOyUbTE6qG4Aun0YjWLDK_vdcmxdbgnNVyLU)

4. В Wireshark перехватываю сетевые пакеты для заданного узла

![Прикрепленное фото работы](https://s741sas.storage.yandex.net/rdisk/d84b87ad3c396f94aa57d561df1559af0ff7f2cc724df81d9bd230b4b86e26ad/671a58dc/0S5-avnlyGtePn4FbRxK9jfeZtgdWBLc_MmCDlnCf0EvDIVQ1pp328Rs-5lIe9MC4t4uPJKkWOLlupxcrhcTpA==?uid=691504936&filename=Wireshark_4qtEul0Z6U.png&disposition=inline&hash=&limit=0&content_type=image%2Fpng&owner_uid=691504936&fsize=181306&hid=d5ea4821055f6213fd9d817ed8163f03&media_type=image&tknv=v2&etag=40354faf6cb818c21da70e89499cf75b&ts=62539c662ef00&s=feca6125b604f98541eb6326f51e5f4f5349a2f7fc320d4223d0211123c15bd8&pb=U2FsdGVkX18GqVddwR4onkd-f1oxRGxkcHTtwO-MBCEyaJUMA0n-vjYsZ0bMQIwypXOtxBj9pWo9DEtWLIUTx1ihkh0ZAEFn6DkOYxWKFto)

5. Выбираем HTTP пакет

![Прикрепленное фото работы](https://s54sas.storage.yandex.net/rdisk/afe81286794f6a3cc453e2024e933d97dd50008111fe155fbf147a82319018ee/670f1114/0S5-avnlyGtePn4FbRxK9nq-rHGeaYaRGyohnUuwaGAEjAFBWgILLFDHisCGxzcoXB6j8a1LKuCTPBh_r792Zg==?uid=691504936&filename=А4.png&disposition=inline&hash=&limit=0&content_type=image%2Fpng&owner_uid=691504936&fsize=297454&hid=facbdcce8f374f47bfea18b4deae3dfd&media_type=image&tknv=v2&etag=3be19f6f66614330b766f95e1ea05c67&ts=6248da6576d00&s=0b3c9c2818729b9e8c7ab91a4cf2520bdc60dbb07b61e246ec2246f6423f350a&pb=U2FsdGVkX18yrMq4tDxbqFtBTmbhowrC4brLe9kZO8f_jBkrDmyAl2XpKN6mDyZTIc93DRg8V09Uk_P7Ld9r1_kkCxhmjxkWOEUum3hiD9A)

6. Открываю HTTP поток для просмотра

![Прикрепленное фото работы](https://s303vla.storage.yandex.net/rdisk/c985d37e0750bf52863a6140fceb40201c2e7492a30207f92341e1c1f4602b74/670f128b/0S5-avnlyGtePn4FbRxK9oZ_E7G7W8iXIp2lDLDVGxIYVhIDiAav8ZaUdu0EHCixW7Cy4jP_uTVfI-TJc20Cmg==?uid=691504936&filename=А5.png&disposition=inline&hash=&limit=0&content_type=image%2Fpng&owner_uid=691504936&fsize=283075&hid=c84a323b6347872a6d545077aacf7036&media_type=image&tknv=v2&etag=b4f7d17ffc8872b55e695e79f1aa40c1&ts=6248dbcb178c0&s=9aa204a81d9c35808285b25e91e911e879880dc68eff59e35a1ce7c972474903&pb=U2FsdGVkX1_eYgQiHrxZa697QzJ8UfCGZpOcR83sV3jFKpxIeFyp7cxuyR0yJSZB6CmTPlaifCgfjogIs-4QhWM7VLtxpba5M6Z8nWI2-5s)

7. Показываю то, что заданный ресурс не использует шифрование, а содержимое пакетов представлено в открытом виде

![Прикрепленное фото работы](https://s99klg.storage.yandex.net/rdisk/840584041663b6bc02367fcd141e806346b0143e7d38d481e5e16e996cb9791c/671a595f/0S5-avnlyGtePn4FbRxK9vu_Bt2ihXdeHeJZGDPZVkibZt_JeqZetCBNAWJ4S3QE04BAwLFaGEMrXI5YqqExzA==?uid=691504936&filename=А6.png&disposition=inline&hash=&limit=0&content_type=image%2Fpng&owner_uid=691504936&fsize=90848&hid=bcf01f2c0269d4c37ccc65e9c8dabf21&media_type=image&tknv=v2&etag=1545dafb80aeb61e0932d713d2556cdd&ts=62539ce31d5c0&s=9b3239e609adb473d61ef7cbecda1a7a3d13a070a0d08ed11206668c10de8301&pb=U2FsdGVkX18gAYQhNiZkGP2T9EE3P2OZK8Mrfj8UHR65-VmTqPJKR_6HQCNtFa4YW-eVj9xQgBynLY6cui9GPb8G8VFM4a4Lo996rj8Nd-U)

8. В интернет браузере перехожу на сайт, использующий протокол HTTPS, к примеру [сайт расписание НПИ](https://schedule.npi-tu.ru/)

![Прикрепленное фото работы](https://s989sas.storage.yandex.net/rdisk/9d14b16318dea78d10539cea6f1b351192bb39a1a263131bf24ff7b5106536dc/671a5a81/0S5-avnlyGtePn4FbRxK9p3TB4AYr2xbr6kKNGuGyX42ck4NL73Yt_UeTydWcwKmeeVpz2VLMjdoTk2dFa7IfQ==?uid=691504936&filename=А7.png&disposition=inline&hash=&limit=0&content_type=image%2Fpng&owner_uid=691504936&fsize=721080&hid=6c3ee8e4d332d08e1ceaa28b115c030b&media_type=image&tknv=v2&etag=65ed51437e26a58b34617558e6daac88&ts=62539df7ae240&s=a01ce9b39cc1b9f8345d4427c859f87911c2b0efdeadb6fe39c8ec0952d56f04&pb=U2FsdGVkX1_gLaHRl7tDjrjUFI1QgCxKljBXmSuYY4YUl-bUZoRR7JH9tYkrcleqDsPTg0FYce6fPHXwG-DhFqxzhR7ajoc8CsQHAI_i_EE)

9. В Wireshark перехватываю сетевые пакеты для заданного узла и проверяю то что они представлены в зашифрованном виде

![Прикрепленное фото работы](https://s913sas.storage.yandex.net/rdisk/08bc304e527594ac6642b29b0e133eb5a267ce8b85840fc37ba1ed82860828d0/671a5a54/0S5-avnlyGtePn4FbRxK9to5d8u0Ox9zGcf-zuZqPUgJIlP2YNsgylyU7zLDAOD1CNfongMHLkeCVdr4Ot9cOw==?uid=691504936&filename=QpFJQBafR0.png&disposition=inline&hash=&limit=0&content_type=image%2Fpng&owner_uid=691504936&fsize=307846&hid=7e726176dc38e6ad5738752ee67432c1&media_type=image&tknv=v2&etag=80335e362cdc9a1ec071c1e8d2bbb025&ts=62539dccc3d00&s=f1990ebc6617ed74d0eae1fff0c63e32bdd4554f059bd936cb7cb8cea2ef056f&pb=U2FsdGVkX1_ByNVSXWkkIsFTJGRmKkqq4J5-8klbthbHuORyAK0A1zOidyqRNKUfbiY_V8-UBIzQ5IGX4Ulkvd6mI56kjlLgwz1bpA1xTtI)

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

## Практическая работа 2 "Знакомство с брутфорсом паролей".
### Цель работы
Знакомство с протоколом SSH, знакомство с понятием брутфорса паролей на примере брутфорса SSH пароля
### Ход работы:
1. Запускаю Hydra с параметрами:
`hydra -l user -V -x 4:4:Aa1 -s 22 -I  62.109.19.160 ssh`

![Прикрепленное фото работы](https://s139klg.storage.yandex.net/rdisk/7c45131bf77c23d506081330127838e8f2c7867fe4390aa8d01ae6a2cc1858cc/671a5ce1/0S5-avnlyGtePn4FbRxK9vFXBjoLeDpMycYmdC10hOnx-bb3B4R9vUsMIV-mHtzmxHPWh1xOfIoNGNBRV76jsQ==?uid=691504936&filename=ubuntu_1bnWMXlPk9.png&disposition=inline&hash=&limit=0&content_type=image%2Fpng&owner_uid=691504936&fsize=14899&hid=943d3e06c947f9a98337421c9931e153&media_type=image&tknv=v2&etag=56e9b7c299b8daff1fddb5705a5ffcf6&ts=6253a03b83a40&s=014fa8320ce1c851fa2cded2add6debc71b5dde06f8fd661f40ba5e069de2ac9&pb=U2FsdGVkX19TP59spczWsJNuK4vm76qEfyuJ-mEfgFO_-vBg5FqlMYhFTeMQlAfftFCn96vOk88tSBY-e6RLw-JoF8bMH-ldLxyBE8JIXJY)

2. В случае успешного запуска можно наблюдать процесс брутфорса
   
![Прикрепленное фото работы](https://s450vla.storage.yandex.net/rdisk/2bebe4b7f82898f14bb3e0d66abc2ed1a1eaf76930ac2505806ca8c3cb1b39d4/671a5e51/0S5-avnlyGtePn4FbRxK9pomc4Qnic193aKfGVkUUKCYhuXzqIMRpwQz-AgZ9Wsd7ZwP4afR1ExiQkPLUdSz0A==?uid=691504936&filename=ubuntu_ZjkpK9PGp5.png&disposition=inline&hash=&limit=0&content_type=image%2Fpng&owner_uid=691504936&fsize=131615&hid=b54a9ae1b589994a3609cfd5ee83be0d&media_type=image&tknv=v2&etag=ba77be3bb1c214ef14b36d1a00626d48&ts=6253a19a77640&s=6262ce4a915d4be438eaf5f4c5bdf8cfbc3d26165fa8a1e17cf7df563adc5600&pb=U2FsdGVkX1_AVq8GT71p7ZJRpqNRHP1YM-r2KEnDfQtgYMiQxqq9H0jaR5b61WdA7VrEeaYWFP4MlHpn946mePBxpTaMQzjn4YzGJzcHC0A)

3. После брутфорса Hydra отобразит сообщение с найденным паролем
   
![Прикрепленное фото работы](https://s439vla.storage.yandex.net/rdisk/ba03f63fa09b3c9f2fc386a5f872015c407c6e70c7c782a15b58fd07b961cd7e/671a5f42/0S5-avnlyGtePn4FbRxK9hEceHuUFdCNXbQh4H2ap3dRUIRHGJos6JUxSjtoqUbwnsXzq5kgr1aB3dtNjtkd7g==?uid=691504936&filename=ubuntu_IinSWiViFV.png&disposition=inline&hash=&limit=0&content_type=image%2Fpng&owner_uid=691504936&fsize=133424&hid=d9d2f5627744db6eb933877e90610578&media_type=image&tknv=v2&etag=b1b62105d408f2e70786565d1459bfda&ts=6253a2804d480&s=bb179b814aaf6914aeb96130bdf1c90f7f26c87ffa10462a0e82edf5c446c439&pb=U2FsdGVkX1-H4ZetQn-p5If8zPNDGdZWEMNSrp7S89M9B0xdQBQzmKM96WPMvX78UbZzXoAwEmg1EUG64lXx6SS6ZGy56gWA9g0NFEV4TEo)

4. При помощи ssh я выполняю команду ниже, указав найденный пароль. После чего выполняю перемещение между директориями и при помощи команды `cat` отобразите содержимое текстового файла, представленного в директории `/home`.

`ssh user@62.109.19.160`

![Прикрепленное фото работы](https://s174vla.storage.yandex.net/rdisk/d3ab78ed32865ab676a5a0ce0f64bf9ba58dd6da274a6a879cdecef9ed21e847/671a6005/0S5-avnlyGtePn4FbRxK9iPAy-hi1y7NLDttERfnBLT71R15xgRLe4S6Et8OAp9pWOivDyY_D5erQ_Q0yXVopQ==?uid=691504936&filename=ubuntu_ZV7uGIhVyQ.png&disposition=inline&hash=&limit=0&content_type=image%2Fpng&owner_uid=691504936&fsize=62458&hid=a77a482a9eaa3e967032ae9034f239ed&media_type=image&tknv=v2&etag=e21b5c6491b9fe189796fa1daf5816d5&ts=6253a33a44b40&s=6ccf2acc53ec54d6c145273a623663bc54a46747b4b9327b56405ea243c51ed8&pb=U2FsdGVkX18CtfPJT9hnElcQ19_8n7mt2i_TKMs1dSygqhQ9d5W0Igp8IeIKjjxEuHipWbTwfNv3JuXC17oNwwbhS2rQ6XJcsT6BFzSmIbc)

### Контрольные вопросы:
1. Что такое SSH?
2. Какой порт по умолчанию используется протоколом SSH?
3. Каким образом обеспечивается организация шифрованного соединения при использовании SSH?
4. Что такое брутфорс? В каких случаях он может использоваться?
5. Какие рекомендации по безопасности вы могли бы дать владельцу данного веб сервера?
6. За что отвечают те или иныные параметры при запуске hydra?`.
