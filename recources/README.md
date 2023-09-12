# Notes

## Conventional Commits
site: https://www.conventionalcommits.org/en/v1.0.0/
_A specification for adding human and machine readable meaning to commit messages_

> The commit message should be structured as follows:
> ```bash
>  <type>[optional scope]: <description>
>  
>  [optional body]
>  
>  [optional footer(s)]
> ```

### ``<type>``    

|         type: EN description                          |             UA description                          |
|-------------------------------------------------------|-----------------------------------------------------|
| init: initialize new project or Git repository        | _ініціалізовуємо новий проект або сховище Git_      |
| init: create project structure and initial files      | _створюємо структуру проекту та початкові файли_    |
| init: establish essential configurations and settings | _установлюємо основні конфігурації та налаштування_ |
| init: add basic README file with project overview     | _додаємо основний файл README з оглядом проекту_    |
| init: set up project structure and dependencies       | _налаштовуємо структуру проекту та залежності_      |
| init: add necessary file                              | _додаємо необхідний файл_                           |
| init: create an additional file                       | _створюємо додатковий файл_                         |
| init: set up development environment and tools        | _налаштувуємо середовище розробки та інструменти_   |
| init: configure dependencies and package managers     | _конфігуруємо залежності та менеджери пакетів_      |


|         type: EN description                         |             UA description                              |
|------------------------------------------------------|---------------------------------------------------------|
| docs: document project installation instructions     | _документуємо інструкції зі встановлення проекту_       |
| docs: write description of certain functionality     | _пишемо опис певної функціональності_                   |
| docs: add usage examples and code snippets           | _додаємо приклади використання та фрагменти коду_       |
| docs: update API reference in project documentation  | _оновлюємо посилання на API в проектній документації_   |
| docs: clarify descriptions of key functionalities    | _уточнюємо описи ключових функцій_                      |
| docs: correct typos and grammatical errors           | _виправляємо друкарські та граматичні помилки_          |
| docs: make changes to documentation file             | _вносимо зміни до файлу документації_                   |
| docs: update and improve README file                 | _оновлюємо та покращуємо файл README_                   |
| docs: add code examples on topic                     | _додаємо приклади коду по темі_                         |
| docs: improve installation instructions in README    | _покращуємо інструкції зі встановлення в README_        |


|         type: EN description                       |             UA description                                |
|----------------------------------------------------|-----------------------------------------------------------|
| style: enhance code comments                       | _вдосконалюємо коментарі до коду_                         |
| style: format codebase for consistent style        | _форматуємо код для узгодженого стилю_                    |
| style: adjust indentation and whitespace in code   | _налаштовуємо відступи та пробіли в коді_                 |
| style: improve code readability through formatting | _покращуємо читабельність коду за допомогою форматування_ |
| style: standardize CSS styles for cohesive design  | _стандартизуємо стилі CSS для цілісного дизайну_          |
| style: remove unused imports and variables         | _видаляємо невикористані імпорти та змінні_               |
| style: create new CSS module or file               | _створюємо новий модуль або файл CSS_                     |


|         type: EN description                          |             UA description                         |
|-------------------------------------------------------|----------------------------------------------------|
| build: update Webpack for improved bundling           | _оновлюємо Webpack для покращеного комплектування_ |
| build: configure babel for ES6+ support               | _налаштовуємо babel для підтримки ES6+_            |  
| build: make changes related to dependencies           | _вносимо зміни, пов’язані із залежностями_         |
| build: make modifications to build scripts or tools   | _модифікуємо сценарії збірки або інструменти_      |
| build: optimize build process for faster compilation  | _оптимізуємо процес для швидшої компіляції_        |
| build: streamline build scripts for better efficiency | _впорядковуємо сценарії для кращої ефективності_   |
| build: implement performance improvements in system   | _впроваджуємо покращень продуктивності системи_    |


|         type:(like MINOR) EN description                        |             UA description                                |
|-----------------------------------------------------------------|-----------------------------------------------------------|
| feat: implement new module                                      | _реалізовуємо новий модуль_                               |
| feat: introduce new feature to codebase                         | _представляємо нову функцію в кодовій базі_               |
| feat: introduce user authentication feature                     | _запроваджуємо функцію автентифікації користувача_        |
| feat: implement search functionality in app                     | _реалізовуємо функцію пошуку в додатку_                   |
| feat: add significant enhancements or entirely new capabilities | _додаємо значні покращення або повністю нові можливості_  |
| feat: integrate third-party library for image processing        | _інтегруємо сторонню бібліотеку для обробки зображень_    |
| feat: add drag-and-drop support for file uploads                | _додаємо підтримку перетягування для завантаження файлів_ |
| feat: create new data visualization component                   | _створюємо новий компонент візуалізації даних_            |
| feat: incorporate new user-facing feature                       | _включаємо нову функцію, спрямовану на користувача_       |
| feat: introduct new API endpoint                                | _представляємо нову кінцеву точку API_                    |


|         type: EN description                                |             UA description                             |
|-------------------------------------------------------------|--------------------------------------------------------|
| chore: update package manager files                         | _оновлюємо файли менеджера пакетів_                    |
| chore: update dependencies to latest versions               | _оновлюємо залежності до останніх версій_              |
| chore: perform general project maintenance tasks            | _виконуємо загальні завдання з обслуговування проекту_ |
| chore: refactor code to maintain code style consistency     | _рефакторимо код для підтримки узгодженості стилю коду_ |
| chore: reorganize project structure for better organization | _реорганізовуємо структуру проекту для кращої організації_ |
| chore: add new entries to the database                      | _додаємо нові записи до бази даних_               |
| chore: update information within the database               | _оновлюємо інформацію в базі даних_               |
| chore: remove unused files and assets                       | _видаляємо невикористані файли та ресурси_        |
| chore: update project documentation                         | _оновлюємо проектну документацію_                 |
| chore: add code examples related to a specific topic        | _додаємо приклади коду, пов’язані з певною темою_ |


|         type:(like PATCH) EN description              |             UA description                         |
|-------------------------------------------------------|----------------------------------------------------|
| fix: patche bug in codebase | _виправляємо помилки в кодовій базі_ |
| fix: resolve problem with | _вирішуємо проблему з_ |
| fix: address bug or issue in codebase | _усуваємо помилку або проблему в кодовій базі_ |
| fix: fix incorrect behavior or software defect | _виправляємо некоректну поведінки або дефект ПЗ_ |
| fix: patch a security vulnerability in the authentication module | _виправляємо вразливість безпеки в модулі автентифікації_ |
| fix: address performance issue in rendering component | _вирішуємо проблему з продуктивністю компонента візуалізації_ |
| fix: resolve issue with incorrect data rendering | _вирішуємо проблеми з некоректним відтворенням даних_ |
| fix: handle API response errors  | _обробляємо помилок відповідей API_ |
| fix: fix broken link in navigation bar | _виправляємо пошкоджене посилання на навігаційній панелі_ |


|         type: EN description                                |             UA description                             |
|-------------------------------------------------------------|--------------------------------------------------------|
| refactor: rename variables for better clarity | _перейменовуємо змінні для кращої ясності_ |
| refactor: simplify complex logic within a function | _спрощуємо складну логіку в межах функції_ |
| refactor: restructure or reorganize existing codebase | _реструктуризуємо або реорганізуємо існуючу кодову базу_ |
| refactor: optimize performance without changing behavior | _оптимізуємо продуктивність без зміни поведінки_ |
| refactor: extract a reusable component from the existing code | _витягуємо повторно використовуваний компонент із існуючого коду_ |
| refactor: improve code organization and structure | _покращуємо організацію та структуру коду_ |
| refactor: enhance code readability | _вдосконалюємо читабельність коду_ |
| refactor: remove redundant code | _видаляємо зайвий код_ |


|         type: EN description                                |             UA description                             |
|-------------------------------------------------------------|--------------------------------------------------------|
| perf: optimize algorithms for better performance | _оптимізуємо алгоритми для кращої продуктивності_ |
| perf: enhance execution speed or resource usage | _підвищуємо швидкість виконання або використання ресурсів_ |
| perf: implement lazy loading for improved page load times | _реалізовуємо відкладене завантаження для покращеного часу завантаження сторінки_ |
| perf: enhance caching mechanisms for faster data retrieval | _вдосконалюємо механізми кешування для швидшого отримання даних_ |
| perf: make changes to improve overall project performance | _вносимо зміни для покращення загальної продуктивності проекту_ |
| perf: optimize network request handling for quicker responses | _оптимізуємо обробку мережевих запитів для швидшої відповіді_ |
| perf: reduce memory usage through optimized resource management | _зменшуємо використання пам'яті завдяки оптимізованому управлінню ресурсами_ |
| perf: enhance rendering performance for handling large datasets | _підвищуємо продуктивність візуалізації для обробки великих наборів даних_ |


|         type: EN description                                |             UA description                             |
|-------------------------------------------------------------|--------------------------------------------------------|
| test: add, modify, or update tests | _додаємо, змінюємо або оновлювлюємо тести_ |
| test: write integration tests for API endpoints | _пишемо інтеграційні тести для кінцевих точок API_ |
| test: add unit tests for user authentication module | _додаємо модульні тести для блоку автентифікації користувача_ |
| test: improve test coverage for data validation functions | _покращуємо тестове покриття для функцій перевірки даних_ |
| test: create test suite for edge cases and error scenarios | _створюємо набір тестів для крайніх випадків і сценаріїв помилок_ |
| test: fix failing test case in component rendering | _виправляємо невдалий тестовий приклад у рендерингу компонентів_ |
| test: change unit or integration tests | _змінюємо одиничні або інтеграційні тести_ |
| test: refactor unit tests for improved readability | _рефакторимо модульні тести для покращення читабельності_ |
| test: fix failing integration tests in user authentication | _виправляємо помилки тестів інтеграції в автентифікації користувача_ |
| test: enhance test suite for performance benchmarking | _розширюємо набір тестів для порівняльного аналізу продуктивності_ |
| test: add end-to-end tests for user registration process | _додаємо наскрізні тести для процесу реєстрації користувача_ |
| test: update snapshot tests for UI components | _оновлюємо тести знімків для компонентів інтерфейсу користувача_ |   


|         type: EN description                                |             UA description                             |
|-------------------------------------------------------------|--------------------------------------------------------|
| ci: configure automated tests for pull requests | _налаштовуємо автоматичні тести для запитів на отримання_ |
| ci: integrate code quality checks with SonarQube | _інтегруємо перевірку якості коду з SonarQube_ |
| ci: made adjustments to integration or deployment processes | _вносимо зміни до процесів інтеграції або розгортання_ |
| ci: Update CI/CD configuration for deployment to production | _оновлюємо конфігурацію CI/CD для розгортання у виробництві_ |
| ci: set up continuous integration pipeline with Jenkins | _налаштовуємо конвеєр безперервної інтеграції з Jenkins_ |
| ci: add deployment pipeline for staging environment | _додаємо конвеєр розгортання для проміжного середовища_ |
| ci: automate deployment to staging environment on successful tests | _автоматизуємо розгортання в проміжному середовищі після успішних тестів_ |
| ci: configure GitHub Actions workflow for running tests | _налаштувуємо робочий процес GitHub Actions для виконання тестів_ |
| ci: integrate code style checks using ESLint | _інтегруємо перевірку стилю коду за допомогою ESLint_ |
| ci: optimize build process for faster CI/CD | _оптимізуємо процесу збирання для швидшого CI/CD_ |
| ci: add Slack notifications for build status updates | _додаємо сповіщення Slack для оновлень статусу збірки_ |
  




+ type/scope **!:** 
  - introduce breaking API change (like **MAJOR**);  

  
### ``[optional scope]``
> you should choose relevant value that reflects area of project being modified
- core
  * _include essential features and services used by framework_
- forms
  * _handle form validation, data binding, and form controls_
- http
  * _provides services for making HTTP requests and handling responses_
- animations
  * _adding, modifying, or fixing animation-related features or effects_
- common
  * _changes in common/shared components or functionality used throughout app_
- router
  * _provide routing and navigation functionality for application_
- service-worker
- upgrade

### ``<description>``
> * _the subject contains a succinct description of the change_
> * _use the imperative, present tense: "change" not "changed" nor "changes"_
> * _don't capitalize the first letter_
> * _no dot (.) at the end_
  
###  ``[optional body]``
> * _use the imperative, present tense: "change" not "changed" nor "changes"._
> * _it should include the motivation for the change and contrast this with previous behavior._
  
### ``[optional footer(s)]``  
> * _it should contain any information about Breaking Changes_
> * _it is also the place to reference GitHub issues that this commit Closes_
> * _BREAKING CHANGE: with a space or two newlines. The rest of the commit message is then used for this._
  
- - -

## useful study materials

* 🔗 JavaScript Algorithms and Data Structures 
  - en: https://github.com/trekhleb/javascript-algorithms
  - ua: https://github.com/trekhleb/javascript-algorithms/blob/master/README.uk-UA.md

* [✔] Node.js Best Practices
  - en: https://github.com/goldbergyoni/nodebestpractices
  - ru: https://github.com/goldbergyoni/nodebestpractices/blob/master/README.russian.md
 
> Structure your solution by self-contained components
> ```bash
>  my-system
>  ├─ apps (components)
>  │  ├─ orders
>  │  │ ├─ package.json
>  │  │ ├─ api
>  │  │ ├─ domain
>  │  │ ├─ data-access
>  │  ├─ users
>  │  ├─ payments
>  ├─ libraries (generic cross-component functionality)
>  │  ├─ logger
>  │  ├─ authenticator
> ```

* 🔗 The Algorithms
  - en: https://github.com/TheAlgorithms
  - Open Source resource for learning Data Structures & Algorithms and their implementation in any Programming Language
  - Python: https://github.com/TheAlgorithms/Python
  - TypeScript: https://github.com/TheAlgorithms/TypeScript

* [✔] Public APIs
  - en: https://github.com/public-apis/public-apis
  - A collective list of free APIs for use in software and web development

* 🔗 Build your own X
  - en: https://github.com/codecrafters-io/build-your-own-x
  - it is compilation of well-written, step-by-step guides for re-creating our favorite technologies from scratch

- - -











