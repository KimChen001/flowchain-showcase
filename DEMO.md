# FlowChain demonstration

A five-minute walkthrough of the desktop workspace, conversation assistant, purchasing decisions, and beta mobile operations. The screenshots below come from the running application with fictional business records.

## 1 Desktop workspace — 30 seconds

Open Today and show the work queue, overdue count, and links to recent documents. Explain how purchasing, receiving, inventory, sales, and bills share records.

[Desktop overview](assets/01-workspace-overview.jpg)

## 2 AI conversation and draft — 90 seconds

Ask: **“Which purchase orders are overdue?”**

The captured walkthrough returns eight overdue orders. Show the most overdue order, its supplier, promised date, and next-step suggestion. Open a cited record to inspect the evidence. The assistant also supports contextual follow-ups from previously cited records; this capability is not separately pictured here.

Choose **Review draft** for LOCAL-DEMO-PO-020. Show the supplier contact, order number, 7,000 pcs remaining, promised date, and editable message. Explain that preparing a draft does not send an email or change the PO.

[Assistant answer](assets/02-ai-assistant-overdue-orders.jpg) · [Follow-up draft](assets/03-ai-supplier-follow-up-draft.jpg)

These captures use deterministic business services without an external language model. Optional model planning, checked answer wording, and semantic knowledge search are described in the README, not demonstrated by these screenshots.

## 3 Purchasing, stock, and supplier performance — 90 seconds

Show the RFQ line comparison: the suppliers offer different unit prices and delivery dates. Explain the commercial trade-off and historical PO price context. Formal award requires a separate reviewed decision.

Open inventory balances and explain on-hand, reserved, available, safety stock, and reorder points. The current walkthrough has no qualifying reorder rows, so it does not demonstrate a replenishment recommendation. For a live reorder demonstration, first use a fictional scenario with a shortage or sufficient shipment history, then show incoming-order coverage and the prefilled request.

Show the supplier scorecard. Explain the difference between performance against the original date and against the revised date, then inspect the underlying deliveries.

[Quotation comparison](assets/06-rfq-quotation-comparison.jpg) · [Inventory balances](assets/04-inventory-balances.jpg) · [Supplier performance](assets/05-supplier-performance.jpg)

## 4 Mobile operations — 60 seconds

State the status first: **implemented beta responsive web module, explicitly enabled for this demo and outside the current core trial scope**.

Show the task inbox and open a pending purchase order. Review its supplier, amount, lines, and available decision controls. Stop before approving, rejecting, or returning it.

Open Mobile receiving, search LOCAL-DEMO-PO-020, and show the warehouse, location, outstanding quantity, accepted quantity, and Prepare draft control. Stop before creating or posting a receipt.

[Task inbox](assets/07-mobile-task-inbox-beta.jpg) · [PO review](assets/08-mobile-po-review-beta.jpg) · [Receiving preparation](assets/09-mobile-receiving-beta.jpg)

The images demonstrate mobile web layouts. They do not imply a native app, production rollout, offline readiness, or completed approval/receiving transactions.

## Screenshot index

| Screenshot | What is actually shown |
| --- | --- |
| [01 Desktop workspace](assets/01-workspace-overview.jpg) | Work queue, overdue orders, and document activity |
| [02 AI assistant](assets/02-ai-assistant-overdue-orders.jpg) | Data-backed overdue-order answer and next-step suggestions |
| [03 Supplier follow-up](assets/03-ai-supplier-follow-up-draft.jpg) | Editable message with outstanding quantity and promised date |
| [04 Inventory](assets/04-inventory-balances.jpg) | Posted stock, availability, warehouses, and thresholds |
| [05 Supplier performance](assets/05-supplier-performance.jpg) | Original/revised-date performance, in-full, OTIF, and delays |
| [06 RFQ comparison](assets/06-rfq-quotation-comparison.jpg) | Recorded quotes, delivery dates, historical prices, and commercial terms |
| [07 Mobile task inbox](assets/07-mobile-task-inbox-beta.jpg) | Pending purchasing tasks in the beta web module |
| [08 Mobile PO review](assets/08-mobile-po-review-beta.jpg) | Order information and decision controls, without executing a decision |
| [09 Mobile receiving](assets/09-mobile-receiving-beta.jpg) | Quantity review and receipt-draft preparation controls |

All business names, contacts, and transactions in the images are fictional walkthrough data. Capture date: October 8, 2026. Source snapshot: `33542e12`.
