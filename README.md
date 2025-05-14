# Practice Exercise - Order System

Read the data of an order with N items (N provided by the user). Then, display a  
summary of the order as shown in the example (next page). Note: the order timestamp must be  
the system's current time: `DateTime.Now`

---

### ✅ The system must:
- Read the data of an order with **N items** (N provided by the user).  
- The order timestamp must be the system's current time (`DateTime.Now`).  
- After reading the data, display a **summary** with the client's information, the order, and the purchased items with their subtotals and the total amount.

---

### 🧩 Class Diagram

![Diagrama de Classes](img.jpg)

---

### 🧾 Example output:

```bash
Enter cliente data:
Name: Alex Green
Email: alex@gmail.com
Birth date (DD/MM/YYYY): 15/03/1985

Enter order data:
Status: Processing
How many items to this order? 2

Enter #1 item data:
Product name: TV
Product price: 1000.00
Quantity: 1

Enter #2 item data:
Product name: Mouse
Product price: 40.00
Quantity: 2

ORDER SUMMARY:
Order moment: 20/04/2018 11:25:09
Order status: Processing
Client: Alex Green (15/03/1985) - alex@gmail.com
Order items:
TV, $1000.00, Quantity: 1, Subtotal: $1000.00
Mouse, $40.00, Quantity: 2, Subtotal: $80.00
Total price: $1080.00

