# design
The design space of the `S²PIRE` project.

# ATTENTION: Most projects currently listed are part of my vision on how to structure everything. THere is nothing set in stone tho and projects (including their names) can change at any point. Especially in the beginning, there is going to be quite a lot of moving parts.

## Overview
`S²PIRE` is an innovative software ecosystem designed for revolutionizing how people interact with code. It introduces a common language that can be represented in multiple syntaxes,
supported by an interactive runtime environment akin to Smalltalk and Lisp.

## Projects
### MIRAGE: Modular Interactive Runtime And Generic Editor
`MIRAGE` is a core component of the `S²PIRE` platform, offering a multi-syntax interactive code editor that empowers developers with a flexible and efficient coding experience.
It supports various syntaxes, enabling users to work in their preferred coding style.

### NEOS: New Environment Operating System
- **Goal**: To build a custom operating system tailored for the `S²PIRE` ecosystem, optimizing interaction with the core system and its unique features.

### LEXICON: Language EXpression & Integration CONstruct
- **Goal**: To create a flexible framework for language expression, enabling the integration of various syntaxes into a cohesive and unified coding language.

### PROVISE: PROjectional VIsual SEtup
- **Goal**: To develop a projectional editor component that enhances visual representation of code, improving usability and accessibility for diverse coding practices.

### NETRIX: NETwork Relations and Integration eXperience
- **Goal**: To ensure seamless networking and integration capabilities, fostering a collaborative and distributed working environment.

### DEVIX: DEVelopment Innovation eXperience
- **Goal**: To create advanced development tools, plugins, and extensions that augment the functionality and versatility of the `S²PIRE` system.

### PERFORMA: PERFORMance Advancement
- **Goal**: To focus on optimizing the performance and efficiency of the system across various hardware and software environments.

### GUARDEN: GUARDed ENvironment
- **Goal**: To emphasize the security and integrity of the `S²PIRE` system, ensuring safe and protected coding and data management.

### ENGAGE: ENabling Growth And GEnerational exchange
- **Goal**: To build and nurture a vibrant community around `S²PIRE`, facilitating resource sharing, learning, and collaborative development.

## How it works together
`NEOS` will be the OS which runs the `S²PIRE` platform. On top of `NEOS`, `MIRAGE` will take care of visualizing the code through `PROVISE`, which builds upon `LEXICON` and can be extended through `DEVIX`.
`MIRAGE` will also use `PERFORMA` and `GUARDEN` to provide optimizations and safety. `NETRIX` will take care of network related tasks inside `MIRAGE` and `NEOS`.

`ENGAGE` is not software per-se, but community programs and documentation, to help the project grow, but it can contain software, if it needs to.
