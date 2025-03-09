# CRUD-Operations-on-Sales-Dataset


This project is a simple **Sales Data Management System** built with Python and Pandas. It allows users to **create, read, update, and delete (CRUD)** sales records stored in a CSV file.

---

## 🚀 Features

✅ Create new sales records  
✅ Retrieve and view records by ID  
✅ Update existing records  
✅ Delete records  
✅ Prevent duplicate IDs  
✅ Handles empty datasets gracefully  

---

## 📂 File Structure

```
📁 sales_data_project/
│── sales_data.csv        # CSV file to store records
│── CRUD Operations on Sales Dataset.ipynb      # Python script for managing records
│── README.md             # Documentation (this file)
```

---

## 🛠️ Setup Instructions

### 1️⃣ Install Dependencies
Ensure you have **Python 3** installed, then install Pandas:
```sh
pip install pandas
```

### 2️⃣ Run the Script
Execute the Python script to initialize the dataset and perform operations:
```sh
python CRUD Operations on Sales Dataset.ipynb
```

---

## 📖 How to Use

### ▶️ Adding New Records
Modify the script to add new records like this:
```python
create_record({"ID": 1, "Product": "Laptop", "Quantity": 2, "Price": 1200, "Customer": "Alice"})
```

![Screenshot (355)](https://github.com/user-attachments/assets/edcdf889-b199-48d2-8fa8-99fb751d194e)



### 🔍 Reading a Record
```python
read_record(1)  # Retrieves record with ID 1
```

### ✏️ Updating a Record
```python
update_record(1, {"Price": 1100, "Quantity": 3})  # Updates record with ID 1
```

![Screenshot (356)](https://github.com/user-attachments/assets/eeec780a-7317-4c2e-ba0f-b00f28419dcb)


### ❌ Deleting a Record
```python
delete_record(2)  # Removes record with ID 2
```

![Screenshot (359)](https://github.com/user-attachments/assets/73684e5e-40d5-4dc5-a0e5-ae939561d3e3)
![Screenshot (358)](https://github.com/user-attachments/assets/b38e7eb1-e7c3-4182-b977-14505e036150)


---

## 📌 Notes
- The script **creates `sales_data.csv` automatically** if it doesn’t exist.
- It **ensures IDs are unique** when adding new records.
- It **converts ID values to integers** for accurate lookups.
