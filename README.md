# Music Recommendation System on Spotify

## Dataset: [Spotify Million Song Dataset](https://www.kaggle.com/datasets/notshrirang/spotify-million-song-dataset)

<img src="https://res.cloudinary.com/dgwuwwqom/image/upload/v1731325452/Spotify.jpg" alt="Spotify" width="800"/>

This project implements a music recommendation system using data from **Spotify**. The system recommends personalized tracks based on users' listening preferences, leveraging machine learning and data analysis techniques.

## Key Features:
- **Personalized Recommendations**: Suggests tracks based on user preferences and listening history.
- **Collaborative Filtering**: Uses user-item interactions to suggest songs based on the behavior of similar users.
- **Content-Based Filtering**: Analyzes song features (e.g., genre, tempo, mood) to recommend similar tracks.
- **Hybrid Model**: Combines collaborative and content-based methods for more accurate suggestions.
  
## Technologies Used:
- **Spotify API**: For fetching user data, track features, and playlists.
- **Python**: Primary language for data processing, model development, and analysis.
- **Pandas, NumPy**: For data manipulation and analysis.
- **Scikit-Learn**: For implementing machine learning algorithms.


## Installation:
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/music-recommendation-spotify.git
   ```
2. Install required dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
3. Set up Spotify API credentials as per the instructions in the `config.py`.

## How It Works:
1. **User Data Collection**: The system connects to the Spotify API to collect user data such as listening history and playlist details.
2. **Model Training**: It trains machine learning models to understand user preferences and song attributes.
3. **Recommendations**: Based on the trained model, the system suggests personalized tracks for the user.

## Future Improvements:
- **Real-time recommendations**: Implementing real-time suggestions based on live listening behavior.
- **Enhanced Models**: Exploring deep learning techniques for better accuracy.
