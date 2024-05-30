## CPP Final Project


### Assignment: Create a Textual Game Engine in C++

#### Overview
For this assignment, you will work in teams of 2 or 3 to develop a simple textual game engine using C++ and the Entity-Component-System (ECS) architecture. The game engine will be capable of interacting with the user through text input and output. Your task is to design and implement the core components of the game engine, along with a simple game that demonstrates its capabilities.

#### Objectives
- Learn and apply the Entity-Component-System (ECS) architecture.
- Practice teamwork and collaborative coding.
- Develop a foundational understanding of game engine development in C++.
- Implement a simple textual game to demonstrate the engine's capabilities.

#### Requirements

1. **Core Engine Components**
   - **Entity Manager**: Manage creation and destruction of entities.
   - **Component Manager**: Handle component storage and retrieval.
   - **System Manager**: Manage systems and their interactions with entities and components.

2. **Basic Systems**
You must include at least 5 systems.
For each system, you have to analyze, understand and include purpose, required components and functionality. Example systems include. 
- **Input System**: Handle user input and convert it into game actions.
- **Render System**: Output the current game state to the console.
- **Movement System**: Update entity positions based on user input or predefined behavior.
- **Health System**: Manage health-related components and interactions (e.g., damage, healing).
- **Collision System**: Detect and respond to collisions between entities.
- **AI System**: Control non-player character (NPC) behaviors and decision-making processes.
- **Inventory System**: Manage player and NPC inventories, including item pickup, drop, and use.
- **Audio System**: Handle sound effects and background music based on game events.
- **Animation System**: Update and manage animations for entities.
- **Physics System**: Simulate physical interactions, such as gravity and forces, on entities.
- **Lighting System**: Calculate and apply lighting effects to the game environment.
- **Quest System**: Track and manage the state of quests and missions in the game.
- **Dialogue System**: Manage and display dialogues between characters.
- **Skill System**: Handle character skills, abilities, and their cooldowns.
- **Resource Gathering System**: Manage the collection and use of resources (e.g., mining, logging).
- **Crafting System**: Handle the creation of items from raw materials.
- **Combat System**: Manage combat mechanics, including attack, defense, and special moves.
- **Weather System**: Simulate and update weather conditions in the game world.
- **Networking System**: Handle multiplayer interactions, including synchronization of game state across clients.
- **Save/Load System**: Manage saving and loading of game state to/from persistent storage.

4. **Game Components**
   - **Position Component**: Store the position of an entity.
   - **Velocity Component**: Store the velocity of an entity (if applicable).
   - **Health Component**: Store the health of an entity.
   - **Name Component**: Store the name or description of an entity.

5. **Game Implementation**
   - Create a simple game that uses the engine. Examples include:
     - A text-based adventure game where the player can navigate through different rooms and interact with objects.
     - A simple RPG with basic combat mechanics.
     - Any other creative idea that fits within the textual interface constraint.

6. **User Interaction**
   - Allow users to input commands to control the game (e.g., move, attack, pick up items).
   - Provide clear and informative text output to guide the player through the game.

#### Development Process

1. **Team Formation**: Form teams of 2 or 3 students.
2. **Planning**:
   - Discuss and plan the game engine architecture and game design.
   - Define roles and responsibilities within the team.
3. **Implementation**:
   - Implement the core ECS components.
   - Develop the required systems and components.
   - Implement the game logic and user interaction.
4. **Testing and Debugging**:
   - Thoroughly test the game engine and the game itself.
   - Debug and refine the code to ensure a smooth user experience.
5. **Documentation**:
   - Document the code to explain the design decisions and functionality.
   - Provide a user guide to explain how to play the game.






#### Submission

1. **Code**: Submit the complete source code of the game engine and the game.
2. **Documentation**: Submit documentation including:
   - A brief overview of the game engine architecture.
   - Instructions on how to compile and run the game.
   - A user guide for playing the game.
3. **Presentation**: Prepare a short presentation (5-10 minutes) to demonstrate your game and discuss your development process.

#### Evaluation Criteria

1. **Functionality (40%)**
   - Core ECS functionality (entity, component, system management).
   - Implementation of required systems and components.
   - Game functionality and user interaction.

2. **Code Quality (20%)**
   - Code organization and structure.
   - Readability and use of comments.
   - Proper use of C++ features and best practices.

3. **Creativity and Design (20%)**
   - Creativity and originality of the game.
   - Effective use of the textual interface.
   - Overall game design and user experience.

4. **Teamwork and Collaboration (10%)**
   - Effective collaboration and division of tasks.
   - Evidence of teamwork in the project.

5. **Presentation and Documentation (10%)**
   - Quality and clarity of the presentation.
   - Completeness and usefulness of the documentation.

#### Resources

- **C++ Reference**: https://en.cppreference.com/
- **ECS Articles and Tutorials**:
  - [Understanding ECS](https://austinmorlan.com/posts/entity_component_system/)
  - [Entitiy Component System](https://en.wikipedia.org/wiki/Entity_component_system)
- **Text-Based Game Examples**:
  - Look up text-based adventure games or simple RPGs for inspiration.

This assignment will help you apply the ECS architecture in a practical setting and develop a foundational understanding of game engine development in C++. Good luck, and have fun!
