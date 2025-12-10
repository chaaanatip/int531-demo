## 🚀 How to Use

### 1️⃣ Create your environment file

Copy the example environment file:

```bash
cp .env.example .env
```

Update the variables inside `.env` as needed.

---

### 2️⃣ Start the full stack (App + MariaDB)

```bash
docker-compose up -d --build
```

Your app should now be available at:

👉 **[http://localhost:3000](http://localhost:3000)**

---

### 3️⃣ Stop the services (optional)

```bash
docker-compose down
```

---

### 4️⃣ (Optional) Rebuild everything from scratch

```bash
docker compose down
docker compose up -d --build
```
# int531-demo
