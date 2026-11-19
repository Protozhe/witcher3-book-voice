# Сторонние компоненты публичной версии 0.1.3

Приложение имеет закрытый исходный код. Публичный установщик не содержит игровых ресурсов, моделей Piper/Ирины, sherpa-onnx или eSpeak NG. Речь создаётся установленным голосом Windows через Microsoft SAPI / OneCore. Голос при необходимости устанавливается через Windows Update. Лицензию Windows предоставляет Microsoft.

В установщике есть Python (PSF), Qt/PySide6/Shiboken 6.11.2 (применимые модули LGPL-3.0), FFmpeg 7.1.5 (LGPL-2.1-or-later, сборка без enable-gpl/enable-nonfree), Pillow и его кодеки, LZ4, pycaw, comtypes, psutil, OpenSSL, Microsoft Runtime. Полные тексты лицензий, уведомления и версии входят в папку licenses установленной программы. Открыть сведения можно в мастере первого запуска или настройках приложения.

В [релизе](https://github.com/Protozhe/witcher3-book-voice/releases/tag/v0.1.3) рядом с установщиком опубликован WitcherBookVoice-0.1.3-ThirdPartySources.zip: соответствующие неизменённые исходники QtBase, QtMultimedia, PySide/Shiboken, FFmpeg и zlib, контрольные суммы и инструкции. Это исходники сторонних компонентов, а не закрытого приложения. Версии зависимостей по сравнению с 0.1.1 не изменились.

Динамические DLL/PYD LGPL-библиотек можно заменять совместимыми модифицированными версиями; обратное проектирование для отладки таких изменений разрешено. Условия собственного приложения не ограничивают права по LGPL.

Сборка установщика: Inno Setup, Jordan Russell / Martijn Laan. Программа не связана с CD PROJEKT RED. The Witcher и игровые материалы принадлежат правообладателям.

Карточка модели ru_RU-irina-medium указывает неизвестную лицензию датасета, поэтому прежний локальный архив с ней не публикуется: https://huggingface.co/rhasspy/piper-voices/blob/main/ru/ru_RU/irina/medium/MODEL_CARD
