# Risk analysis for contents insurance

The model was designed to identify high risk policies when creating quotes and policies.

## Model Summary

- Target Region: UK
- Target User: Underwriters for insurance companies
- Target Insurance product(s): Contents-only and building with contents insurance products.

**Inputs and outputs:** The model receives information about the insured, property information and the area. The output is either high or low risk. All details can be found in the ModelCard.

**Model Architecture:** The model is RandomForest. It was trained with 13K policies balanced with high and low risk. All the details on accuracy, limitations, sensitive data and trade-offs are described in the ModelCard

## References

This folder has the following information:

- Jupyter Notebook. All technical information and step by step can be found here. At the end of the notebook there is information about all the results and decisions made.
- Model Card. All information about data used for training this model can be found in this document. Also the inputs and outputs and all the details can be found here
