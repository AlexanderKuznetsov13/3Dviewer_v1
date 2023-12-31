# 3Dviewer_v1

Инструкция по использованию 3D Model Visualizer

О программе

Эта программа предназначена для визуализации каркасных моделей в трехмерном пространстве, написана на C11 и поддерживает различные GUI-библиотеки.

Функционал

Загрузка моделей из файла формата OBJ
Перемещение, поворот и масштабирование моделей
Настройка вида и типа проекции
Сохранение изображений и создание анимаций
Сборка и установка

Для сборки и установки программы используйте следующие команды:

    make all       - сборка и запуск
    make install   - установка
    make uninstall - удаление
    make clean     - очистка
    make dist      - создание архива
    make tests     - запуск тестов
    make gcov_report - отчет по покрытию кода
    make dvi       - создание документации
  
Использование

Для запуска введите команду make all.

Используйте кнопку для выбора файла с моделью.
Пользуйтесь полями и кнопками для перемещения, поворота и масштабирования.
В разделе настроек можно изменить тип проекции, вид и цвет ребер, и другие параметры.
Дополнительные возможности

Сохранение изображений в BMP и JPEG.
Создание GIF-анимаций текущих пользовательских преобразований.
