# 🔍 Hash Table & 🌳 Binary Search Tree (BST)

**Subject:** Algorithms and Data Structures (ADS) / Hashing & Trees  
**Name:** Abdanur

## 📌 Project Description
This repository contains two classic data structures written in **Java**:

1) A custom **Hash Table** (`MyHashTable<K, V>`) using chaining to handle collisions  
2) A **Binary Search Tree (BST)** (`BST<K, V>`) that supports insert, search, delete, and in-order traversal

The goal of this project is to practice how these structures work inside (without using Java’s built-in collections).

## 💡 Features
### Hash Table
- Generic `MyHashTable<K, V>`
- Collision handling with linked-list chaining
- Basic operations: `put`, `get`, `remove`, `contains`
- Bucket size / distribution check (example: `printBucketSizes()`)

### Binary Search Tree (BST)
- Generic key-value BST
- Operations: `put`, `get`, `delete`
- Size tracking
- In-order traversal using an iterator (loop through nodes)

## 📦 Technologies
- **Java**
- **Data Structures** (Hash Table, BST)
- Git + GitHub

## 🚀 How to Run
1) Clone the repository:
```bash
git clone https://github.com/MnstrsParago/ADS.HashTables.BST.git
cd ADS.HashTables.BST
```

2) Open the project in any Java IDE, or compile from terminal.

3) Run the demo/test classes:
- `Main.java` (hash table demo)
- `BSTTest.java` (BST demo)

Example compile/run (simple way):
```bash
javac *.java
java Main
```

## 📘 Reflection
This project helped me understand hashing and tree logic more clearly.  
Implementing collisions in a hash table and writing BST traversal made it easier to see how these structures manage data, and why performance depends on good design choices.
