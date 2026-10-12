---
title: Payment Links
---

## Create a payment link

1. Open the Sales Invoice.
2. Click **Create > Stripe Payment Link**.
3. Copy the link and send it to the customer.

```text
Status flow: Draft → Link Sent → Paid → Payment Entry created
```

## Troubleshooting

- **Link expired:** create a new one from the invoice.
- **Payment not reflected:** check the webhook log on your site.
