# movie_rec_system
A smart movie recommendation system that suggests relevant movies to users by utilizing “all-MiniLM-L6-v2” (from the Sentence Transformers library) and trying a side AI component (BERT as a Zero-Shot Classifier).
The "TMDB Movies Dataset 2024 (1M Movies)" dataset was used, which contains 1 million movies with extensive metadata. This data provides essential information for building an effective recommendation model.
The dataset includes various key features, including the Title, Genres, Release Date, Runtime, Vote Average, Vote Count, Popularity, Overview, and finally Cast and Crew. The dataset is suitable for its encompassing features that all inclusively affect one’s choice for a film. 

<img width="500" height="100" alt="image" src="https://github.com/user-attachments/assets/9d33244e-9c73-4d43-bc3f-2c7bf39b4845" />

The dataset’s size and statistics included a million movies with various ranges. It also had descriptive data including popularity scores, vote counts, and movie summaries. Due to the extensive amount of missing data, only a subset was selected (100k instances) before the Modeling phase.  
For the UI, Streamlit was used due to its rapid prototyping capabilities, Python-native integration, and ability to create interactive web apps with minimal code. Users input their preferences via a text box, triggering the system to generate top five recommendations.
<img width="1000" height="500" alt="image" src="https://github.com/user-attachments/assets/caae1504-ce00-4a6a-8428-0ed7786f6316" />
