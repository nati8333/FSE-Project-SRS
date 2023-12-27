# FSE Project README

This repository is for collaborating on the software requirement specification for an FSE project with title of online shopping website/webapp. 

## Software Requirement Specification

### Gathered Basic Requirements

- User account creation, session management and administration. (admin, buyer, seller)

- Stock management per seller. Must be able to search and filter stock items.

- Item exchange verification; Requires signatures of both seller and buyer. the verification can also be digital.
 
- Payment method will be emulated in the website.

- Sellers register items in stock.
- Buyers pick from items in stock (put in cart) and complete the payment.
- The money paid will be held until successful exchange of items.

- If the item exchange fails then the money will be returned, and so do the items back to stock. 
- If the item exchange succeeds then the money will be transferred to the seller (minus fees) after verification is done.

- Item exchange verification should be either digital or paper form and must include a list of items purchased with checkboxes and a signature box to assert that the items were received in full and as advertised or expected.
