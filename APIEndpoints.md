
# API Endpoints

| **Endpoint**       | **Method** | **Purpose**                      | **Request/Response**
                                                  |
|--------------------|------------|----------------------------------|------------------------------------------------------------------------------|
| `/products`        | GET        | Fetch all products              | Response: `[{"id":1,"name":"Product A","price":100}]`                        |
| `/orders`          | POST       | Save a new order                | Request: `{"userId":123,"items":[{"id":1,"qty":2}]}`<br>Response: `{"status":"success"}` |
| `/shipment-status` | GET        | Fetch shipment status of order  | Response: `{"orderId":456,"status":"In Transit","ETA":"2025-01-18"}`         |

---

![API Diagram](/images/endpoint.webp)