# Auto-Battle Sandbox – UE4 C++ Final Project

A minimal real-time auto-battler demo built with **Unreal Engine 4.27** and **C++**, developed as a final assignment for [Your Course Name]. The game features autonomous units that automatically navigate and attack enemy structures using UE4's AI and navigation systems.

> ✅ Meets all course requirements:  
> - Written in **C++** (with Blueprint integration)  
> - Uses **Git** for team collaboration  
> - Fully functional Windows executable  
> - Includes STL, C++11/14 features, and OOP design (inheritance & polymorphism)

---

## 🎮 Gameplay Overview

- Click the **"Spawn Warrior"** or **"Spawn Archer"** button to deploy units.
- Units automatically pathfind to the enemy base using **NavMesh**.
- Upon reaching attack range, they deal damage over time.
- Destroy the red enemy base to win!

This is a simplified prototype inspired by auto-battler mechanics (e.g., *Clash of Clans*), focusing on core systems rather than full gameplay depth.

---

## 🛠️ Technical Features

| Feature | Implementation |
|--------|----------------|
| **Core Architecture** | C++ classes (`AUnit`, `ABase`, `AGameMode`) with inheritance and virtual functions |
| **AI & Navigation** | `AAIController` + `UNavigationSystemV1` + NavMesh Bounds Volume |
| **Polymorphism** | `AWarrior` and `AArcher` override `Attack()` from base `AUnit` class |
| **UI Integration** | UMG widgets call C++ functions via `UFUNCTION(BlueprintCallable)` |
| **Modern C++** | `std::vector`, `auto`, `nullptr`, range-based loops |
| **Resource Safety** | Input validation and null checks to prevent crashes |

---

## 🧑‍💻 Team Members

| Name | Role | Responsibilities |
|------|------|------------------|
| [Your Name] | Programmer | C++ core logic, damage system, game state |
| [Teammate 1] | AI & Behavior | Unit AI, pathfinding, combat behavior |
| [Teammate 2] | UI & Integration | UMG interface, scene setup, testing & packaging |

> All members contributed C++ code and participated in Git-based collaboration.

---

## ▶️ How to Run

### Prerequisites
- Windows 10/11
- Visual Studio 2019 or 2022 (with C++ desktop development workload)
- Unreal Engine **4.27** (installed via Epic Launcher)

### From Source (Recommended for Grading)
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/AutoBattleSandbox.git