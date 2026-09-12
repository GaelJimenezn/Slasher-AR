# Slasher-AR

Unreal Engine project focused on gameplay prototyping, NPC behavior, and experimentation with AR/VR-oriented project configuration.

> **Status:** Experimental / secondary portfolio project

## Overview

Slasher-AR is an Unreal Engine project that evolved through several iterations. Earlier versions explored AR/VR and Oculus/OpenXR configuration; the current `main` branch is centered on a third-person gameplay setup with NPC AI, Behavior Trees, Blackboard data, and reusable AI tasks/decorators.

The repository is kept as a record of the project's development and experimentation rather than as a polished commercial game.

## Technical Focus

- Unreal Engine project configuration
- Blueprint-based gameplay systems
- NPC AI and Behavior Trees
- Blackboard-driven AI state/data
- Custom Behavior Tree tasks and decorators
- Third-person character/game-mode setup
- Rendering and platform configuration
- Earlier AR/VR and Oculus/OpenXR experimentation

## AI Systems

The current project contains a dedicated `Characters/AI` area with assets for NPC behavior, including:

- `AI_NPC`
- `BB_NPC`
- `BT_NPC`
- `BTDecorator_CheckScale`
- `BTTask_ClearBlackboard`
- `BTTask_MoveRandomLocation`

These assets represent the project's main technical focus in its current state: organizing NPC behavior through Unreal's AI framework instead of placing all gameplay logic directly inside a single Blueprint.

## Project Evolution

The repository went through several iterations during development:

1. **AR/VR exploration** — the project was migrated to an AR/VR-oriented structure with Oculus/OpenXR-related configuration and assets.
2. **AR/VR cleanup** — VR/AR assets and platform-specific configuration were later removed while the project direction changed.
3. **Gameplay and AI iteration** — the project moved toward a third-person setup with enemy/NPC Blueprints, Behavior Trees, Blackboard data, and custom AI tasks/decorators.
4. **Current state** — the `main` branch contains the current third-person/AI version.

This history is useful when revisiting the project because the repository name reflects an earlier direction that is no longer the main focus of the current branch.

## Repository Structure

```text
MyProject2/
├── Config/
│   ├── DefaultEngine.ini
│   ├── DefaultGame.ini
│   └── ...
├── Content/
│   ├── Characters/
│   │   ├── AI/
│   │   │   ├── AI_NPC
│   │   │   ├── BB_NPC
│   │   │   ├── BT_NPC
│   │   │   └── Task/
│   │   └── Mannequin_UE4/
│   └── ThirdPerson/
└── MyProject2.uproject
```

## Configuration Notes

The current project configuration targets desktop hardware and uses DirectX 12 as the default Windows graphics RHI. Rendering settings include Lumen-related configuration, virtual shadow maps, mesh distance fields, and ray tracing options.

The `.uproject` currently enables Unreal's `ModelingToolsEditorMode` for the editor.

## Getting Started

1. Clone the repository.
2. Open `MyProject2/MyProject2.uproject` with the Unreal Engine version associated with the project.
3. Allow Unreal Engine to generate any required intermediate/project files.
4. Open the default third-person map.
5. Review the assets under `Content/Characters/AI` to inspect the NPC behavior setup.

Because the repository contains Unreal `.uasset` files, the project should be opened through the Unreal Editor rather than treated as a conventional source-code-only project.

## Notes

- The repository contains a significant amount of Unreal Engine asset data (`.uasset`).
- Some historical AR/VR assets and configurations were removed as the project direction changed.
- The project should be considered an experimental/learning project, not a finished production game.

## Español

### Descripción

Slasher-AR es un proyecto de Unreal Engine enfocado en prototipado de gameplay, comportamiento de NPCs y experimentación con configuraciones relacionadas con AR/VR.

El proyecto tuvo varias etapas. Las primeras versiones exploraron AR/VR y configuraciones de Oculus/OpenXR; el estado actual de `main` está orientado principalmente a un juego en tercera persona con IA de NPCs, Behavior Trees, Blackboard y tareas/decoradores personalizados.

### Enfoque técnico actual

- Configuración de proyectos en Unreal Engine
- Gameplay mediante Blueprints
- IA de NPCs
- Behavior Trees
- Blackboard
- Tareas y decoradores personalizados
- Personaje y GameMode de tercera persona
- Configuración gráfica y de plataforma
- Experimentación histórica con AR/VR y Oculus/OpenXR

### Estado

Proyecto experimental/secundario. Se conserva principalmente como evidencia del trabajo realizado con Unreal Engine y como referencia para recuperar el contexto técnico del proyecto en el futuro.
