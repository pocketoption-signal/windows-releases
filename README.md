**Русский** | [English](README.en.md)

# PocketOption Signal для Windows — релизы

В этом репозитории лежат **только релизные сборки** PocketOption Signal для Windows
и лента автообновлений. Исходного кода здесь нет.

- Скачать последнюю версию: [Releases → Latest](https://github.com/pocketoption-signal/windows-releases/releases/latest)
- В каждом релизе есть `PocketOptionSignal-Setup-{version}.exe`, `update.json` и `update.json.sig`.
- Приложение само проверяет `releases/latest` и ставит обновление, только если
  подпись `update.json` и SHA-256 установщика верны.

Релизы публикует CI автоматически из приватного репозитория разработки.
