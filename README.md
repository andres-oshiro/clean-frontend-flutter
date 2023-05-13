# TODO: Clean Architecture for Flutter

- [Clean architecture](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html) to improve productivity across all projects.
  - It is framework agnostic so can apply across all projects.
  - Helps to improve team productivity by separating responsibilities.
- Readable code to improve maintainability.
  - Readable code saves future developers time and effort.
    Code readability is key for large software projects with many developers, and where the source code that is being written will have to be modified by another person.
  - Usually, readable code leads to a good implementation of the user's requirements and makes it easier to tune performance.

## Blueprint

- BLoC State management
- ...

![architecture](./docs/images/architecture.png)

## Directory structure

```sh
├── android
├── docs
├── ios
├── lib
│   ├── app
│   │   ├── assets
│   │   ├── core
│   │   └── features
│   │       │
│   │       │
│   │       ├── data
│   │       │   ├── datasources
│   │       │   └── repositories
│   │       ├── domain
│   │       │   ├── interfaces
│   │       │   ├── entities
│   │       │   └── usecases
│   │       └── presentation
│   │           ├── screen
│   │           └── shared
│   │
│   ├── mock
│   │   ├── data
│   │   └── server
│   └── test
├── scripts
├── web
└── windows
```

## Setup

- Clone repository

  ```sh
  git clone git@github.com:andres-oshiro/clean-frontend-flutter.git
  ```

- Change directory

  ```sh
  cd clean-frontend-flutter
  ```

- Execute setup shell
  - Mac users

    ```sh
    ./scripts/initial-setup.sh
    ```

  - Windows users

    ```sh
    ./scripts/initial-setup.ps1
    ```

## Quick start
