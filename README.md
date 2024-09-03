# Be-Healthy-System-Design-Case-Study
>
> This is a system design case study for Be Healthy, a health platform. The case study focuses on the system designed required for hosting a custom NER Model.

## Table of Contents

- [Be-Healthy-System-Design-Case-Study](#be-healthy-system-design-case-study)
  - [Table of Contents](#table-of-contents)
  - [General Information](#general-information)
    - [Problem Statement](#problem-statement)
    - [Solution](#solution)
  - [Contact](#contact)
  - [License](#license)

## General Information

### Problem Statement

‘BeHealthy’ has a web platform that allows doctors to list their services and manage patient interactions and provides services for patients such as booking interactions with doctors and ordering medicines online. Here, doctors can easily organise appointments, track past medical records and provide e-prescriptions.

## Solution

### Tasks expected in the assignment

*  Process and modify the data into sentence format. This step has to be done for the 'train_sent' and ‘train_label’ datasets and for test datasets as well.
*  Define the features to build the CRF model.
*  Need to apply these features in each sentence of the train and the test dataset to get the feature values.
*  Once the features are computed, need to define the target variable and then build the CRF model.
*  Next step is to perform the evaluation using a test data set.
*  Lastly, create a dictionary in which diseases are keys and treatments are values.
*  Predict the treatment for the disease named 'hereditary retinoblastoma'

### Treatment for the disease 'hereditary retinoblastoma' is predicted as 'radiotherapy'

## Contact

Created by [@kalyanvkb] - feel free to contact me!
