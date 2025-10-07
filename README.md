# 🛒 CrownAuction – Online Auction System

**CrownAuction** a full-stack ASP.NET Core online auction platform with real-time bidding, product listings, and secure database integration using Entity Framework Core and SQL Server. It is a web-based auction platform developed using **ASP.NET Core MVC** and **Entity Framework Core**, designed to provide users with a secure and interactive online marketplace.  
It enables users to list, bid, and purchase products in real-time, with a robust admin dashboard for managing users, products, and auctions.

---

## 🚀 Features and 📸 Screenshots

- 🧑‍💼 *User Roles* – Admin, Seller, and Bidder access control.
- <img width="1883" height="861" alt="Screenshot 2025-03-31 195550" src="https://github.com/user-attachments/assets/8da30991-9064-4056-81c5-deed58473ae8" />


- ⏱ *Real-time Bidding* – Dynamic auction updates with countdown timers.
- <img width="1919" height="578" alt="Screenshot 2025-03-31 195652" src="https://github.com/user-attachments/assets/c1921a26-a5f0-4710-8744-2f6acd0f640b" />


- 📦 *Product Management* – Add, edit, and categorize products easily.
- <img width="1919" height="544" alt="Screenshot 2025-03-31 195905" src="https://github.com/user-attachments/assets/08867fbd-b305-4fa8-982d-ecdc8118a206" />


- 💳 *Secure Transactions* – Integrated with SQL Server for secure data handling.
- <img width="1883" height="861" alt="Screenshot 2025-03-31 195550" src="https://github.com/user-attachments/assets/ff884cfc-4d5f-4a13-b39e-b3e923b31eaf" />


- 📊 *Admin Dashboard* – Manage users, products, bids, and analytics.
- <img width="1889" height="857" alt="Screenshot 2025-10-06 201442" src="https://github.com/user-attachments/assets/edd5ee6c-8846-45c6-8b21-edd0a3300906" />


- 📱 *Responsive UI* – Clean, mobile-friendly design with Bootstrap / Tailwind CSS.
- <img width="1892" height="852" alt="Screenshot 2025-03-31 195330" src="https://github.com/user-attachments/assets/0b5ba1b9-ac5e-467d-94ce-a34db36d8627" />


- 🔐 *Authentication* – ASP.NET Core Identity for secure login & registration.
- <img width="1908" height="493" alt="Screenshot 2025-03-31 200214" src="https://github.com/user-attachments/assets/cc02fd79-913e-4c33-b5a4-da831f1d6c3c" />



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
