# Content-Based-Movie-Recommendation-System
I developed a content-based recommendation system using Tmdb data and implemented it on a website using <b>Streamlit</b>. To create the model, I first preprocessed the data by removing duplicate entries, handling missing values, and converting text fields to lowercase. I then used <b>Stemming</b> and <b>Bag of Words</b> techniques to process the overview and tagline fields, which helped in identifying the relevant keywords and improving the accuracy of the model.

The recommendation system suggests movies based on the similarity of their <b>overview,cast,crew,genre and keywords</b> to the user's input. To achieve this, I calculated the <b>cosine similarity</b> of the processed overview and tagline fields, and sorted the results to suggest movies with the highest similarity score.

I implemented the model on a website using Streamlit, which allows users to enter a movie title, and get recommendations based on the similarity of their plots to the input movie. The website also displays additional information about the recommended movies, such as the release date, vote average, and overview.
