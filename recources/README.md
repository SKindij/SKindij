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
+ **init:** 
  - _init: initialize new project or Git repository_
  - _init: add basic README file_
  - _init: set up development environment_
  - _init: create initial configuration files_
  - _init: set up project structure and dependencies_
  - _init: perform essential configurations_
  - _init: add necessary files_  
+ **build:** 
  - _build: update webpack configuration_
  - _build: configure babel for ES6 support_
  - _build: update dependencies and package versions_
  - _build: make changes related to build systems or dependencies_
  - _build: make modifications to build scripts, configurations, or tools_
  - _build: optimize build process for faster compilation_
+ **docs:**
  - _docs: add examples to the usage guide_
  - _docs: update API reference in README_
  - _docs: make changes to documentation file_
  - _docs: document project setup and installation instructions_
  - _docs: correct grammar in documentation_
  - _docs: update or improve README files_
+ style:
  - _style: change code style or formatting
  - _style: make whitespace or indentation adjustments
  - _style: update code comment  
  - _
  - _
  - _
  - _
+ refactor:
  - restructure or reorganize existing codebase
  - improve code readability
  - optimize performance without changing overall behavior
  - _
  - _
  - _
+ **fix:** 
  - patche bug in codebase (like **PATCH**);
  - address bug or issue in codebase
  - resolve problem
  - fix incorrect behavior or software defect
  - _
  - _
  - _
  - _
+ **feat:** 
  - introduce new feature to codebase (like **MINOR**);
  - add significant enhancements, improvements, or entirely new capabilities
  - implement new module
  - introduct new API endpoint
  - incorporate new user-facing feature
  - _
  - _
  - _
+ perf:
  - make changes aimed at improving performance of project
  - optimizate algorithm
  - enhance execution speed or resource usage
  - _
  - _
  - _
+ test:
  - add, modify, or update tests
  - change unit or integration tests
  - _
  - _  
  - _
  
+ ci:
  - configure continuous integration (CI) 
  - modificate CI pipeline, build scripts 
  - made adjustments to integration or deployment processes 
  - _  
  - _  
  - _
  
+ chore:
  - for miscellaneous or trivial changes that don't fit into any other category
  - update package manager files,
  - refactore code for code style consistency
  - make general project maintenance changes
  - _
  - _
  - _
+ type/scope **!:** 
  - introduce breaking API change (like **MAJOR**);  
  
### ``[optional scope]`` should be the name of the npm package affected
- animations
- common
- compiler
- compiler-cli
- core
- elements
- forms
- http
- language-service
- platform-browser
- platform-browser-dynamic
- platform-server
- platform-webworker
- platform-webworker-dynamic
- router
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
> * _it should contain any information about Breaking Changes
> * _it is also the place to reference GitHub issues that this commit Closes
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











