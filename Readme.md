# PHP Skeleton project

This project permit to start the new symfony project.

## Pre-requisites

- PHP >=8.3
- Composer
- Make (unix utilities to execute make commands)

## Installation

You can install by executing:

```
composer create-project ug-php/symfony-clean-architecture symfony-boilerplate
cd symfony-boilerplate
make install
```

## Tests

You can run tests by executing:

```
make tests
```

## Coding quality

You can run coding quality by executing:

```
make check-code-quality
```

## Project structure

You can know more about the `src/Shared` structure regarding the `https://github.com/ug-libraries/clean-architecture-core-php`
`src/Module` folder must contain your application features.