# Crop Recommendation System (Agro-Advisor)

- Crop recommendation is a crucial aspect of precision agriculture, aiming to optimize crop selection based on various factors. The precision agriculture approach tailors recommendations to specific sites, ensuring optimal outcomes.
- While advancements in "site-specific" methodologies have enhanced performance, ongoing monitoring remains crucial for system validation.
- Precision agriculture systems vary in efficacy, emphasizing the paramount importance of accurate and precise recommendations. In the agricultural context, errors in these recommendations can lead to substantial material and capital losses.

## Application Overview

This application serves as a valuable tool for farmers, aiding in the enhancement of agricultural productivity, prevention of soil degradation, reduction of chemical usage in crop production, and maximization of water resource efficiency.

## [Dataset](#)

The dataset used for this application was constructed by augmenting existing datasets containing rainfall, climate, and fertilizer data for India.

### Attributes Information:

- **N**: Ratio of Nitrogen content in soil
- **P**: Ratio of Phosphorous content in soil
- **K**: Ratio of Potassium content in soil
- **Temperature**: Temperature in degrees Celsius
- **Humidity**: Relative humidity in %
- **pH**: pH value of the soil
- **Rainfall**: Rainfall in mm

## [How to Run the Code](#)

1. Clone the repository:

    ```bash
    git clone https://github.com/CodeWizardl/Agro-Advisor.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Agro-Advisor
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Run the Streamlit app:

    ```bash
    streamlit run app.py
    ```

5. Open your web browser and go to the provided URL (usually http://localhost:8501) to interact with the Crop Recommendation System.


## [Experiment Results](#)

### Data Analysis
- All columns exhibit outliers except for N.

### Performance Evaluation
- Dataset split into 80% training set and 20% validation set.

### Training and Validation
- GaussianNB outperformed other classification models, achieving a 99% accuracy score.

### Performance Results
- Training Score: 99.5%
- Validation Score: 99.3%

## [Demo Images](#)

### _Before Prediction Output_
![Main](https://github.com/CodeWizardl/Agro-Advisor/assets/142290678/beed11a0-2863-48c1-ae05-a5bd872766f5)
### _After Prediction Output_
![Output](https://github.com/CodeWizardl/Agro-Advisor/assets/142290678/061551ce-d33a-47a0-9cfe-d71a36d3d082)

Feel free to explore the application, input your data, and experience the benefits of precision agriculture in crop selection.

## [Conclusion](#)

This Crop Recommendation System not only facilitates informed decision-making for farmers but also plays a pivotal role in sustainable agriculture practices. The high accuracy scores obtained during training and validation demonstrate the reliability and effectiveness of the model in providing precise crop recommendations.
