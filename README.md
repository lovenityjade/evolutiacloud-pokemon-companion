# 🕹️ EvolutiaCloud Pokémon Companion  
### _A Wear OS Tamagotchi-style Watch Face powered by PokéAPI and Pokémon Showdown_

---

## 📖 Overview

**EvolutiaCloud Pokémon Companion** is a **Wear OS 3.5+ watch face** inspired by the classic **Pokémon Black & White** interface.  
It transforms your smartwatch into a **virtual Pokémon companion** — a tiny Tamagotchi Pokémon that grows, eats, sleeps, and evolves with your daily activity.

This project is part of the larger **EvolutiaCloud** ecosystem but is fully functional on its own, even without cloud sync or the Android companion app.

---

## 🌟 Features (Core Version)

✅ Random Pokémon hatches from an egg at startup (shiny chance included)  
✅ Animated **Gen V sprite** from [PokéAPI](https://pokeapi.co)  
✅ Real Pokémon **cries** from [Pokémon Showdown](https://play.pokemonshowdown.com)  
✅ XP progression based on player activity (steps, time, interactions)  
✅ Basic needs simulation (Hunger, Cleanliness, Sleep, Health)  
✅ HP bar, emotion emoji, and status icons (🍽️ 💊 🛁 😴)  
✅ Evolution with music and simple animation  
✅ Local notifications when your Pokémon needs attention  
✅ Data stored locally on the watch (no network required)  

---

## 🧩 Tech Stack

| Component | Technology |
|------------|-------------|
| **Language** | Kotlin |
| **Framework** | Jetpack Compose for Wear OS |
| **API Data** | [PokéAPI](https://pokeapi.co) (sprites, items, species) |
| **Audio** | [Pokémon Showdown](https://play.pokemonshowdown.com/audio/cries) `.ogg` |
| **Storage** | SharedPreferences / Room |
| **Sensors** | Health Services (Steps, Activity, Time Active) |
| **Graphics** | Canvas + AnimatedImageDrawable |
| **Notifications** | Wearable Local Notifications (Vibration + Sound) |

---

## 🧠 Project Structure

