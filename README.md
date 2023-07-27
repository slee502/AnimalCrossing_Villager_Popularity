# AnimalCrossing_Villager_Popularity
<img src="https://i0.wp.com/mynintendonews.com/wp-content/uploads/2020/08/animal_crossing_new_horizons-1.jpg?resize=930%2C620&ssl=1" alt="ACNH image" width="500" height="300">

## About
Welcome! This analysis will delve into the world of Animal Crossing: New Horizons, a popular video game developed and published by Nintendo. More specifically, we will try to understand the various factors that contribute to the popularity of the game's characters, known as villagers, among the player base.

Here are the villager attributes we will be looking at to see how they correlate with their popularity:

- Species
- Gender
- Personality
- Hobbies
- Requests (unique requests/desires expressed by each villager in the game) 
- Song (song associated with the character)

## Data Sources
CSVs:
- [Kaggle Animal Crossing Portal Villager Popularity acnh_villager_data.csv](https://www.kaggle.com/datasets/ampiiere/acnh-villager-popularity)
- [Kaggle New Horizons Catalog | Animal Crossing Paradise Planning.csv](https://www.kaggle.com/datasets/whenamancodes/new-horizons-catalog-animal-horizon)

API:
- [ACNH API](https://acnhapi.com/)

## Installation
Follow these steps to run the project on your local machine:

1. **Clone the repository**

   You can clone this repository by running the following command in your terminal:

   ```
   git clone https://github.com/slee502/AnimalCrossing_Villager_Popularity.git
   ```
  
3. **Navigate to the cloned directory**

   Change your current directory to the cloned repository's directory AnimalCrossing_Villager_Popularity

4. **Set up a virtual environment**

   It's recommended to create a virtual environment to keep the project's dependencies isolated from your system's Python environment.       You can create a virtual environment using the following command:

   On Windows:

   ```
   python -m venv venv
   ```

   On macOS and Linux:

   ```
   python3 -m venv venv
   ```

   This will create a new virtual environment named `venv` in your current directory.

4. **Activate the virtual environment**

   Activate the virtual environment using the following command:

   On Windows:

   ```
   .\venv\Scripts\activate
   ```

   On macOS and Linux:

   ```
   source venv/bin/activate
   ```

   Your prompt should change to indicate that you are now operating within a Python virtual environment. 

5. **Install the required packages**

   Install the required packages by running the following command:

   ```
   pip install -r requirements.txt
   ```

   You're now ready to run the project!

6. **Run the ```Villager_Popularity_Analysis.ipynb``` file:
    - If you have Jupyter Notebook installed, enter ```jupyter notebook``` and open the `.ipynb` file.
    - If you are using Visual Studio Code, open the `.ipynb` file and run the cells using the run button that appears at the top left of each cell.

To deactivate the virtual environment when you're done, simply type `deactivate` in your terminal.

## Visualizations

## Summary of Findings
### Species
The species of a villager appears to have a significant impact on their popularity. The Octopus species stands out as the most popular, with the highest average popularity ranking and the highest proportion of villagers in the top tier. The Deer, Wolf, Cat, and Koala species also tend to be more popular, with high average popularity rankings.

On the other hand, the Gorilla, Pig, Mouse, Hippo, and Kangaroo species are generally less popular, with low average popularity rankings and little to no presence in the top tier.

There is also a notable variation in popularity within some species. For instance, the Goat species has the widest range of popularity rankings, indicating a significant disparity in popularity among its villagers.

These findings suggest that the species of a villager is a key factor influencing their popularity among players.

### Gender
The gender of a villager does seem to have an impact on their popularity. Female villagers are generally more popular than male villagers, as indicated by their lower average popularity ranking. However, the variation in popularity rankings is slightly wider for female villagers, suggesting a broader range of popularity levels within this group.

While there are more male villagers overall, they are disproportionately represented in the lowest popularity tier. This suggests that male villagers are more likely to be less popular among players.

These findings suggest that gender is a factor that can influence a villager's popularity, with female villagers tending to be more popular overall.

### Personality
The personality of a villager appears to significantly influence their popularity. Villagers with 'Big Sister', 'Normal', and 'Peppy' personalities tend to be more popular, as indicated by their lower average popularity rankings and their higher presence in the top popularity tiers.

On the other hand, villagers with 'Cranky', 'Jock', and 'Snooty' personalities are generally less popular, with higher average popularity rankings and a greater presence in the lower popularity tiers.

'Lazy' personality type is quite common and has a mixed popularity, with a significant presence across all tiers.

These findings suggest that the personality of a villager is a key factor in determining their popularity among players.

### Hobbies
The hobby of a villager appears to have an impact on their popularity. Villagers with 'Nature' and 'Music' hobbies are generally more popular, as indicated by their lower average popularity rankings and higher representation in the top popularity tier.

On the other hand, villagers with 'Fitness', 'Education', and 'Fashion' hobbies are generally less popular, with higher average popularity rankings and lower representation in the top popularity tier.

'Play' hobby is quite common but has a mixed popularity, with a significant presence across all tiers.

These findings suggest that the hobby of a villager is a factor in popularity among players.

### Requests
The nature of a villager's requests seems to have a correlation with their popularity. Villagers who make requests related to 'palace', 'place', and 'full' are generally more popular, as indicated by their lower average popularity rankings.

On the other hand, villagers who make requests related to 'sports' are generally less popular, with higher average popularity rankings.

Other request themes such as 'home', 'house', 'garden', 'space', 'café', 'gym', 'studio', 'paradise', 'secret', 'cabin', 'grounds', 'bungalow', 'life', 'manor', 'hideaway', and 'field' have varying levels of popularity among villagers.

These findings suggest that the content of a villager's requests could be a factor in their popularity among players.

### Songs
The song preferences of villagers appear to correlate with their popularity. Villagers who favor songs like "Bubblegum K.K." and "K.K. Lovers" tend to be more popular, as these songs have the lowest average popularity rankings. Conversely, villagers who favor songs like "Only Me" and "Spring Blossoms" tend to be less popular, as these songs have the highest average popularity rankings among the top 10 songs. This suggests that the song preferences of villagers could be a factor in their popularity among players.

## Code Louisville Data Analysis 2 Final Project Requirements
**Category 1: Loading Data:**
- Read TWO data files (CSV).
- Read data set in with an API.

***Category 2: Clean and Operate the Data While Combining Them:**
- Clean your data and perform a pandas merge with your data sets, then calculate some new values based on the new data set.

**Category 3: Visualize/Present Your Data:**
- Make matplotlib or seaborn (or another plotting library) visualizations to display your data.

**Category 4: Best Practices:**
- Utilize a virtual environment and include instructions in your README on how the user should set one up.
- List dependencies in a requirement.txt file.

**Category 5: Interpretation of Your Data:**
- Annotate your code with markdown cells in Jupyter Notebook, write clear code comments, and have a well-written README.md.
