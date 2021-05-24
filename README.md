# food_facts

The objective of this project is to check the current food facts, more specific check if it is true that having a vegetarian diet is more eco-friendly than having an omnivore one.

To do that we combined the food production worldwide of different type of aliments, with how much each type of aliment pollutes, and after we established for each diet a percentage of type aliments that they eat. 

On this way we are able to see how much the production of the type of aliments that are eaten in each diet consume

**Presentation (Tableau): https://public.tableau.com/views/Beveganmoreecofriendly/Story1?:language=en-GB&:display_count=y&:origin=viz_share_link**

# For Jupyter notebook (python), we follow the next steps:
1.	Collecting the data, we took the date from 2 webpages: FAO Food and Agriculture Organization and Kaggle.
2.	After having all the data, we visualize it and saw how we can merge it.
3.	First, we merge the FAO data sets vertically.
4.	After we merge FAO (worldwide production) data sets with production pollution. As the aliment types are different in each data set, we are not able to mix them. To solve it we create and excel file matching category types of each data set.
5.	The next step is to mix all data sets once we have done the previous match and clean the joins.
6.	The last steps are to export the final file (csv), import it in tableau and create the presentation.

# For tableau, we follow the next steps.
1.	We imported the previous created csv
2.	To define how much pollute each diet, we established a percentage of how much cereals, vegetables, dairy products, meat… each diet eat.
3.	The final result is a map, in which we can see how much different diets pollute worldwide or in each country.

As a conclusion we can say that being **vegetarian** is the diet with less pollute worldwide.


