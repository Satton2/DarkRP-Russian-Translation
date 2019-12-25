## О переводе ##
Перевод сделан для DarkRP версии 2.7.0.

Автор перевода: Satton(RU) — https://steamcommunity.com/id/Satton/

Ссылка на страницу в Мастерской: https://steamcommunity.com/sharedfiles/filedetails/?id=1946256913

Ссылка на режим: https://github.com/FPtje/DarkRP

Ссылка на дополнение **darkrpmodification**: https://github.com/FPtje/darkrpmodification

Автор режима и дополнения: Falco Peijnenburg (FPtje) — https://steamcommunity.com/id/FPtje

Отдельная благодарность проекту SpyLony (http://spylony.ru/) за его помощь при переводе.

## Установка ##
1) Установите режим **DarkRP** и дополнение **darkrpmodification** на свой сервер;

2) Откройте папку сервера и перенесите папку перевода в следующий каталог: ***<сервер>*\garrysmod\addons\darkrpmodification-master** (файл **README.md** устанавливать не нужно);

3) Если язык сервера не установлен на русский язык, найдите в CFG-файлах сервера консольную переменную **gmod_language** и,
если значение установлено на **"en"** или любой другой языковой код, замените переменную на **"ru"**. Итоговый вид переменной и значения:
**gmod_language "ru"**;

Примечание: если в CFG-файлах нет этой переменной, внесите её в любой удобный для вас CFG-файл, который автоматически запускается вместе
с сервером. Например, в **server.cfg**.

## Удаление ##
1) Удалите файлы **russian.lua** и **chatcommandsru.lua** из следующего каталога: ***<сервер>*\garrysmod\addons\darkrpmodification-master\lua\darkrp_language**.

2) Значение консольной переменной **gmod_language** поменяйте на **"en"**.

## Частые вопросы ##
#### **В**: У меня нет перевода некоторого текста! Что делать? ####

**О**: Сообщите об этом мне через вкладку Issues или в соответствующем обсуждении на странице перевода в Мастерской, приложив скриншот и информацию о том, как вызвать этот текст. Если вы используете старую версию
DarkRP, укажите номер версии. Также вы можете попробовать перевести текст сами (*информация об этом находится в файлах локализации*), но *убедительно прошу сообщить о находке*!

#### В: В переводе отсутствует перевод названий работ, категорий, законов и... ####

О: Названия работ, категорий, предметов, оружия, законов и дверных групп изменяются, переводятся и настраиваются разработчиками серверов.
Их перевод не входит в перевод самого режима. Файлы локализации стандартной таблицы счёта и FAdmin не предоставлены автором режима и
не будут предоставлены в ближайшем будущем по различным причинам, поэтому их перевода тоже нет.

#### В: Я нашёл ошибку в переводе! Что делать? ####

О: Сообщите об этом мне через вкладку Issues или в соответствующем обсуждении на странице перевода в Мастерской, приложив скриншот и информацию о том, как вызвать этот текст. Если вы используете старую версию
DarkRP, укажите номер версии. Также вы можете исправить текст сами, но *убедительно прошу сообщить о находке*!

#### В: У меня на сервере используются собственные названия работ, а в переводе местами есть такие названия, как мэр, нищий и пр. Что делать? ####

О: Самостоятельно найдите и замените названия работ на те, которые вы используете на своём сервере, в соответствующи файлах перевода.

#### В: Мне понравился ваш перевод. Как я могу вас отблагодарить? ####

О: Сообщив о всех найденных ошибка и отсутствующих строках, а также поделившись этим переводом со всеми разработчиками серверов,
использующих плохой перевод режима. Это будет наилучшей благодарностью.

#### В: Русский текст отличается от некоторых символов и английских букв. Что делать? ####

О: Большинство шрифтов в Garry's Mod не поддерживают кириллицу, вследствие чего русский текст автоматически использует стандартный шрифт
**"Tahoma"**, а все прочие символы и английский текст — шрифт, заданный разработчиком режима или дополнения. Единственным способом решения данной проблемы является замена всех шрифтов режима или дополнения на шрифт **"Tahoma"** или другой шрифт, поддерживающий кириллицу.


