# ethima.in Customer Acquisition & Automation CRM

A luxury omnichannel acquisition CRM and automation prototype suite engineered for **ethima fine jewellery**, specializing in bespoke lab-grown diamond enquiries, website and Instagram conversations, WhatsApp journeys, and salon appointments.

---

## 📁 Repository Structure

```text
ethima-automation/
├── index.html                 # Screen 1: Store Owner Overview (Intuitive Executive Briefing)
├── funnels.html               # Screen 2: Omnichannel Store Funnels Dashboard
├── whatsapp-workflow.html     # Screen 3: WhatsApp Concierge Acquisition Workflow & Sandbox
├── custom-studio.html         # Screen 4: Bespoke 3D Diamond Studio Lead Qualification Funnel
├── analytics.html             # Screen 5: Automation Attribution & ROI Engine
├── README.md                  # System architecture, deployment & integration guide
└── workflows/
    ├── webhook-schema.json    # Ingress payloads from website, Instagram, QR and web popups
    └── whatsapp-templates.md  # Meta-approved message template copy & buttons
```

---

## 💎 Designed Screens

1. **`index.html` (Store Owner Overview)**:
   - Built specifically for jewelry atelier owners without technical jargon.
   - Live revenue metrics (`₹38.4 Lakhs` automated revenue, `68 Consultations`).
   - VIP human takeover queue with 1-tap WhatsApp handoff.
   - High-intent active automations: Instant WhatsApp Welcome & Cart/Browse Recovery.

2. **`funnels.html` (Omnichannel Store Funnels)**:
   - Full acquisition funnel tracking: Website / Instagram / QR Enquiry $\to$ 3D Configurator $\to$ Spec Selection $\to$ Concierge Call.
   - Real-time customer activity stream across salon locations (Mumbai, Delhi-NCR, Bengaluru).

3. **`whatsapp-workflow.html` (WhatsApp Concierge Workflow)**:
   - Interactive WhatsApp sandbox simulating enquiry greeting, cut selection, 4K video drop, and gemologist audio note.
   - 5-stage automated pipeline nodes (Quiz, Lookbook, Cal.com scheduling, Razorpay handoff, Milestone concierge).
   - VIP human takeover triage queue.

4. **`custom-studio.html` & `analytics.html`**:
   - Custom bespoke studio qualification tracking and complete ROI attribution modeling.

---

## 🚀 Quick Setup & Deployment

### 1. Local Preview
Open any `.html` file directly in your browser or run a lightweight local server:
```bash
# Using Python
python3 -m http.server 3000

# Using Node / npx
npx serve .
```

### 2. Pushing to your GitHub Repository
To initialize or push updates into your GitHub repo (`https://github.com/rigved2407-arch/ethima-automation.git`):

```bash
# Clone the repository locally
git clone https://github.com/rigved2407-arch/ethima-automation.git
cd ethima-automation

# Copy your HTML files and documentation into the folder, then commit:
git add .
git commit -m "feat: add ethima CRM screens and automation architecture"
git branch -M main
git push -u origin main
```

---

## 🔌 Integration Roadmap

- **WhatsApp Provider**: WhatsApp Cloud API through an approved provider such as Interakt, AiSensy, or Wati.
- **E-Commerce Webhooks**: Shopify / WooCommerce order & abandoned checkout events.
- **Calendar & Appointments**: Cal.com or Google Meet API for salon gemologist consultations.
- **Payment Gateway**: Razorpay SmartCollect / Payment Links with 0% EMI split.
