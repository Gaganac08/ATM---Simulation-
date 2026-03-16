# 🏦 ATM Simulation - Java Project

A complete ATM (Automated Teller Machine) simulation built with **Core Java** using Object-Oriented Programming concepts. Great for freshers to showcase on GitHub!

---

## 🎯 Features

| Feature | Description |
|---|---|
| 🔐 Login | Secure login with Account Number + PIN |
| 💰 Check Balance | View available account balance |
| ⬆️ Deposit | Add money to your account |
| ⬇️ Withdraw | Withdraw cash (max Rs.20,000 per transaction) |
| 🔄 Transfer | Transfer funds to another account |
| 📋 Mini Statement | View last 5 transactions |
| 🔑 Change PIN | Update your 4-digit PIN securely |
| 🚪 Logout | Safe session logout |

---

## 🛠️ Tech Stack

- **Language:** Java (Core Java, No frameworks needed)
- **Concepts Used:** OOP, Classes, Inheritance, Collections, Exception Handling

---

## 📁 Project Structure

```
ATM-Simulation/
└── src/
    ├── Main.java                    ← Entry point
    └── atm/
        ├── model/
        │   └── Account.java         ← Account data + operations
        ├── service/
        │   ├── BankService.java     ← Manages all accounts
        │   └── ATMMachine.java      ← ATM logic & validation
        └── ui/
            └── ATMConsole.java      ← User interface (console)
```

---

## 🚀 How to Run

### Option 1: Using Terminal/Command Prompt

```bash
# Step 1: Go to src folder
cd ATM-Simulation/src

# Step 2: Compile all Java files
javac -d . Main.java atm/model/Account.java atm/service/BankService.java atm/service/ATMMachine.java atm/ui/ATMConsole.java

# Step 3: Run the program
java Main
```

### Option 2: Using an IDE (IntelliJ / Eclipse / VS Code)
1. Open the `src` folder as a project
2. Run `Main.java`

---

## 👤 Demo Accounts (Pre-loaded)

| Account No | PIN  | Account Holder | Balance     |
|------------|------|----------------|-------------|
| 1001       | 1234 | Rahul Sharma   | Rs. 50,000  |
| 1002       | 5678 | Priya Patel    | Rs. 30,000  |
| 1003       | 9999 | Amit Verma     | Rs. 75,000  |

---

## 📸 Sample Output

```
╔══════════════════════════════════════╗
║        🏦  JAVA ATM MACHINE          ║
║      Secure Banking Simulation       ║
╚══════════════════════════════════════╝

  Enter Account Number: 1001
  Enter PIN: 1234

  ✅ Welcome, Rahul Sharma!

╔══════════════════════════════════════╗
║  1. Check Balance                    ║
║  2. Deposit Money                    ║
║  3. Withdraw Money                   ║
║  4. Transfer Money                   ║
║  5. Mini Statement                   ║
║  6. Change PIN                       ║
║  7. Logout                           ║
╚══════════════════════════════════════╝
```

---

## 💡 OOP Concepts Used

- **Encapsulation** – Account data is private, accessed via methods
- **Abstraction** – ATMMachine hides complex logic from UI
- **Single Responsibility** – Each class has one clear job
- **Collections** – ArrayList for transaction history, HashMap for accounts
