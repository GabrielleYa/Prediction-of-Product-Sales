# Prediction-of-Product-Sales

## Understanding outlet and product sales

- **Author:** Gabrielle Ray

## **Business Problem:**
A retailer is looking to understand the relationship between the propertes of the products and the outlets that play crucial roles in increasing sales. 

## **Data:**

![Screenshot 2023-09-13 151215](https://github.com/GabrielleYa/Prediction-of-Product-Sales/assets/135492530/53a7366f-5f21-47bc-a85c-3ccce4c32def)

## **Methods:**
- Three of the features during this anaysis presented a strong realtionship with the target
- Only one feature was removed during the data cleaning. The "Item ideninfier" feature presented a high cardinalty and provided no inght to the anlysis.

## **Results:**
![Screenshot 2023-10-06 075213](https://github.com/GabrielleYa/Prediction-of-Product-Sales/assets/135492530/c7a235ce-37c7-4756-9e09-497df83fe454)


![Screenshot 2023-10-06 074511](https://github.com/GabrielleYa/Prediction-of-Product-Sales/assets/135492530/a2d991d9-287d-47e5-bcff-26ced2fe9b57)

Logistic Regression Coefficents Feature Interpretation:

![Screenshot 2023-10-12 211055](https://github.com/GabrielleYa/Prediction-of-Product-Sales/assets/135492530/fbbf6654-abe9-4b2e-8ac0-936c79891e1a)
- Most of the feature coeffiecents are negativly corellated with the target.
- The following features have the highest feature importance to the target
  - Outlet Identifier
  - Outlet Establishment Year
  - Outlet Location Type

Random Forest Model Feature Importance Interpretation:

![Screenshot 2023-10-12 211142](https://github.com/GabrielleYa/Prediction-of-Product-Sales/assets/135492530/bdac14e2-5c78-4e0a-b1e9-f6d838762a36)
- The following features have the highest feature importance to the target:
 - Item MRP
 - Outlet Type Grocery Store
 - Item Visibilty
 - Item Weight
 - Outlet Identifier


