<div align="center">

# 🌳 Red-Black BST - Self-Balancing Search Tree

### Java · Data Structures · Algorithms

A generic red-black binary search tree with insertion, deletion, and in-order traversal - the tree stays balanced so lookups stay fast.

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Data Structures](https://img.shields.io/badge/Data_Structures-5382A1?style=for-the-badge&logoColor=white)
![Algorithms](https://img.shields.io/badge/Algorithms-6E4C13?style=for-the-badge&logoColor=white)

</div>

## What it does

| Feature | Detail |
|---|---|
| Self-balancing tree | Red-black rotations and recoloring keep the tree balanced after inserts and deletes |
| Generic implementation | Works with comparable key types, not just one hardcoded type |
| Full operations | Insertion, deletion, and in-order traversal |
| Test driver | `TestRedBlackTree` inserts 1–60 and deletes 1–20 to exercise the tree |

## Run

```bash
javac *.java
java TestRedBlackTree
```

## Files

- `RedBlackBST.java` - the generic red-black tree
- `TestRedBlackTree.java` - insert/delete test driver

> Originally a Data Structures & Algorithms (CIS 27) project, extracted here as a standalone repo from [java-algorithms-and-concurrency](https://github.com/afshinmalek/java-algorithms-and-concurrency).
