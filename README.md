# Interpretable Machine Learning Approach to Alzheimer's Classification
Interpretable machine learning approach to identifying white matter brain differences between healthy aging and Alzheimer’s onset through diffusion tensor imaging

### See short presentation here : https://vimeo.com/544808812

![image](https://user-images.githubusercontent.com/54241448/116970200-29605280-ac7d-11eb-837e-794cc2e4822d.png)

## The Approach 
My approach was to use a variety of models to classify scans of those diagnosed with AD and those without AD and look at the features the models considered important in making the classification. These features could reveal details about how and where AD effects the connectivity of the brain.
![image](https://user-images.githubusercontent.com/54241448/116971049-9cb69400-ac7e-11eb-8ed6-e709cd90a87e.png)

## The Data (data folder)
- primary data : Baltimore Longitudinal Study of Aging (BLSA) (NOT INCLUDED)
- bundles dict & measures dict : Bundle & Measure Names

## The Outputs (feature_imps folder)
- feature importances : output of jupyter notebooks
- feature importances final : modified for easy input into Tableau for visualizations
- feature importances ranked final : ranked by committee importance methedology

## The Models
I chose 5 separate models (logistic regression, support vector classification, random forest classifier, multi-layer perceptron (fully connected neural net), and gradient boosted trees classifier), that had acceptable performance in classifying AD and non-AD scans from which to extract feature importance’s’.
![image](https://user-images.githubusercontent.com/54241448/116971164-c66fbb00-ac7e-11eb-9050-236db9cca623.png)

## The Feature Importances
![image](https://user-images.githubusercontent.com/54241448/116970989-84df1000-ac7e-11eb-99cc-985aa3a9e232.png)
![image](https://user-images.githubusercontent.com/54241448/116970998-87da0080-ac7e-11eb-821c-c6ffe038afdf.png)
![image](https://user-images.githubusercontent.com/54241448/116971003-8ad4f100-ac7e-11eb-8121-803171c20dfa.png)



