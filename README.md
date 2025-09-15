# 📚 Urduversity – Digital Urdu Library System

**Urduversity** is a web-based digital library system focused on **Urdu poets, ghazals, and literature**.  
It is built using **Node.js** and **MongoDB**, featuring an **Admin Dashboard** for managing content such as poets and ghazals.

---

Demo:


## 🚀 Features
- 👨‍🎓 **Browse Urdu Poets** – View detailed profiles of Urdu poets.
- 📝 **Explore Ghazals** – Read and discover classic and modern Urdu ghazals.
- 🔍 **Search & Filter** – Quickly find poets or specific ghazals.
- 🛠️ **Admin Dashboard**  
  - ➕ Add new poets & ghazals  
  - ✏️ Edit poet/ghazal information  
  - 🗑️ Delete entries  
- 💾 **MongoDB Database** – All data stored securely.
- 🎨 **Responsive UI** – Easy to use on desktop and mobile.

---

## 🛠️ Tech Stack
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Frontend:** HTML, CSS, JavaScript (EJS / or your chosen template engine)  
- **Admin Dashboard:** Secured CRUD operations for content management  

---

## 📂 Project Structure
urduversity/
┣ 📂 config # Database & environment configs
┣ 📂 controllers # Logic for handling requests
┣ 📂 models # MongoDB models (Poets, Ghazals)
┣ 📂 routes # Express routes
┣ 📂 views # EJS templates (if applicable)
┣ 📂 public # CSS, JS, Images
┣ server.js # Entry point
┗ package.json



---

## ⚡ Getting Started

### Prerequisites
- Install [Node.js](https://nodejs.org/)  
- Install [MongoDB](https://www.mongodb.com/) locally or use MongoDB Atlas  

### Installation
```bash
# Clone this repository
git clone https://github.com/your-username/urduversity.git

# Navigate into the project
cd urduversity

# Install dependencies
npm install

# Start MongoDB (if local)
mongod

# Run the project
npm start
