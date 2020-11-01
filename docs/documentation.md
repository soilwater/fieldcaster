# Fieldcaster

Fieldcaster is a soil water balance model based on the widely accepted FAO-56 dual crop coefficient method (Allen et al 1998). Fieldcaster generates forecasts of the soil water balance using plausible scenarios based on environmental conditions of the ongogin growing season and historical climate records. This approach departs from existing crop models that typically allow for modeling one scenario at the time.

The core of the model was implemented in pure, functional Javascript and has no external dependencies. This approach makes Fieldcaster lightweight (only 48 KB) and extremely fast, taking about 100 milliseconds to generate forecasts based on 20 years of climate data. The web interface relies on few external open source libraries such as Materialize CSS for styling, Plotly for generating interactive graphs, and noUiSlider for interactive controls.

Fieldcaster is a portmanteau between the words "Field" and "Forecaster"

## Differences with the Dual Kc model




## Input data

### Climate

Historical weather data constitutes the source of plausible scenarios for the model. Although there is no certainty of the future environmental conditions, past weather records provide a reliable source of scenarios for the region.

### Observations

Daily weather data for the current growing season.

### Soil

