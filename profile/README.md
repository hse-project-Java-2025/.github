# "TimeTamer" SmartCalendar
**"TimeTamer" SmartCalendar** is an Android productivity app with gamification elements that helps users manage tasks, track progress, and stay motivated through achievements.

## Key Features
- **Task Management**: Create, edit, complete, and delete categorized tasks
- **Progress Tracking**: 
  - Daily/weekly statistics
  - Streak counters
  - Time tracking
- **Achievement System**:
  - Completion streaks
  - Task diversity badges
  - Time-based milestones
- **Smart Reminders**: Customizable notifications with pre-task alerts
- **User Profiles**: Secure login/registration with profile customization

<div align="center">
  <img src="https://github.com/user-attachments/assets/92517826-2dca-43d2-b207-5541186694b3" width="23%" alt="Settings"/>
  <img src="https://github.com/user-attachments/assets/2f5eda16-4066-45c5-8a5d-eba8468eedc9" width="23%" alt="Achievements"/>
  <img src="https://github.com/user-attachments/assets/bdc2a243-a8d2-47b9-bfda-bf3f3412f9fb" width="23%" alt="Statistics"/>
  <img src="https://github.com/user-attachments/assets/938e9b5a-ae16-49fe-bdf8-5217e25cf6df" width="23%" alt="Navigation"/>
</div>

---

## Project Architecture
```mermaid
graph LR
    A[Android Client] --> B[Spring Boot Server]
    B --> C[(PostgreSQL)]
    B --> D[OpenAI API]
    subgraph Components
    A --> E[Kotlin]
    A --> F[Jetpack Compose]
    B --> G[Java 21]
    B --> H[Spring Security]
    end
```

---

## Repository Structure
| Component | Repository | Tech Stack | Documentation |
|-----------|------------|------------|---------------|
| **Android Client** | [SmartCalendar-Android](https://github.com/hse-project-Java-2025/client) | Kotlin, Jetpack Compose | [Client README]() |
| **Backend Server** | [SmartCalendar-Server](https://github.com/hse-project-Java-2025/server) | Java 21, Spring Boot, PostgreSQL | [Server README](https://github.com/hse-project-Java-2025/server/blob/main/README.md) |


---

## Contributors
- [Pavel Usatov](https://github.com/UsatovPavel)
- [Timofey Ustinov](https://github.com/timustinov)
- [Dmitry Rusanov](https://github.com/DimaRus05)
- [Mikhail Minaev](https://github.com/minmise)

---

## License
Distributed under the MIT License - see [LICENSE](LICENSE) for details
