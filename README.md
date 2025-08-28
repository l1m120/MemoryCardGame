# 🧠 Memory Card Game  

A full-stack **desktop application** built with **ScalaFX** and **Apache Derby**, designed to showcase **Object-Oriented Programming (OOP)** through an engaging memory game experience.  

🎮 Challenge yourself to match pairs of cards in the **fewest moves** and **fastest time** across multiple difficulty levels, with a persistent leaderboard to track your performance!  

---

## 🚀 About the Project
This project was developed as part of the **Object-Oriented Programming Fundamentals** subject.  
It demonstrates a practical application of **OOP design**, **GUI development**, and **database integration**, using a **Model-View-Controller (MVC)** architecture for scalability and maintainability.  

Players can:  
- Enter a username, play across multiple difficulty levels, and compete for leaderboard rankings.  
- Track real-time progress including moves, elapsed time, and matched pairs.  
- Enjoy music, pause/resume functionality, and access built-in rules/FAQs for guidance.  

---

## ✨ Key Features
- 🎨 **Graphical User Interface (GUI)** – Interactive, visually appealing interface powered by ScalaFX  
- 🎯 **Multiple Difficulty Levels** – Easy (4x4), Intermediate (6x4), Hard (6x6)  
- 🏆 **Leaderboard System** – Stores top 15 results per difficulty, sorted by moves & time  
- 📊 **Game Status Tracking** – Real-time updates of moves, matched pairs, and timer  
- 🎵 **Sound & Music Control** – Background music with toggle option  
- ⏸ **Pause & Resume** – Stop anytime and continue without losing progress  
- 📖 **Rules & FAQs Page** – Clear instructions for new players  
- 🗄 **Database Integration** – Persistent storage of results with **Apache Derby**  

---

## 🔑 Technical Highlights & OOP Principles

**Inheritance & Abstraction**  
- `GameResult` class leverages `StringProperty` and `ObjectProperty` to bind data directly to GUI components.  

**Parametric Polymorphism & Generics**  
- Generic components (e.g., `TableView<GameResult>`) used in Leaderboard design.  

**Collections**  
- Efficient use of Scala **mutable** collections (e.g., tracking matched pairs) and **immutable lists** (e.g., displaying top results).  

**Database Integration**  
- `Database.scala` handles all Derby operations: setup, saving, retrieving, and filtering results.  

**MVC Pattern**  
- Code structured into `model`, `util`, and `view` packages for modularity and scalability.  

---

## 🛠️ Technologies Used
- **Scala 2.12.19 & Java 8** – Core languages  
- **ScalaFX 8** – GUI framework  
- **Apache Derby** – Embedded relational database  
- **ScalikeJDBC** – SQL-based database interaction  
- **JavaFX Scene Builder** – Visual UI layout design  

---

## 🎬 Demo & Documentation
- 📺 **Video Walkthrough:** [YouTube Demo](https://www.youtube.com/watch?v=-D-FL23MTZA)  
- 📑 **Detailed Project Report:** *(Attach your PDF link here once uploaded)*  

---

## 🚀 Getting Started
To run the project locally:  

1. **Clone the repository**
   ```bash
   git clone [https://github.com/sunwaydcis/finalprojectv2-limm-21](https://github.com/l1m120/MemoryCardGame)
