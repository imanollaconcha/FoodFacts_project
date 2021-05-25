# food_facts

The objective of this project is to check the current food facts, more specific check if it is true that having a vegan diet is more eco-friendly than having an omnivore one.

To do that we combined the food production worldwide of different type of aliments, with how much each type of aliment pollutes, having like this how much pollute the production of food worldwide. 
After we established a percentage of type aliments that is eaten in each diet. 

**Presentation (Tableau): https://public.tableau.com/views/Beveganmoreecofriendly/Story1?:language=en-GB&:display_count=y&:origin=viz_share_link**

# For Jupyter notebook (python) We follow the next steps:
1.	Collecting the data, we took the date from 2 webpages: FAO Food and Agriculture Organization and Kaggle.
2.	After having all the data, we visualize it and saw how we can merge it.
3.	First, we merge the FAO data sets vertically.
4.	After we merge FAO (worldwide production) data sets with production pollution (Kaggle data set).
To do that we have to creates and extra file in order to match categories of both data sets.
5.	The next step is to mix all data sets once we have done the previous match and clean the joins.
6.	The last steps are to export the final file (csv), import it in tableau and create the presentation.


# In tableau we follow the next steps.
1.	We imported the previous created csv
2.	To define how much pollute each diet, we established a percentage of how much cereals, vegetables, dairy products, meat… each diet eats.
3.	The final result is a map, in which we can see how much different diets pollute worldwide or in each country.

**As a conclusion we can say that being vegetarian is the diet with less pollute worldwide.**
![foodFacts](https://user-images.githubusercontent.com/79746831/119482208-e3664e00-bd53-11eb-85ec-7f75c08a43f9.png)

