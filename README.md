# Data Visualization Project

## Data

I would like to base my project on a [dataset of cocktails](https://gist.github.com/jgorsett/6492ab1253c04167d1639c4ced71b3bf) collected by alcohol importer and distiller Hotaling & Co. The original dataset was modified to parse out and clean up the ingredients into rows.

## Prototypes

### 1)
I’ve created a proof of concept visualization of this data. It is a bar graph showing ingredients included in cocktails containing selected ingredients.  For the prototype, the chart can be interactive if the user modifies the ingredient constants in the index.js file. The user can enter up to 5 ingredients to filter on. The user can also modify the “nSlices” constant in order to modify the number of results returned in the chart. The tooltip will show the cocktail names and the colors indicate the main alcohol contained in the cocktail.

[![image](https://user-images.githubusercontent.com/44886644/65655061-d62a1680-dfe8-11e9-8c74-7822644fbc6e.png)](https://vizhub.com/jgorsett/c5ae89a319ac45d691be5c0f69ff8ca9/fullscreen)

### 2) 
This prototype shows the top ingredients in cocktails across the US.  The legend is interactive.  I plan to extend this further to make the map make more sense.  For example right now trends are not very obvious.  San Francisco had the largest sample of cocktails so the circles on the map are very large for most ingredients compared to other locations.

[![image](https://user-images.githubusercontent.com/44886644/66532258-c1677b80-eadc-11e9-9a7a-3bb51b983662.png)](https://beta.vizhub.com/jgorsett/4f713ace93ca4f25895cef013ce00771)

### 3) 
This basic prototype has the beginnings of what I intend to do to show cocktail compositions across the US.  The data has been prepared so each location can show the ingredient compositions filtered for locations with common ingredients in 3 or more cocktails.  Right now the chart shows circles for the locations.  However, I would like to include radial charts at each location.
[![image](https://user-images.githubusercontent.com/44886644/66533101-b82bde00-eadf-11e9-9224-2d68cc21a394.png)](https://beta.vizhub.com/jgorsett/e5ac059bc26a4d1b8e0924876843ca10)


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

## Breakthroughs

The week 6 lectures were extremely helpful for me in completing my prototypes, especially the lectures about Points on the Map and Interactive Highlighting.  I was able to apply these to my project quite successfully. (Thank you, Curran!)


## Schedule of Deliverables

* 10/9: Finalize sketches and first drafts of prototypes and solicit feedback
* 10/16: Finalize prototypes, data manipulations and cleanup required to do visualizations
* 10/23: Finalize interactivity and continue to refine visualizations
* 10/30: Polish and perform final edits on the visualization and submit


