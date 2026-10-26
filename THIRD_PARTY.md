# Сторонние компоненты

Switchkey распространяется под лицензией MIT (см. `LICENSE`). Ниже перечислены сторонние
компоненты, которые входят в приложение или скачиваются им по кнопке, с их лицензиями. Тексты
лицензий лежат внутри приложения: `Switchkey.app/Contents/Resources/Licenses/`.

## whisper.cpp — распознавание речи (Whisper)

<https://github.com/ggml-org/whisper.cpp>, тег v1.9.4, лицензия MIT. Встроена в программу.

Модели Whisper (`ggml-*.bin`) в приложение не входят: скачиваются по кнопке из репозитория
<https://huggingface.co/ggerganov/whisper.cpp> (зафиксированный коммит, проверка SHA-256).
Веса Whisper — OpenAI, лицензия MIT.

## FluidAudio — распознавание речи (Parakeet, Apple Silicon)

<https://github.com/FluidInference/FluidAudio>, тег v0.15.4, лицензия Apache-2.0. Встроена в программу. Лицензии её собственных сторонних компонентов (fastcluster, VBx) лежат
внутри программы, в `Switchkey.app/Contents/Resources/Licenses/`.

Модель **NVIDIA Parakeet TDT v3** (CoreML-порт FluidInference) в приложение не входит:
скачивается по кнопке с <https://huggingface.co/FluidInference>. Лицензия CC-BY-4.0
(атрибуция указана в окне «О программе»).

## Языковые данные RU/EN

`trigrams_ru.json`, `trigrams_en.json`, `words_ru.json`, `words_en.json` — лицензия MIT.
Текст лицензии с уведомлением об авторских правах лежит внутри приложения:
`Switchkey.app/Contents/Resources/Licenses/LanguageData-LICENSE.txt`.

## Системные фреймворки Apple

AppKit, Carbon, CoreGraphics, IOKit, AVFoundation, CoreML, Metal, Translation и прочие — часть
macOS, отдельной атрибуции не требуют.
