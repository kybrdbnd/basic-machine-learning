<h1>Welcome to Basic of Machine Learning !!!! </h1>
<b>Definition:</b>
<p>
  Machine learning is an application of artificial intelligence (AI) that provides systems the ability to automatically learn and improve from experience without being explicitly programmed. Machine learning focuses on the development of computer programs that can access data and use it learn for themselves.
</p>
<p>
The process of learning begins with observations or data, such as examples, direct experience, or instruction, in order to look for patterns in data and make better decisions in the future based on the examples that we provide. The primary aim is to allow the computers learn automatically without human intervention or assistance and adjust actions accordingly.
</p>
<b>How to use this repo:</b>
<p>
This repo is just for the introduction to Machine Learning. This repo consists of Ipython notebooks which will help you to analyse that what is going on each step. Graphs are also there so that you can check the performance of the the algorithm that that has been discussed in the notebook
</p>
<b>Requirements:</b>
<p>
  <ul>
    <li>Python 3.X</li>
    <li>Anaconda</li>
  </ul>
  Note: Make sure the kernel of Ipython is installed for Python3
</p>
<h1>Getting Started</h1>
<p>
  To understand the basis of Machine Learning, we must understand that there are 4 simple steps involved in the process:
  <ol>
    <li>Train Data Set</li>
    <li>Choosing the Algorithm</li>
    <li>Applying ML algorithm to train the system</li>
    <li>Test Data Set</li>
  </ol>
</p>
<h1>Aim: To predict the pizza price</h1>
<h2>Pre-requiste Knowledge</h2>
<p>
  Price price follows a linear relationship with several parameters like diameter, quantity of cheese, veg or non veg, pizza toppings. Therefore Simple Linear Regression can be applied to estimate the price of the pizza.
  
  <b>Train Data Set: </b>sample_data.csv containing columns like cost, diameter, toppings etc 
</p>
<h2>How It works </h2>
<p>
  <ol>
    <li> CSV file is read using pandas</li>
    <li> Train Data is chosen </li>
    <li> A modeler is generated using Linear Regression</li>
    <li> Cost are predicted with the random pizza size</li>
  </ol>
  <p>
  Linear Regression take two input parameters: X and y. X being the independent quantity and y being the dependent quantity because linear regression take the form of straight line whose equation is given by
  ```
  y = mx+c
  ```, y=dependent, x=independent, m=slope of the line and c being the y-intercept.
  </p>
  <p>In our <b>pizza price prediction system</b> X=['size','pizza toppings'..etc] and y=['cost']</p>
</p>
