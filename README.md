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

## Live Demo
Visit the live visualization at: https://maggatronn.github.io/tarotemotiondata/

## Local Setup
1. Clone the repository
2. Place your `agreement_results_combined.csv` file in the root directory
3. Open `index.html` in a web browser

If that doesn't work, try running a local server:
```bash
python3 -m http.server 2000
```
Then open `http://localhost:2000` in your web browser.

## GitHub Pages Deployment
1. Go to your repository on GitHub
2. Go to Settings > Pages
3. Under "Source", select "main" branch
4. Click Save
5. Your site will be published at https://[YOUR_USERNAME].github.io/[REPO_NAME]/

## Data Format
The visualization expects a CSV file named `agreement_results_combined.csv` with the following columns:
- ImageID
- Image_[Emotion]_agreement (for each emotion)
- Transcript_[Emotion]_agreement (for each emotion)

## Technologies Used
- D3.js v7
- HTML5
- CSS3
