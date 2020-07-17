# covid19
Exploring COVID 19 data.


### Project Overview: 
Why is this important? What is the potential here?

### Project Goals:

1. Create innovative visualizations for COVID-19 data 
2. Implement statistics that can be used by the general public
3. Establish a pattern for building serverless web applications using HydroShare and CUAHSI JupyterHub

### List of Technologies/Software/Datasets:

- Python 3+
- Bokeh
- Pandas
- GitHub
- COVID-19 Data
- NetCDF

### Learning Opportunities

- All programming levels welcome. We'll be primarily using Python but other languages can be used too!
- Cloud computing with Jupyter Notebooks
- Learn methods for visualizing data in the cloud
- Munging environmental and health datasets together
- Data analysis techniques

### On-boarding Steps: 

The following steps should get you going :). Please edit/add as necessary.    

1. Go to HydroShare.org and login
2. Select "Apps" in the menu bar and then click on CUAHSI JupyterHub. This will require you to join the CUAHSI JupyterHub HydroShare group. Once approved, you'll have access to our compute environemnt.
3. Launch CUAHSI JupyterHub (or go to jupyterhub.cuahsi.org) and choose the WaterHackWeek 2020 environment profile. This environment will contain all the libraries that we need.
4. Open an new "Terminal" session and clone the github repository by running the command:
```
$ git clone https://github.com/waterhackweek/covid19.git
```
5. Create anaconda environment. In the terminal from the previous step run the following commands:
```
$ cd covid19/bokeh-app
$ conda env create -f environment.yml
```
5. Navigate into covid19/bokeh-app using the directory browser on the right side of the screen
6. Double click on covid-notebook.ipynb. This will open the Jupyter notebook that contains the code for running our app
7. Run each cell of the notebook by pressing ctrl+ENTER (cmd+ENTER on mac). If everything goes as planned, you should see a plot of COVID-19 confirmed cases and deaths by state.
