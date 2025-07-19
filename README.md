# 🏦 ATM Simulation - Modern Web Frontend

A beautiful, modern web-based ATM simulation with neon black theme and full functionality.

## 📁 Project Structure

```
ATM simulation/
├── app.py                 # Flask backend server
├── templates/
│   └── index.html        # Main frontend (HTML/CSS/JS)
├── ATM simulation.py     # Original Python ATM code
├── requirements.txt      # Python dependencies
├── start_atm.bat        # Windows startup script
└── README.md            # This file
```

## ✨ Features

- **🎨 Neon Black Theme**: Modern dark UI with glowing effects
- **🔐 Secure Login**: Account number + PIN authentication
- **📝 New Account Creation**: Register new accounts with initial deposit
- **💰 Complete ATM Functions**:
  - View Balance (hidden by default)
  - Withdraw Cash (quick amounts + custom)
  - Deposit Money
  - Transfer Funds
  - Transaction History (separate page)
  - Change PIN
  - Print Receipt (separate page)
- **📱 Responsive Design**: Works on all devices
- **⚡ Real-time Updates**: Instant balance updates

## 🚀 Quick Start

1. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

2. **Run the server**:
   ```bash
   python app.py
   ```
   Or double-click `start_atm.bat` (Windows)

3. **Open browser**: `http://localhost:5000`

## 👤 Test Accounts

| Account | PIN | Name | Type | Balance |
|---------|-----|------|------|---------|
| 123456 | 1234 | Ankur Saini | Savings | ₹50,000 |
| 654321 | 4321 | Yashvardhan | Current | ₹75,000 |
| 789012 | 5678 | chiku | Savings | ₹25,000 |
| 345678 | 9012 | rahul | Premium | ₹1,00,000 |

## 🆕 New Account Creation

1. Click **"Open New Account"** button
2. Fill in details:
   - Full Name
   - Account Type (Savings/Current/Premium)
   - Initial Deposit (minimum ₹1)
   - 4-digit PIN
3. Click **"Create Account"**
4. Use the generated account number to login

## 🛠️ Technical Stack

- **Backend**: Flask (Python)
- **Frontend**: HTML5, CSS3, JavaScript
- **Theme**: Neon Black with CSS animations
- **API**: RESTful endpoints for all operations

## 📞 Support

For issues: Check console errors or contact 1800-123-4567

---

**Enjoy your modern ATM experience! 🏦✨** 
