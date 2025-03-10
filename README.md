# Скрипты
Различные скрипты для сайтов Комитета.

## Счётчики количества статей и комментариев в профилях участников
![Пример счётчиков на DTF](https://user-images.githubusercontent.com/1946939/145716783-a5a41122-ca11-4dd0-98ac-c8469ca501f2.png "Пример счётчиков")


### Известные проблемы
1. Не работает для профилей, которые скрыла администрация или сам участник в настройках.
2. Не учитываются посты и комменты в закрытых подсайтах.
3. Отображается не сразу, т. к. нужно сделать дополнительный запрос к Очобе.
4. После переходов между страницами может перестать работать.

# Установка
1. Устанавливаем Tampermonkey.
   - Chrome (Vivaldi, Яндекс Браузер, Chromium, etc.) — https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo
   - Firefox — https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/
   - Opera — https://addons.opera.com/en/extensions/details/tampermonkey-beta/
   - Safari — с сайта разработчика расширения или из Mac Store
2. Открываем файл нужного скрипта, например, для отображения счётчиков постов и комментв: https://github.com/Suvitruf/dtf-scripts/raw/master/profile-counters/profile-counters.user.js. 
   Устанавливаем скрипт (жмём на кнопку Install / Установить).