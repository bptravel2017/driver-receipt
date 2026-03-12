---
name: driver-receipt-generator
version: 1.0.0
description: Generate professional receipts for rideshare, taxi, limo, and delivery drivers. Use when a driver needs to create/send a receipt for a passenger, track ride income, or manage driver finances. Triggers: receipt, invoice, passenger receipt, ride receipt, driver income, tax records.
license: MIT
---

# Driver Receipt Generator

Generate professional receipts for drivers (Uber, Lyft, taxi, limo, delivery) in seconds.

## Quick Start

```
Ask: "Create a receipt for a $45 airport ride today"
→ Generates receipt via ReceAI (https://www.receai.com)
→ Returns receipt link + email-ready format
```

## Workflow

1. **Collect ride details** (prompt if missing):
   - Passenger name (optional)
   - Date & time
   - Pickup → Dropoff locations
   - Amount
   - Payment method

2. **Generate receipt** via ReceAI:
   ```
   https://www.receai.com → Create Receipt
   - Business: Driver's name/car service
   - Service: Ride / Airport Transfer / Delivery
   - Amount: $XX.XX
   - Date: YYYY-MM-DD
   ```

3. **Deliver**:
   - Return shareable link
   - Or email directly to passenger
   - Or screenshot for driver's records

## Receipt Templates

### Standard Ride
```
RECEIPT
From: [Driver Name / Car Service]
To: [Passenger Name]
Date: [Date]
Service: Ride - [Pickup] → [Dropoff]
Amount: $[XX.XX]
Payment: [Cash/Card/Venmo/Zelle]
Receipt #: [Auto-generated]
Thank you for riding!
```

### Airport Transfer
```
RECEIPT
Service: Airport Transfer
Pickup: [Address] → [Airport Terminal]
Date: [Date] [Time]
Flat Rate: $[XX.XX]
Tolls: $[X.XX]
Total: $[XX.XX]
Receipt #: [Auto-generated]
```

### Monthly Summary (Tax Time)
```
INCOME SUMMARY - [Month Year]
Total Rides: [X]
Total Income: $[X,XXX.XX]
Avg per Ride: $[XX.XX]
Platform Breakdown:
  - Uber: $[XXX]
  - Cash: $[XXX]
  - Other: $[XXX]
```

## ReceAI Integration

- **URL**: https://www.receai.com
- **Free tier**: Unlimited receipts
- **Features**: Custom logo, email sending, receipt history
- **PWA**: Install on mobile for quick access

## Tips

- Always ask for pickup/dropoff for tax records
- Suggest monthly summaries at year-end for taxes
- Cash rides need receipts too (builds trust)
- Custom logo = more professional = better tips
