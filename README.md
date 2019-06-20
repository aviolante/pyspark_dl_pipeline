# Distributed Deep Learning Pipelines with PySpark and Keras

#### _Introduction_
In this notebook I use PySpark, Keras, and Elephas python libraries to build an end-to-end deep learning pipeline that runs on Spark. Spark is an open-source distributed analytics engine that can process large amounts of data with tremendous speed. PySpark is simply the python API for Spark that allows you to use an easy programming language, like python, and leverage the power of Apache Spark.
</br></br>
#### _Objective_
My interest in putting together this example was to learn and prototype. More specifically, learn more about PySpark pipelines as well as how I could integrate deep learning into the PySpark pipeline. I ran this entire project using Jupyter on my local machine to build a prototype for an upcoming project where the data will be massive. Since I work for IBM, I'll take this entire analytics project (Jupyter Notebook) and move it to IBM. This allows me to do my data ingestion, pipelining, training and deployment on a unified platform and on a much larger Spark cluster. Obviously, if you had a real and sizable project or using image data you would NOT do this on your local machine.
</br></br>
Overall, I found it not too difficult to put together this prototype or working example so I hope others will find it useful. I'll break down this project into 9 steps. A lot of steps will be self explanatory, but for others I'll try and make it painless. If you want to see just the notebook with explanations and code you can go directly to GitHub. If I can do this, so can you!
