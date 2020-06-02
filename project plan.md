# Product-Recomendation-Project

## Motivation:
When we are shopping online, it is difficult for us to distinguish the quality of a product from the information given by the merchant. At this point, we need to find a way to help us look through all the products. It is important because sometimes when we
are trying to buy something we want, however there might be a couple of similar products with different prices, which might mislead us from choosing the right one. Thus, I am trying to make a recommendation program that could provide us with some high-rated similar products and the reviews of them. My expectation is that customers would see a list of similar good rating products and their comparison. This would help the customers choose wisely by looking at the description and reviews of the products.

## How:
### Data Source
This project will use amazon public dataset.

### Functions
The system will sort, search products from the Amazon-review web data. Then it will provide a list of products ranking from the higher-ratings to the worst under different categories and the relationship between what other products a customer has bought and what he/she is going to purchase.

### UI
This project uses a Java Swing Library as a user-friendly interface. Before customers enter what they want to query, the system will automatically present some highly rated products to recommend. Then, after customers enter the name of a product, the system will search the entire database for products with the same name as customers entered. If it cannot find the exact same name, the system will pick a few words in the entered name to search. As soon as a match is found, feedback is given to customers. If no matching products are found after multiple attempts, the program will suggest that customers re-select keywords to describe the product they are looking for. When a customer clicks on the “not interested” button, the program would pop out this item out of the list and then recommend a new item.

## Challenge
I will use sorting, searching and graphs as our main methods as my project will face a huge number of data which I need to find the best way to select and utilize. There might be issues when handling data, making mistakes on different types, running into an infinite loop or building a wrong mathematical model. On the other hands, a proper recommendation algorithm needs to be selected carefully to increase the accuracy of the recommended results.
