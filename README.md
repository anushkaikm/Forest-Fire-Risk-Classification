# Forest Fire Risk Classification 🌲🔥

## Overview
This project addresses the pressing issue of forest fires by developing a machine learning model to classify fire risk in a cost-effective manner. Using environmental data (temperature, humidity, wind speed, rainfall) and fire occurrence data from Montesinho Natural Park, Portugal, we built a classification model to predict fire risk on a hectare-by-hectare basis.

---

## Motivation
The increasing frequency of forest fires has severe economic, environmental, and social implications. Traditional fire monitoring methods, such as satellite imagery, are expensive and inaccessible for under-resourced regions. This project aims to demonstrate whether widely available weather data can offer an affordable alternative for predicting fire risks.

---

## Features
- **Data Analysis & Preprocessing**: 
  - Integrated and cleaned environmental and fire data.
  - Addressed class imbalance and converted categorical features into numerical representations.
  
- **Model Development**:
  - Built and optimized a Random Forest classifier.
  - Conducted hyperparameter tuning via grid search and cross-validation.

- **Trustworthiness Audit**:
  - Verified data provenance and reliability.
  - Evaluated ethical implications and model limitations.

---

## Key Results
- **Model Performance**:
  - Accuracy: 63.11%.
  - Key predictors: Temperature, Relative Humidity, Wind Speed.
  - Low confidence in predictions limits its reliability as a standalone tool.

- **Recommendations**:
  - Suitable as a supplementary tool for under-resourced regions.
  - Requires a more robust dataset for better accuracy.

---

## Dataset
The dataset used is from the Montesinho Natural Park, Portugal, sourced from [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/162/forest+fires). The data includes:
- Temperature, wind speed, relative humidity, and rainfall.
- Fire occurrence and severity.

---

## Tools & Libraries
- **Languages**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Version Control**: Git

---

## Limitations
- The model is not a substitute for high-cost fire surveillance systems.
- Predictions are limited by low confidence and data reliability.

---

## Future Work
- Improve accuracy using a more diverse and extensive dataset.
- Explore ensemble models or advanced algorithms for better predictions.
- Integrate real-time weather data for continuous monitoring.

---

## Contributing
Contributions are welcome! Please open an issue or submit a pull request with your suggestions or improvements.

---

## License
This project is licensed under the [MIT License](LICENSE).

---

## Acknowledgements 🙏

We would like to express our gratitude to the following individuals and organizations for their support and contributions to this project:

- **San Francisco State University**: For providing the platform and resources to conduct this project as part of the CSC 859 course, "AI Ethics and Explainability."
- **Professor [Dragutin Petkovic]**: For their invaluable guidance, feedback, and support throughout the project.
- **Teaching Assistant [Dave Daly]**: For assisting with technical challenges and ensuring the quality of our model development.
- **UCI Machine Learning Repository**: For the Montesinho Natural Park dataset that served as the foundation for this project.
- **Team 4 Members**:
  - Anushka Mondal: For leading coding efforts, organizing meetings, and ensuring the project stayed on track.
  - Zoe Long: For conducting due diligence, rechecking calculations, and contributing significantly to the coding process.
  - Rosaclaire Baisinger: For research, documentation, and auditing the ethical and trustworthiness aspects of the project.
- **OpenAI (ChatGPT)**: For supporting the team in debugging, optimizing code, and clarifying concepts related to machine learning.

Thank you all for making this project a reality!

