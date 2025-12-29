# 🌱 GardenTale (Prototype)

![Godot Engine](https://img.shields.io/badge/Godot_Engine-4.x-blue?logo=godotengine&logoColor=white)
![Status](https://img.shields.io/badge/Status-Prototype-orange)
![License](https://img.shields.io/badge/License-MIT-green)

**GardenTale** — це прототип 2D-гри у жанрі *Farming RPG / Life Sim*, натхненний класикою жанру, такою як *Stardew Valley*.

Проєкт розроблено в рамках технологічної практики (2025) на базі компанії **Grass Business Labs**. Основна мета  створення гнучкої архітектури для подальшого масштабування в дипломний проєкт.

---

## 🎮 Функціональність (Features)

На даному етапі реалізовано ядро ігрового процесу (Core Loop):

- **Movement System:** Переміщення персонажа (Top-Down) з анімаціями та колізіями.
- **Inventory System:** Повноцінний інвентар з підтримкою **Drag & Drop**, стакуванням предметів та панеллю швидкого доступу (Hotbar).
- **Gathering & Resources:**
  - Руйнування об'єктів (дерева, каміння).
  - Система випадіння луту (Loot Drops).
  - Компонентна архітектура (`HurtComponent`), що дозволяє легко додавати нові руйнівні об'єкти.
- **NPC AI:** Тварини з базовим інтелектом, що патрулюють територію та мають різні стани (Idle/Walk).

---

## 📸 Скріншоти

| Ігровий процес |
|:---:|
| ![Gameplay](https://github.com/DESTROYchambo/Praktika-GardenTale-2025/blob/791629ef6e0ae5e45f497861c87118c6bd202b29/Screenshots/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20(500).png) |
| ![Gameplay](https://github.com/DESTROYchambo/Praktika-GardenTale-2025/blob/791629ef6e0ae5e45f497861c87118c6bd202b29/Screenshots/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20(501).png) |
| ![Gameplay](https://github.com/DESTROYchambo/Praktika-GardenTale-2025/blob/791629ef6e0ae5e45f497861c87118c6bd202b29/Screenshots/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20(502).png) |
| ![Gameplay](https://github.com/DESTROYchambo/Praktika-GardenTale-2025/blob/791629ef6e0ae5e45f497861c87118c6bd202b29/Screenshots/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20(503).png) |

---

## 🛠️ Технології

- **Рушій:** [Godot Engine 4.x](https://godotengine.org/)
- **Мова:** GDScript
- **Архітектура:** Компонентно-орієнтована (Composition over Inheritance), EventBus (Signals).
- **Графіка:** Pixel Art (Aseprite).

---
