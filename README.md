# Daniel

<div align="center">

### I build things instead of just thinking about them.

**Programming Languages · Software · Linux · Aviation**

<br>

[![Geonex](https://img.shields.io/badge/Geonex-My%20Programming%20Language-000000?style=for-the-badge)](https://github.com/danielaufnahme-cmd/Geonex)
[![GitHub](https://img.shields.io/badge/GitHub-danielaufnahme--cmd-000000?style=for-the-badge\&logo=github)](https://github.com/danielaufnahme-cmd)

</div>

---

# About Me

I'm **Daniel**.

I'm interested in building software, programming languages, Linux, and aviation.

I like taking an idea and actually turning it into something that works.

Right now, my biggest project is **[Geonex](https://github.com/danielaufnahme-cmd/Geonex)** — a programming language I'm building from scratch.

I'm learning **Java** and **Dart**, while building Geonex in **Python**.

---

# Geonex

<div align="center">

## A programming language built from an idea.

[![Geonex Repository](https://img.shields.io/badge/Repository-Geonex-000000?style=for-the-badge\&logo=github)](https://github.com/danielaufnahme-cmd/Geonex)

</div>

Geonex is my main long-term project.

The current implementation is written in **Python**. I'm building the language piece by piece and using the project to learn how programming languages actually work.

The long-term goal is **self-hosting**.

Eventually, Geonex should be able to build its own compiler and tools.

### Current architecture

```text
                         GEONEX
                            │
                            ▼
                      ┌───────────┐
                      │   SOURCE  │
                      └─────┬─────┘
                            │
                            ▼
                      ┌───────────┐
                      │   LEXER   │
                      └─────┬─────┘
                            │
                            ▼
                      ┌───────────┐
                      │   PARSER  │
                      └─────┬─────┘
                            │
                            ▼
                      ┌───────────┐
                      │    AST    │
                      └─────┬─────┘
                            │
                            ▼
                   ┌─────────────────┐
                   │    SEMANTICS    │
                   └────────┬────────┘
                            │
                            ▼
                      ┌───────────┐
                      │ GVM / IR  │
                      └─────┬─────┘
                            │
                            ▼
                     ┌─────────────┐
                     │ OPTIMIZER   │
                     └──────┬──────┘
                            │
                            ▼
                    ┌──────────────┐
                    │ CODEGEN      │
                    └──────┬───────┘
                           │
                           ▼
                      EXECUTION
```

### The idea

I want Geonex to combine the things I like about different languages.

**Python**

Readable and simple.

**Java**

Structured and capable of handling larger software.

**Geonex**

My own take on what a language should feel like.

---

# What Geonex Is Aiming For

<div align="center">

|      Readable      |        Structured       |         Fast        |          Practical         |        Self-hosted       |
| :----------------: | :---------------------: | :-----------------: | :------------------------: | :----------------------: |
| Easy to understand | Built for real projects | Performance matters | Useful outside experiments | Eventually builds itself |

</div>

### Planned direction

```text
Readable Syntax
      +
Automatic Memory Management
      +
GVM
      +
Optimization
      +
Python Library Support
      +
Standard Library
      +
Developer Tooling
      +
Package Ecosystem
      +
Cross-Platform Support
      ↓
   Self-Hosted
```

---

# My Stack

## Languages

<div align="center">

<a
