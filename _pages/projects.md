---
layout: page
title: Projects
permalink: /projects/
---
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
<script> 
$(document).ready(function(){
  $("#project").click(function(){
    $(this).next("#description").slideToggle("slow");
  });
});
</script>

<style> 
#description, #project {
  padding: 10px;
  text-align: left;
  border: 1px #e1e4e8 solid;
  box-shadow: 0 3px 6px rgba(149,157,165,0.15) !important;
  border-radius: 5px;
  font-size: 15px;
}

#description {
  padding: 10px;
  display: none;
}
</style>

<div style="text-align: center;">
    <img src="/blog/images/Profile_picture.jpg" alt=""
        style=" width: 300px; border-radius: 400px; margin-bottom:10px;"/>
</div>


<div id="project">Machine Learning on IoT Data: Predicting Battery Health Status and User Type</div>
<div id="description">
• Built a predictive model that can warn of initial glitches or anomalies in battery health allowing early detection and prevention  <br/><br/>   
• Applied Supervised and Unsupervised methods such as K-Means Clustering and K-Nearest Neighbors to label health status of batteries  <br/><br/>   
• Developed Tableau reports and dashboards from MongoDB to showcase Exploratory Data Analysis (EDA) and anomaly detection  <br/><br/> 
• Performed predictive analytics to identify global and contextual anomalies present in faulty batteries prompting early detection/prevention
</div>

<div id="project">Intelligent Transportation - Machine Learning in Taxi Industry</div>
<div id="description">
• Performed analysis for over 2.4 million taxi records to predict the demand for 25 zones over temporal resolution of 24 hours  <br/><br/> 
• Explored a range of supervised and unsupervised learning models like Regression, Random Forest, XGboost, and Multi-Layer
Perceptron (MLP) using Keras and TensorFlow libraries to select the winning model  <br/><br/>
</div>

<!-- 
* Machine Learning on IoT Data: Predicting Battery Health Status and User Type
* Intelligent Transportation - Machine Learning in Taxi Industry
* Real-Time Billing System for 4G/5G Network
* Machine Learning Techniques for Stock Market Prediction 
-->