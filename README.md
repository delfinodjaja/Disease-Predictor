<h1>Interactive Disease Diagnosis via Naive Bayes and Entropy-Based Querying</h1>
<p>
  This project aims to develop a disease predictor based on user-reported symptoms. The system utilizes Naive Bayes classification, 
  and information gain for selecting which symptom to ask for next. By asking the most informative question, we can reduce the number 
  of symptoms asked instead of asking for all symptoms in the dataset.
</p>

<h2>Key Features:</h2>
<ul>
  <li><strong>Naive Bayes Classifier:</strong> Predicts diseases based on symptoms, calculating the posterior probability of each disease given the observed symptoms.</li>
  <li><strong>Information Gain:</strong> Selects the most informative symptom to ask the user first, ensuring that each question maximizes the reduction in uncertainty about the disease.</li>
  <li><strong>Interactive Questioning System:</strong> The system asks a sequence of questions about symptoms, updating disease probabilities as the user responds.</li>
  <li><strong>Disease Prediction:</strong> After gathering sufficient information, the system predicts the most likely disease with high confidence.</li>
</ul>

<h2>Project Components</h2>

<h3>1. Dataset</h3>
<p>
  The dataset used in this project is the <a href="https://www.kaggle.com/datasets/choongqianzheng/disease-and-symptoms-dataset/data" target="_blank">Disease And Symptoms Dataset</a> from Kaggle.
</p>
<h3>2. Naive Bayes</h3>
<p>
  Naive Bayes is a probabilistic classifier that calculates the probability of a disease based on the given symptoms. 
  The model assumes that the symptoms are conditionally independent given the disease, simplifying the computation of joint probabilities.
</p>

<p>The Naive Bayes classifier uses:</p>
<ul>
  <li><strong>Prior Probabilities:</strong> The likelihood of each disease occurring.</li>
  <li><strong>Likelihood Probabilities:</strong> The probability of observing a symptom given a specific disease.</li>
</ul>
<h3>3. Information Gain for Symptom Selection</h3>
<p>
  Information Gain is used to select the most informative symptom to ask the user first. The goal is to maximize the reduction 
  in entropy (uncertainty) about the disease with each question.
</p>
