
# System Architecture - Day 2

## Architecture Overview
This document provides a high-level overview of how the marketplace application components interact.

### Components
1. **Frontend (Next.js)**: Manages user interaction and fetches data via APIs.
2. **Sanity CMS**: Acts as the backend to manage data (e.g., products, orders).
3. **Third-party APIs**: Handles external integrations like Payment Gateway and Shipment Tracking.

### Architecture Diagram
```
[Frontend (Next.js)] ---> Fetch data from ---> [Sanity CMS]
     |                                    \
     |                                     ---> Call ---> [Third-party API (Payment Gateway)]
     |                                     ---> Call ---> [Third-party API (Shipment Tracking)]
```

### Workflow
1. **User Browses Products**:
   - Frontend fetches product data from Sanity CMS.
2. **Order Placement**:
   - Frontend sends order details to Sanity CMS.
3. **Payment Process**:
   - Payment Gateway API processes the payment.
4. **Shipment Tracking**:
   - Shipment status is retrieved via a third-party API.

---
