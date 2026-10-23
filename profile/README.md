<div align="center">
  <img src="https://github.com/user-attachments/assets/dad69bf4-8d80-4604-abcc-67c804c743e6" alt="Tamus" width="128" height="128" />

  # Tamus

  Настольный редактор моделей процессов IDEF0 и DFD на Tauri 2, Svelte 5 и Rust. Tamus создаётся на основе исследования возможностей Ramus: декомпозиции функций, потоков данных, классификаторов и работы с несколькими уровнями диаграмм.
  
</div>

> [!WARNING]
> Проект в бета-тестировании: возможны ошибки и нестабильная работа.

## Навигация

* [Основной репозиторий «Tamus».](https://github.com/tamus-org/tamus)

## Возможности

- **IDEF0** — контекст A-0, вложенные диаграммы, стрелки I/C/O/M и наследование интерфейсов родительского блока.
- **DFD** — процессы, внешние сущности, хранилища данных, направленные потоки и декомпозиция процессов.
- **Редактор** — размещение, перемещение и изменение размера блоков, сетка, масштабирование, автоматическая ортогональная трассировка стрелок и контекстные меню.
- **Лист диаграммы** — рамка и штампы в стиле Ramus, автор, даты, замечания, узел, контекст, цвет фона, заливка и текст блоков.
- **Классификаторы** — создание и редактирование элементов, поиск, сортировка и присоединение справочных объектов к потокам. Доступны в расширенном режиме.
- **Работа с проектом** — несколько моделей, дерево функций, вкладки, инспектор свойств, отмена/повтор последних 100 изменений и подтверждение перед потерей изменений.
- **Русский и английский интерфейс** — переключение без перезапуска; язык и расширенный режим сохраняются локально.
- **Темная и светла тема** — переключение без перезапуска; темы сохраняются локально.

## Демонстрация интерфейса
<p align="center">
      <img src="https://github.com/user-attachments/assets/034d0678-0dab-483f-b24f-fe7b90dda101" alt="Демонстрация интерфейса" width="900">      
</p>

## Стек технологий

| Категория | Стек |
| --- | --- |
| Язык программирования | Rust, TypeScript |
| UI-фреймворк | Svelte 5, SvelteKit, Tauri 2 |
| Библиотеки | Serde, Tauri API, Playwright |

## Участники проекта

<a href="https://github.com/tamus-org/tamus/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=tamus-org/tamus&max=300&columns=15" />
</a>

<br>

<a href="https://star-history.com/#tamus-org/tamus&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=tamus-org/tamus&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=tamus-org/tamus&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=tamus-org/tamus&type=Date" />
 </picture>
</a>

## Лицензия
Tamus распространяется под лицензией [GNU GPL-3.0](LICENSE).
