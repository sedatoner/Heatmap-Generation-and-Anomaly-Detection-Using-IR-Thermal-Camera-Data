# Heatmap Generation and Anomaly Detection Using IR Thermal Camera Data (Python)

This is a project where I simulate IR thermal camera data and use Python to create heatmaps and detect anomalies based on temperature.

## What I Did

I wrote a Python script that:

- Generates synthetic thermal data (basically a fake thermal image)
- Adds random hot spots to simulate anomalies
- Visualizes the data as a heatmap using matplotlib and OpenCV
- Detects anomalies based on mean plus two standard deviations
- Draws boxes around those anomalies
- Saves the output images and a CSV report with stats

## Tech Stack

- Python, NumPy, Matplotlib, OpenCV, SciPy, Pandas

## How It Works

1. I create 64x64 arrays with temperature values between 20°C and 80°C
2. I randomly insert a few high-temperature areas (around 90–110°C)
3. I plot the data as a heatmap
4. I detect anomaly pixels that are above mean + 2 * std
5. I draw bounding boxes around the anomalies
6. I save the images and generate a CSV file with mean, std, threshold, and anomaly count

## Next Steps

I plan to:

- Use real thermal image datasets from the internet
- Try machine learning-based anomaly detection methods like Isolation Forest
- Build a simple dashboard or web app using Streamlit

## Why I Did This

I wanted to learn how to work with thermal sensor data, practice image processing, and combine that with basic data analysis. 
