# Purchase

!!! info

    This is the `index.md` page specific to the section named Purchase. The file is located under `docs/purchase`.

The purchase flow represents a number of steps and actions taken by more than one department in order to complete a purchase. Different combination of steps and actions are taken by a department depending on the type of goods or services being purchased and the degree of due diligence required to complete the purchase efficiently.

## Departments

There are up to four departments involved in completing a purchase.

1. ==User Department== makes a request to purchase some goods or services.
2. ==Central Stores== may have the inventory of the goods requested.
3. ==Purchase Department== directly purchases from a external supplier.
4. ==Accounting Department== pays the external supplier.

Each department has a protocol to exchange information necessary to complete the purchase.

## Forms

- A ==Indent== form represents an intent to purchase goods or services. This request is made by the User Deparment and will go to a Department for processing.
- A ==Purchase Request== form represents a formal request to purchase goods or services and will include additional information such as delivery address. This request will go to a Department for processing.
- A ==Purchase Order== represents a formal instruction to the external supplier who will provide the goods or services for delivery.
- A ==Goods Received Note== represents a formal acknowledgement of receipt of goods or services by a Deparment.
- A ==Request for Payment== represents a formal instruction to pay a external suppler who has delivered the goods or services. This request will go to a Deparment for processing.

The purchase flow varies depending on the type of goods or services being requested and how the purchase is completed. For example:

- The Central Store may have a complete inventory of the goods being requested. In such case, the Central Store may be able to complete the purchase fully without involving external supplier.
- The Central Store may have a partial inventory of the goods being requested. In such case, the Central Store may partially complete the purchase and raise a Purchase Request for the remainder of the purchase request.
- The Purchase Request may have a delivery address of the User Department or the Central Store.
- The GRN is competed by the Department that receives the goods or services from the external supplier.
- The purchase is a unique item that is usually not stocked by the Central Store - in which case the Indent is not required, and the User Department can directly make the Purchase Request.
- The purchase is a misc general purchase item and can be completed in less number of steps and actions.

## Flows

We have configured the ERP software to broadly enable two types of purchase flows with three variations - making it a total of 5 different flows:

1. The purchase of goods can be fulfilled fully or partially by the Central Stores.
2. The complete purchase flow of goods or services and involves all the four deparments.
3. Good are directly delivered to the User Department
4. Good are delivered to the Central Store and will later be transferred to the User Department
5. Services are being purchased
