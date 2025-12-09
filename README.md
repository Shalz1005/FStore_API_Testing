# FStore_API_Testing
This API Testing project presents a well-structured Postman test suite built to validate core CRUD operations of a sample Product Management API. The collection includes automated test scripts covering response code verification, schema validation, data integrity checks, and negative scenario testing for robust error handling. All assertions are written using Postman’s JavaScript testing framework to maintain consistency and accuracy across endpoints.
The project highlights practical QA capabilities such as API test design, parameterized requests, environment configuration, chained workflows, and automated validations. It reflects solid familiarity with REST best practices and aligns with testing approaches commonly applied in product-based, fintech, and cloud-driven environments.

# 🛠 Tools & Technologies
- Postman
- Postman Test Scripts (JavaScript)
- GitHub
- JSON

## ✔ Test Coverage

This project includes automated test scenarios for:

- GET all products (status, schema, data integrity)
- GET product by ID (dynamic parameter)
- POST create product (validation + saving productId)
- PUT update product (field-level validation)
- DELETE product (confirmation + cleanup)
- Negative test cases (invalid IDs, missing fields, unauthorized access)
- Response time checks
- Error-handling validations


## 📁 Folder Structure
FStore_API_Testing/  
│  
├── README.md  
├── Collection/  
│ &nbsp;&nbsp;&nbsp;  └── Product_API_Collection.json  
├── Environment/  
│ &nbsp;&nbsp;&nbsp;  └── Product-API-Environment.json  
└── Screenshots/   
  &nbsp;&nbsp;&nbsp;  ├── get-all-products.png  
  &nbsp;&nbsp;&nbsp;  ├── create-product.png  
  &nbsp;&nbsp;&nbsp;  └── delete-product.png
  


