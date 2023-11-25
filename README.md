🚧 **This repository is a work in progress and was just started. Keep an eye on its [Roadmap](https://github.com/users/kaiosilveira/projects/5/views/1) for an overview of how it's progressing!** 🚧

# Patterns of Enterprise Application Architecture

This repository contains the working implementation of the patterns described in the "Patterns of Enterprise Application Architecture" (PoEAA) book, by Martin Fowler.

## Base patterns

Base patterns are commonly used approaches to well-known problems, such as creating objects that are only meant to carry certain values ([value objects](https://github.com/kaiosilveira/poeaa-base-patterns)), setting up a [Registry](https://github.com/kaiosilveira/poeaa-registry/tree/main) to keep track of in-memory instances or even simply configuring a [Money](https://github.com/kaiosilveira/poeaa-money) class.

| Pattern                                                            | Description                                                                               |
| ------------------------------------------------------------------ | ----------------------------------------------------------------------------------------- |
| [Value Object](https://github.com/kaiosilveira/poeaa-value-object) | A small simple object, like money or a date range, whose equality isn’t based on identity |
| [Registry](https://github.com/kaiosilveira/poeaa-registry)         | A well-known object that other objects can use to find common objects and services.       |
| [Special Case](https://github.com/kaiosilveira/poeaa-special-case) | A subclass that provides special behavior for particular cases.                           |
| [Money](https://github.com/kaiosilveira/poeaa-money)               | Represents a monetary value.                                                              |
