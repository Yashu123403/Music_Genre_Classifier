#  Music Genre Classifier

A Machine Learning project that classifies songs into different music genres using audio feature extraction and a Random Forest classifier.

##  Features
- Audio feature extraction using Librosa
- Genre prediction using Machine Learning
- Random Forest classification model
- PCA visualization of genre clusters
- Confidence score prediction
- Model saving using Joblib

## Technologies Used
- Python
- Librosa
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib

##  Project Workflow
1. Load audio files
2. Extract audio features
3. Store features in CSV format
4. Train ML model
5. Test model performance
6. Predict genre for new songs
7. Save trained model

## Genres Used
- Classical
- HipHop
- Jazz

## Audio Features Extracted
- MFCCs
- Chroma STFT
- Spectral Centroid
- Spectral Bandwidth
- Spectral Rolloff
- Zero Crossing Rate
- Harmony & Percussive Features
- RMS Energy

##  Model Used
- Random Forest Classifier

##  Saved Model Files
- `music_genre_model.pkl`
- `music_scaler.pkl`
- `music_encoder.pkl`

##  How to Run
Install the required Python libraries and run the notebook or Python script to:
- Extract features
- Train the model
- Predict genres

##  Future Improvements
- Add more music genres
- Improve dataset size
- Build a web application
- Try deep learning models like CNN or LSTM

## Author
YASHU A.B.
