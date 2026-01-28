# eds240-infographic


Data Sources:
https://eds-240-data-viz.github.io/resources.html#data-sources

https://github.com/awesomedata/awesome-public-datasets?tab=readme-ov-file#museums






Some of the typics that I will consider include:

Art/Museums

Food

https://www.kaggle.com/code/ritesaluja/food-restaurants/input

https://www.kaggle.com/code/arunjangir245/mapping-food-wastage-trends

Games - what how much are people willing to spend for reminiscing 


Music

https://www.kaggle.com/code/varunsaikanuri/spotify-data-visualization

Cooking 

https://www.kaggle.com/datasets/paultimothymooney/recipenlg


https://www.kaggle.com/datasets/irkaal/foodcom-recipes-and-reviews






1/21/26 - Chose Recipe Data

III. Find data and brainstorm questions
This week, you’ll focus on finding data that interest you and begin brainstorming some questions that you might explore / answer using those data. Your data set(s) may be related to a past project, or even your current Capstone or GP. It may also be a completely new data set(s), unrelated to anything you’re currently working on. Some people have a goal or question(s) in mind first, which drives what data they seek out. Others choose to explore various data sources first, and build their questions around their chosen data. Keep in mind that your infographic should be designed around a clear goal. Consider checkout out these data sources if you need some inspiration on where to start (you are not limited to just these data sources).

Asking the right question is critical and also one of the most challenging steps
I highly recommend checking out the following resources before diving in:

this short Substack piece by Enrico Bertini, titled Asking the right data questions and asking the data questions right, for some great insights on the challenges and approaches to discovering and revising your data question
this TED talk titled, The Power in Effective Data Storytelling, by Malavica Sridhar (~15 min; yes, I know the audio gets a little wonky part-way through )
IV. Reflect on your data, goal, and questions
Create a GitHub issue with the title, FPM1 - finding data / initial brainstorming, and add your responses to the following questions:



# Questions to Consider

1. What is your goal with these data (consider, what might be the goal of your infographic)? This goal may evolve as you continue working through your project.
There are a few simmering goals I have in mind for this data set, but for now I will focus on that is on mind. I would like to build insight into the types of recipes people have come to rate more often and understand what recipe types have become more prevalent as time progresses.

2. What questions do you hope to answer using these data (remember to read over Enrico Bertini’s article)? Jot down at least three questions that could help to illuminate your goal. It’s okay if these change later too (think of this as a starting point!).
Questions to Consider
How does the calorie content of a recipe relate to the number of user reviews it receives?
How do average user ratings differ across recipe categories? (cuisine type or meal type)?
Which recipe categories (cuisine/meal type) have the highest average number of ingredients?
Does the number of ingredients/recipe steps tend to influence certain score/ratings?
What are the five most frequently used ingredient and the five least frequently used ingredients across all recipes?
What is the average preparation time for each recipe category (cuisine/meal type)?
Which recipe has the highest number of user reviews in the dataset?
How has the number of newly added recipes in each category changed over time?
3. Link to and describe your data set(s). Be sure to address (a) where you found these data, and (b) what variables do these data contain, including if there is sufficient metadata for understanding them?
Link: https://www.kaggle.com/datasets/irkaal/foodcom-recipes-and-reviews

The data set contains information related to the food network's recipes. This includes reviews, review authors, ingredients, nutritional facts, meal classifications and time required. Below are the columns within this dataset:

Columns:
[1] "RecipeId"
[2] "Name"
[3] "AuthorId"
[4] "AuthorName"
[5] "CookTime"
[6] "PrepTime"
[7] "TotalTime"
[8] "DatePublished"
[9] "Description"
[10] "Images"
[11] "RecipeCategory"
[12] "Keywords"
[13] "RecipeIngredientQuantities"
[14] "RecipeIngredientParts"
[15] "AggregatedRating"
[16] "ReviewCount"
[17] "Calories"
[18] "FatContent"
[19] "SaturatedFatContent"
[20] "CholesterolContent"
[21] "SodiumContent"
[22] "CarbohydrateContent"
[23] "FiberContent"
[24] "SugarContent"
[25] "ProteinContent"
[26] "RecipeServings"
[27] "RecipeYield"
[28] "RecipeInstructions"

There is sufficient metadata to distinguish columns that is provided by the author on the website.

4. What steps are involved in downloading or accessing the data (e.g. “I can download the data directly from an online portal,” “I need to use an API,” “There’s an R package,” “I collected these data myself,” etc.)?
I can download the data directly from the owner from the Kaggle website without issue.

5. Will you need to combine multiple data sets to successfully answer your questions? If so, have you found all the necessary data? Do you have a way to combine it (e.g. matching key values across all data sets)?
I do not necessarily need to download and merge the reviews data set. However, if I wish to answer questions related to reviews or author participation, I will need to merge based on Author ID or Author Name. Considering my goal, this won't be necessary.

V. (OPTIONAL) Begin cleaning / wrangling your data
This will be a focus of FPM #2, but if you’re excited to dive in or are looking to get ahead, you should certainly take this time to do so!

DO NOT push large data files to GitHub
Take care to not push any large data files (>2GB) to GitHub. Instead, add your data file(s) or entire data folder to your .gitignore.


## Theme

Use styling consistent, weights, visual heigharchy, color choices, draw attention to main topic

Do key words influence the number of ratings or views?


