# Конфигурация Neovim, которую я взращивал годы
Данный репозиторий предназначен для моей конфигурации NeoVim, которую я писал и улучшал годы используя данный редактор.

# Политика
* Я стараюсь придерживаться стандартных горячих клавиш в редакторе и верю, что чем меньше кастомных клавиш, тем легче любому другому человеку использовать конфигурацию
* Я стараюсь добавлять только те плагины, которые нужны в работе, именно поэтому вы не увидите здесь плагинов по типу `goyo.vim`, которые не несут никаких функциональных изменений

# Полезные советы

## Сoc.nvim
В данной конфигурации включен `coc.nvim`. Это плагин для поддержки LSP (Language server protocol), который позволяет добаить такие вещи как автодополнение, рефакторинг (переименование структуры), а также поиск по коду.

Вам понадобятся следующие комбинации клавиш:

| Горячая клавиша | Действие                                |
|-----------------|-----------------------------------------|
| Space + s       | Поиск структуры по всем файлам по имени |
| Space + e       | Открытие проводника                     |
| Space + a       | Поиск по ошибкам                        |
| Space + o       | Поиск по структурам в файле             |
| Space + j       | Перейти к следующей ошибке              |
| Space + k       | Перейти к предыдущей ошибке             |
| gd              | Перейти к объявлению                    |
| gr              | Перейти к использованию                 |
| <leader> + K    | Показать документацию (JSDoc)           |
| <leader>rn      | Переименовать структуру                 |
