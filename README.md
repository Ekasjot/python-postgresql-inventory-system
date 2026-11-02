# Smart Inventory and Billing System

A Python-based inventory and billing system built using PostgreSQL and Streamlit. It helps manage products, customers, sales, and billing through a simple dashboard.

### Features
- Manage products and customers
- Track inventory and stock levels
- Record sales and generate bills
- View revenue and sales analytics
- Track top-selling products and low-stock items

### Tech Stack
- Python
- PostgreSQL
- SQL
- Psycopg2
- Streamlit

### How to Run

1. Clone this repository:
   ```bash
   git clone <your-repository-url>
   ```
2. Install dependencies:
   ```bash
   pip install streamlit psycopg2-binary
   ```
3. Create a PostgreSQL database named `ecommerce`.
4. Update the database credentials in `Database.py`.
5. Run the application:
   ```bash
   python -m streamlit run app.py
   ```

**Note:** Configure your database credentials before running the project.
