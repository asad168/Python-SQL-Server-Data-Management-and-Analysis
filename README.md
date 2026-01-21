# Data Integration & Analytics Pipeline (SQL Server ↔ MongoDB ↔ Flask) 🚀

This project demonstrates a complete data lifecycle: from generating relational data in **SQL Server**, exposing it through a **Flask REST API**, migrating it to **MongoDB** for flexible storage, and performing deep **Data Analytics** with interactive visualizations.

## 🛠️ Tech Stack
- **Databases:** Microsoft SQL Server (Relational), MongoDB (NoSQL)
- **Backend/API:** Flask, Python (Requests, PyODBC)
- **Data Analysis:** Pandas, NumPy
- **Visualization:** Plotly (Interactive), Matplotlib, Seaborn

## 📋 Key Features
1. **Dynamic Data Generation:** Automated Python scripts to create schemas and populate SQL tables with sample retail data (Customers, Products, Sales).
2. **RESTful API:** A Flask-based backend allowing for CRUD operations (Create, Read, Update, Delete) on the SQL database.
3. **Data Migration Pipeline:** A custom migration script that transforms relational SQL rows into JSON-like documents for MongoDB, enabling hybrid data management.
4. **Multi-Source Analytics:**
   - **SQL Analytics:** Top-spending customers and best-selling products using complex joins.
   - **NoSQL Analytics:** Trend analysis and city-based filtering directly from MongoDB.
5. **Interactive Visuals:** Dynamic sales trends and branch comparisons using Plotly.

## ⚙️ Installation & Setup
1. **Database Connections:**
   - Ensure SQL Server is running and update the `get_connection()` function with your local `SERVER` name.
   - Ensure MongoDB is running locally on port `27017`.
2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
