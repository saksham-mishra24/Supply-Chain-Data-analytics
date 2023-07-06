### Given Metrics : 

![image](https://github.com/saksham-mishra24/Supply-Chain-Data-analytics/assets/120908587/da238e97-8faf-4b1b-9abd-e65505c3a26c)


## :one:  Orders and Lines :
 *   Orders are nothing but a unique request placed by a customer on a given date.

 *   Within an order, a customer could request multiple items. Each of these items requested within the order is called an `order line`.

### Example: 
Let's say you order 4 notebooks and 2 pens at Amazon. 

A unique order ID is generated for all these items. Notebook and Pen is an order line.


## :two:   Measuring Line Fill Rate & Volume Fill Rate :

 *  Line Fill Rate is an important metric for the supply planning team to understand how many lines they shipped out of the total lines ordered. This metric does not consider the
delivery time of the order.

 *  Volume fill rate or case fill rate is a similar metric useful for the supply planning team to understand the total quantity they are able to ship for a customer per order or for a given
period of time.

### Example: 

In above example let's say Amazon is able to ship you 4 notebooks and 1 pen.

The line item pen is failed because you requested 2 nos. So Line Fill Rate for Amazon for your order is order lines fulfilled / lines ordered => 1/2 => 50 %.

Volume Fill rate will be total quantity shipped / total quantity ordered => 5/6 => 83 %


## :three:    Measuring On Time delivery %

 *  Unlike Line Fill Rate, this measure is measured at the order level. It determines if an order is delivered as per the agreed time with the customer.

 *  This metric is important for the warehouse & distribution team.

 *  An order is On Time only when all the line items inside the order is delivered on time.

## :four:   Measuring In Full delivery % :

 *  Unlike Line Fill Rate, this measure is measured at the order level. It determines if an order is delivered in full as per the requested quantity by the customer.

 *  This metric is important for the supply planning team.

 *  An order is In Full only when all the line items inside the order are delivered In Full.

## :five:   Measuring On Time In Full (OTIF) %

 *  Unlike Line Fill Rate, this measure is measured at the order level. It determines if an order is delivered BOTH in full and On Time as per the customer order request.

 *  This metric is important for all the sub functions in the supply chain team.

 *  An order is OTIF only when all the line items inside the order are delivered In Full and ON Time. 

 *  This is a hard metric which measures the reliability of an order from customer's point of view.
