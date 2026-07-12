# Stanislav

### Senior Unity Developer · C# · Architecture & Gameplay Systems

I design and implement Unity codebases with an emphasis on clear boundaries, maintainable gameplay systems, runtime services, and platform integrations.

My public work covers modular game architecture, dependency injection, finite-state machines, object pooling, ECS, asynchronous workflows, monetization and analytics services, and WebGL platform SDKs.

[Telegram — @stanislavnur](https://t.me/stanislavnur)

## Engineering profile

- **Architecture:** dependency injection, game state machines, factories, service layers, persistence, and scene lifecycle.
- **Gameplay:** 2D physics, input abstraction, UI flows, spawning systems, object pooling, and configuration-driven behaviour.
- **Platform services:** Unity WebGL, Unity Ads, In-App Purchasing, Firebase Analytics, and Remote Config.
- **Data-oriented and asynchronous code:** ECS contexts and code generation, UniTask, and interface-driven runtime services.

## Selected public work

### [Asteroids — modular Unity game](https://github.com/StanislavNO/Asteroids_Kefir)

A Unity 2022 LTS project that separates core gameplay from platform-facing meta services.

- Core gameplay is organised around interfaces, factories, installers, and reusable runtime services.
- Includes object pooling, scene switching, pause handling, configurable weapons and enemies, and separate UI controllers.
- Integrates UniTask, Unity Ads, In-App Purchasing, Firebase Analytics, Remote Config, and local session persistence behind dedicated abstractions.

`Unity 2022 LTS` `C#` `UniTask` `DI` `Pooling` `Firebase` `IAP`

### [ECS Survival 2D — data-oriented gameplay](https://github.com/StanislavNO/ECS_Survival_2D)

A 2D survival-game architecture experiment built around Entitas-style ECS contexts, generated code, and small runtime services.

- Separates game, input, and meta contexts.
- Contains custom generator plugins for entity APIs and single-value components.
- Isolates physics, time, randomness, input, identifiers, static data, assets, and scene loading through interfaces.

`Unity 2022 LTS` `C#` `Entitas ECS` `Code Generation` `Zenject` `2D`

### [Bot Collectors — autonomous-agent gameplay](https://github.com/StanislavNO/bot-collectors)

A Unity 2022 LTS gameplay project built around autonomous collector agents and explicit runtime composition.

- Models agent behaviour as a finite-state machine with search, movement, collection, and return states.
- Uses factories, object pooling, presenters, installers, and configuration objects to separate gameplay from infrastructure.
- Includes AI Navigation, configurable spawning, scoring, bot-path visualisation, and input abstractions.

`Unity 2022 LTS` `C#` `AI Navigation` `State Machine` `DI` `Pooling`

[Watch the gameplay demo](https://youtu.be/lXjnF72bpWo)

### [WebGameYG — Unity WebGL integration](https://github.com/StanislavNO/WebGameYG)

A Unity WebGL gameplay project with separate runtime systems and browser-platform packages.

- Separates character and enemy behaviour into dedicated finite-state machines.
- Uses an enemy queue pool with event-based return, plus abstractions for scene loading, pause, time, and wallet state.
- Includes Agava WebUtility and Yandex Games packages alongside Unity's Input System.

`Unity WebGL` `C#` `Yandex Games SDK` `Input System`

## Engineering approach

- Keep gameplay rules separate from infrastructure and platform SDKs.
- Put runtime dependencies behind small interfaces and compose them at explicit entry points.
- Use factories and pools when object lifetime is part of the design.
- Isolate platform-specific behaviour so the gameplay layer remains portable.
- Prefer code that is easy to inspect, extend, and replace over hidden coupling.

## Contact

For professional conversations and collaboration, reach me on [Telegram](https://t.me/stanislavnur).
