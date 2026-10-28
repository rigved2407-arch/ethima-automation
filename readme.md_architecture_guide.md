# Ethima WhatsApp Concierge MVP

A focused customer-enquiry and WhatsApp handoff prototype for ethima fine jewellery.

This repository is scoped as a **₹49,000 MVP setup**, not as a full custom CRM or ecommerce automation platform.

## Included MVP scope

The proposed first version covers one simple workflow:

```text
Website / Instagram / QR / Referral / Direct WhatsApp enquiry
        → basic preference questions
        → approved product information
        → appointment-link sharing
        → manual stylist or gemologist handoff
```

The MVP is designed to reduce missed enquiries and give the store team a consistent first response. It does not promise automatic sales, revenue outcomes, or fully autonomous customer service.

## What is included

- One WhatsApp enquiry flow.
- Basic questions for jewellery category, preferred style, and consultation intent.
- Three sample product categories: engagement rings, solitaire pendants, and tennis bracelets.
- Approved product images, short descriptions, and selected media links.
- One appointment-link handoff for salon or video consultation.
- Manual takeover by a stylist or gemologist.
- A simple owner view showing sample enquiry and handoff activity.
- Basic setup guidance, workflow testing, and a staff walkthrough.

## What is not included in the ₹49,000 MVP

The following are explicitly outside this package and require a separate quote:

- Custom CRM development or a multi-user CRM workspace.
- Payment links, Razorpay, UPI, EMI, orders, refunds, or payment webhooks.
- Ecommerce or inventory synchronisation.
- Bespoke CAD, 3D design, sizing-kit logistics, or production tracking.
- Automated aftercare, anniversary, referral, or repeat-purchase campaigns.
- Advanced analytics, revenue attribution, AI agents, or predictive scoring.
- Multi-location routing or complex staff permissions.
- Paid campaign management or advertising integrations.
- Custom mobile applications or a custom backend dashboard.

The repository may retain earlier concept screens as **reference material only**. They are not included in the MVP implementation or price.

## Prototype status

The current HTML screens contain simulated data and interactions for workflow review. They do not currently send real WhatsApp messages, store real customer information, create live appointments, or process payments.

A working MVP would still require:

1. An approved WhatsApp provider account.
2. A verified business number and approved message templates.
3. A small backend or provider workflow configuration.
4. Secure storage for the minimum customer details required by the flow.
5. The store's approved product copy, images, links, appointment URL, and handoff rules.
6. Testing with real staff before any production launch.

## Monthly maintenance scope

The proposed ₹10,000/month maintenance plan should cover only:

- Monitoring the included WhatsApp flow.
- Up to four support hours or two small content changes per month.
- Updating product links, approved copy, or appointment links.
- Minor fixes and one monthly review.

New workflows, integrations, dashboards, payment features, bespoke studio features, and major redesigns require a separate quote.

## Local preview

Open `index.html` directly in a browser or run a lightweight server:

```bash
python3 -m http.server 3000
```

## Relevant screens

- `index.html` — MVP overview and scope.
- `store_owner_overview/code.html` — sample owner view.
- `whatsapp_concierge_workflow/code.html` — the included WhatsApp sandbox flow.
- `omnichannel_store_funnels/code.html` — reference enquiry board.
- `custom_studio_lead_funnel/code.html` — future-scope reference screen, not part of the MVP.
- `automation_analytics_roi/code.html` — future-scope reference screen, not part of the MVP.

## Third-party costs

The owner pays separately for any WhatsApp provider subscription, message charges, hosting, storage, calendar software, taxes, and other external services. The MVP setup fee does not include those charges.
