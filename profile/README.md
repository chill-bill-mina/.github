# No extra data, just what you need – Chill Bill.

# Problem

Large home appliance manufacturers conduct product sales through authorized dealers. Manufacturers sell their products to authorized dealers, who then offer these products to customers. The warranty coverage for electronic home appliances purchased by customers from authorized dealers depends on the manufacturer. When a product malfunction occurs, the customer contacts the manufacturer, and the warranty process begins. The warranty coverage starts from the purchase date stated on the invoice and continues for the specified period (for example, 2 years).

The company regularly requests sales invoices from dealers to determine whether a product is under warranty. When a customer applies with an invoice or warranty certificate, the company compares it with the invoice they have on file and determines the warranty coverage based on the date on it.
![product-purchasing(traditional)](https://hackmd.io/_uploads/SyN5_5b0R.png)
![warranty-process-traditional](https://hackmd.io/_uploads/SyS6dqbRC.png)

The company, which only needs proof that the sale occurred and the date of sale, engages in unnecessary data storage by keeping all invoices in its own database. In addition to this information, the invoice contains many data points that the company doesn't need, such as the customer's identification number, address, tax number, and the price paid. Besides the risk posed to the company by storing this unnecessary data, the biggest risk is storing the sales price. This is because, according to competition regulations, the company must not manipulate the dealers' sales prices and must leave the market free. In the event of a possible competition authority investigation, keeping the dealer sales prices of all products could cause serious legal damages to the company.

As a solution to this situation, the company requests that dealers upload their sales invoices to the system with unnecessary parts blacked out. Of course, dealers who are not responsible for this issue and don't consider free market problems usually do not comply with this directive.

# Solution

> In commercial transactions between two parties, the parties agree on the product to be purchased and the amount to be paid. ZK-Proofs are used to prove that the agreement has taken place without disclosing the details of the agreement. For example, by settling the proof of this agreement on the Mina Protocol, parties can present evidence of their agreement to the whole world. This way, both the accuracy of the transaction is proven and privacy is protected.

This solution meets the needs of the company and dealers while protecting customer privacy. The company can access only the information necessary for warranty coverage: the date the product was sold and proof that the sale took place. Dealers, on the other hand, can document their sales without having to share sensitive data such as price information.

First, the customer purchases a product from an authorized dealer. The dealer creates a smart contract for the product in question and settles it on Mina with mutual signatures. They receive the payment, transfer ownership of the product to the customer, and provide a document containing this information.
![product-purchasing-with-zk](https://hackmd.io/_uploads/BJ-eKqbRR.png)

When the customer contacts the company for the warranty process, they only present proof to the company containing ownership, product serial number, and purchase date. The company verifies this proof through Mina, and the process is completed.

![warrant-process-with-zk-proofs2](https://hackmd.io/_uploads/HyifYc-AC.png)

Because each product is a smart contract, product ownership can easily change hands. For example, when a second-hand refrigerator is sold between peers, this change of ownership can be instantly updated on the blockchain. With this approach, we are essentially turning products into programmable digital assets — NFTs.

In conclusion, Chill Bill aims to provide innovative solutions to many commercial and legal issues. Through ZK (Zero Knowledge) technology, it minimizes data sharing, ensuring compliance with strict data protection standards such as GDPR and KVKK, and eliminating the need for sharing data with third parties. Additionally, by preventing actions that risk violating competition laws, such as collecting price information in secondary sales, it provides effective protection against heavy penalties from the Competition Authority.

It simplifies the cumbersome invoice uploading processes for authorized dealers, providing convenience to dealers while preventing potential violations at this stage. Issues such as lost invoices or incorrect invoice issuance no longer lead to customer grievances.

The customer confirms the accuracy of their data during the sale, ensuring no incorrect information is entered, and holds the ownership of the product with blockchain assurance.
