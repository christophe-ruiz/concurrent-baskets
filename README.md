# Concurrent Baskets
I want to develop a small website where customers have concurrent access to available products. This will allow real time information of product availability for customers and a more pleasant online shopping experience
### Criteria 
- When a customer places a product in their basket, the number of available products with the same size and characteristics drops.  
- When an item is removed from the basket, they become available again for other customers to buy.
- When no item are available new customers can't buy the product and it is out of stock
- When no item are avaible but some are currently in other customer's basket, the customer waiting for availability can oin a queue to automatically put the item in their basket if it becomes available (happens when a customer remove an item from their basket)
