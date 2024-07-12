# goodreads-nlp-analysis
## Project Overview
This project aims to perform an in-depth analysis of Goodreads reviews using Natural Language Processing (NLP) techniques. It includes sentiment analysis, topic modeling, and various visualizations to uncover insights from book reviews.

## Features
* **Data Preprocessing:** Cleaning and preparing the data for analysis using NLTK and spaCy.
* **Sentiment Analysis:** Using the VADER sentiment analyzer to classify reviews into positive, negative, and neutral categories.
* **Topic Modeling:** Identifying common topics in reviews using LDA (Latent Dirichlet Allocation).
* **Visualizations:** Creating plots and word clouds to visually represent the sentiment and topics in the reviews.

## Data source
https://mengtingwan.github.io/data/goodreads.html - goodreads_reviews_spoiler.json

## Repository Structure
* Goodreads_Reviews_Analysis.ipynb: The main Jupyter Notebook containing the project code.
* GoodReads_Data_Preparation.ipynb: The  Jupyter Notebook containing data preprocessing code.
* requirements.txt: The list of dependencies required to run the project.
* README.md: Project documentation.

## Key Insights:
* **Ratings Distribution**: The analysis showed a strong preference for higher ratings, with the majority of reviews clustering around 4 and 5 stars. This suggests a generally positive reception of the books reviewed.

* **Review Length**: Most reviews were relatively short, with approximately 67% consisting of fewer than 200 words. This indicates that users often express their opinions succinctly, focusing on key impressions rather than extensive critiques.

* **User Engagement**: The user distribution highlighted that a small number of highly active users contributed a large portion of the reviews, reflecting a dedicated community of avid readers.

* **Sentiment Analysis**: The sentiment analysis revealed that the majority of reviews were classified as positive, with 83.57% of reviews expressing favorable opinions. This indicates a strong overall satisfaction with the books reviewed.

* **Topic Modeling**: The topic modeling identified 15 distinct themes within the reviews, encompassing various genres and reader experiences. Key topics included romance, fantasy, young adult fiction, and themes related to life and relationships, demonstrating the diverse interests of the Goodreads community.

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## Acknowledgements
* Goodreads for providing the review data.
* The developers of NLTK, spaCy, and other libraries used in this project.
