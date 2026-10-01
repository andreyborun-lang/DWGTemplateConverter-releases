# DWGTemplateConverter

Установщики преобразования чертежей для AutoCAD. Выпуски 2020 и 2026 устанавливаются отдельно.

## AutoCAD 2020

[Версия 1.0.0](https://github.com/andreyborun-lang/DWGTemplateConverter-releases/releases/tag/v1.0.0)

[Скачать EXE для AutoCAD 2020](https://github.com/andreyborun-lang/DWGTemplateConverter-releases/releases/download/v1.0.0/DWGTemplateConverter-1.0.0-AutoCAD2020.exe)

## AutoCAD 2026

[Версия 1.0.0 для AutoCAD 2026](https://github.com/andreyborun-lang/DWGTemplateConverter-releases/releases/tag/v1.0.0-acad2026)

[Скачать EXE для AutoCAD 2026](https://github.com/andreyborun-lang/DWGTemplateConverter-releases/releases/download/v1.0.0-acad2026/DWGTemplateConverter-1.0.0-AutoCAD2026.exe)

Пакет 2026 содержит панель .NET 8 и отдельно скомпилированный FAS. Загрузка и замена блоков проверены в AutoCAD 2026.1. **AutoCAD 2026.1.2 / .NET 10 ещё не проверены; совместимость не подтверждена.** Статусы испытаний конкретного выпуска указаны в его описании.

Перед установкой закройте AutoCAD. После установки выберите целевой шаблон DWG в панели. Преобразование проверяйте на копиях чертежей.

[Все версии и история обновлений](https://github.com/andreyborun-lang/DWGTemplateConverter-releases/releases)

## Проверка автоматического обновления

Для испытания установите сначала [0.1.124 для AutoCAD 2020](https://github.com/andreyborun-lang/DWGTemplateConverter-releases/releases/tag/v0.1.124) или [0.1.124 для AutoCAD 2026](https://github.com/andreyborun-lang/DWGTemplateConverter-releases/releases/tag/v0.1.124-acad2026). После запуска AutoCAD обновлятор должен предложить более новую версию своего канала. Сохраните чертежи, закройте все окна AutoCAD и подтвердите Windows UAC. Полный цикл ещё требует ручной проверки; сборки, скачивание, SHA-256 и запрет установки при открытом AutoCAD проверены.
