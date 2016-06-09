# The Checkout Kata

We’re going to see how far we can get in implementing a supermarket checkout that calculates the total price of a
number of items. In our store, we sell Apples, Bananas, Carrots and Drinks. Our goods are priced individually. In
addition, some items are multi priced: buy n of them, and they’ll cost you x pounds. For example, an Apple might cost
50 pounds individually, but this week we have a special offer: buy three Apples and they’ll cost you 130. The price
and offer table:


    Item    Price   Offer
    --------------------------
    Apple   50      3 for 130
    Banana  30      2 for 45
    Carrot  20
    Drink   15
