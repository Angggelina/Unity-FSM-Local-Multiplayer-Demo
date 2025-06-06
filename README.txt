# Unity FSM Local Multiplayer Demo 🎮


- **Локальний мультиплеєр** за допомогою `PlayerInputManager`
- **Finite State Machine (FSM)** для керування станами гравця (Idle, Run)
- Кожен гравець має свою копію `PlayerController`, `PlayerInput`, і незалежну FSM
- Для відлагодження змінюється колір капсули відповідно до поточного стану

## 🔧 Управління

- 🎮 Підтримуються геймпади та клавіатура (через Unity Input System)
- FSM автоматично перемикає стани:
  - 🟢 Idle — гравець стоїть
  - 🔵 Run — гравець рухається

## 📂 Основні папки

- `Assets/Scripts/States/` — реалізація FSM (`PlayerState`, `IdleState`, `RunState`)
- `Assets/Prefabs/` — префаб гравця з `PlayerInput` і `PlayerController`
- `Scenes/Main.unity` — головна сцена

