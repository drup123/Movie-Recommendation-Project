Features

 - Search for Movies: Users can search for a movie from a preloaded list of titles.

 - Get Recommendations: Provides a list of 10 similar movies along with their posters.

 - Interactive Interface: Built with Streamlit, the app offers an intuitive and user-friendly interface.

----------------------------------------------------------------------------------------------------------

Technologies Used

 - Python: Core programming language.

 - Streamlit: For building the web application.

 - Pandas: For data manipulation.

 - Pickle: To save and load preprocessed data.

 - Requests: For fetching movie posters via The Movie Database (TMDb) API.

 -------------------------------------------------------------------------------------------------------------

File Structure

 movies_hub/
├── app.py              # Main application script
├── movies.pkl          # Preprocessed movie data
├── similarity.pkl      # Precomputed similarity matrix
├── requirements.txt    # Dependencies

Run the Application
Launch the Streamlit app by executing:
 - streamlit run app.py