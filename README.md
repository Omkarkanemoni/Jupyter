
# Movie Recommender System

## Overview
The Movie Recommender System is a Python-based application that suggests movies to users based on their preferences. This project leverages content-based filtering techniques using cosine similarity and text processing to generate personalized movie recommendations. The system has been deployed on Streamlit, allowing users to input a movie title and receive a list of similar movies.

## Features
- **Content-Based Filtering:** Recommends movies based on the similarity of their descriptions.
- **User-Friendly Interface:** Deployed on Streamlit with a simple, interactive UI.
- **Data Processing:** Handles text data processing, including cleaning and vectorization.
- **Real-Time Recommendations:** Provides instant movie recommendations and displays movie posters.

## Dataset
The dataset used for this project was sourced from Kaggle. It contains information on various movies, such as titles, genres, overviews, popularity scores, and release dates.

## Tools and Technologies
- **Programming Language:** Python
- **Libraries:** `pandas`, `scikit-learn`, `Streamlit`, `requests`, `pickle`
- **API:** TMDB API for fetching movie posters
- **Deployment Platform:** Streamlit

## Usage
1. **Launch the Application:** Run the Streamlit app using the command above.
2. **Select a Movie:** Use the dropdown menu to select a movie title.
3. **Get Recommendations:** Click the "Recommend" button to see a list of similar movies along with their posters.

## Project Structure
- `app.py`: Main application file containing the Streamlit code.
- `movie_recommender.py`: Core recommendation logic, including data processing and similarity computation.
- `movies.csv/`: Folder containing the movie dataset.
- `main.ipynb/`: Folder containing serialized models or processed data (e.g., pickled files).
- `README.md`: Project documentation.

## Future Enhancements
- **Collaborative Filtering:** Incorporate collaborative filtering techniques for improved recommendations.
- **Enhanced UI:** Further improve the user interface with additional features like genre filters.
- **Model Optimization:** Experiment with different similarity measures and feature selection methods to enhance recommendation accuracy.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes. For major changes, please open an issue to discuss what you would like to change.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- **Diginique Techlabs:** For providing the internship and learning resources.
- **Kaggle:** For the movie dataset.
- **Streamlit:** For the easy-to-use app framework.

---
