## 🎮 POOBvsZombies: Tower Defense Java Game

<p align="center">
  <img src="https://cdn-icons-png.flaticon.com/512/226/226777.png" width="80" title="Java Logo"/>
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTC-gwee_9e_EtkamiqHKlSNYDWffhGx741Yg&s" width="80" title="Escuela Colombiana de Ingeniería Julio Garavito"/>
  <img src="https://static.wikia.nocookie.net/fifa/images/c/cd/EA_Sports.png/revision/latest?cb=20140505204917&path-prefix=es" width="80" title="EA SPORTS Logo"/>
</p>

### 🏆 Best OOP Project — Escuela Colombiana de Ingeniería Julio Garavito

**POOBvsZombies** is a fully object-oriented tower defense game inspired by *Plants vs Zombies*, developed in **Java** as part of the **POOB (Object-Oriented Programming)** course. This project blends software engineering best practices, advanced Java skills, and real-time gameplay mechanics to deliver an engaging and technically solid gaming experience.

> **Note:** This is not the complete version of the game. It represents only part of the general game.

---

### ⚙️ Features & Gameplay
- 🧠 AI-Driven Matches: PvE, PvP, and even Machine vs Machine
- 🌻 Real-time combat: Every plant and zombie runs as a thread
- 💾 Save/Load your matches with persistent state
- 🔧 Custom exceptions with error logging
- 💸 Resource & score management system
- 🧟 New plants and zombie types

---

### 🛠️ Tech Stack
- ☕ Java + Maven for build & dependency control
- 🧱 MVC Clean Architecture (Domain, UI, Logic separated)
- 🧬 UML Design: Class & Sequence Diagrams
- 🧪 Testing & Static Analysis with Eclipse + Jacoco
- 🔁 GitHub for version control and teamwork
- 🗃️ Custom `Queue-Priority` for entity control

---

### 📝 Current Game Elements

#### Plants:
- **Sunflower:** Generates suns over time.
- **Peashooter:** Attacks zombies by shooting peas.
- **Wall-nut:** Acts as a defensive barrier.
- **PotatoMine:** Explodes after a delay, eliminating nearby zombies.
- **ECIPlant:** Unique representation; generates a larger sun.

#### Zombies:
- **Basic:** The common, straightforward zombie.
- **Conehead:** Zombie with a protective cone, offering increased resistance.
- **Buckethead:** Highly resilient with a bucket as extra armor.
- **Brainstein:** Remains stationary and generates brains over time.
- **ECIZombie:** Shoots projectiles (POOmBas) periodically.

> These elements are part of an evolving project. Further game features, plants, zombies, and refined rules will be implemented in future versions.

---

### 🚀 Wanna Play? Clone & Run the Game || Download the branch

Here’s how to launch **POOBvsZombies** on your machine in minutes:

```bash
# 1. Clone the repository
git clone https://github.com/AnderssonProgramming/POOBvsZombies.git
cd POOBvsZombies

# 2. Clean and compile the code
mvn clean
mvn compile

# 3. Package into a runnable JAR
mvn package

# 4. Run the game (if exec plugin is configured)
mvn exec:java

# Or run the JAR manually (replace with actual JAR name)
java -jar target/poobvszombies.jar
```

> 🧰 Requirements: Java 8+ & Maven installed

---

### 📸 Including Screenshots

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/en/d/da/Plants_vs_Zombies_logo.png" width="180" title="Plants vs Zombies Logo"/>
</p>
<p align="center">
  
![pvz_main](https://github.com/user-attachments/assets/45de30b6-133a-4b58-b05e-14f6762c2390)
![pvsp](https://github.com/user-attachments/assets/3b4b8d08-2278-4e25-ba8b-374287040996)
![pvsm](https://github.com/user-attachments/assets/e9406b97-a1a4-4f74-a484-3a95c66dfd36)
![mvm](https://github.com/user-attachments/assets/edfd6bb2-6bfc-4b76-968b-c25e1985bb51)
![garden](https://github.com/user-attachments/assets/b19246fc-a4fb-4ccd-ad79-9bc8adf7a434)

---

> 🔗 Want to learn more? Reach out via:  
📧 andersson.sanchez-m@mail.escuelaing.edu.co
