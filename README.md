# Price Optimization

## Objective:

Provide actionable insights to the business, so that they can decide which price point to use in the future while making sure the results are statistically significant.

## About the problem:

Pricing is one of toughest challenges for most companies.

To begin, there are different  pricing methodologies depending on the industry, product, brand power, and so on.
And to make things trickier, a product can command drastically different prices depending on the context.

Let's take a bottle of water for example. For $2, you could buy a 6-pack of bottled water at a supermarket. however, those same $2 might only afford you
one bottle at a movie theatre.

As a result, companies will try to find the optimal price, that which maximizes earnings ( a.k.a "gross revenue"), for their market.

![demand curve](https://user-images.githubusercontent.com/56021627/199002670-1b5764d6-efaf-4c10-9555-7b0781ed8b65.PNG)

We have one two tables.

The first is called promo_results.csv.

It contains 270,000 observations from a pricing test ran by a small rafting comapny.
The company sells rafting trips down the Delware river.

![table 1](https://user-images.githubusercontent.com/56021627/199003244-d1b5ab3b-6f7c-4540-b06d-fe58b99bb96d.PNG)

### Data Dictionary:

- __user_id__ - Unique ID of visitor
- __date__ - Date the visitor recieved the promotion
- __source__ - Marketing channel that the visitor came from.
- __device__ - Mobile or desktop
- __OS__ - Visitor device's operating system.
- __test__ - Did the visitor belong in the test group?
- __price__ - the price seen for the rafting trip.
- __booked__ - Did the visitor book a trip?

The second table is called user_data.csv.
It contains any information we have about the site visitor.

![table 2 user](https://user-images.githubusercontent.com/56021627/199004233-371349e1-ab6d-494d-a226-cfa785ffe1ae.PNG)

### Data Dictionary:

- __user_id__ - Unique ID of visitor
- __state__ - State of origin
- __country__ - Country of origin

