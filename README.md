# pharmacy_management_B-_Trees
This project is a robust and efficient inventory management system for pharmacies, designed with a B+ Tree data structure at its core. It efficiently handles insertion, deletion, search, and range queries on a large set of pharmaceutical data, ensuring optimal performance and real-time inventory tracking.

🚀 Features
🔍 Efficient Searching: Fast lookup of medicines, suppliers, and batches using B+ Tree indexing.

➕ Insertion & Deletion: Add or remove medicine records, batches, and supplier data with proper tree balancing.

🧾 Detailed Reporting:

View batch-wise information for each medicine.

Supplier-wise contribution and contact info.

Alert for low stock or expired medications.

📦 Batch Tracking: Manage individual batches with expiry, pricing, quantity, and sales data.

📁 File I/O Integration:

Reads from structured data files for medicines, suppliers, and batches.

Can be extended for database or live data integration.

📊 Statistics Generation: Identify top-selling products and suppliers with high turnover.

🧠 Data Structures Used
B+ Tree:

Acts as the backbone for all indexing and efficient data operations.

Custom implementation supporting range queries and node balancing.

Custom Linked Structures:

Medicine, Batch, and Supplier nodes are interconnected.

Multiple batches per medicine, with supplier mappings.

🗃️ Project Structure
BPLUS_dbms/
├── include/            # Header files (data structures, B+ Tree logic, utilities)
├── src/
│   ├── bplus/          # B+ Tree insert, delete, utilities
│   ├── file_io/        # Functions to load data from files
│   ├── io/             # Pretty-printers and display functions
│   └── main/           # Main entry point and user interface
├── data/               # Input data files: medicines, suppliers, batches
├── build/              # Compiled object files and final executable
└── scripts/
    └── Makefile        # Build script

