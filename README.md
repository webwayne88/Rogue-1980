# Rogue 1980  

A console-based roguelike game in Python, inspired by the classic Rogue (1980), implemented using the curses library.  

## Features  
- **Classic gameplay**: Explore procedurally generated dungeons, collect items, and battle monsters  
- **21 levels** with increasing difficulty  
- **5 enemy types** with unique behaviors (zombies, vampires, ghosts, etc.)  
- **Item system**: Weapons, armor, potions, scrolls, and food  
- **Character stats**: Health, strength, agility  
- **Fog of war** and limited visibility  
- **Leaderboard** with saved results  
- **3D mode** (in addition to the main 2D view)  

## Architecture  
The project follows a layered architecture:  
- **Presentation** – rendering and input (curses)  
- **Domain** – game logic and entities  
- **DataLayer** – progress saving (JSON)  

## Controls  
- **WASD** – movement  
- **H/J/K/E** – use items from inventory  
- **1-9** – select an item  

## Installation & Running  
Requires Python 3.x and the curses library:  
```
pip install windows-curses  # for Windows
```  

Run:  
```
python main.py
```

# Rogue 1980 (rus)

Консольная roguelike-игра на Python в стиле классической Rogue (1980), реализованная с использованием библиотеки curses.

## Особенности
- **Классический геймплей**: исследование случайно генерируемых подземелий, сбор предметов, бои с монстрами
- **21 уровень** с возрастающей сложностью
- **5 типов противников** с уникальным поведением (зомби, вампиры, привидения и др.)
- **Система предметов**: оружие, броня, зелья, свитки, еда
- **Характеристики персонажа**: здоровье, сила, ловкость
- **Туман войны** и ограниченная видимость
- **Таблица рекордов** с сохранением результатов
- **3D-режим** (дополнительно к основному 2D)

## Архитектура
Проект использует многослойную архитектуру:
- **Presentation** - рендеринг и ввод (curses)
- **Domain** - игровая логика и сущности
- **DataLayer** - сохранение прогресса (JSON)

## Управление
- **WASD** - перемещение
- **H/J/K/E** - использование предметов из инвентаря
- Цифры **1-9** - выбор предмета

## Установка и запуск
Требуется Python 3.x и библиотека curses:
```
pip install windows-curses  # для Windows
```

Запуск:
```
python main.py
```
