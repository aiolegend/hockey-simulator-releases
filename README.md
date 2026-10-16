# Hockey Simulator — сборки

Хоккейный менеджер КХЛ для Windows, Android и iPhone.

## Скачать

Все файлы последней версии лежат на странице **[Releases](https://github.com/aiolegend/hockey-simulator-releases/releases/latest)**.

Текущая версия — **0.1.0**:
- [Лаунчер для Windows](https://github.com/aiolegend/hockey-simulator-releases/releases/download/v0.1.0/HockeySimulator-Launcher-Setup-0.1.1.exe) (103 МБ)
- [Игра для Windows без лаунчера, zip](https://github.com/aiolegend/hockey-simulator-releases/releases/download/v0.1.0/HockeySimulator-0.1.0-win-x64.zip) (140 МБ)
- [Android, APK](https://github.com/aiolegend/hockey-simulator-releases/releases/download/v0.1.0/HockeySimulator-0.1.0.apk) (4 МБ)
- [iPhone, IPA](https://github.com/aiolegend/hockey-simulator-releases/releases/download/v0.1.0/HockeySimulator-0.1.0.ipa) (1,3 МБ)

| Устройство | Файл | Как установить |
|---|---|---|
| Windows | `HockeySimulator-Launcher-Setup-<версия>.exe` | Запустить установщик, в лаунчере нажать «Установить». Лаунчер сам обновляет игру. |
| Windows без лаунчера | `HockeySimulator-<версия>-win-x64.zip` | Распаковать архив и запустить `HockeySimulator.exe`. |
| Android | `HockeySimulator-<версия>.apk` | Открыть файл на телефоне. Или поставить по кабелю через лаунчер: вкладка «Android». |
| iPhone | `HockeySimulator-<версия>.ipa` | Через Sideloadly на Windows — инструкция ниже. |

## Windows

Если появится окно «Windows защитила компьютер», нажмите «Подробнее» → «Выполнить в любом случае». Так бывает, потому что у программы пока нет платного сертификата подписи.

## Android

1. Откройте APK на телефоне.
2. Разрешите «Установку из неизвестных источников» для приложения, которым открыли файл.

Если игра работает медленно, включите в игре «Настройки» → «Режим слабого устройства» и обновите «Android System WebView» в Play Маркете.

## iPhone (через Sideloadly, бесплатно)

1. Установите iTunes с сайта Apple (не из Microsoft Store) и программу [Sideloadly](https://sideloadly.io/).
2. Подключите iPhone кабелем к ПК и нажмите на телефоне «Доверять этому компьютеру».
3. Перетащите `.ipa` в окно Sideloadly, введите свой Apple ID и нажмите **Start**.
4. На iPhone доверьте профилю разработчика: «Настройки» → «Основные» → «VPN и управление устройством».
5. Включите режим разработчика: «Настройки» → «Конфиденциальность и безопасность» → «Режим разработчика». iPhone перезагрузится.

С бесплатным Apple ID приложение работает 7 дней. После этого его нужно переустановить так же, сохранения при этом остаются.

## Проверка файлов

`manifest.json` содержит контрольные суммы SHA-256 всех файлов и цифровую подпись. Лаунчер проверяет их перед установкой.
