# Food Ordering System - Frontend

Plain HTML, CSS and JavaScript pages for the food ordering system.
It talks to the backend REST API (separate repo: `food-ordering-backend`).

## Pages
- `index.html` - login / register
- `menu.html` - list of restaurants (with star ratings)
- `restaurant.html` - restaurant menu, cart, rate with stars
- `orders.html` - my orders
- `admin.html` - admin dashboard

## Run
1. Start the backend first (see the backend README). It runs on http://localhost:8080
2. Open this folder in VS Code.
3. Install the extension **Live Server** (Ritwick Dey).
4. Right-click `index.html` -> **Open with Live Server**
   (opens http://127.0.0.1:5500/index.html)

If the backend uses another port, change `API_BASE` at the top of `js/app.js`.

Admin login: admin@food.com / admin123
