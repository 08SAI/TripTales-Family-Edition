# 🌍 TripTales-Family-Edition  

> ✈️ Track your family's adventures across the globe with a fun, interactive map!  
> Color-coded journeys, personalized profiles, and a beautiful visualization of your memories.  

---

## ✨ Features  

✅ **Multiple Family Members** — Add, edit, and manage each traveler.  
✅ **Country Tracking** — Record visited countries for every member.  
✅ **Interactive World Map** — SVG map with **color-coded highlights**.  
✅ **Persistent Storage** — Powered by PostgreSQL for reliable data saving.  
✅ **Clean UI** — Built with EJS templates + CSS for a smooth experience.  

---

## 📂 Project Structure  

```
TripTales-Family-Edition/
│── index.js
│── package.json
│── queries.sql
│── solution.js
│
├── public/
│   └── styles/
│       ├── main.css
│       └── new.css
│
└── views/
    ├── index.ejs
    └── new.ejs
```

---

## 🚀 Getting Started  

### 📌 Prerequisites  
- [Node.js](https://nodejs.org/)  
- [PostgreSQL](https://www.postgresql.org/)  

### ⚙️ Installation  

1️⃣ **Clone the Repository**  
```bash
git clone https://github.com/yourusername/family-travel-tracker.git
cd family-travel-tracker
```

2️⃣ **Install Dependencies**  
```bash
npm install
```

3️⃣ **Set Up the Database**  
- Create a PostgreSQL database named **`world`**  
- Run the SQL commands from `queries.sql` to create tables  

4️⃣ **Update DB Credentials**  
Modify database credentials in [`index.js`](8.5%20Family%20Travel%20Tracker/index.js) or [`solution.js`](8.5%20Family%20Travel%20Tracker/solution.js).  

---

## ▶️ Running the App  

Start with:  
```bash
node index.js
```
or  
```bash
node solution.js
```

🌐 Open your browser at: [http://localhost:3000](http://localhost:3000)  

---

## 📖 Usage Guide  

1. Select a **family member** or add a **new traveler**.  
2. Enter a **country name** to mark it as visited.  
3. Watch the **map update** with the member’s **unique color**.  
4. View the **total visited countries** in real-time.  

---

## 🛠 Tech Stack  

| Technology | Purpose |
|------------|---------|
| **Node.js** | Backend runtime |
| **Express** | Web framework |
| **EJS** | Dynamic templating |
| **PostgreSQL** | Database |
| **CSS** | Styling |

---

## 💡 Future Improvements  
- 🌎 Add city-level tracking  
- 📱 Make it mobile-responsive  
- 🗺 Offline mode for trip planning  

---

## 🤝 Contributing  

Pull requests are welcome! If you’d like to add a feature or fix a bug, please fork the repo and create a PR.  

---
