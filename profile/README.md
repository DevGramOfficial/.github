<p align="center">
  <img src="../assets/banner.svg" alt="DevGram" width="100%">
</p>

<p align="center">
  <a href="https://t.me/DevGramNews"><img alt="Последний релиз" src="https://img.shields.io/badge/Последний_релиз-DevGramNews-7c3aed?style=for-the-badge&logo=telegram&logoColor=white"></a>
  <a href="https://t.me/DevGramNews"><img alt="Telegram" src="https://img.shields.io/badge/Telegram-DevGramNews-26A5E4?style=for-the-badge&logo=telegram&logoColor=white"></a>
  <a href="https://docs.devgram.space"><img alt="Документация" src="https://img.shields.io/badge/Документация-docs.devgram.space-5b21b6?style=for-the-badge"></a>
</p>

## О DevGram

DevGram — современный неофициальный клиент Telegram для Android с расширенными
настройками интерфейса, приватности, чатов и открытой системой Python-плагинов.

Мы развиваем приложение, публичный SDK и инструменты для авторов плагинов в
одном месте. Основные исходники открыты, а документация доступна на русском и
английском языках.

## Проекты

| Проект | Что внутри |
| --- | --- |
| **[DevGram](https://github.com/DevGramOfficial/DevGram)** | Android-приложение, исходный код и официальные релизы. |
| **[DevGram SDK](https://github.com/DevGramOfficial/DevGramSDK)** | Python API, загрузчик `.dgplugin`, нативный Java-мост и Dev Server. |
| **[DevGram Builder](https://github.com/DevGramOfficial/DevGramBuilder)** | CLI для создания, проверки, сборки и загрузки плагинов. |
| **[Документация](https://docs.devgram.space/docs/introduction)** | Руководства, справочник SDK, Builder и формат `.dgplugin`. |

## Быстрый старт для плагинов

```bash
python -m pip install --upgrade "git+https://github.com/DevGramOfficial/DevGramBuilder.git"
mkdir hello-devgram && cd hello-devgram
dgb new
dgb build -a -v -nf
```

Готовый пакет появится в `builds/`. Его можно открыть в DevGram либо загрузить
на устройство через Dev Server командой `dgb upload`.

## Ссылки

- [Скачать последний релиз](https://t.me/DevGramNews)
- [Открыть документацию](https://docs.devgram.space/docs/introduction)
- [Новости и обновления](https://t.me/DevGramNews)
- [Настройки DevGram](https://t.me/DevGramSettings)

<p align="center">
  <sub>Создаём удобный Telegram-клиент и открытую платформу расширений.</sub>
</p>
