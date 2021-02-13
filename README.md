# RESTful API dengan CodeIgniter

## Create Product

  - Method: POST
  - Endpoint : <code>/api-products/products</code>
  - Header:
      - Content-Type: application/json
      - Accept: application/json 
  - Body:
  <pre>
    {
      product_name: "string",
      price: "decimal",
      is_active: "tinyint(1)",
    }
  </pre>
  - Response:
  <pre>
    {
      "code" : http_code,
      "status": "string",
      "message" : "string",
    }
  </pre>
