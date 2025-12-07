# AdoptyCo – Backend Server

This is the backend server for **AdoptyCo – Pet Adoption & Supplies Marketplace**, built with Node.js, Express, and MongoDB Atlas. It provides RESTful APIs for listings and orders with full CRUD functionality.

---

## 🌐 Live Server

[https://adoptyco.vercel.app/](https://adoptyco.vercel.app/)

---

## 📂 Tech Stack

* **Backend:** Node.js, Express.js, MongoDB Atlas  
* **Middleware:** CORS, dotenv  
* **Deployment:** Vercel  

---

## 🔗 API Endpoints

### Listings
| Endpoint                       | Method | Description                |
| ------------------------------ | ------ | -------------------------- |
| `/listings`                    | POST   | Create a listing           |
| `/listings`                    | GET    | Get all listings           |
| `/listings/recentListings`     | GET    | Get 6 most recent listings |
| `/listings/product/:id`        | GET    | Get single product details |
| `/listings/myListings/:email`  | GET    | Get listings by user       |
| `/listings/category/:category` | GET    | Get listings by category   |
| `/listings/update/:id`         | PUT    | Update listing             |
| `/listings/delete/:id`         | DELETE | Delete listing             |

### Orders
| Endpoint         | Method | Description               |
| ---------------- | ------ | ------------------------- |
| `/orders`        | POST   | Create an order           |
| `/orders`        | GET    | Get all orders            |
| `/orders/:email` | GET    | Get orders by buyer email |

---

## ⚙ Setup Instructions

1. Clone the repository:
```bash
git clone https://github.com/saadferozee/PH_assignment_10_server.git
````

2. Install dependencies:

```bash
npm install
```

3. Run the server:

```bash
npm run start
```

4. Ensure `.env` file contains:

```env
MONGODB_URI=your_mongodb_connection_string
PORT=desired_port_number
```

---

## 🔗 Author

**Saad Ferozee**
*GitHub:* [https://github.com/saadferozee](https://github.com/saadferozee)
*LinkedIn:* [https://www.linkedin.com/in/saadferozee/](https://www.linkedin.com/in/saadferozee/)

---