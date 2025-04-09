# Inventory Management System for Small Warehouses  
*A lightweight, web-based solution for tracking inventory, orders, and customer data in small-scale warehouses.*  

![Warehouse Dashboard](media/image17.png)  

---

## 🚀 **Quick Start Guide**

### **Prerequisites**
- XAMPP/WAMP/LAMP installed (Apache, MySQL, PHP)
- Modern web browser (Chrome, Firefox)

### **Installation**
1. **Download & Extract**  
   - Download all the files: (https://github.com/Akashtejareddy/Inventory-Management.git)
   -  Keep all the files in one folder (As Eg: 'inventoryms') and copy 'inventoryms'

2. **Deploy to Server**  
   - Paste `inventoryms` into your server’s root directory:  
     - **XAMPP**: `xampp/htdocs/`  
     - **WAMP**: `wamp/www/`  
     - **LAMP**: `/var/www/html/`  

3. **Set Up Database**  
   - Open **PHPMyAdmin**: [http://localhost/phpmyadmin](http://localhost/phpmyadmin)  
   - Create a database: `inventorydb`  
   - Import the SQL file: `inventoryms/SQL/inventorydb.sql`  

4. **Launch the Application**  
   - Start **Apache** and **MySQL** in XAMPP/WAMP.  
   - Access the system: [http://localhost/inventoryms](http://localhost/inventoryms)  

---

## 🔑 **Default Admin Credentials**  
- **Username**: `admin`  
- **Password**: `Test@123`  
*(Change these after first login for security!)*  

---

## 🌟 **Features for Small Warehouses**  
- **Inventory Tracking**  
  - Add/update stock levels, categories, and brands.  
  - Track low-stock items with alerts.  
- **Order Management**  
  - Process sales orders and generate invoices.  
  - Manage customer purchase history.  
- **Reporting**  
  - Generate daily/monthly stock and sales reports.  
  - Export data to CSV/PDF for audits.  
- **User-Friendly Interface**  
  - Simple dashboard for quick navigation.  
  - Minimal training required for staff.  

---

## 🛠️ **Tech Stack**  
| **Component**      | **Technology**                |  
|---------------------|-------------------------------|  
| **Frontend**        | HTML, CSS, JavaScript         |  
| **Backend**         | PHP                           |  
| **Database**        | MySQL                         |  
| **Server**          | Apache (via XAMPP/WAMP)       |  

---

## 📊 **Database Design**  
### **Key Tables**  
| **Table**          | **Purpose**                               |  
|---------------------|-------------------------------------------|  
| `tblproduct`       | Product details (name, SKU, stock, price) |  
| `tblorders`        | Order transactions (customer, date, total)|  
| `tblcustomer`      | Customer records (name, contact, address) |  
| `tbladmin`         | Admin login credentials                   |  

### **ER Diagram**  


---

## 📸 **Screenshots**  
| **Dashboard**      | **Manage Stock**       | **Sales Report**     |  
|---------------------|------------------------|----------------------|  
| ![Dashboard](media/image19.png) | ![Stock](media/image32.png) | ![Report](media/image41.png) |  

---

## ❓ **FAQ**  
**Q: Can this handle multiple warehouse locations?**  
*A: This version is optimized for single-location small warehouses. For multi-location support, customize the database schema.*  

**Q: How to add new users?**  
*A: Admins can add staff accounts via the dashboard (Admin → Manage Users).*    

---

**📧 Support**: akashteja1173677@gmail.com 
**🔗 GitHub**: [[Your Repository Link](#) ](https://github.com/Akashtejareddy/Inventory-Management) 

*Designed for simplicity and efficiency in small warehouse operations.* 🏭  
