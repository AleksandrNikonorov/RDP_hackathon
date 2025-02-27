# Project: RDP Company Hackathon

## Description

In the RDP Company hackathon, our team tackled three challenges related to network traffic analysis. The project involved tasks for classifying and clustering network protocols, as well as detecting change points in the time series of network traffic.

## Project Tasks

1. **Network Protocol Classification**
   - Developed a model to classify network protocols based on traffic analysis.
   - Utilized machine learning methods such as Random Forest and gradient boosting (CatBoost).
   - The model was trained and tested on real network traffic data.

2. **Protocol Clustering**
   - Applied clustering methods to group various network protocols based on traffic characteristics.
   - Employed algorithms like K-Means and DBSCAN to identify groups of protocols with similar behavior patterns.

3. **Detection of Change Points in Network Traffic Time Series**
   - Analyzed the company's traffic time series to identify points of behavioral change.
   - Used change detection methods, such as the CUSUM method and other approaches for anomaly detection in the data.

## Technologies Used

- **Python** — primary programming language.
- **pandas** / **numpy** — for data processing.
- **scikit-learn** — for classification and clustering.
- **CatBoost** — to enhance classification accuracy.
- **matplotlib** / **seaborn** — for data visualization.
- **ruptures** — for detecting change points in time series.

## Project Structure

- `RDP` — classification of network protocols using gradient methods.
- `RDP Time Series` — Task 3: analysis of time series using various methods, such as time series clustering, moving averages, and more.
- `RDP Clustering` — Task 2: clustering using classical KMeans.
- `Report` — presentation from the hackathon.
- `README.md` — project description.


