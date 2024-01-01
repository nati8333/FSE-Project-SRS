# FSE Project README

This repository is for collaborating on the software requirement specification for an FSE project with title of online shopping website/webapp.

## Software Requirement Specification

### Gathered Basic Requirements

- User account creation, session management and administration. (admin, buyer, seller, deliverer)

- Stock management per seller. Must be able to search and filter stock items.

- Payment method will be emulated in the website. Buyers, sellers and deliverers should have at least one account that they can deposit and withdraw money from outside this organization/system.

- Sellers register items in stock.
- Buyers pick from items in stock (put in cart) and complete the payment.
- The money paid will be held/reserved until successful delivery of items.

- If the item exchange fails then the money will be returned back (minus some fees), and so do the items back to seller's stock.
- If the item exchange succeeds then the money will be transferred to the seller (minus fees) after confirmation is done.

- Item exchange confirmation must include a list of items purchased with checkboxes and a signature box to assert that the items were received in full and as advertised or expected. Each checkbox must be marked with the corresponding item state.

- Deliverers confirm items' states using form(s) before accepting the items to be delivered, and must deliver them within the agreed time frame.

- Upon delivery deliverers must confirm either successful or failed delivery.
  - Upon successful delivery the buyer must confirm items' states using form(s) before accepting.
    - If all items are in the expected condition and the buyer confirms then the transaction will be complete and the purchase money will be transferred to the seller. But if the buyer fails to confirm for some reason then the items must be delivered back to seller's stock.
    - If not all items are in the expected condition then the buyer must report such items and those items are to be sent back to seller. However, the items in the expected conditions must be handled as stated in the previous successful scenario.
    - If the buyer fails to confirm items delivered in the expected condition then the deliverer must report such case with the reason of failure. And the items will be delivered back to seller and the purchase money back to the buyer minus delivery fees and penalty fees.

- Use of internet is unavoidable thus required. A server must be selected and setup to handle at least 10,000 customers for starter. Customer handling capabilities can be scaled up with business growth.
