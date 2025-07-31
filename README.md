# 👥 Social Network Friend Recommendation (Spark)

## Overview
This project builds a **friendship recommendation engine** using social network data. The goal is to suggest potential new connections to users based on the number of mutual friends they share with others. This project simulates how platforms like LinkedIn or Facebook can **increase engagement and connections** by leveraging network graph analytics.

---

## Business Goal
- Improve **user engagement** on social platforms by recommending likely connections.
- Enhance **network growth** using data-driven mutual friend suggestions.

---

## Approach
1. **Data:** Adjacency list of users and their friends (mutual, undirected connections).
2. **Technology:** Big data processing with **Apache Spark (PySpark)** to handle large datasets efficiently.
3. **Algorithm:**
   - Identify second-degree connections (friends-of-friends).
   - Count mutual friends between each pair of non-connected users.
   - Rank potential connections and recommend top 10 for each user.
4. **Output:** List of recommended new friends per user, ordered by number of mutual friends.

---

## Key Results
- Generated top 10 friend recommendations for thousands of users.
- Example (User ID 11):
