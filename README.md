Executive Summary

Unplanned machinery downtime in industrial environments can cause severe operational disruptions and financial losses. Predictive maintenance (PdM) provides a proactive solution by forecasting equipment failures, enabling timely interventions that reduce downtime and maintenance costs. This project applies PdM strategies to mechanical systems using the Case Western Reserve University (CWRU) Bearing Dataset, a benchmark in fault diagnosis research. Notably, our models achieved an accuracy rate of 95.96% and an RMSE of 69.52, demonstrating robust predictive capabilities. These results highlight the potential for PdM to enhance operational efficiency and reliability across industries.

Project Overview:

The CWRU Bearing Dataset comprises vibration data collected from a motor test bench equipped with accelerometers positioned at the drive end (DE), fan end (FE), and base (BA) of the motor. Artificial defects were introduced into the bearings at specific locations—ball, inner race, and outer race—with varying defect sizes (0.007 inches, 0.014 inches, and 0.021 inches). The accelerometers sampled vibration signals at frequencies up to 48 kHz, capturing high-resolution time series data under different operational conditions.
Leveraging this dataset, the project aims to develop a machine learning model capable of detecting and classifying bearing faults. The process involves several key steps:
1.	Data Preprocessing: Segmenting the continuous vibration signals into manageable time frames and extracting relevant statistical features—such as maximum, minimum, mean, standard deviation, root mean square (RMS), skewness, kurtosis, crest factor, and form factor—from each segment.
2.	Feature Engineering: Applying signal processing techniques, including Fast Fourier Transform (FFT), to convert time-domain signals into the frequency domain, facilitating the identification of characteristic fault frequencies associated with specific defect types.
3.	Model Development: Training machine learning classifiers, such as Support Vector Machines (SVM) or Random Forests, to distinguish between normal and faulty bearing conditions based on the extracted features.
4.	Model Evaluation: Assessing the performance of the classifiers using metrics like accuracy, precision, recall, and F1-score to ensure reliable fault detection and classification.
5.	Predictive Analysis: Implementing time series forecasting models, potentially utilising Long Short-Term Memory (LSTM) networks, to predict the remaining useful life (RUL) of bearings, thereby enabling timely maintenance interventions.

Key Questions to Address:

1.	Feature Selection: Which statistical and frequency-domain features are most indicative of specific bearing faults, and how does their selection impact model accuracy?
2.	Model Performance: How do different machine learning algorithms compare in terms of fault detection and classification accuracy for this dataset?
3.	Predictive Capability: What is the effectiveness of time series forecasting models in estimating the remaining useful life of bearings, and how can their predictions be validated?
4.	Mechanical Correlation: How do the identified vibration signal patterns correspond to known mechanical failure modes in bearings, and what insights can be drawn for maintenance planning?
5.	Practical Implementation: What are the challenges and considerations in deploying the developed predictive maintenance model in a real-world industrial environment?
By addressing these questions, the project not only demonstrates technical proficiency in data analysis and machine learning but also showcases the ability to apply engineering knowledge to practical, industry-relevant problems.
