# 🌐 Social Network Explorer (SNE)

## 📌 Project Overview
Social Network Explorer (SNE) is a Python-based command-line application that simulates a simplified social networking system.  
It demonstrates the practical implementation of core Data Structures and Algorithms such as **Hashing, Graphs, BFS, DFS, and Sorting**.

The system allows users to create profiles, connect with other users, explore relationships, and receive friend recommendations based on shared interests.

---

## 🎯 Features
- 👤 Add, update, and view user profiles  
- 🔗 Create and remove friendships between users  
- 🧭 Find shortest connection path using BFS (Degrees of Separation)  
- 🌳 Explore network connections using DFS (Depth-based search)  
- 🤝 Friend recommendation system based on common interests  
- 💻 Interactive menu-driven CLI interface  

---

## 🧠 Data Structures & Algorithms Used

### 1. Hashing (Dictionary)
- Used to store user profiles efficiently  
- Provides fast O(1) access for user data  

### 2. Graph (Adjacency List)
- Represents social connections  
- Nodes = Users, Edges = Friendships  

### 3. Breadth-First Search (BFS)
- Used to find the shortest path between two users  
- Helps in calculating degrees of separation  

### 4. Depth-First Search (DFS)
- Used for exploring friends-of-friends up to a certain depth  
- Helps in network exploration  

### 5. Sorting & Set Operations
- Used in recommendation system  
- Ranks users based on common interests  

---

## 📁 Project Structure
SocialNetworkExplorer/
│
├── profiles.py # User profile management
├── graph.py # Graph structure (connections)
├── bfs_dfs.py # BFS and DFS algorithms
├── recommendation.py # Friend recommendation system
├── main.py # Main CLI application
├── test_cases.py # Automated test cases
└── README.md # Project documentation


---

## ▶️ How to Run the Project

### 1. Run Main Application (Interactive Mode)
```bash
python main.py

Profiles:
1 : {'name': 'A', 'interests': ['music', 'coding', 'AI']}
2 : {'name': 'B', 'interests': ['sports', 'music']}

Shortest Path:
1 → 6 : [1, 6]

DFS (Depth 2):
[1, 2, 3, 5, 6]

Friend Recommendations:
[(4, 1), (5, 1)]
