```mermaid
   graph TD;
id1([Open the restaurant menu]) -->2[choose a bun type]
2 --> 2.1[Plain]
2 --> 2.2[Ciabatta]
2 --> 2.3[Sesame Seed]
2 --> 2.4[Kaiser Roll]
2 --> 2.5[Pretzel Roll]
2 --> 2.6[Sliced Roll]
2.1 --> 3[Choose bun size]
2.2 --> 3
2.3 --> 3
2.4 --> 3
2.5 --> 3
2.6 --> 3
3 --> 3.1[Small] 
3 --> 3.2[Medium] 
3 --> 3.3[Large] 
3.1 --> 4[Choose a side Dish]
3.2 --> 4
3.3 --> 4
4 --> 4.1[Sweet Potato Fries]
4 --> 4.2[Chipotle Slaw]
4 --> 4.3[Onion Rings]
4 --> 4.4[Avocado Salad]
4 --> 4.5[Simple Salad]
4 --> 4.6[None]
4.1 --> 5[Choose a drink]
4.2 --> 5
4.3 --> 5
4.4 --> 5
4.5 --> 5
4.6 --> 5
5 --> 5.1[Still Water]
5 --> 5.2[Sparkling Water]
5 --> 5.3[Fruit Smoothy]
5 --> 5.4[Lemonade]
5 --> 5.5[Orange Juice]
5 --> 5.6[None]
5.1 --> 6[Toppings]
5.2 --> 6
5.3 --> 6
5.4 --> 6
5.5 --> 6
5.6 --> 6
6 --> 6.1[Mozzarella]
6 --> 6.2[Bacon]
6 --> 6.3[Cheddar]
6 --> 6.4[Lettuce]
6 --> 6.5[Egg]
6 --> 6.6[Onions]
6.1 --> 7[Sauce]
6.2 --> 7
6.3 --> 7
6.4 --> 7
6.5 --> 7
6.6 --> 7
7 --> 7.1[Ketchup]
7 --> 7.2[Mayo]
7 --> 7.3[Aioli]
7 --> 7.4[BBQ Sauce]
7 --> 7.5[Chili Sauce]
7 --> 7.6[Ranch]
7.1 --> 8{Proceed to payment?}
7.2 --> 8
7.3 --> 8
7.4 --> 8
7.5 --> 8
7.6 --> 8
8 --> 8.1{Yes}
8 --> 8.2{NO}
8.1 --> 9[Pay]
8.2 --> 10[Cancel my order]
