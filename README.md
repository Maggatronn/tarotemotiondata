# Emotion Agreement Visualization

An interactive D3.js visualization showing emotion agreement scores between images and transcripts. The visualization uses a radial bar chart to display agreement scores for eight different emotions:
- Joy
- Trust
- Fear
- Surprise
- Sadness
- Disgust
- Anger
- Anticipation

## Features
- Interactive selection of individual images or view of average scores
- Dual visualization of image and transcript agreement scores
- Color-coded emotions with distinct patterns for transcript scores
- Hover tooltips showing exact percentage values
- Concentric reference circles for easy value reading

## Setup
1. Clone the repository
2. Place your `agreement_results_combined.csv` file in the root directory
3. Open `radial_emotions.html` in a web browser

If that doesn't work, try opening the file in VS code or cursor, and then run this: 
<python3 -m http.server 2000> and then open localhost:2000 in a web browser


## Data Format
The visualization expects a CSV file named `agreement_results_combined.csv` with the following columns:
- ImageID
- Image_[Emotion]_agreement (for each emotion)
- Transcript_[Emotion]_agreement (for each emotion)
