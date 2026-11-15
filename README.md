# TPD4168 Game Design

A 3D platformer prototype built with Unity. The project includes a city-themed tutorial level with moving traffic and obstacles, a platforming sandbox, and a simple main menu.

## Requirements

- Unity **6000.6.2f1** (Unity 6)
- Unity Hub

Unity will install the project's packages when you open it. The project uses the Universal Render Pipeline (URP).

## Open and run

1. Clone or download this repository.
2. In Unity Hub, choose **Add > Add project from disk** and select the project folder.
3. Open it with Unity 6000.6.2f1.
4. In the Unity Editor, open `Assets/Scenes/TutorialScene.unity` and press **Play**.

To try the menu, open `Assets/Scenes/MenuScene.unity` and press **Play**. Choose **Tutorial** to load the tutorial level. The sandbox can be played by opening `Assets/Scenes/SandboxScene.unity` directly.

## Controls

| Action | Keyboard |
| --- | --- |
| Move left/right | A/D or Left/Right Arrow |
| Jump | Space |
| Crouch | Hold Left Ctrl |

Some obstacles restart the current scene when touched.

## Scenes

| Scene | Purpose |
| --- | --- |
| `MenuScene` | Main menu, tutorial navigation, and settings |
| `TutorialScene` | City-themed platforming level with moving buses and obstacles |
| `SandboxScene` | Platforming test area |
| `SampleScene` | Default URP sample scene |

## Project notes

- The build settings currently include `MenuScene` and `TutorialScene`; `SandboxScene` is available in the Editor but is not in the build scene list.
- The menu's **Play** button currently targets a scene named `Level1`, which is not present in the project. Use **Tutorial** or open `TutorialScene` directly instead.
- Gameplay input is handled by the player movement script; the included Input System actions asset is also part of the project.
