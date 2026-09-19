# tea-spoons

A personal **playground and showcase** for the Unity code I write and experiment with. It's where I try ideas,
keep tools in one place, and share the work openly.

Everything here is provided **as-is**. Expect things to change, break and be rewritten. It is a workshop, not a
supported product line.

I'm **Muhammad Tarek Abdou** ([@MuhammadTarek0](https://github.com/MuhammadTarek0)).

## What's here

### My own tools (MIT)

Written by me, not for an employer. The packages work on their own and get extra features when you also install one
of the others (Unity detects that automatically).

| Repo | What it is | License |
|---|---|---|
| [unity-ci-kit](https://github.com/tea-spoons/unity-ci-kit) | Composable GitHub Actions for Unity: run tests, build players, handle Unity licensing, publish UPM packages | MIT |
| [Variable References](https://github.com/tea-spoons/variable-references) | ScriptableObject variables and serializable references that are either a constant or a variable, with editor drawers and UI components that update when a variable changes. | MIT |
| [Localizer](https://github.com/tea-spoons/localizer) | A small localization runtime: language tables from JSON or ScriptableObjects, fallback chains (pt-BR to pt to the default language), named placeholders, plural rules and a localized text component. | MIT |
| [Game Reward](https://github.com/tea-spoons/game-reward) | Rewards as data: bundles of typed items, a service that grants them through handlers you register (all or nothing, with rollback), weighted reward tables and ScriptableObject reward definitions. | MIT |
| [Game Task](https://github.com/tea-spoons/game-task) | Tasks and quests as data: progress reported by action key, prerequisites, expiry, claiming, save and restore. Optional integrations hand out Game Reward rewards and localize text with Localizer. | MIT |

### Unity packages that started at Bigpoint

One repo per package, each installable with Unity's Package Manager.

| Package | What it does | Version |
|---|---|---|
| [Addressables Toolbox](https://github.com/tea-spoons/addressables-toolbox) | A collection of handy additions to the Addressables system. | 0.6.0 |
| [Attribute Modifier System](https://github.com/tea-spoons/ams) | A hierarchical attribute management system for calculating game stats with support for absolute values, percentage modifiers, weighted averages, and parent-child value propagation. | 0.1.0 |
| [CodeModule Helper](https://github.com/tea-spoons/code-module-helper) | An editor tool for managing code modules in a consistent, standardized way. | 0.2.2 |
| [Collections](https://github.com/tea-spoons/collections) | Handy multi-purpose collections. | 0.10.0 |
| [Editor Toolbox](https://github.com/tea-spoons/editor-toolbox) | A collection of handy editor tools. | 0.4.0 |
| [Large Numbers](https://github.com/tea-spoons/large-numbers) | Support for creating numbers with plenty of digits. | 0.7.2 |
| [Logging](https://github.com/tea-spoons/logging) | Lightweight, modular logging. | 1.4.0 |
| [Mobile Notifications](https://github.com/tea-spoons/mobile-notifications) | Local notification abstraction layer for iOS and Android. Provides scheduling, cancellation, category management, and deep link support via the TeaSpoons service locator. | 0.5.0 |
| [Number Formatting](https://github.com/tea-spoons/number-formatting) | Makes numbers human readable and intuitive. | 0.3.4 |
| [Package Core](https://github.com/tea-spoons/package-core) | Core functionality for other packages. | 1.5.0 |
| [Runtime Toolbox](https://github.com/tea-spoons/runtime-toolbox) | A collection of diverse, handy runtime scripts. | 0.11.1 |
| [Service Locator](https://github.com/tea-spoons/service-locator) | Lightweight service binding and location. | 0.5.7 |
| [Simple Grids](https://github.com/tea-spoons/simple-grids) | Lightweight general-purpose 2D grids in 3D space. | 0.5.2 |
| [Simple Localization](https://github.com/tea-spoons/simple-localization) | Lightweight localization. | 0.5.0 |
| [Stacking Dialogs](https://github.com/tea-spoons/stacking-dialogs) | A lightweight, UGUI-based dialog system. | 0.18.0 |
| [Static Data](https://github.com/tea-spoons/static-data) | Management for gamedesign static data. Prepares and loads files, stores them in a runtime library and allows cross-referencing. | 0.23.0 |
| [Structured Documents](https://github.com/tea-spoons/structured-documents) | Unified document parsing for fundamentally different file formats. | 0.7.0 |
| [UGui Design System](https://github.com/tea-spoons/ugui-design-system) | A design system foundation for UGui projects. | 0.15.0 |
| [UI Toolbox](https://github.com/tea-spoons/ui-toolbox) | A collection of handy things for UGUI. | 0.6.1 |
| [UniTask Toolbox](https://github.com/tea-spoons/unitask-toolbox) | Useful tools for when using UniTask. | 0.11.0 |

Every package repo has a `CHANGE-PLAN.md` describing what was changed on the way here and what is planned next.

## Installing a package

In Unity: **Window > Package Manager > + > Add package from git URL**, then enter the repo URL, for example:

```
https://github.com/tea-spoons/collections.git
```

Unity can't resolve git dependencies on its own. Some packages need others; each package README lists what to add first.

## Licensing

- **unity-ci-kit**, **Variable References**, **Localizer**, **Game Reward** and **Game Task** are my own work and MIT
  licensed. (Variable References follows Ryan Hipple's MIT-licensed Unite 2017 sample; the notice is in that repo.)
- **The packages that started at Bigpoint** were work I wrote for them and are published here with their permission, under the
  [PolyForm Noncommercial 1.0.0](https://polyformproject.org/licenses/noncommercial/1.0.0) license. They are available
  for research, education and other noncommercial use; commercial use is not permitted.
  Copyright (c) 2026 Bigpoint.

Unity is a trademark of Unity Technologies. This organization is not affiliated with or endorsed by Unity.
