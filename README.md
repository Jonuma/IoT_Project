# IoT Data Analysis Assignment
IoT for a Parking System

**Introduction**

Traditionally, electricity would be produced at electric utility companies and distributed via the electric grid to individual households. Today, more an more houses are equipped with solar panels allowing households to generate electricity locally. The electricity generation capacity of solar panels, however, strongly depends on the time of day and weather conditions. For example, during the night no electricity will be produced and during a cloudy day only little. Therefore, houses with solar panels are still connected to the electric grid to bridge the times when the solar panels cannot provide enough electricity to satisfy the demand (e.g. doing laundry in the evening). Moreover, during a sunny day the electricity production of the solar panels may exceed the demand, allowing to provide the excess electricity to the grid.

Since it is difficult to store electric energy, in order to avoid waste, utility companies try to adapt their energy production capacity to the demand and are interested in predicting the demand for the electricity from the grid. This assignment aims to build a predictive model for estimating the net electricity consumption of households equipped with solar panels.

**Goal**

The goal of this assignment is to gain experience with cleaning and exploring data, basic machine learning (training a simple regression model), and interpreting the results.

The assignment is to predict the energy consumption of a house given a weather forecast. The training data  consists of sensor data gathered at a particular house in the Eindhoven area, accompanied by the weather measurements collected around the Eindhoven Airport.

**Deliverable**

The assignment is distributed as an archive containing the data and a partially filled jupyter notebook with explanations and gaps to be filled in (you can find a preview [here](https://canvas.tue.nl/files/508309)). The deliverable is the filled in notebook which will then be executed on a held out test set.

The assignment is to be carried out in groups of 2. The delivered python notebook should include the names and the student numbers of both students.

**Grading**

Provided that 4 or more groups will take this assignment, the group whose model will achieve the best evaluation score will get a 10 (irrespective of the remainder of the delivered notebook). For the other groups (or if fewer than 4 groups take this assignment), the grade will be determined based on the entire notebook, including the model performance as well as the documentation of the data exploration, modeling and interpretation. You need to fill in at least all the cells marked with TODO to pass. Extra insights will give you extra credit.

**Instructions**

1. Install [Jupyter Notebook](http://jupyter.org/install.html) server on your computer. It is recommended to use the Anaconda installation with Python 2.7.
2. Download the [practical_data_analysis.zip](https://canvas.tue.nl/files/508283) archive containing the data and the notebook for this assignment.
3. Start the Jupyter Notebook server by navigating in your Terminal/Command Prompt to the directory where you have downloaded the assignment and executing "jupyter notebook" (see [Running the Notebook](https://jupyter.readthedocs.io/en/latest/running.html#running)). This should start your browser.
4. Navigate to assignment.ipynb notebook in the browser.
5. Follow the instructions in the notebook.