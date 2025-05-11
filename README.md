Proposed this work for the Google Girl Hackathon 2024 . 

This is a disease prediction ML project is which we have done the integration of Artificial Intelligence .
Incorporated various ML algorithms , trained and tested their models. 

# TechMed Innovations
Welcome to our cutting-edge Personalized Web Application, TechMed Innovations : AI for a healthier tomorrow.
Introducing a robust platform meticulously crafted to empower users in comprehending and navigating their health journey. Harnessing the prowess of machine learning, our innovative system meticulously dissects user-provided symptoms to forecast potential diseases with unparalleled precision. Here lies the essence of our system's distinction. 
User-Friendly Interface: Our intuitive interface allows users to input their symptoms effortlessly, creating a seamless user experience.

Advanced Machine Learning Models: We've integrated state-of-the-art machine learning models that accurately predict diseases based on input symptoms, ensuring reliable and precise results.
Our induced system gives the predicted disease based on the symptoms, medication information , diet and workout to follow and a list of recommended doctors on the basis of user ratings and desired appointment schedules. 

Personalized Suggestions: Access tailored recommendations encompassing the top 5 medications, prescription specifics, and customized workout regimens aligned with the predicted disease.

Flask Integration: Empowered by a Flask web application, our system ensures seamless accessibility for users, enabling them to access healthcare recommendations effortlessly from any location.

Privacy and Protection: We place paramount importance on safeguarding user privacy and data security. Rest assured, your health information is handled with utmost confidentiality, adhering strictly to the highest industry standards.

Continuous Enhancement: Committed to perpetual refinement, our system is engineered for ongoing advancement. With each data iteration, our machine learning models evolve, delivering increasingly precise and pertinent recommendations.

Embrace control over your well-being with our Personalized Healthcare Web Application . Your health is our foremost concern, and we are devoted to furnishing you with the resources and insights necessary for a life of vitality and wellness.
////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
To set up an environment to run the provided code in PyCharm, you'll need to follow these steps:

Install PyCharm:
If you haven't already installed PyCharm, you can download and install it from the JetBrains website: PyCharm Download.
Create a New Project:
Open PyCharm and create a new project. Choose an appropriate location for your project directory.
Set Up Virtual Environment:
It's a good practice to use virtual environments to manage dependencies for different projects. You can set up a virtual environment within PyCharm:
Go to File -> Settings.
In the Settings dialog, navigate to Project: <your_project_name> -> Python Interpreter.
Click on the gear icon on the right and select Add.
Choose Virtualenv Environment and specify the location for the virtual environment.
Select the Python interpreter version (make sure it's compatible with your code).
Click OK to create the virtual environment.
Install Dependencies:
You'll need to install the necessary Python packages within your virtual environment. In your case, you'll need Flask and scikit-learn , panda and numpy . 
Set Up Flask App:
Create a new Python file for your Flask application, for example, app.py.
Copy the Flask code provided in your HTML file into this app.py file.
Make sure your directory structure includes the necessary static and templates folders for Flask to locate your HTML and static files.
Ensure you have the necessary CSV files (e.g., symptoms_df.csv, precautions_df.csv, etc.) in your project directory.
Run Flask App:
Run your Flask application by executing the app.py file.
PyCharm provides a built-in Flask server that you can use for development purposes.
Once the server is running, you should be able to access your Flask application through a web browser.
/////////////////////////////////////////////////////////

Setting up the provided Jupyter Notebook code involves a few steps. Here's how you can do it:

Install Anaconda:
If you haven't already installed Anaconda, it's a convenient way to manage Python environments and packages, including Jupyter Notebook. You can download and install Anaconda from the official website: Anaconda Download.
Launch Jupyter Notebook:
Once Anaconda is installed, you can launch Jupyter Notebook by:
Opening Anaconda Navigator from your applications menu.
Clicking on the Jupyter Notebook icon.
Create a New Notebook:
In the Jupyter Notebook interface, click on the "New" button and select "Python 3" to create a new Python notebook.
This will open a new notebook in your browser.
Copy and Paste Code:
Copy the provided code cells from the notebook file you have (or from the provided code snippet) and paste them into the cells of the new Jupyter Notebook.
Ensure that you paste the code into separate cells, as in the original notebook, to execute them step by step.
Run Code Cells:
After pasting the code into the notebook cells, you can run each cell individually by selecting it and either clicking the "Run" button in the toolbar or pressing Shift+Enter.
Make sure to run the code cells in the correct order to execute the code sequentially.
Check Output:
As you run each code cell, you'll see the output directly below it.
Ensure that each code cell executes without errors and produces the expected output.
Install Dependencies:
If any libraries are used in the notebook that are not already installed in your Anaconda environment, you can install them using the Anaconda Navigator or by running conda install or pip install commands in a notebook cell.
Save and Export:
Once you've verified that the code runs correctly, you can save your Jupyter Notebook file (.ipynb).
You can also export the notebook to other formats if needed, such as HTML, PDF, or Python script.
