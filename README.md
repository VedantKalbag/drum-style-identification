# Drum Playing Style Recognition

The aim of this project is to listen to a sample of drum-only audio and classify it into one of the following playing styles:
1. Funk
2. Rock
3. Hip Hop
4. Jazz

Experiments with feature selection were conducted using mutual information and variance thresholding across the following features:
- 13 MFCCs
- Spectral Centroid
- RMS
- ZCR
- Spectral Flux
- Spectral Slope
- Signal Energy
- Signal Power

The selected features were used along with an SVM and Random Forest Classifier. The best results were obtained with a RF classifier and achieved a 70% f1-score
