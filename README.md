# Book Recommendations

This project implements a Book Recommendation System using Machine Learning algorithms. The system recommends books to users based on their movie preferences. By leveraging collaborative filtering and other ML techniques, the system aims to provide personalized book recommendations to users, enhancing their reading experiences.

## Overview

People often find watching movie adaptations of books, less cumbersome and more relaxing than reading the original books itself. Moreover the number of people that truly spare time to read novels has only been declining ever since numerous online streaming platforms have taken over the internet/entertainment industry. Our project helps discover and revive users interest in the marvellous world of books by recommending the perfect book to start off with based on their movie preferences.


## Datasets

1. `Keywords.csv` -id,keywords
2. `Metadata_movies.csv`- adult,belongs_to_collection,budget,genres,homepage,id,imdb_id,original_language,original_title,overview,popularity,poster_path,production_companies,production_countries,release_date,revenue,runtime,spoken_languages,status,tagline,title,video,vote_average,vote_count
3. `Data.csv`-index,title,genre,summary

Find the datasets here - https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset

## Usage

1. Clone the repository or download the project files to your local machine.
2. Ensure that the dataset files are located in the `data` directory.
3. Open and run the Jupyter Notebook or Python script associated with the Telco Churn analysis.
4. Follow the code comments and instructions within the notebook/script to execute the analysis step by step.

## Graph Data

Unweighted Graph:
Nodes-200 
Edges- 16726 
Weighted Graph:
Nodes - 200 
Edges - 16726

## Implementation:
1. 3 Cosine similarity matrices are created
    * Movies cosine similarity
    * Books cosine similarity
    * Movies vs Books cosine similarity
2. Applied 3 Link Prediction ML models
   * Traditional link prediction method using Jaccard Coefficient
   * Link prediction using Graph Neural Networks
     * GCN
     * GraphSage
       
## Results:

Accuracy provided by our models
1. GCN Model-0.8676
2. GraphSage-0.8655

* Jaccard coefficient:
AUC 0.83
* Adamic-Adar:
AUC 0.85
* Preferential Attachment:
AUC 0.86
