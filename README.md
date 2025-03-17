# Minishell

Minishell est un projet de l'école 42 visant à créer une version minimale d'un shell Unix, inspirée de bash (Bourne Again SHell). Ce projet permet de comprendre en profondeur la création et la synchronisation des processus en langage C.

## Fonctionnalités

- Affichage d'un prompt interactif pour l'utilisateur.
- Exécution de commandes avec leurs arguments.
- Gestion des chemins relatifs et absolus.
- Implémentation des redirections (`<`, `>`, `>>`).
- Gestion des pipes (`|`) pour la communication entre processus.
- Support des variables d'environnement et de leur expansion.
- Gestion des signaux comme `Ctrl+C` et `Ctrl+\`.
- Implémentation de certaines commandes internes (builtins) :
  - `echo` avec l'option `-n`
  - `cd` avec un seul argument
  - `pwd` sans options
  - `export` sans options
  - `unset` sans options
  - `env` sans options
  - `exit` sans options

## Compilation et Exécution

### Prérequis

- GNU Make
- GCC

### Instructions

1. Cloner le dépôt :

   ```bash
   git clone https://github.com/JPKpointFR/Minishell.git
   cd Minishell
