# Machine Learning 101 for Business Central Course

<b>This exploration wants to predict demand of menu items in certain restaurant. If the owner of the restaurant will know weekly forecast, he will purchase needed quantity of ingridients just on time, no more no less.</b>

<b>OVERVIEW</b>

Have you ever ordered a dish in a cafe, but you were told that it was not available?
I did. This is a very unpleasant situation. And for both parties.
The cafe can lose the client, simply because the demand was incorrectly predicted.
In this workshop we will see how machine learning can solve this problem. What general problems can be solved through machine learning? And what is it? A fashion word or a working tool?
We will see how using Dynamics 365 Business Central and machine learning in pairs, you can quickly solve problems that were previously very difficult to solve or not solved at all.
Detailed agenda:
- Here is the answer, so what was the question? Understanding customer request.
- Looking for treasure. Data search and preprocessing.
- Swiss knife for prediction. Azure Machine Learning Studio.
- Let’s try a role of Data Scientist. Data engineering with R or Python.
- Teach me. Machine Learning data flow
- Give me that brain please. Choosing right algorithm
- I know the answer, can I share it? Publishing and AML web services
- Everyone can be fortune-teller. Prediction from Dynamics 365 Business Central

<b>GOALS</b>
- Understand Machine Learning principles
- Get knowledge about data search and preprocessing
- Techniques to explore data
- Try AML Studio
- Show predictions on dashboard
- Become ready to implement ML in production

<b>Inputs</b>
- *AML-restaurant-sales-by-menu-item.csv* - historical sales transactions from one particular restaurant
>- *menu_item* - name of menu item
>- *date* - transaction date
>- *stock_count* - qty of item on stock on this date
>- *orders* - qty of orders of this item on this date

- *AML-restaurant-menu-items.csv* - restaurant menu
>- *menu_item* - name of menu item
>- *in_children_menu* - if menu item relates to children menu category

- *AML-restaurant-int-events.csv* - schedule of internal events organised in this restaurant
>- *date* - calendar date 
>- *children_event* - if children event is scheduled on this date
>- *music_event* - if music event is scheduled on this date

- *AML-menu-items-max-stock.csv* - maximum allowed qty of menu items on stock, per day
>- *menu_item* - name of menu item
>- *max_stock_quantity* - maximum allowed qty of menu items on stock

- *AML-city-festivals.csv* - schedule of external events organised in the city, where restaurant is located
>- *date* - calendar date
>- *fest_name* - name of event
