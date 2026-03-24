# Alias para Git

Configuración avanzada de alias de Git diseñada para optimizar la productividad, mejorar la legibilidad del historial y simplificar el flujo de trabajo en terminal.

Este conjunto de alias permite trabajar de forma más rápida, consistente y eficiente en cualquier repositorio.

---

## Descripción General

Los alias definidos en este repositorio tienen como objetivo:

- Reducir la cantidad de comandos repetitivos
- Mejorar la visualización del historial de commits
- Simplificar operaciones comunes
- Mantener un flujo de trabajo limpio y consistente

Todos los alias se configuran a nivel global, por lo que estarán disponibles en todos los proyectos.

---

## Instalación

Ejecuta los siguientes comandos en tu terminal:

```bash
# Visualización avanzada del historial
git config --global alias.lg "log --graph --abbrev-commit --decorate --format=format:'%C(bold blue)%h%C(reset) - %C(bold green)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(bold yellow)%d%C(reset)' --all"

# Estado del repositorio (modo compacto)
git config --global alias.s "status -sb"

# Gestión de ramas
git config --global alias.b branch

# Commit con mensaje
git config --global alias.co "commit -m"

# Añadir todos los cambios
git config --global alias.a "add ."

# Cambio de rama
git config --global alias.c checkout

# Fusión de ramas
git config --global alias.m merge
