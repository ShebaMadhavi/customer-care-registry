Step 1: Install Required Software

They should have:

✅ Git
✅ Node.js (v18 or later)
✅ VS Code (optional)
✅ MongoDB Atlas account or your MongoDB connection string

Check versions:

node -v
npm -v
git --version
Step 2: Clone the Repository
git clone https://github.com/ShebaMadhavi/customer-care-registry/new/main?filename=README.md

Go into the project:

cd customer-care-registry
Step 3: Install Backend Dependencies
cd server
npm install
Step 4: Create .env

Inside the server folder create:

.env

Paste:

MONGO_URI=mongodb+srv://kartheekbendamuri79121_db_user:Zxcvbnm%40123@cluster0.3fdkfdk.mongodb.net/customer-care-registry?retryWrites=true&w=majority&appName=Cluster0
PORT=5000
Step 5: Start Backend
npm run dev

They should see:

✅ MongoDB Connected
🚀 Server running on port 5000

Leave this terminal running.

Step 6: Open Another Terminal
cd client
npm install
Step 7: Check API URL

In CreateTicket.jsx, make sure it is:

const API_BASE_URL = "http://127.0.0.1:5000/api/tickets";

If it points to your Render URL, change it back for local development.

Step 8: Start React
npm run dev

They'll get something like:

Local: http://localhost:5173/

Open it in the browser.

That's it 🎉 
<img width="1600" height="737" alt="WhatsApp Image 2026-07-15 at 22 15 43 (1)" src="https://github.com/user-attachments/assets/1248f056-eb0f-4eda-b98c-3e893d5f09f0" />
<img width="1600" height="736" alt="WhatsApp Image 2026-07-15 at 22 15 43" src="https://github.com/user-attachments/assets/1f0b61fa-ee19-43a9-aad8-cfee76123832" />
                                                                                                                                                                                          
