# Product

## Platform

Web for the MVP. Mobile is planned for later versions.

## Users

For the MVP, the only user is the developer: someone with many tasks piling up and being left aside, who could not stay organized with common productivity tools and ended up splitting their life across several apps. Gamification keeps them going on low-energy days.

A wider audience will be defined later through user research. Until then, do not design for an imagined audience.

## Product Purpose

Tales of Seasons is a gamified personal organization tool based on RPG systems. Success is the developer becoming more productive and organized, with fewer tasks piling up and being left aside.

## Positioning

- **Everything in one place.** Habits, tasks, projects, goals, and gamification work together in a single tool, so there is no need to split life across several apps.
- **Gamification that motivates.** Gamification is what keeps the developer going on low-energy days, so it is a core part of the product, not decoration.
- **Clear, not cluttered.** Gamified apps such as Habitica are visually overwhelming and disorienting. Tales of Seasons keeps the interface clear.
- **Ready to use.** Unlike Notion, the developer does not build the system themselves. The structure and the connections between items, such as XP, coins, items, gains and losses, come built in.
- **Plan ahead.** Recurring habits and tasks show on future days, not only on the day they happen, so the calendar can be planned.

## Vocabulary

Tales of Seasons has its own vocabulary. Use the code name in code and the UI name in the interface.

| Code | UI (pt-BR) | Meaning | MVP |
|---|---|---|---|
| `User` | Usuário | The person: email, password, and authentication. | Yes |
| `Character` | Personagem | The user's in-app version: nickname, level, and XP. Completes actions. Basic avatar customization (hair, eyes) is planned after the MVP. | Yes |
| `Action` | Ação | Everything that can be completed is an action, with a start, middle, and end, such as habits, tasks, quests, and missions. Coins, for example, are not actions. | Yes |
| `Habit` | Hábito | An action meant to become automatic in daily life, tracked by frequency. Builds a streak. Example: drinking water daily. | Yes |
| `Streak` | Ofensiva | Consecutive days of a habit without failures. | Yes |
| `Task` | Tarefa | Something that must be done in a planned way, even when recurring. Example: taking out the trash every Tuesday, Thursday, and Saturday. | Yes |
| `Quest` | Quest | A goal. Usually lasts one season. | Yes |
| `Mission` | Missão | A project. | Yes |
| `Adventure` | Aventura | A theme or hobby outside the plan, explored in spare time during the day. | Yes |
| `Attribute` | Atributo | An area of life, with its own XP and level. Each one has a fixed definition and cannot be customized yet. Examples: Lazer (rest, hobbies, happiness) and Ambiente (home chores). | Yes |
| `Experience` | XP | Earned by completing actions. Belongs to the character and to each attribute. | Yes |
| `Level` | Nível | The level of the character or of an attribute, based on the XP earned. | Yes |
| `Achievement` | Conquista | An achievement unlocked inside the app. | Yes |
| `Priority` | Prioridade | 1 to 5 points on habits and tasks: how important completing it is. Higher priority means more coins gained on completion and more coins lost on failure. | Yes |
| `Difficulty` | Dificuldade | 1 to 5 points on habits and tasks: how hard or long it is. No effect in the MVP. | Yes |
| `Week` | Semana | 7 days, following the real calendar. | Yes |
| `Cycle` | Ciclo | 4 weeks. | Yes |
| `Season` | Estação | 3 complete cycles. | Yes |
| `Coin` | Moeda | Gained or lost with each action. | Yes |
| `Market` | Mercado | Where items are bought. | Yes |
| `Item` | Item | Bought with coins. Customizable. | Yes |
| `Mana` | MP | The character's energy. Completing actions spends it, more for harder ones; Lazer actions recover it instead. | No |
| `Health` | HP | The character's life. Lost when actions fail; higher priority means a bigger loss. | No |
| `CharacterClass` | Classe | To be explained during the project. | No |

## Rules

Rules every feature must keep:

- **Only weeks follow the real calendar.** Cycles and seasons run on their own count and never align with calendar months or seasons.
