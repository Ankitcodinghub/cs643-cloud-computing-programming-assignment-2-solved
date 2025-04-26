# cs643-cloud-computing-programming-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [CS643, Cloud Computing Programming Assignment 2 Solved](https://www.ankitcodinghub.com/product/cs643-cloud-computing-programming-assignment-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;103503&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;5&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (5 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS643, Cloud Computing  Programming Assignment 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (5 votes)    </div>
    </div>
<strong>Goal:</strong> The purpose of this individual assignment is to learn how to develop parallel machine learning (ML) applications in Amazon AWS cloud platform. Specifically, you will learn: (1) how to use <a href="https://spark.apache.org/">Apache Spark</a> to train an ML model in parallel on multiple EC2 instances; (2) how to use <a href="https://spark.apache.org/mllib/">Spark’s MLlib</a> to develop and use an ML model in the cloud; (3) How to use <a href="https://www.docker.com/">Docker</a> to create a container for your ML model to simplify model deployment.

&nbsp;

<strong>Description:</strong>&nbsp; You have to build <u>a wine quality prediction ML model in Spark over AWS</u>. The model must be trained in parallel using 4 EC2 instances. Then, you need to save and load the model in a Spark application that will perform wine quality prediction; this application will run on one EC2 instance. The assignment must be implemented in Java on Ubuntu Linux. The details of the assignment are presented below:

<ul>
<li><u>Input for model training</u>: we share 2 datasets with you for your ML model. Both datasets are available in Canvas, under Programming Assignment 2.
<ul>
<li>csv: you will use this dataset to train the model in parallel on multiple EC2 instances.</li>
<li>csv: you will use this dataset to validate the model and optimize its performance (i.e., select the best values for the model parameters).</li>
</ul>
</li>
<li><u>Input for prediction testing</u>: TestDataset.csv. We will use this file, which has a similar structure with the two datasets above, to test the functionality and performance of your prediction application. Your prediction application should take such a file as input. This file is not shared with you, but you can use the validation dataset to make sure your application works.</li>
<li><u>Output</u>: The output of your application will be a measure of the prediction performance, specifically the F1 score, which is available in MLlib.</li>
<li><u>Model Implementation</u>: You have to develop a Spark application that uses MLlib to train for wine quality prediction using the training dataset. You will use the validation dataset check the performance of your trained model and to potentially tune your ML model parameters for best performance. You should start with a simple linear regression or logistic regression model from MLlib, but you can try multiple ML models to see which one leads to better performance. For classification models, you can use 10 classes (the wine scores are from 1 to 10). Note: there will be <u>extra-credit</u> for the top 5 applications/students in terms of prediction performance (see below under grading).</li>
<li><u>Docker container</u>: You have to build a Docker container for your prediction application. In this way, the prediction model can be quickly deployed across many different environments.</li>
<li>The model training is done in parallel on 4 EC2 instances.</li>
<li>The prediction with or without Docker is done on a single EC2 instance.</li>
</ul>
&nbsp;

<strong>Submission:</strong> You will submit in Canvas, under Programming Assignment 2, text/Word/pdf file that contains:

<ul>
<li>A link to your code i<a href="https://github.com/">n </a><a href="https://github.com/">GitHub</a><a href="https://github.com/">.</a> The code includes the code for parallel model training and the code for prediction application.</li>
<li>A link to your container in <a href="https://hub.docker.com/">Docker Hub</a><a href="https://hub.docker.com/">.</a></li>
</ul>
This file must also describe step-by-step how to set-up the cloud environment and run the model training and the application prediction. For the application prediction, you should provide instructions on how to run it with and without Docker.

&nbsp;
