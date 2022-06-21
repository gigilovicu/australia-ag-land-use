# Predicting Agricultural Land Use in Australia

Farmers often have to decide how to deploy land for agricultural production. In particular, they
must consider how topography, weather and other environmental factors affect the suitability of
their land for particular types of production. Farmers have traditionally made such decisions on
the basis of experience, past performance (something worked well, something else didn’t) or
perhaps on the advice of peers or other professionals. However, the growing availability of
highly granular data means that this decision can be more data-driven.

To demonstrate this, we train a neural network to predict agricultural land use. This model can
act as a recommender system for farmers. We train the model using a geo-spatial cross-section
of agricultural land use (by commodity) in Australia, joined spatially with environmental features
related to that particular piece of land. We have chosen Australia to construct our data set
because it has a large agricultural sector, varied
