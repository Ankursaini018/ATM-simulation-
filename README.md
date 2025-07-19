# 🏦 ATM Simulation - Modern Web Frontend

A beautiful, modern web-based frontend for the ATM simulation system with a responsive design and intuitive user interface.

## ✨ Features

- **Modern UI/UX**: Clean, responsive design with smooth animations
- **Secure Authentication**: Account number and PIN-based login
- **Complete ATM Functions**:
  - 💰 View Balance
  - 💸 Withdraw Cash (with quick amount options)
  - 💳 Deposit Money
  - 🔄 Transfer Funds
  - 📋 Transaction History
  - 🔐 Change PIN
  - 📄 Print Receipt
- **Real-time Updates**: Balance updates immediately after transactions
- **Mobile Responsive**: Works perfectly on all devices
- **Error Handling**: Comprehensive error messages and validation

## 🚀 Quick Start

### Prerequisites
- Python 3.7 or higher
- pip (Python package installer)

### Installation

1. **Clone or download the project files**

2. **Install Python dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application**:
   ```bash
   python app.py
   ```

4. **Open your browser** and navigate to:
   ```
   http://localhost:5000
   ```

## 👤 Test Accounts

Use these pre-configured accounts to test the system:

| Account Number | PIN | Name | Account Type | Balance |
|----------------|-----|------|--------------|---------|
| 123456 | 1234 | Ankur Saini | Savings | ₹50,000 |
| 654321 | 4321 | Yashvardhan | Current | ₹75,000 |
| 789012 | 5678 | chiku | Savings | ₹25,000 |
| 345678 | 9012 | rahul | Premium | ₹1,00,000 |

## 🎨 Features Overview

### Login Screen
- Clean, modern design with gradient background
- Secure PIN input with masked characters
- Loading animation during authentication

### Dashboard
- **User Information Card**: Displays name, account number, and type (balance hidden by default)
- **Service Grid**: 8 main ATM services in an intuitive grid layout
- **Balance Display**: Balance only shown when "View Balance" is clicked
- **Real-time Balance**: Updates immediately after transactions when visible

### Transaction Features

#### 💰 View Balance
- Displays current balance with account details
- Beautiful card-style presentation

#### 💸 Withdraw Cash
- Quick amount options (₹500, ₹1,000, ₹2,000, ₹5,000)
- Custom amount input
- Real-time balance validation
- Success/error feedback

#### 💳 Deposit Money
- Simple amount input
- Instant balance update
- Transaction confirmation

#### 🔄 Transfer Funds
- Recipient account validation
- Amount validation
- Transfer confirmation
- Real-time balance updates

#### 📋 Transaction History
- **Dedicated Page**: Full-page view with comprehensive transaction list
- Last 10 transactions with detailed timestamps
- Professional layout with hover effects
- Easy navigation back to dashboard

#### 🔐 Change PIN
- Current PIN verification
- New PIN validation (4 digits)
- PIN confirmation
- Security feedback

#### 📄 Receipt
- **Dedicated Page**: Full-page receipt view
- Professional receipt format with ASCII borders
- Account details and current balance
- Recent transaction history
- Print functionality for physical receipt
- Contact information

## 🛠️ Technical Details

### Backend (Flask)
- **Framework**: Flask 2.3.3
- **CORS**: Enabled for cross-origin requests
- **API Endpoints**: RESTful API design
- **Data Storage**: In-memory user data (same as original Python script)

### Frontend (HTML/CSS/JavaScript)
- **Design**: Modern, responsive design
- **Icons**: Font Awesome 6.0
- **Fonts**: Inter (Google Fonts)
- **Animations**: CSS transitions and transforms
- **Modals**: Custom modal system for different services

### API Endpoints
- `POST /api/login` - User authentication
- `GET /api/balance/<account_number>` - Get account balance
- `POST /api/withdraw` - Process withdrawal
- `POST /api/deposit` - Process deposit
- `POST /api/transfer` - Process fund transfer
- `GET /api/transactions/<account_number>` - Get transaction history
- `POST /api/change-pin` - Update PIN
- `GET /api/receipt/<account_number>` - Generate receipt

## 🎯 User Experience Features

- **Intuitive Navigation**: Clear service icons and labels
- **Visual Feedback**: Loading states, success/error messages
- **Responsive Design**: Works on desktop, tablet, and mobile
- **Accessibility**: Proper contrast, readable fonts, keyboard navigation
- **Error Prevention**: Input validation and confirmation dialogs

## 🔒 Security Features

- **PIN Masking**: PIN input is hidden during typing
- **Session Management**: User session handling
- **Input Validation**: Server-side validation for all inputs
- **Error Handling**: Secure error messages without exposing system details

## 📱 Mobile Responsiveness

The application is fully responsive and optimized for:
- Desktop computers
- Tablets
- Mobile phones
- Different screen orientations

## 🎨 Design Highlights

- **Modern Gradient Background**: Eye-catching visual appeal
- **Glass Morphism**: Translucent cards with backdrop blur
- **Smooth Animations**: Hover effects and transitions
- **Color-coded Services**: Different colors for different service types
- **Professional Typography**: Clean, readable fonts

## 🚀 Future Enhancements

Potential improvements for future versions:
- Database integration (SQLite/PostgreSQL)
- User registration system
- Email/SMS notifications
- Advanced security features (2FA)
- Transaction limits and restrictions
- Multi-language support
- Dark mode theme
- Offline functionality

## 📞 Support

For any issues or questions:
- Check the console for error messages
- Verify all dependencies are installed
- Ensure port 5000 is available
- Contact: 1800-123-4567 (as shown in receipt)

## 📄 License

This project is for educational purposes. Feel free to modify and enhance as needed.

---

**Enjoy your modern ATM experience! 🏦✨** 