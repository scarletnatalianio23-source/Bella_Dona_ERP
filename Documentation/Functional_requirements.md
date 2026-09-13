# Functional Requirements

## Introduction

Functional requirements describe the main functions that Bella Dona ERP should have.

These requirements were defined based on the current needs of Bella Dona and the analysis of similar applications.

The main areas of the system are:

- Inventory.
- Sales and Billing.
- Customer Management.
- Suppliers and Purchasing.
- Reports.

---

# Functional Decomposition Tree

```text
BELLA DONA ERP
 1. Inventory
│   │
│   ├── 1.1 Product Management
│   │   ├── Register products
│   │   ├── Edit products
│   │   └── Add product information
│   │
│   └── 1.2 Stock Management
│       ├── Register stock entries
│       ├── Register stock exits
│       └── Check available stock
│
├── 2. Sales and Billing
│   │
│   ├── 2.1 Sales Management
│   │   ├── Register sales
│   │   ├── Check product availability
│   │   └── Check orders
│   │
│   └── 2.2 Billing
│       ├── Generate receipts
│       └── Save sales information
│
├── 3. Customer Management
│   │
│   ├── 3.1 Customer Information
│   │   ├── Register customers
│   │   └── Update customer information
│   │
│   └── 3.2 Customer History
│       ├── Check previous orders
│       └── Record style preferences
│
├── 4. Suppliers and Purchasing
│   │
│   ├── 4.1 Supplier Management
│   │   ├── Register suppliers
│   │   └── Update supplier information
│   │
│   └── 4.2 Purchasing
│       ├── Register purchases
│       └── Manage purchase orders
│
└── 5. Reports
    │
    ├── 5.1 Sales Reports
    │   ├── Check sales information
    │   └── Check revenue
    │
    └── 5.2 Inventory Reports
        ├── Check stock information
        └── Identify best-selling products
```



# Inventory Requirements

## FR-01 Product Registration

The system should allow authorized users to register new products.

## FR-02 Product Editing

The system should allow authorized users to update product information.

## FR-03 Product Classification

The system should allow products to be classified according to characteristics such as material, chain type, charm, and style.

## FR-04 Stock Entries

The system should allow the inventory manager to register products that enter the inventory.

## FR-05 Stock Exits

The system should allow the inventory manager to register products that leave the inventory.

## FR-06 Stock Consultation

The system should allow authorized users to check the available quantity of products.

## FR-07 Inventory Alerts

The system should show an alert when the quantity of a product is low.



# Sales and Billing Requirements

## FR-08 Sales Registration

The system should allow the salesperson to register daily sales.

## FR-09 Product Availability

The system should allow the salesperson to check product availability before registering a sale.

## FR-10 Order Tracking

The system should allow users to check customer orders.

## FR-11 Receipt Generation

The system should allow the generation of a digital receipt for a registered sale.


# Customer Requirements

## FR-12 Customer Registration

The system should allow authorized users to register customer information.

## FR-13 Customer Update

The system should allow authorized users to update customer information.

## FR-14 Customer History

The system should allow authorized users to check previous customer orders.

## FR-15 Customer Preferences

The system should allow customer style preferences to be recorded when this information is available.



# Supplier and Purchasing Requirements

## FR-16 Supplier Registration

The system should allow authorized users to register suppliers.

## FR-17 Supplier Information

The system should allow authorized users to update supplier information.

## FR-18 Purchase Registration

The system should allow purchases to be registered.

## FR-19 Purchase Orders

The system should allow users to keep track of purchase orders.


# Reports Requirements

## FR-20 Sales Reports

The system should provide basic information about sales.

## FR-21 Revenue Information

The system should allow authorized users to check basic revenue information.

## FR-22 Inventory Reports

The system should provide information about current inventory.

## FR-23 Best-Selling Products

The system should allow users to identify the products with the highest number of sales.


# User Roles

| User | Main Functions |
|---|---|
| Administrator | Manage the main modules of the system. |
| Salesperson | Register sales and check product availability. |
| Inventory Manager | Manage product entries, exits, and stock. |
| Customer | Consult products and make purchase requests if included in the project. |



# Added Value

Bella Dona ERP will have functions focused on the characteristics of the business.

Some of the proposed added value is:

- Gothic product classification.
- Material classification.
- Chain type classification.
- Charm classification.
- Product images.
- Inventory alerts.
- Customer style preferences.

The purpose is to create a system that fits the business instead of using a general solution without customization.