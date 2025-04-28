## **Setup Instructions**

### **1. Clone the Repository**

```bash
git clone https://github.com/redsoftware-hq/global-scoring-be-app.git
cd project
```

### **2. Install Dependencies**

```bash
npm install
```

### **3. Configure Environment Variables**

Create a `.env` file in the root directory and configure the following:

```env
PORT=3000
MONGODB_URL=<your-mongo-db-uri>  # Or MONGO_URI, adjust to your code
EMAIL_USER=<default-master-email>
EMAIL_PASS=<default-master-email-pass>
RESET_PASSWORD_SECRET=<reset-pass-secret>
ACCESS_TOKEN_SECRET=<acces-token>
FRONTEND_URL=<frontend-url>
# REDIS_URL=<your-redis-url>  # If you are using Redis, uncomment and provide the URL.
```

### **4. Run the Application**

```bash
npm start
```

### **4. Create Dummy Data**

```bash
npm run seed
```
