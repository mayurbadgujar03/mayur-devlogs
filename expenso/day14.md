### 📍 Day 14 — June 14, 2025

#### 🧠 Frontend & Backend Full Link-Up

- ✅ **Login Page** now connected to the backend:
  - Captures form input and authenticates using `/api/v1/users/login`.
  - Displays real-time UX feedback (loading indicator or error messages).

- 🧑‍💼 **Profile Page Integration**:
  - Successfully fetched and rendered user data (name, email, avatar).
  - Rendered directly on page load using fetch call to profile endpoint.

#### 🛒 Dynamic Dashboard Items

- Connected dashboard to live item data from the backend.
- Rendered product cards dynamically using JS:
  - Pulled from `/api/v1/items` (filtered by logged-in user).
  - Attached MongoDB `_id` to each card with `data-id` for future interactions.

---

🎯 Huge leap today: All major frontend pages (Login, Dashboard, Profile) now **pull live data** from backend and reflect user state.

🛠️ Next: Make purchase interactions functional!
