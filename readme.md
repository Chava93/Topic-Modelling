# Topic Modeling From Trip Advisor

This repository contains the files I used to lead a workshop at my "Alma Máter" congress of actuary.

This repository contains the files I used to lead a workshop about a Natural Language Processing model called "Topic Modelling" at the Marista University (Mexico City).
The objective of this model is to find relevant topics out of a bunch of comments, opinions, etc.
Follow these steps to understand the model:
1) **Get the data**:  The script Tripadvisor_webScraping.ipynb will allow you to download reviews about "Paseo de la Reforma" ( A place in Mexico), it may take considerable time since it iterates through 459 trip advisor pages, downloads about 1300 reviews and stores them in the file "reviews.csv".
2) *If you want to skip the previous step* and go ahead to the topic modeling model there's no problem because the repository already contains the "reviews.csv" file.
3) **Topic Modeling:** The file "Trip_Advisor_TopicModelling.ipynb" will guide you through the steps to perform the topic modeling on the data obtained in step 1.