Heart Disease Predcition

--------------------------------------------------------------------------------------------------------------
Dataset: cardio_train.csv source(https://www.kaggle.com/sulianova/cardiovascular-disease-dataset)

--------------------------------------------------------------------------------------------------------------
Data Description:

Data description
There are 3 types of input features:

Objective: factual information;

Examination: results of medical examination;

Subjective: information given by the patient.

Features:

Age | Objective Feature | age | int (days)

Height | Objective Feature | height | int (cm) |

Weight | Objective Feature | weight | float (kg) |

Gender | Objective Feature | gender | categorical code |

Systolic blood pressure | Examination Feature | ap_hi | int |

Diastolic blood pressure | Examination Feature | ap_lo | int |

Cholesterol | Examination Feature | cholesterol | 1: normal, 2: above normal, 3: well above normal |

Glucose | Examination Feature | gluc | 1: normal, 2: above normal, 3: well above normal |

Smoking | Subjective Feature | smoke | binary |

Alcohol intake | Subjective Feature | alco | binary |

Physical activity | Subjective Feature | active | binary |

Presence or absence of cardiovascular disease | Target Variable | cardio | binary |

All of the dataset values were collected at the moment of medical examination.

--------------------------------------------------------------------------------------------------------------

Code: heart_disease_prediction.ipynb

Notebook illustrates data exploration and visualization, feature engineering, model selection, hyper parameter tuning of random forest model using grid search then result analysis. 

Discussion can be found in heart_disease.pdf

--------------------------------------------------------------------------------------------------------------

Result Images: graphs_results
