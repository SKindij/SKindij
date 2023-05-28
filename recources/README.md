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

+ **init:** 
  - initialize new project or repository
  - set up project structure
  - add necessary files
  - perform essential configurations
+ **build:** 
  - make changes related to build systems or dependencies
  - make modifications to build scripts, configurations, or tools
+ **docs:**
  - make changes to documentation files or user guides
  - update or improve README files
+ style:
  - change code style or formatting
  - make whitespace or indentation adjustments
  - update code comment  
+ refactor:
  - restructure or reorganize existing codebase
  - improve code readability
  - optimize performance without changing overall behavior  
+ **fix:** 
  - patche bug in codebase (like **PATCH**);
  - address bug or issue in codebase
  - resolve problem
  - fix incorrect behavior or software defect
+ **feat:** 
  - introduce new feature to codebase (like **MINOR**);
  - add significant enhancements, improvements, or entirely new capabilities
  - implement new module
  - introduct new API endpoint
  - incorporate new user-facing feature
+ perf:
  - make changes aimed at improving performance of project
  - optimizate algorithm
  - enhance execution speed or resource usage
+ test:
  - add, modify, or update tests
  - change unit or integration tests
+ ci:
  - configure continuous integration (CI) 
  - modificate CI pipeline, build scripts 
  - made adjustments to integration or deployment processes  
+ chore:
  - for miscellaneous or trivial changes that don't fit into any other category
  - update package manager files,
  - refactore code for code style consistency
  - make general project maintenance changes  
+ type/scope **!:** 
  - introduce breaking API change (like **MAJOR**);  
  
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











