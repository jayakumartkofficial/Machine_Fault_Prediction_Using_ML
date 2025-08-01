<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Machine Fault Prediction using IBM watsonx.ai</title>
</head>
<body>
  <h1>🔧 Machine Fault Prediction using IBM watsonx.ai</h1>
  <p>This project demonstrates how to use <strong>IBM watsonx.ai Studio</strong> with AutoAI to build, train, and deploy a predictive maintenance model that detects machine failures like <strong>Power Failure</strong>, <strong>Overstrain Failure</strong>, and <strong>Tool Wear Failure</strong>.</p>

  <h2>🚀 Steps to Build and Deploy the Model</h2>

  <h3>1️⃣ IBM Cloud Setup</h3>
  <ul>
    <li>Login to <a href="https://cloud.ibm.com/">IBM Cloud</a></li>
    <li>Search for <strong>watsonx.ai Studio</strong></li>
    <li>Select the appropriate <strong>server location</strong></li>
    <li>Create a <strong>new project</strong> and enter a name</li>
    <li>Create a <strong>storage service</strong> (free tier) and click <em>Refresh</em></li>
  </ul>

  <h3>2️⃣ Associate Runtime Environment</h3>
  <ul>
    <li>Go to <em>Manage &gt; Services and Integrations</em></li>
    <li>Click <strong>Associate Service</strong></li>
    <li>Select the <strong>Watsonx.ai Runtime</strong> and confirm</li>
  </ul>

  <h3>3️⃣ Start AutoAI Model Building</h3>
  <ul>
    <li>Click <em>Build machine learning models automatically</em> in the overview</li>
    <li>Name the experiment and upload your dataset</li>
    <li>If prompted, create an <strong>API key</strong> under your profile</li>
    <li>Select the <strong>target column</strong> for prediction</li>
    <li>Choose the Watsonx.ai runtime and start the experiment</li>
  </ul>

  <p><strong>AutoAI generates multiple pipelines with optimized algorithms and enhancements.</strong></p>

  <h4>📷 AutoAI Relationship & Pipeline View</h4>
  <img src="[./1.png](https://github.com/jayakumartkofficial/Machine_Fault_Prediction_Using_ML/blob/main/Screenshot/1.png)" alt="AutoAI Relationship Map" width="700"/>

  <h4>📷 AutoAI Progress Workflow</h4>
  <img src="./2.png" alt="AutoAI Progress Map" width="700"/>

  <h3>4️⃣ Select & Save the Best Model</h3>
  <ul>
    <li>Review the <strong>Pipeline Leaderboard</strong></li>
    <li>Click <strong>Save As</strong> on the top pipeline and give it a name</li>
  </ul>

  <h3>5️⃣ Promote and Deploy the Model</h3>
  <ul>
    <li>Click <em>Go to Project</em> → then click <strong>Promote</strong></li>
    <li>Select or create a <strong>Deployment Space</strong></li>
    <li>Click <strong>Create Deployment</strong> and proceed</li>
    <li>If prompted, configure the Watsonx.ai runtime under <em>Manage</em> tab</li>
  </ul>

  <h3>6️⃣ Test the Deployed Model</h3>
  <ul>
    <li>Open the <strong>Test</strong> tab in the deployment</li>
    <li>Upload sample input data via form or CSV</li>
  </ul>

  <h4>📷 Model Test Interface</h4>
  <img src="./3.png" alt="Model Test Data Input" width="700"/>

  <h3>7️⃣ View Prediction Results</h3>
  <ul>
    <li>Click <strong>Predict</strong> and view the results with predicted labels and confidence</li>
  </ul>

  <h4>📷 Prediction Output</h4>
  <img src="./4.png" alt="Model Prediction Output" width="700"/>

  <h2>📊 Outcome</h2>
  <ul>
    <li>Model trained using <strong>Snap Random Forest Classifier</strong></li>
    <li>Achieved <strong>99.5% accuracy</strong></li>
    <li>Predicts machine failure types with high confidence</li>
    <li>Deployable and usable via online interface or API</li>
  </ul>

  <h2>📁 Dataset</h2>
  <p><strong>Features include:</strong> Air Temperature, Process Temperature, Rotational Speed, Torque, Tool Wear, Failure Type</p>
</body>
</html>
