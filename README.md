# RESTful API dengan CodeIgniter

## Create Product

  - Method: POST
  - Endpoint : /api-products/products
  - Header:
      - Content-Type: application/json
      - Accept: application/json 
  - Body:
  <pre>
    {
      id: integer, unique,
      product_name: "string",
      sku: "string",
      price: "decimal",
      is_active: "tinyint(1)",
      created_at: "datetime"
    }
  </pre>
  - Response:
  <pre>
    {
      "code" : number,
      "status": "string",
      "message" : "string",
      "data" : [
          {
            id: integer, unique,
            product_name: "string",
            sku: "string",
            price: "decimal",
            is_active: "tinyint(1)",
            created_at: "datetime"
          },
          {
            id: integer, unique,
            product_name: "string",
            sku: "string",
            price: "decimal",
            is_active: "tinyint(1)",
            created_at: "datetime"
          }
        ]
    }
  </pre>
