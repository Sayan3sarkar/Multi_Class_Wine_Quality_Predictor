# Wine Quality Predictor

What's our one of the most favourite(if not the most favourite) TV Series? If your answer is [Game of Thrones](https://en.wikipedia.org/wiki/Game_of_Thrones) , you're absolutely correct. 

Talking about **Game of Thrones**, we can't neglect the great house [Lannister](https://awoiaf.westeros.org/index.php/House_Lannister) and 2 of the most important characters, [Cersei Lannister](https://en.wikipedia.org/wiki/Cersei_Lannister) and [Tyrion Lannister](https://en.wikipedia.org/wiki/Tyrion_Lannister). 

Now the fact that these 2 are siblings is obvious. But what else do they have in common?

Their love for [WINE](https://en.wikipedia.org/wiki/History_of_wine), which played a major role in their character development. They would'nt want their wine to be anything less than **legendary**,quality wise. The impression, a wine leaves at the back of their mouths would truly determine the quality.

![Red Wine](https://www.google.com/url?sa=i&source=images&cd=&ved=2ahUKEwjE-tKl08jiAhXMP48KHeB-B1wQjRx6BAgBEAU&url=https%3A%2F%2Fwww.winemag.com%2F2015%2F10%2F27%2Fred-wine-basics%2F&psig=AOvVaw0kShCq--LC7DCK-OytQ4uE&ust=1559491119105772)

So, we make a **Wine quality predictor** to categorize whether our wine is **Game of Thrones** level, or not.

## About Model

This is my first **Multi Class Classifier** and I have deisgned it with the help of a [Support Vector Classifier](https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html) on the [Red Wine Dataset](https://www.kaggle.com/uciml/red-wine-quality-cortez-et-al-2009).

We perform **Exploratory Data Analysis** on the dataset,at first, before making our model. We perform several visualizations with help of [matplotlib](https://matplotlib.org/) and [seaborn](https://seaborn.pydata.org/) libraries to help us understand the relation among different attributes of the dataset in order to determine the **Quality** of it.
