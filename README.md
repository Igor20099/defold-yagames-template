# Defold YaGames Template v 1.0

Шаблон для проектов на движке **Defold** для создания **HTML5** игр для платформы **Яндекс Игры**

При инициализации шаблона скачиваются два модуля **yagames** и **defsave**

По-умолчанию при старте или билде проекта загружает коллекцию **level_manager** который загружает коллекцию **main**. Можно изменить в настройках **bootstap** в **game.project**

## Архитектура проекта

Основная папка в проекте **assets**. В которой находятся:

- **atlasses** - здесь создаем атласы спрайтов
- **collections** - здесь создаем коллекции объектов
- **fonts** - сюда ложим шрифты и здесь же создаем компонент **Font**
- **game_objects** - здесь создаем игровые обекты (**go**)
- **gui** - здесь создаем **gui**
- **levels** - здесь создаем коллекции уровней. Коллекция **level_manager** управляет переходами между уровнями или перезагрузкой уровней.
- **particles** - здесь создаем системы частиц
- **scripts** - здесь создаем скрипты. Внутри есть три папки **components**, **gui**, **modules**. В **components** создаем скрипты которые будем добавлять как компоненты к игровым объектам. В **gui** создаем скрипты которые будем добавлять в самом **gui**. В **modules** создаем модульные скрипты
- **sounds** - сюда добавляем звуки и фоновую музыку
- **sprites** - сюда добавляем спрайты
- **tiles** - сюдад добавляем **Tile Map** и **Tiles Source**

_P.S: Пустые папки которые не будут использоваться в проекте можно удалить_
