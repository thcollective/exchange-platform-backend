# What is it
1. A platform where users are able to exchange products as they have second hand products that they no longer wish to use
2. Example are clothes and shoes. Often we have extra things in our closet that we no longer wear. Instead of selling it for half the price, 
we can exchange it on the marketplace at full price. 

# System Overview
1. USERS are able to create, delete and update PRODUCTS
2. PRODUCTS have a NUMERICAL_VALUES (VALUE) on it
3. USERS are able to exchange PRODUCTS with equal NUMERICAL_VALUES
4. When PRODUCTS are EXCHANGED, a TRANSACTION is created
5. The TRANSACTION has a STATUS of PENDING, COMPLETED, CANCELED 
6. THE SYSTEM is able to algorithmically place a PROPOSED_VALUE on a PRODUCT 
7. USERS are able to place a PROPOSED_VALUE on a PRODUCT
8. THE SYSTEM is able to determine the ACTUAL_VALUE of a PRODUCT based on the SYSTEM_DEFINED PROPOSED_VALUE and USER_DEFINED PROPOSED_VALUE
9. SYSTEM_DEFINED PROPOSED_VALUE will be the ceiling value of a PRODUCT
10. ALL USER_DEFINED PROPOSED_VALUE will be discarded if it exceeds the SYSTEM_DEFINED PROPOSED_VALUE
11. USERS can sell their PRODUCT to THE_SYSTEM or place it on the MARKETPLACE to be bought by other USERSQ
12. When selling on the MARKETPLACE, they need to provide VERIFICATION on the PRODUCT_PRICE and PRODUCT_AUTHENTICITY
13. When selling on the MARKETPLACE, they are free to place any PROPOSED_VALUE. Other USERS are able to purchase the PRODUCT at the PROPOSED_VALUE
14. In order to prevent FRAUD, USERS need to sell minimum number of PRODUCTS first before they are able to sell directly to THE_PLATFORM
15. The more PRODUCTS they sell, the higher their level will be. 
16. Every higher Level will allow them to sell more clothes of equivalent value to THE SYSTEM
17. USERS are only allowed to place 5 (MAX_LIMIT) PRODUCTS on the MARKETPLACE.
18. This will ensure that USERS are placing their BEST_PRODUCTS on the marketplace 
19. As USERS sell out their PRODUCTS, they are then able to sell more PRODUCTS without going over the MAX_LIMIT


# How to contribute
Propose your new feature idea in the issues tab. Follow this format
```
What is your proposal about:
Explain what is your feature proposal about

What problem is it solving: 
Explain how will this new feature solve a problem

How:
How do you propose to implement this feature. 

Backend Feature Reference: 
Is this feature linked to a specific backend feature. If yes, share the link
to the backend isssue for reference

External Links:
Any links to backup your proposal or support your proposal
```

**Example**
What:
Proposal to allow users to review the ideas of other users

What problem is it solving:
Users right now wish to get feedback on their ideas but are unable to do so

How:
Allow users to write down their comments on the idea within the idea details page.

Backend Feature Reference:
https://github.com/thcollective/startupforest-backend/issues/2

As soon as you receive a label status as accepted, this issue can be developed.

