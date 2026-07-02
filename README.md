# 🗳️ Majority Vote Counter and Decision System

## 📌 Project Overview
This project models a committee consisting of six members:
P – President
V – Vice President
S – Secretary
T – Treasurer
X – Member 1
Y – Member 2
Each member casts a binary vote:
1 → YES
0 → NO
The system:
1) Counts the total number of YES votes (0–6).
2) Determines whether the proposal passes.

## ✅ Decision Rule
The proposal is approved if:
The number of YES votes is 4 or more, OR
There is a 3–3 tie, and the President votes YES.
Mathematically,
PASS=(N≥4)+P(N=3)
where:
N = total number of YES votes,
P = President's vote.
