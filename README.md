# UnrealEngine-Core-Mechanic

This project focuses on developing and testing core game mechanics using Unreal Engine 5. The structure of the project is designed to facilitate the rapid prototyping and integration of gameplay features while ensuring maintainability and scalability. The repository contains essential systems for implementing various core mechanics, physics interactions, and character controls, providing a solid foundation for any game prototype or production-level project.

## Project Structure

```
/UnrealEngine-Core-Mechanic
│
├── /Source
│   ├── /CoreMechanic
│   │   ├── PlayerCharacter.cpp
│   │   ├── EnemyAI.cpp
│   │   └── GameManager.cpp
│
├── /Content
│   ├── /Blueprints
│   │   ├── PlayerCharacter_BP.uasset
│   │   ├── EnemyAI_BP.uasset
│   │   └── GameManager_BP.uasset
│   ├── /Animations
│   ├── /Materials
│   └── /Sounds
│
├── /Config
│   └── DefaultGame.ini
│
├── /Build
├── /Plugins
│   └── CoreMechanicPlugin
│
└── /Docs
    └── README.md (You are here)
```

## Key Features

- **PlayerCharacter System**: Modular player movement system with customizable abilities and smooth animation blending.
- **Enemy AI**: Advanced enemy AI behavior using Unreal's behavior trees, supporting multiple strategies (e.g., patrol, chase, attack).
- **GameManager**: Centralized management of game rules, states, and high-level events. Handles level transitions, respawn mechanics, and global variables.
- **Plugin Support**: Core mechanics are isolated into plugins for better code reuse and maintainability, allowing for easy expansion and modularity.

## Setup and Usage

### Prerequisites

- **Unreal Engine 5** (minimum version 5.1 recommended)
- **Visual Studio 2022** or **Rider**
- **C++17** enabled in your IDE

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/unrealengine-core-mechanic.git
    ```

2. Open the project in Unreal Engine:
    ```bash
    cd unrealengine-core-mechanic
    UnrealEditor UnrealEngine-Core-Mechanic.uproject
    ```

3. Build the project in your IDE (Visual Studio/Rider), ensuring that all plugins and dependencies are resolved.

### Running the Game

- Navigate to the **Play** button in the Unreal Editor and run the project from any of the pre-configured test levels.
- For custom mechanics testing, create a new level and implement the desired features using the provided blueprints and source code as references.

## Contributing

1. Fork the repository and create your branch:
    ```bash
    git checkout -b feature/my-new-feature
    ```

2. Commit your changes:
    ```bash
    git commit -am 'Add new feature'
    ```

3. Push to your branch:
    ```bash
    git push origin feature/my-new-feature
    ```

4. Create a new pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
