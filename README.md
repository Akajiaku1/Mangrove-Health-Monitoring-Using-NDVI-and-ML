🌿 Mangrove Health Monitoring Using NDVI and Machine Learning
📌 Project Overview

This project focuses on assessing the health of mangrove ecosystems using satellite-derived vegetation indices, particularly the Normalized Difference Vegetation Index (NDVI), combined with Machine Learning (ML) models. The study aims to map, monitor, and classify mangrove health conditions over time, with applications in environmental conservation, ecosystem restoration, and climate resilience.
🎯 Objectives

    Extract and analyze NDVI values from multi-temporal satellite imagery (e.g., Landsat, Sentinel-2).

    Classify mangrove vegetation health into categories (e.g., healthy, stressed, degraded).

    Apply supervised ML models (e.g., Random Forest, SVM, XGBoost) for health prediction.

    Generate geospatial health maps to visualize degradation patterns.

    Validate results using ground-truth data and/or high-resolution images.

🛰️ Data Sources

    Satellite Imagery: Sentinel-2A, Landsat 8 OLI

    Preprocessing Tools: Google Earth Engine (GEE), QGIS, ArcGIS

    NDVI Calculation: (NIR - Red) / (NIR + Red)

    Ancillary Data: Field observations (if available), land cover maps, DEMs

🧠 Machine Learning Models

Implemented classifiers for NDVI-based mangrove health prediction:

    Random Forest (RF)

    Support Vector Machine (SVM)

    Gradient Boosted Trees (XGBoost)

    K-Nearest Neighbors (KNN)

Each model is trained and evaluated using accuracy, confusion matrix, precision, recall, and F1-score.
🗂️ Project Structure

Mangrove-Health-Monitoring-Using-NDVI-and-ML/
├── data/                  # Satellite and ancillary data
├── notebooks/             # Jupyter Notebooks for analysis and modeling
├── scripts/               # Python scripts for automation
├── results/               # Maps, model outputs, evaluation metrics
├── figures/               # Visualizations and plots
├── models/                # Trained ML models
└── README.md              # Project documentation

🔧 Tools & Technologies

    Google Earth Engine (GEE)

    Python (Pandas, Scikit-learn, Rasterio, Numpy, Matplotlib, Seaborn)

    QGIS / ArcGIS Pro

    Jupyter Notebooks

    Git for version control

📊 Outputs

    NDVI time-series maps of mangrove regions

    Mangrove health classification maps

    ML model performance reports

    Geostatistical and accuracy assessment charts

📌 Use Cases

    Coastal ecosystem health monitoring

    Environmental impact assessments

    Restoration planning for degraded mangroves

    Climate change adaptation and biodiversity conservation

🧪 Future Work

    Integration with SAR data (e.g., Sentinel-1) for improved detection under cloud cover.

    Use of deep learning (e.g., CNN) for higher classification accuracy.

    Real-time NDVI change detection with cloud-based pipelines.

📚 References

    Giri, C., Ochieng, E., Tieszen, L. L., et al. (2011). Status and distribution of mangrove forests of the world using earth observation satellite data. Global Ecology and Biogeography, 20(1), 154–159.

    Tucker, C. J. (1979). Red and photographic infrared linear combinations for monitoring vegetation. Remote Sensing of Environment, 8(2), 127–150.

    Belgiu, M., & Drăguţ, L. (2016). Random forest in remote sensing: A review of applications and future directions. ISPRS Journal of Photogrammetry and Remote Sensing, 114, 24–31.

🤝 Contribution

Feel free to fork the repository, submit issues, or create pull requests to improve the project. Collaboration is welcome!
📝 License

This project is open-source and available under the MIT License.
