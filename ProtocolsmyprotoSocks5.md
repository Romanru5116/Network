протолы проксирования
первый приудман разработкой телегарамм, второй давно известен
На данный момент выбрать адрес хоста ни из одного известных ИИ источников неполучается(сайты просто не открываются)
1. MTProto (MTProxy)
Это «родной» протокол, созданный командой Telegram специально для своего мессенджера. 
Зачем: Чтобы обойти блокировки и при этом не потерять скорость (высокая скорость).
Как работает: Маскирует ваш трафик под обычное зашифрованное соединение (HTTPS/TLS), поэтому провайдеру сложно понять, что вы сидите в Telegram.
Особенности:
Работает только для Telegram.
Часто не требует логина/пароля (достаточно только адреса, порта и секретного ключа).
Практически не снижает скорость работы мессенджера. 
Хабр
Хабр
 +3
2. SOCKS5
Это старый, универсальный стандарт прокси-серверов, который используется не только в Telegram.

ссылки: https://blog.apple-avenue.ru/proksi-v-telegram-chto-eto-zachem-nuzhno-i-kak-vklyuchit-na-iphone-android-i-pk/
https://www.securitylab.ru/blog/personal/SimlpeHacker/360035.php
https://gerronfox.ru/blogs/blog/proxy_telegram2?srsltid=AfmBOopM26fUhQjE-wQydhasC0NIBehqEePFasXuy_IRxrONUiCxdd_K#:~:text=MTProto:%20%D0%A1%D0%BF%D0%B5%D1%86%D0%B8%D0%B0%D0%BB%D0%B8%D0%B7%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%BD%D0%BE%D0%B5%20%D1%80%D0%B5%D1%88%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%BE%D1%82%20Telegram.%20MTProto%20%E2%80%94,%D0%BF%D1%80%D0%B5%D0%B4%D0%BD%D0%B0%D0%B7%D0%BD%D0%B0%D1%87%D0%B5%D0%BD%D0%BD%D1%8B%D0%B9%20%D0%B8%D1%81%D0%BA%D0%BB%D1%8E%D1%87%D0%B8%D1%82%D0%B5%D0%BB%D1%8C%D0%BD%D0%BE%20%D0%B4%D0%BB%D1%8F%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D1%8B%20%D1%81%20Telegram%20.
