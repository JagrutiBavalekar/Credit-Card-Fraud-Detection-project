# Credit-Card-Fraud-Detection-project

# Project Overview
The Credit Card Fraud Detection project focuses on building an intelligent system that can detect fraudulent credit card transactions in real-time. With the rise in digital payments, financial institutions face a growing need to identify suspicious transactions to reduce financial loss and protect customer trust. The project utilizes historical transaction data to train a classification model that can distinguish between legitimate and fraudulent activities based on behavioral patterns. The system was designed to be lightweight, efficient, and deployable in real-time environments. It also includes a user-friendly web interface where transaction details can be entered to get instant predictions.

# Technologies Used
Programming Languages: Python
Libraries/Frameworks: Pandas, NumPy, Scikit-learn
Model Deployment: streamlit
Visualization: Matplotlib, Seaborn
Tools: Jupyter Notebook, GitHub

# Your Role and Contribution
I was solely responsible for end-to-end development of the project. This included data preprocessing, feature engineering, model selection and evaluation, and creating the streamlit for deployment. I also designed the frontend interface of the project.

# Key Challenges and How You Solved Them
One major challenge was the class imbalance, as fraudulent transactions made up less than 1% of the dataset. This data is highly imbalance 
So first I do data preprocessing for that I balance data which was highly imbalance. I use synthetic minority oversample techniques to balance data. After that I scale time and amount using standard scalar and then I performed tarin test split used 70:30 split .Then I trained and compared 3 algorithm Logistics regression :It was descent with high precision but lower recall
Decision tree :It captures non linear relationship there was risk of over fitting but handel imbalance data more better 
Naive bayse:This algorithm was fast and scalable with credit card fraud data as the data was imbalance I didn't focus much on accuracy Instead I use precision,recall and f1 scored Decision tree give best recall 93%


