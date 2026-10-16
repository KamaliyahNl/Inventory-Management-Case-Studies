# Inventory-Management-Case-Studies
Project Overview
This repository contains an Inventory Management to improve stock efficiency, reduce holding and ordering costs, and prevent stockouts. By applying inventory control techniques, specifically ABC Classification, Economic Order Quantity (EOQ) , and Reorder Point (ROP).

# Problem Statement
Jean-Marie Bourjolly’s restaurant has the following inventory items that it orders on a weekly basis:

<img width="334" height="362" alt="image" src="https://github.com/user-attachments/assets/2c93b505-7559-472d-ba26-caf413fddd26" />

a) Which is the most expensive item, using annual dollar volume?
b) Which are C items?
c) What is the annual dollar volume for all 20 items?
d) To extend into a more comprehensive inventory management dashboard, I incorporated additional inventory control techniques and assumptions: 1. Economic Order Quantity (EOQ): Estimates the optimal order quantity by considering annual demand, ordering costs, and inventory holding costs. 2. Reorder Point (ROP): Determines the inventory level at which a replenishment order should be placed, based on demand during lead time and any applicable safety stock, and 3. Inventory Simulation: Simulates inventory level fluctuations over a 30-day period to illustrate stock movements and replenishment decisions.

# Key Findings
1. Category A represents 30% of the inventory items, Category B represents 20%, and Category C represents 50%, based on the dashboard classification.
Inventory Prioritization: Category A items should receive closer monitoring because they represent a larger share of inventory value, while Category C items can generally be managed using simpler control procedures.
2. The dashboard identifies Fish Fillets as the item with the highest annual value, recorded at 74,360.
3. Category C represents 50% of the inventory items, equivalent to 10 out of 20 items (Table cloth, Eggs, Oil, Trash can liners, Garlic powder, Napkins, Order pads, Pepper, Sugar, and Salt). The items classified as Category C are generally the lower-priority items in terms of annual dollar volume. They typically require less stringent inventory control than Category A items.
4. The total annual dollar volume for all 20 inventory items is $423,852. This figure is calculated by multiplying the unit cost of each inventory item by its annual demand and summing the results across all 20 items.

# Recommendations:
1. Monitor stock levels regularly and initiate replenishment when inventory approaches the ROP.
2. Review EOQ and ROP periodically as demand, supplier lead time, and inventory costs change.
3. Prioritize Category A items for tighter stock monitoring, more frequent reviews, and improved demand forecasting.
4. Use a simplified replenishment policy for Category C items to reduce administrative effort.
5. Incorporate holding costs and ordering costs into inventory decisions to evaluate the trade-off between ordering frequency and average stock levels.

# Tools
Microsoft Excel
Inventory Management
Economic Order Quantity (EOQ)
Reorder Point (ROP)
ABC Analysis
However, the dashboard only displays the category distribution, not the individual item names assigned to Category C. Therefore, the exact C items cannot be identified from the dashboard alone.
