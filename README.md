# 🚀 SAP ABAP Tabstrip Control – EKKO & EKPO Module Pool

## 📌 Overview
This project demonstrates a Module Pool program in SAP ABAP using a Tabstrip Control.

The application allows users to:
- Enter Purchase Order Header data (EKKO)
- Enter Purchase Order Item data (EKPO)
- Navigate between screens using tabs
- Save data into SAP database tables

---

## 🎯 Objective
To design a dialog program that:
- Uses Tabstrip Control for navigation  
- Separates Header and Item data screens  
- Performs database insert operations  
- Demonstrates SAP screen programming concepts  

---

## 🧩 Tables Used
- EKKO – Purchase Order Header  
- EKPO – Purchase Order Item  

---

## ⚙️ Program Details
**Program Name:** `ZMP05`

---

## 📺 Screen Details

### 🔹 Screen 2000 (Main Screen)
- Contains Tabstrip Control  
- Tabs:
  - TAB1 → Header Screen (2001)  
  - TAB2 → Item Screen (2002)  

---

### 🔹 Screen 2001 (Header – EKKO)
Fields:
- Company Code (BUKRS)  
- Vendor (LIFNR)  
- Document Type (BSTYP)  

Action:
- SAVE → Inserts data into EKKO  

---

### 🔹 Screen 2002 (Item – EKPO)
Fields:
- Purchase Order (EBELN)  
- Material (MATNR)  
- Quantity (MENGE)  

Action:
- SAVE1 → Inserts data into EKPO  

---

## 📤 Sample Output

- On clicking **SAVE**  
  → "Header Data Inserted Successfully"
  <img width="790" height="707" alt="image" src="https://github.com/user-attachments/assets/1f6e10bc-c745-4d86-963d-d6c89df5b86d" />

- On clicking **SAVE1**  
  → "Item Data Saved Successfully"  
<img width="742" height="704" alt="image" src="https://github.com/user-attachments/assets/723cea85-e0d4-45a9-83be-5e3acf7801b6" />

---

## 🔄 Process Flow
1. User opens the main screen (2000)  
2. Tabstrip is displayed  
3. User switches between Header and Item tabs  
4. Enters required data  
5. Clicks Save button  
6. Data is inserted into database tables  

---

## 💡 Key Features
- Tabstrip Control navigation  
- Multi-screen interaction  
- Separate handling of header and item data  
- Database insert operations  
- Simple and clean UI design  

---

🏷️ Tags
sap-abap, module-pool, tabstrip, ekko, ekpo, sap-ui, erp

  ENDCASE.

ENDMODULE.
