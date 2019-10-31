# Data Visualization Project - Hotaling & Co Cocktails

## Data

This project is based on the [dataset of cocktails](https://gist.github.com/jgorsett/6492ab1253c04167d1639c4ced71b3bf) collected by alcohol importer and distiller Hotaling & Co. The original dataset was modified to parse out/clean up the ingredients into rows, categorize the alcohol types and add location longitude and latitude coordinates.

## Motivations
The visualizations and interaction decisions in this project were motivated by the following tasks and questions:
 *  How do cocktail ingredient trends compare across the US?
 *  What are the most common ingredient combinations?
 *  If the user would like to use specific ingredients, what other ingredients can they combine with them to make different cocktails?
 *  What are the most popular types of cocktails?
 *  What is the composition of cocktails served in different locations?

## Sketches
The sketch below shows a chart showing ingredient breakdowns with interactive filters and coloring for different types of ingredients.

![image](https://user-images.githubusercontent.com/44886644/65655486-6583f980-dfea-11e9-886d-f7a58a1c2242.png)

The sketch below displays three maps showing the top categories including alcohol types, cocktail ingredients, and words in cocktail names for each location in the dataset.  Having the different maps all in one display will allow the user to see the different trends across the locations.

![image](https://user-images.githubusercontent.com/44886644/65656068-76ce0580-dfec-11e9-808b-09dac51ad11c.png)

## Prototypes

### Ingredient Pairings Bar Chart
Displays a bar graph showing ingredients included in cocktails containing selected ingredients.  For the prototype, the chart can be interactive if the user modifies the ingredient constants in the index.js file. The user can enter up to 5 ingredients to filter on. The user can also modify the “nSlices” constant in order to modify the number of results returned in the chart. The tooltip will show the cocktail names and the colors indicate the main alcohol contained in the cocktail.

[![image](https://user-images.githubusercontent.com/44886644/65655061-d62a1680-dfe8-11e9-8c74-7822644fbc6e.png)](https://vizhub.com/jgorsett/c5ae89a319ac45d691be5c0f69ff8ca9/fullscreen)

### Cocktail locations on a U.S. Map 
This basic prototype is a starting point for displaying cocktail compositions across the US.  The data has been prepared so each location can show the ingredient compositions filtered for locations with common ingredients in 3 or more cocktails.  The chart shows circles for the locations. 
[![image](https://user-images.githubusercontent.com/44886644/66533101-b82bde00-eadf-11e9-9224-2d68cc21a394.png)](https://beta.vizhub.com/jgorsett/e5ac059bc26a4d1b8e0924876843ca10)

## Visualizations

### Filterable Cocktail Ingredient Bar Chart
Displays a bar chart including the top 20 ingredients found in the cocktails data set.  Selecting an alcohol in the dropdown will filter the cocktails data and return ingredients found in cocktails containing the selected alcohol.
[![image](https://user-images.githubusercontent.com/44886644/67910418-fd7c8200-fb58-11e9-8abc-dcfab49d4870.png)](https://beta.vizhub.com/jgorsett/74fec17030cb49298c397eeac028a908?edit=files)

### Interactive Bubble Chart for Top Cocktail Ingredients
Displays a U.S. map with circle marks for the top 10 ingredients in the data set, sized by the count of the cocktail items found at each location.  Hovering over the values in the legend will highlight the selected ingredients on the map.
[![image](https://user-images.githubusercontent.com/44886644/67910513-619f4600-fb59-11e9-8d69-69dd7293259b.png)](https://beta.vizhub.com/jgorsett/18e06a65bb964e0ebebab124d8bb2148)

### Interactive Cocktail Alcohol Pie Charts on U.S. Map
Displays pie charts containing the top 10 alcohols found in cocktails across locations on a U.S. map.  Hovering over the values in the legend will highlight the alcohol and counts within each pie chart.
[![image](https://user-images.githubusercontent.com/44886644/67909715-96f66480-fb56-11e9-86b1-e777bf3ba5b8.png)](https://beta.vizhub.com/jgorsett/7f4eab84f0d747159880fee9b3334633)

## Future Work
 * Add ingredient composition bar chart to the pie chart by region chart displayed across the bottom of the axis.  In addition to the current behavior, hovering over an alcohol type would filter the bar chart and return the ingredients and counts for cocktails in the filtered set.
 * Add multi-select capability to ingredient filtering to give the user more options to slice the data.
 * Look for a more robust dataset that includes cocktail ratings or a better popularity metric so these dimensions can be added to the visualizations.
