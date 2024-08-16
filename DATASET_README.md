## Dataset

### Context
This is a multivariate dataset, meaning it involves a variety of separate mathematical or statistical variables, and is suitable for multivariate numerical data analysis. The dataset is composed of 14 attributes, including age, sex, chest pain type, resting blood pressure, serum cholesterol, fasting blood sugar, resting electrocardiographic results, maximum heart rate achieved, exercise-induced angina, ST depression induced by exercise relative to rest, the slope of the peak exercise ST segment, the number of major vessels, and Thalassemia. Although the database includes 76 attributes, all published studies have focused on a subset of 14. The Cleveland database is the primary dataset used by machine learning researchers to date.

One of the main tasks with this dataset is to predict, based on the given attributes, whether a particular patient has heart disease or not. Another task is to diagnose and extract insights from the dataset that could help in understanding the problem more deeply.

### Column Descriptions
- `id`: Unique ID for each patient
- `age`: Age of the patient in years
- `origin`: Place of study
- `sex`: Gender of the patient (Male/Female)
- `cp`: Chest pain type (typical angina, atypical angina, non-anginal, asymptomatic)
- `trestbps`: Resting blood pressure (in mm Hg on admission to the hospital)
- `chol`: Serum cholesterol in mg/dl
- `fbs`: Fasting blood sugar > 120 mg/dl (True/False)
- `restecg`: Resting electrocardiographic results (normal, ST-T abnormality, left ventricular hypertrophy)
- `thalach`: Maximum heart rate achieved
- `exang`: Exercise-induced angina (True/False)
- `oldpeak`: ST depression induced by exercise relative to rest
- `slope`: The slope of the peak exercise ST segment
- `ca`: Number of major vessels (0-3) colored by fluoroscopy
- `thal`: Thalassemia (normal, fixed defect, reversible defect)
- `num`: The predicted attribute (target variable)

### Acknowledgements
**Creators:**
- Hungarian Institute of Cardiology, Budapest: Andras Janosi, M.D.
- University Hospital, Zurich, Switzerland: William Steinbrunn, M.D.
- University Hospital, Basel, Switzerland: Matthias Pfisterer, M.D.
- V.A. Medical Center, Long Beach and Cleveland Clinic Foundation: Robert Detrano, M.D., Ph.D.

### Relevant Papers:
- Detrano, R., Janosi, A., Steinbrunn, W., Pfisterer, M., Schmid, J., Sandhu, S., Guppy, K., Lee, S., & Froelicher, V. (1989). *International application of a new probability algorithm for the diagnosis of coronary artery disease.* American Journal of Cardiology, 64, 304--310.
- David W. Aha & Dennis Kibler. *Instance-based prediction of heart-disease presence with the Cleveland database.*
- Gennari, J.H., Langley, P., & Fisher, D. (1989). *Models of incremental concept formation.* Artificial Intelligence, 40, 11--61.

### Citation Request
The authors of the databases have requested that any publications resulting from the use of the data include the names of the principal investigators responsible for data collection at each institution:

- Hungarian Institute of Cardiology, Budapest: Andras Janosi, M.D.
- University Hospital, Zurich, Switzerland: William Steinbrunn, M.D.
- University Hospital, Basel, Switzerland: Matthias Pfisterer, M.D.
- V.A. Medical Center, Long Beach and Cleveland Clinic Foundation: Robert Detrano, M.D., Ph.D.
