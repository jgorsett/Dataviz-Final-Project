# Data Visualization Project

## Data

I would like to base my project on a [dataset of cocktails](https://gist.github.com/jgorsett/6492ab1253c04167d1639c4ced71b3bf) collected by alcohol importer and distiller Hotaling & Co. The original dataset was modified to parse out and clean up the ingredients into rows.

## Prototypes

I’ve created a proof of concept visualization of this data. It's a bar graph showing ingredients included in cocktails containing selected ingredients.  For the prototype, the chart can be interactive if the user modifies the ingredient constants in the index.js file. The user can enter up to 5 ingredients to filter on. The user can also modify the nSlices constant in order to modify the number of results returned in the chart. The tooltip will show the cocktail names and the colors indicate the main alcohol contained in the cocktail.

[![image](https://user-images.githubusercontent.com/44886644/65655061-d62a1680-dfe8-11e9-8c74-7822644fbc6e.png)](https://vizhub.com/jgorsett/c5ae89a319ac45d691be5c0f69ff8ca9/fullscreen)


## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 *  How do cocktail ingredient trends compare across the US?
 *  What are the most common ingredient combinations?
 *  If the user would like to use specific ingredients, what other ingredients can they combine with them to make different cocktails?
 *  What are the most popular types of cocktails.

## Sketches

The sketch below shows a chart similar to the protoype above.  In the actual version, I'd like to have interactive filters for the user to select the ingredients to include and exclude.  There should be some type of color coding to help the user visualize the categories of ingredients.  

![image](https://user-images.githubusercontent.com/44886644/65655486-6583f980-dfea-11e9-886d-f7a58a1c2242.png)


The sketch below shows three maps showing the top categories including alcohol types, cocktail ingredients, and words in cocktail names for each location in the dataset.  Having the different maps all in one display will allow the user to see the different trends across the locations.

![image](https://user-images.githubusercontent.com/44886644/65656068-76ce0580-dfec-11e9-808b-09dac51ad11c.png)


## Open Questions

1) I don't know how to add data points to existing maps.  I've learned from the lectures on how to create and render a map, but I'm not sure how to combine the map data with my dataset and get it to render in the same visualization. 
2) I don't know how to do the interactive filtering in D3 and React.
3) I'm not sure how to display multiple maps all in the same visualization.
