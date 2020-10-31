# Order Microservice and EDA View 
This view covers all functionality related to placing an order: adding/removing items from a shopping cart, selecting
a pick-up location for the order, checkout with payment validation and order processing, querying, viewing and 
cancelling existing orders, rating meals and creating reviews for verified purchases. 

This is a microservice architecture that also uses the event-driven architecture (EDA) architecture style for 
processing an order. Key patterns used:
- BFF
- Database per Microservice (aka Database per Service)
- Wrapper (aka Legacy Wrapper, Anticorruption Layer)
- CQRS
- Publish-subscribe (in the event-driven architecture) 

![Order runtime view](../images/order-runtime-view-primary.png?raw=true)
![Notation key](../images/notation-key-runtime-views.png?raw=true)


## Element Catalog 

#### Checkout
- TO-DO

#### Payment
- TO-DO

#### Payment wrapper
- TO-DO

#### Payflow by PayPal
- TO-DO

#### Customer notification
- TO-DO


## Behavior
- TO-DO: sequence diagram for placing an order to pick-up in a smart fridge

 
## Related ADRs 
- [Payment gateway](../ADRs/ADR001-payment-gateway.md)
- [Wrapper pattern](../ADRs/ADR003-wrapper-pattern.md)
- [CQRS pattern](../ADRs/ADR004-cqrs-pattern.md)
- [BFF pattern](../ADRs/ADR002-bff-pattern.md)

## Related Views
- TO-DO: link to catalog view 
- TO-DO: link to order view 