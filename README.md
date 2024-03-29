# Sales Forecast Web Application
Author: Xavier M. Puspus


### Description
I used a sample dataset on advertising cost and sales and built a simple web application with a machine learning backend to see live changes to sales foreacst based on changes in advertising cost.

### Data

You can get the [data](https://www.kaggle.com/fayomi/advertising) here.
 
### Model

I only used a low-order machine learning technique for demo purposes. The web app's backend can work for more complex models.

### Deployment Through Web Application

I used the most recently released API of [Streamlit](https://streamlit.io) to deploy the ml model and locally serve the web app.

### Running the App

In order to run the app, you must have the basic data science packages available on your machine, (`pandas`, `numpy`, `seaborn`, `matplotlib`, `sklearn`, 'joblib' and install streamlit using:

```console
foo@bar:~$ pip install streamlit
```
Afterwards, `cd` into the directory of `app.py` and run this on the terminal:

```console
foo@bar:~$ streamlit run app.py
```

### Display

The web app should look something like this:

![Sample image of the sales forecasting model web application.](sales_forecast_webapp_image.png) 

