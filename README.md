# amazon-archaeology-gee
A geospatial project for the OpenAI to Z Challenge, using NDVI and texture analysis in Google Earth Engine to detect suspected archaeological zones in the Amazon.
# 🏺 Amazon Archaeology Detection via Google Earth Engine

This project was developed for the [OpenAI to Z Challenge (2024)](https://www.kaggle.com/competitions/openai-to-z-challenge-2024) and aims to discover possible archaeological sites in the western Amazon basin using satellite imagery and NDVI-based anomaly detection via Google Earth Engine (GEE).

## 🌍 Region of Interest
**Vale do Javari**, a remote area along the Brazil–Peru border, rich in ecological diversity and potentially undocumented historical human activity.

## 🚀 Methodology
- Sentinel-2 NDVI time series analysis (2019–2022)
- GLCM texture (contrast) filtering
- Slope filtering from SRTM DEM
- EVI and NDBI filtering for confirmation
- Change detection and anomaly masking
- Centroid extraction and CSV export

## 📁 Project Structure
- `/data` – Output CSV (`archaeology_submission.csv`)
- `/notebooks` – Final Kaggle notebook used for processing
- `/images` – Visual samples of GEE results

## 🧠 Final Output
- ~770 NDVI anomaly pixels processed
- 4 suspected archaeological zones extracted
- CSV includes coordinates for potential field investigation

## 📜 License
Released under [CC0 1.0 Public Domain](https://creativecommons.org/publicdomain/zero/1.0/)

## 🔗 Resources
- [Kaggle Notebook](https://www.kaggle.com/code/mohammadteimoury/notebook304eff8b8b)
- [Submission CSV](https://www.kaggle.com/datasets/mohammadteimoury/archaeology-submission)

## ✨ Author
**Mohammad Teimoury**  
Kaggle: [@mohammadteimoury](https://www.kaggle.com/mohammadteimoury)
