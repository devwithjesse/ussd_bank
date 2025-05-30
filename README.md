💳 SmartBank USSD Banking Simulation
A fully interactive, menu-driven Python-based USSD Banking System that simulates real-life mobile banking operations through the command line. 
Built with a MySQL backend, the system models account creation, fund transfers, airtime/data purchases, bill payments, and transaction history — all via simple USSD-style inputs like *919#.

🚀 Features
Account creation with PIN protection
SmartBank-to-SmartBank & inter-bank transfers
Airtime and data purchases (self & others)
Utility bill payments (Electricity, TV)
Transaction history viewer
Customer care interface & PIN change
MySQL database with transaction logging

🛠 Tech Stack
Python 3.11+
MySQL (via PyMySQL)
Faker for generating dummy data
Modular architecture for maintainability

📁 Structure
ussd_bank/
├── app.py               # Entry point (simulates USSD codes)
├── menu.py              # Main menu interface
├── db/                  # Database connection & table setup
├── services/            # Functional modules (account, airtime, bills, etc.)
└── utils/               # Helper functions (generators, formatters)

📦 How to Run
Clone the repo:
git clone https://github.com/Ydevwithjesse/ussd-bank.git
cd ussd-bank

Set up your database in MySQL using the credentials in connect.py.
Run the app:
python app.py
