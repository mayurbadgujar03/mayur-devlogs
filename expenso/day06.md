# 📍 Day 6 — June 6, 2025

## ✅ Progress

* Developed purchase history API
* Used .populate("item") to return full item details
* Implemented clean status codes and response structure

## 📘 Learnings

* Mongoose .populate() needs field key, not the value
* How JSON responds with nested populated data

## ⚠️ Challenges

* Accidentally tried to .populate(user.createdBy) instead of .populate("item")