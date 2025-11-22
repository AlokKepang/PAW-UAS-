LOGIN CREDENTIALS
--------------------------
Direktur:
- Username: direktur
- Password: password123

Manajer Unit:
- Username: manajer
- Password: password123

Kasir:
- Username: kasir1
- Password: password123

Logistik:
- Username: logistik
- Password: password123

Admin TI:
- Username: admin
- Password: password123

==============================================
STRUKTUR FOLDER PROJECT
==============================================

sistem-ritel-abc/
├── app/
│   ├── Http/
│   │   ├── Controllers/
│   │   │   ├── AuthController.php
│   │   │   ├── DashboardController.php
│   │   │   ├── ProductController.php
│   │   │   ├── CustomerController.php
│   │   │   ├── SupplierController.php
│   │   │   ├── TransactionController.php
│   │   │   ├── EmployeeController.php
│   │   │   ├── AttendanceController.php
│   │   │   ├── PurchaseOrderController.php
│   │   │   ├── StockCardController.php
│   │   │   ├── ReportController.php
│   │   │   ├── SalaryPaymentController.php
│   │   │   └── UserController.php
│   │   └── Middleware/
│   │       └── CheckRole.php
│   └── Models/
│       ├── Role.php
│       ├── User.php
│       ├── Product.php
│       ├── Customer.php
│       ├── Supplier.php
│       ├── Employee.php
│       ├── Shift.php
│       ├── Attendance.php
│       ├── Transaction.php
│       ├── TransactionDetail.php
│       ├── StockCard.php
│       ├── PurchaseOrder.php
│       └── SalaryPayment.php
├── database/
│   ├── migrations/
│   │   ├── xxxx_create_roles_table.php
│   │   ├── xxxx_create_users_table.php
│   │   ├── xxxx_create_suppliers_table.php
│   │   ├── xxxx_create_products_table.php
│   │   ├── xxxx_create_customers_table.php
│   │   ├── xxxx_create_employees_table.php
│   │   ├── xxxx_create_shifts_table.php
│   │   ├── xxxx_create_attendances_table.php
│   │   ├── xxxx_create_transactions_table.php
│   │   ├── xxxx_create_transaction_details_table.php
│   │   ├── xxxx_create_stock_cards_table.php
│   │   ├── xxxx_create_purchase_orders_table.php
│   │   └── xxxx_create_salary_payments_table.php
│   └── seeders/
│       ├── RoleSeeder.php
│       ├── UserSeeder.php
│       ├── ShiftSeeder.php
│       ├── SupplierSeeder.php
│       ├── ProductSeeder.php
│       └── CustomerSeeder.php
├── resources/
│   └── views/
│       ├── layouts/
│       │   ├── app.blade.php
│       │   └── sidebar.blade.php
│       ├── auth/
│       │   ├── login.blade.php
│       │   └── profile.blade.php
│       ├── dashboard/
│       │   ├── direktur.blade.php
│       │   ├── manajer.blade.php
│       │   ├── kasir.blade.php
│       │   ├── logistik.blade.php
│       │   └── admin.blade.php
│       ├── products/
│       │   ├── index.blade.php
│       │   ├── create.blade.php
│       │   ├── edit.blade.php
│       │   ├── show.blade.php
│       │   ├── conversion.blade.php
│       │   └── stock-opname.blade.php
│       ├── customers/
│       │   ├── index.blade.php
│       │   ├── create.blade.php
│       │   ├── edit.blade.php
│       │   └── show.blade.php
│       ├── suppliers/
│       │   ├── index.blade.php
│       │   ├── create.blade.php
│       │   ├── edit.blade.php
│       │   └── show.blade.php
│       ├── transactions/
│       │   ├── index.blade.php
│       │   ├── pos.blade.php
│       │   ├── show.blade.php
│       │   └── print.blade.php
│       ├── employees/
│       │   ├── index.blade.php
│       │   ├── create.blade.php
│       │   ├── edit.blade.php
│       │   └── show.blade.php
│       ├── attendances/
│       │   ├── index.blade.php
│       │   ├── create.blade.php
│       │   └── edit.blade.php
│       ├── purchase-orders/
│       │   ├── index.blade.php
│       │   ├── create.blade.php
│       │   └── show.blade.php
│       ├── stock-cards/
│       │   ├── index.blade.php
│       │   └── by-product.blade.php
│       ├── salaries/
│       │   ├── index.blade.php
│       │   └── generate.blade.php
│       ├── reports/
│       │   ├── daily.blade.php
│       │   ├── stock.blade.php
│       │   ├── sales.blade.php
│       │   ├── profit.blade.php
│       │   ├── salary.blade.php
│       │   └── laba-rugi.blade.php
│       └── users/
│           ├── index.blade.php
│           ├── create.blade.php
│           └── edit.blade.php
└── routes/
    └── web.php
