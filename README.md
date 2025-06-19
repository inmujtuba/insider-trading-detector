# Insider Trading Detector

## Setup Instructions
1. **Start XAMPP MySQL**:
   - Open XAMPP Control Panel and start MySQL (and Apache for phpMyAdmin).
   - Verify: `C:\xampp\mysql\bin\mysql -u root` (or equivalent for macOS/Linux).

2. **Setup Database**:
   - Open `http://localhost/phpmyadmin`, create database `insider_trading`.
   - Import `db/setup.sql` via phpMyAdmin or run:
     ```bash
     C:\xampp\mysql\bin\mysql -u root < db/setup.sql