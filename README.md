# 🛒 CrownAuction – Online Auction System

**CrownAuction** a full-stack ASP.NET Core online auction platform with real-time bidding, product listings, and secure database integration using Entity Framework Core and SQL Server. It is a web-based auction platform developed using **ASP.NET Core MVC** and **Entity Framework Core**, designed to provide users with a secure and interactive online marketplace.  
It enables users to list, bid, and purchase products in real-time, with a robust admin dashboard for managing users, products, and auctions.

---

## 🚀 Features and 📸 Screenshots

- 🧑‍💼 *User Roles* – Admin, Seller, and Bidder access control.
- <img width="1883" height="861" alt="Screenshot 2025-03-31 195550" src="https://github.com/user-attachments/assets/886cc158-b43f-4d46-a0bc-3056b1c7ff57" />

- ⏱ *Real-time Bidding* – Dynamic auction updates with countdown timers.
- <img width="1919" height="578" alt="Screenshot 2025-03-31 195652" src="https://github.com/user-attachments/assets/68233b9a-67f7-47dd-80e1-8dcf11c8b6b3" />

- 📦 *Product Management* – Add, edit, and categorize products easily.
- <img width="1919" height="544" alt="Screenshot 2025-03-31 195905" src="https://github.com/user-attachments/assets/f311045e-d170-4868-848e-208caaf87c79" />

- 💳 *Secure Transactions* – Integrated with SQL Server for secure data handling.
- <img width="1883" height="861" alt="Screenshot 2025-03-31 195550" src="https://github.com/user-attachments/assets/6206d62b-e124-4ba8-a4cb-caa4c5362e25" />

- 📊 *Admin Dashboard* – Manage users, products, bids, and analytics.
- <img width="1888" height="857" alt="image" src="https://github.com/user-attachments/assets/6d4d3b24-c621-483c-acab-e76f4103a239" />

- 📱 *Responsive UI* – Clean, mobile-friendly design with Bootstrap / Tailwind CSS.
- <img width="1892" height="852" alt="Screenshot 2025-03-31 195330" src="https://github.com/user-attachments/assets/214877d8-941e-497e-9888-c81ddac7ef47" />

- 🔐 *Authentication* – ASP.NET Core Identity for secure login & registration.
- <img width="1908" height="493" alt="Screenshot 2025-03-31 200214" src="https://github.com/user-attachments/assets/62753ef0-1f33-4782-a932-ea7645b9d18b" />


## 🧰 Tech Stack

| Category | Technology |
|-----------|-------------|
| *Frontend* | HTML, CSS, JavaScript |
| *Backend* | ASP.NET Core MVC |
| *Database* | Microsoft SQL Server |
| *ORM* | Entity Framework Core |
| *Language* | C# |
| *IDE* | Visual Studio 2026 |
| *Version Control* | Git & GitHub |

---

## ⚙ Project Setup

1. *Clone the Repository*
   bash
   git clone https://github.com/<your-username>/AuctionPro.git
   cd AuctionPro
`

2. *Configure Database Connection*

   * Open appsettings.json
   * Update your SQL Server connection string:

     json
     "ConnectionStrings": {
       "DefaultConnection": "Server=YOUR_SERVER;Database=AuctionProDB;Trusted_Connection=True;TrustServerCertificate=True;"
     }
     

3. *Apply Migrations*

   bash
   Add-Migration "InitialMgr"
   Update-Database
   

4. *Run the Application*

   bash
   dotnet run
   

   Then open your browser at:
   *[http://localhost:5000](http://localhost:5000)*

---

## 📈 Future Enhancements

* 🤖 AI-powered bid price prediction
* 📧 Email / SMS notifications for auction updates
* 🔗 Blockchain integration for transparent bidding history
* 💬 Live chat between buyers and sellers

---

## 👨‍💻 Developers

* *Suraj Deepak Vishwakarma*
* *Prof. Ankita Mathur*
  Under the guidance of Mumbai University

---

## 🪪 License

This project is licensed under the [MIT License]
That would make your GitHub project look even more professional.
```
