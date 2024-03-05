# Case-Customer-sales-database-analysis
# Case goal
Collected data from diverse sources and integrated them into analytical dataset to identify problem transactions and reveal the story behind the data through the rule based approach.  Utilized T-SQL queries in Azure SQL Database to analyze Sales performance by product, customer &amp; time Dimensions 
# Data base description
Customer(CustomerID, FirstName, MiddleName, LastName, CompanyName, EmailAddress)
CustomerAddress(CustomerID, AddressID, AddressType)
Address(AddressID, AddressLine1, AddressLine2, City, StateProvince, CountyRegion, PostalCode)
SalesOrderHeader(SalesOrderID, RevisionNumber, OrderDate, CustomerID, BillToAddressID, ShipToAddressID, ShipMethod, SubTotal, TaxAmt, Freight)
SalesOrderDetail(SalesOrderID, SalesOrderDetailID, OrderQty, ProductID, UnitPrice, UnitPriceDiscount)
Product(ProductID, Name, Color, ListPrice, Size, Weight, ProductModelID, ProductCategoryID)
ProductModel(ProductModelID, Name)
ProductCategory(ProductCategoryID, ParentProductCategoryID, Name)
ProductModelProductDescription(ProductModelID, ProductDescriptionID, Culture)
ProductDescription(ProductDescriptionID, Description)
# Data modeling
![c114fc7db20d73e1f715d8a89cf2d00](https://github.com/ethanzzz118/Case-Customer-sales-database-analysis/assets/110695227/91375579-c090-4209-a755-af2a9da8b6f1)
# Ad horc questions & solution
![8c454c62688dab16969beef1f95fa64](https://github.com/ethanzzz118/Case-Customer-sales-database-analysis/assets/110695227/32ebf99e-237f-4fd6-a5a2-f758bd0a2d73)
![640db680500f29de48bca6ebf9cb92b](https://github.com/ethanzzz118/Case-Customer-sales-database-analysis/assets/110695227/40950fd6-cb83-4d5c-a265-e472d72d59d7)
![3dc0f377bba954b16a049dde0fcc8c7](https://github.com/ethanzzz118/Case-Customer-sales-database-analysis/assets/110695227/6536437d-b55a-4633-8007-0281800245e4)
![36a35afa3b8638cf70df95515529b85](https://github.com/ethanzzz118/Case-Customer-sales-database-analysis/assets/110695227/4fa736a6-20be-4ff1-8847-472ac069f253)
![4c1660d33a13c73e640bffa226b6e7d](https://github.com/ethanzzz118/Case-Customer-sales-database-analysis/assets/110695227/ae981687-9252-4a89-b2ef-e2700cd0d1a3)
![06bba80ddfb511e3ddf8a88f83a9406](https://github.com/ethanzzz118/Case-Customer-sales-database-analysis/assets/110695227/ad313237-2f0d-4774-a40a-464739b63baa)
![dd96c6c6642b9b31a4808452134ab61](https://github.com/ethanzzz118/Case-Customer-sales-database-analysis/assets/110695227/94f5a2af-4e4c-4f75-bdf6-38b595b2e23e)
![29b33e59766ce41daa71c6d81ef1bf5](https://github.com/ethanzzz118/Case-Customer-sales-database-analysis/assets/110695227/4b7513b4-fbcf-4d83-b93c-a1d292ac94b9)
![2c2175460d32d15a7ab69d8f2985100](https://github.com/ethanzzz118/Case-Customer-sales-database-analysis/assets/110695227/31d11442-280e-4f83-ab21-a9498826738c)
![00520bd562d7e6ee48776fbc18b2c7a](https://github.com/ethanzzz118/Case-Customer-sales-database-analysis/assets/110695227/0a96f0ec-59d0-4be7-a63b-b816a41d8e0e)
![6fa0198943a1db74f530a942d3b276d](https://github.com/ethanzzz118/Case-Customer-sales-database-analysis/assets/110695227/cfcbe90b-8b39-40c4-8d9c-a632e024a754)
![8864848486a1552865b429cec6f59f3](https://github.com/ethanzzz118/Case-Customer-sales-database-analysis/assets/110695227/eda911bb-0a54-4690-a147-bb139b9316ec)
![365db68fd3ee3c9365f9ecfbb77e9e4](https://github.com/ethanzzz118/Case-Customer-sales-database-analysis/assets/110695227/57af5366-54d8-4230-b2f7-ef2ae819bfd3)
![5d42e1c08bc4d158bb7303176fdd800](https://github.com/ethanzzz118/Case-Customer-sales-database-analysis/assets/110695227/6f55c68d-c43d-46a0-ab76-a4ce02af6ae6)
![1a23a5bab3b0640d55c78907cd08f45](https://github.com/ethanzzz118/Case-Customer-sales-database-analysis/assets/110695227/05fc066f-050c-4fab-b40e-643a6e66c28c)
![37a441f33181017a555c77d8a3cdb03](https://github.com/ethanzzz118/Case-Customer-sales-database-analysis/assets/110695227/bc6913eb-aaf9-4281-b985-926bc9dd4aed)
![0b30230f941faf37a90bc8ec8564279](https://github.com/ethanzzz118/Case-Customer-sales-database-analysis/assets/110695227/28071f8a-f769-45c5-990d-e6c046641682)
![648143d2affa0439e02484f518fd2c6](https://github.com/ethanzzz118/Case-Customer-sales-database-analysis/assets/110695227/a8641eec-5bb3-4524-8c48-2c879b2e0bb4)
![f7b79a1676dca2de99766772046fc47](https://github.com/ethanzzz118/Case-Customer-sales-database-analysis/assets/110695227/54adf508-bb79-4bcd-a081-c4335b8f1d02)
![ffe5ed9d3298bbd4a4090f90ff39e6d](https://github.com/ethanzzz118/Case-Customer-sales-database-analysis/assets/110695227/06432c05-c214-49fd-bf1d-1888b4b4fcb8)

#Lesson learned
From this case, I am familiar with all the sql queries and syntax.I also know how to increace the sql performance by setting correct and necessary indexing or filters.Successfully accompolish all the business requirements and have a fully understanding of the logic inside the datemodel.
