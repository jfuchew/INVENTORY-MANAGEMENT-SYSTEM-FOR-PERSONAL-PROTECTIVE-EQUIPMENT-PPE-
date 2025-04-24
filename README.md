🧰 Inventory Management System for Personal Protective Equipment (PPE)
Course Project – Python Programming
By: Justin Chew, Lee Ken Yang, Lian Yuan Shen

📋 Description
This is a Python-based console application that helps the Department of Health manage PPE (Personal Protective Equipment) inventory. It records and monitors stock levels of PPE received from suppliers and distributed to hospitals. The system is modular, uses file-based storage, and follows object-oriented and functional programming practices.

✅ Key Features
🔐 Login System
Supports 4 inventory controllers with predefined credentials.

Allows up to 3 login attempts before access is denied.

📦 Inventory Management
Initial inventory setup for:

Head Covers (HC)

Face Shields (FS)

Masks (MS)

Gloves (GL)

Gowns (GW)

Shoe Covers (SC)

Stock tracked in boxes with default quantity of 100 per item.

Data saved in ppe.txt.

🏥 Hospital and Supplier Management
Add, view, and update:

Suppliers (suppliers.txt)

Hospitals (hospitals.txt)

Supplier and hospital codes used for tracking.

🔄 Inventory Update
Update item quantities by:

Receiving from suppliers

Distributing to hospitals

Checks for sufficient stock before distribution.

All distributions logged in distribution.txt.

🔍 Tracking & Reports
View:

Total available quantity of all items (sorted by item code)

Low-stock items (less than 25 boxes)

Generate reports:

Supplier list with supplied PPEs

Hospital list with total items received

Monthly transaction overview

🔎 Search Functionality
Search by item code to view distribution history.

Aggregates quantities by hospital code.

📂 Files Used
ppe.txt: Inventory records

suppliers.txt: Supplier details

hospitals.txt: Hospital details

distribution.txt: Distribution logs
