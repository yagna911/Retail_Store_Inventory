# Retail_Store_Inventory
Retail Inventory Management System A scalable inventory management solution designed for retail businesses to efficiently track products, manage stock levels, handle suppliers, and generate sales and inventory reports.
Methodology architecture:

  Retail_Store_Inventory:
        |
        |---/Application ---/Components---|
        |                                 |---/Customer --->Customer.py, CustomerCLI.py, CustomerWindow.py, View.py
        |---/Data------------|            |             
        |                    |            |---Dashboard.py
        |--- migrate.py      |            |
        |                    |            |---/Reports--->PaymentDetails.py, View.py
        |--- run.py(main)    |            |
                             |            |---/Sales--->Receipt.py, View.py
                             |            |
                             |            |---/Stock--->CustomHeader.py, CustomHeaderModel.py, FilterModel.py, View.py
                             |
                             |
                             |--------dashboard.png, database.db, reports.png, sales.png, stock.png 
