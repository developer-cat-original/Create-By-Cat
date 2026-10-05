```scripts/
├── tests/                   временные скрипты для тестирования функций/производительности
⁠├── create/
│   ├── debug.js
│   ├── launcher.js          только регистрация и подписки
│   ├── bridge/              мост для внешнего API
│   ├── fluids/              общая логика жидкостей/баков
│   ├── components/
│   ├── core/
│   │   ├── crTriggers.js    роутер
│   │   └── debug.js         guard с флагом отладки
│   ├── lib/                 чистые функции без API - проверяются в Node
│   │   ├── directions.js 
│   │   └── vectors.js
│   ├── recipes/             рецепты крафтов
│   │   ├── crushingWheelRecipes.js
│   │   ├── mechanicalPressRecipes.js
│   │   ├── mechanicalMixerRecipes.js
│   │   ├── mechanicalSawRecipes.js
│   │   ├── encasedFanRecipes.js
│   │   ├── millstoneRecipes.js
│   │   ├── mechanicalCrafterRecipes.js
│   │   └── spoutRecipes.js
│   ├── rpm/                 кинетика
│   ├── storage/             общая логика инвентарей
│   ├── sound/
│   │   ├── sounds.js
│   ├── templates/           общие обработчики для конкретных объектов
│   │   ├── _main.js
│   │   ├── button.js
│   │   ├── connectedBlocks.js
│   │   ├── door.js
│   │   ├── falling_block.js
│   │   ├── layer.js
│   │   ├── pressure_plate.js
│   │   ├── slab.js
│   │   ├── stairs.js
│   │   ├── trapdoor.js
│   │   └── wall.js
│   └── UI/                  UI ёпт
└── physics/
    ├── index.js             Регистрирует физический движок
    ├── components.js        Позволяет компонентам использовать физический движок
    ├── config.js            Конфиг физического движка
    ├── core/
    └── lib/                 чистые функции без API - проверяются в Node
```