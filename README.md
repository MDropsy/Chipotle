# Chipotle clustering challenge

- Repository: `clustering`
- Type of Challenge: `Learning`
- Duration: `1 day`
- Deployment strategy :
	- Github page
- Team challenge : `yes (max 4)`
	- visualization: 1
	- data analysis: 2
	- project management : 1

## Learning Objectives 

- visualization: to be able to use geopandas, matplotlib (and seaborn) to visualize clustered data onto a map
- data analysis: to be able to determine appropriate clustering methods and variables to cluster 
- data analysis: to evaluate the chosen clustering method in comparison to other methods 
- project managment: to be able to allot the right amount of time for the tasks and present the results onto a readable github page

## The Mission

<img src="https://media.giphy.com/media/l3vR4Fp4U1DhW8bhS/giphy.gif" align="right" width="450"/>

>"Honey, where do you wanna eat?"
>
>"Do you even have to ask? Chipotle, of course!"
>
>"How could I forget, we've been eating chipotle for the last 47 days..."
>
>"So get ready for number 48! Oh I can't wait to stuff my face with a burrito!"
>
>"But the closest one is an hour drive away, couldn't we just get mcdonalds?"
>
>"How dare you utter that word in my presence? First the neighbours, now you!"
>
>"The neighbours? What do they have to d-"
>
>"That's it, we're moving, I can't deal with this anti-chipotle fascism."

Find chipotle **epicentres** to live your ideal chipotle lifestyle by clustering the [chipotle](chipotle_locations.csv) dataset.

### Must-have features

- A visualisation of the USA with chipotle locations
- Visualization of the different clusters
- Intrinsic analysis comparison of the clusters of at least 2 methods with varying arguments (using euclidian distance as criteria)
- A chosen centroid to live. Make your argument of why the chosen centroid is superior to others. Examples of arguments are:
    - highest density
    - greatest uninterrupted link of chipotle locations with smallest link-to-link distance
    - ...
- a Github page where results are visualized


### Nice-to-have features

- Colour coded cluster visualisation
- Clear graph legends

## Deliverables
1. Publish your source code on the GitHub repository.
2. Make a clear github page explaining your results and methods
3. A chosen adress for the couple to live

### Steps
1. Create the repository
2. Install geopandas
3. Plot the [US map](https://jcutrer.com/python/learn-geopandas-plotting-usmaps)
4. Visualize your data on this map
5. Plot a [dendogram](https://scikit-learn.org/stable/auto_examples/cluster/plot_agglomerative_dendrogram.html) of your data to help you decide the appropropriate clustering resolution
6. Compare and analyse different [clustering methods](https://scikit-learn.org/stable/modules/clustering.html) using intrinsic analysis to decide on a chosen method.
7. Choose a centroid/adress to live
8. Publish your results to a Github page with an explanation of your method.

## Evaluation criterias
| Criteria       | Indicator                                                                             | Yes/No |
|----------------|---------------------------------------------------------------------------------------|--------|
| 1. Is complete | The student has realized all must-have features.                                      |        |
|                | There is a published GitHub page available showing the visualized results                                           |        | A US location has been selected an arguments for choosing it has been given
|                | ...                               					                                 |        |
|                | ...                                                                                   |        |
| 3. Is Correct  | All participants have contributed to the git repository										                                         	 |        |
|                | All data is visualised clearly and interpretably								                                                     |        | The method and progress of the project is detailed in the git repository


## A final note of encouragement


![You've got this!](https://media.giphy.com/media/gJuZSbDxv0zLTMdafV/giphy.gif)
