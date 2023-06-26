```mermaid
   graph TD;
1[Open the app on your mobile phone] --> 2[Create an account or log in]
2 --> 3[Provide delivery details]
3 --> 4[Search for the restaurant's name]
4 --> 5[Open the restaurant's menu]
5 --> 6[Choose bun type]
6 --> |Plain| 6.1
6 --> |Ciabatta| 6.2
6 --> |Sesame Seed| 6.3
6 --> |Kaiser Roll| 6.4
6 --> |Pretzel Roll| 6.5
6 --> |Sliced Roll| 6.6
6.1 --> 7[Choose bun size]
6.2 --> 7
6.3 --> 7
6.4 --> 7
6.5 --> 7
6.6 --> 7
7 --> |Small| 7.1
7 --> |Medium| 7.2
7 --> |Large| 7.3
7.1 --> 8[Choose a side Dish]
7.2 --> 8
7.3 --> 8
8 --> |Sweet Potato Fries| 8.1
8 --> |Chipotle Slaw| 8.2
8 --> |Onion Rings| 8.3
8 --> |Avocado Salad| 8.4
8 --> |Simple Salad| 8.5
8 --> |None| 8.6
8.1 --> 9[Choose a drink]
8.2 --> 9
8.3 --> 9
8.4 --> 9
8.5 --> 9
8.6 --> 9
9 --> |Still Water| 9.1
9 --> |Sparkling Water| 9.2
9 --> |Fruit Smoothy| 9.3
9 --> |Lemonade| 9.4
9 --> |Orange Juice| 9.5
9 --> |None| 9.6
9.1 --> 10[Toppings]
9.2 --> 10
9.3 --> 10
9.4 --> 10
9.5 --> 10
9.6 --> 10
10 --> |Mozzarella| 10.1
10 --> |Bacon| 10.2
10 --> |Cheddar| 10.3
10 --> |Lettuce| 10.4
10 --> |Egg| 10.5
10 --> |Onions| 10.6
10.1 --> 11[Sauce]
10.2 --> 11
10.3 --> 11
10.4 --> 11
10.5 --> 11
10.6 --> 11
11 --> |Ketchup| 11.1
11 --> |Mayo| 11.2
11 --> |Aioli| 11.3
11 --> |BBQ Sauce| 11.4
11 --> |Chili Sauce| 11.5
11 --> |Ranch| 11.6
11 --> |Add a comment?| 12{Yes or No}
12 -- Yes --> 13[Proceed to payment]
12 -- No --> 13
