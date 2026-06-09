# NerdPOS Showcase

Public-safe case study and screenshot showcase for an Arabic-first POS and operations product direction.

This repo exists to show the product surface clearly without exposing private backend logic, production data, or business-sensitive implementation details. The screenshots were captured from a safe frontend-only copy, and the case-study framing is designed to communicate product depth in a recruiter-friendly way.

## What this showcase covers

- Cashier order-building flow
- Payment collection flow
- Receipt preview with QR/invoice surface
- Inventory dashboard direction
- Compliance-facing dashboard direction
- Public explanation of how these surfaces fit into a broader ERP/POS workflow

## Why this repo exists

Some business software work should not be published as raw source code. This repo is the public layer for demonstrating the interface quality, workflow depth, and product direction behind NerdPOS.

The screenshots were captured from a safe frontend-only copy. No private backend code, customer data, or secrets are included here.

## Product focus

NerdPOS is positioned around:

- Arabic-first cashier workflows
- Inventory visibility
- Compliance-aware operations
- Practical business UX for real teams

## System map

```mermaid
flowchart TD
    A[Cashier session] --> B[Cart and totals]
    B --> C[Payment collection]
    C --> D[Receipt and invoice output]
    D --> E[Operational history]
    E --> F[Inventory visibility]
    E --> G[Compliance tracking]
```

## Workflow map

```mermaid
flowchart LR
    A[Cashier signs in] --> B[Open session]
    B --> C[Select products]
    C --> D[Build cart]
    D --> E[Collect payment]
    E --> F[Generate receipt]
    F --> G[Update operational history]
    G --> H[Inventory and compliance surfaces]
```

## What the evidence proves

- The cashier surface is not a mock landing page. It includes product selection, cart state, tax and totals, and payment transition.
- The payment flow is part of the same operational thread, not a disconnected popup.
- Receipt output is treated as a real workflow surface with totals and QR/invoice framing.
- Inventory and compliance are presented as adjacent operational modules rather than afterthoughts.

## Showcase boundary

```mermaid
flowchart TD
    A[Public showcase repo] --> B[Real screenshots]
    A --> C[Workflow diagrams]
    A --> D[Case-study copy]
    P[Private product work] --> Q[Backend logic]
    P --> R[Customer-specific workflows]
    P --> S[Operational data]
    A -. safe public layer .-> P
```

## Screenshot gallery

### Live POS order build

Shows an active session, product selection, cart state, tax calculation, and checkout action.

![Live POS order build](assets/screenshots/nerdpos-live-pos.png)

### Payment collection

Shows the cash payment flow in progress inside the POS checkout experience.

![Payment collection flow](assets/screenshots/nerdpos-payment-flow.png)

### Receipt preview

Shows the generated receipt preview with totals, tax, payment method, and QR/invoice surface.

![Receipt preview](assets/screenshots/nerdpos-receipt-flow.png)

### Inventory dashboard

Shows the inventory-facing operational screen for stock visibility and control workflows.

![Inventory dashboard](assets/screenshots/nerdpos-inventory-dashboard.png)

### Compliance dashboard

Shows the compliance-oriented interface direction for invoice and submission workflows.

![Compliance dashboard](assets/screenshots/nerdpos-compliance-dashboard.png)

## Why this matters publicly

For business software, raw code is not always the best public proof. A stronger public signal is often:

- honest screenshots
- clear workflow explanation
- system boundaries stated explicitly
- product thinking shown without leaking private implementation

## Public vs private boundary

Public here:

- Screenshots
- Product framing
- Safe case-study narrative
- UI direction

Private by design:

- Production backend logic
- Customer-specific workflows
- Sensitive ERP/POS implementation details
- Operational or financial data

## Related public surfaces

- Main profile: [KareemQabil](https://github.com/KareemQabil)
- Portfolio: [kerimqabil.me](https://kerimqabil.me)
