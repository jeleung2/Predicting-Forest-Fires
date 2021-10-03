## Predicting-Forest-Fires

### Project Summary
In this personal project, I am attempting to build a neural network that will predict whether a fire occurs based on temporal, weather, and geographic attributes. The region from which that data was collected from is the northeast region of Portugal.

### Data Source
This dataset was taken from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/forest+fires). It contains 517 rows and 131 columns. 1 column indicates how much of an area was burned. This column was one-hot encoded so that a region that never experienced burning was considered '0', and a region that suffered a burning of any magnitude was considered '1'. The other 12 columns describe the attributes of the burn/no-burn observation. 
