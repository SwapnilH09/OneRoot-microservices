# OneRoot-microservices
Microservices to facilitate business on sellers' side for OneRoot

services for #user-onboarding, #inventory-management and #item-listing

## User-Onboarding

### provide CRUD functionality for 
    1. user-name
    2. user-phone-number
    3. aadhar
    
### create a unique user-id for each user (non-collision)    
### share/communicate user-id and other user details with other services.



## Inventory Management -- for sellers/farmers

### provide CRUD functionality for
    1. farm -- is a JSON doc
    2. crop -- is an EmbeddedJSON doc in Farm
    
### fetch user-id and user-details from User-Onboarding service
### Maintain a map of farms for each unique user-id using farm's name as key



## Item-listing -- for marketplace

### fetch user-id and user-details from User-Onboarding service
### creates and maintains a map of listed crops
    
