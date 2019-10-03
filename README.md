# Data Visualization Project

## Data

I would like to base my project on a [dataset of cocktails](https://gist.github.com/jgorsett/6492ab1253c04167d1639c4ced71b3bf) collected by alcohol importer and distiller Hotaling & Co. The original dataset was modified to parse out and clean up the ingredients into rows.

## Prototypes

I’ve created a proof of concept visualization of this data. It is a bar graph showing ingredients included in cocktails containing selected ingredients.  For the prototype, the chart can be interactive if the user modifies the ingredient constants in the index.js file. The user can enter up to 5 ingredients to filter on. The user can also modify the “nSlices” constant in order to modify the number of results returned in the chart. The tooltip will show the cocktail names and the colors indicate the main alcohol contained in the cocktail.

[![image](https://user-images.githubusercontent.com/44886644/65655061-d62a1680-dfe8-11e9-8c74-7822644fbc6e.png)](https://vizhub.com/jgorsett/c5ae89a319ac45d691be5c0f69ff8ca9/fullscreen)


## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 *  How do cocktail ingredient trends compare across the US?
 *  What are the most common ingredient combinations?
 *  If the user would like to use specific ingredients, what other ingredients can they combine with them to make different cocktails?
 *  What are the most popular types of cocktails?
 *  What is the composition of cocktails served in different locations?

## Sketches

The sketch below shows a chart similar to the prototype above.  In the actual version, I'd like to have interactive filters for the user to select the ingredients to include and exclude.  There should be some type of color coding to help the user visualize the categories of ingredients.  

![image](https://user-images.githubusercontent.com/44886644/65655486-6583f980-dfea-11e9-886d-f7a58a1c2242.png)


The sketch below displays three maps showing the top categories including alcohol types, cocktail ingredients, and words in cocktail names for each location in the dataset.  Having the different maps all in one display will allow the user to see the different trends across the locations.  The graphs will either be displayed as three graphs together or the user will be able to select the category from a dropdown and this will dynamically change the attribute displayed on the graph.  To extend this further, I would like to add radial donut charts across the map to show cocktail compositions and include cocktail images to make the visualization more appealing.

![image](https://user-images.githubusercontent.com/44886644/65656068-76ce0580-dfec-11e9-808b-09dac51ad11c.png)


## Interactions

1) The users will select from dropdowns to allow for the filtering of ingredients.
2) In order to view the top trends across locations, the user will be able to select attributes from a dropdown which will allow the attribute to be displayed on the chart.
3) Tooltips will display the details (e.g. Cocktail Name, location) about the data points.

## Schedule of Deliverables

* 10/9: Finalize sketches and prototypes and solicit feedback
* 10/16: Finalize data manipulations and cleanup required to do visualizations
* 10/23: Finalize interactivity
* 10/30: Polish and perform final edits on the visualization and submit


