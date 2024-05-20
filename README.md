# Capstone Project

## Airbnb Analysis

![](https://github.com/SwethaC01/CapstoneAirbnbAnalysis/blob/main/image.gif)

## 🎨Technologies Used

  * Json
  * Python
  * MySQL
  * Pandas
  * Streamlit
  * Plotly
  * WordCloud
  * Matplotlib

## Features

* **📂JSON Files**: Utilize JSON files for data input.
* **✂️Data Filtering:** Python scripting is utilized to filter and preprocess the raw transaction data, ensuring its suitability for visualization.
* **🗃️Database Management:** The project facilitates the creation of a database schema and the insertion of transaction data into MySQL tables.
* **🌐Geo Visualization:** Utilizing Plotly, the project enables geographic visualization of transaction data, allowing users to analyze regional transaction trends.
* **📊Plotly Visualizations:** Different types of Plotly visualizations such as scatter plots, line charts, and pie charts,violin plot,box plot,3D Scatter plot are available to showcase the data through charts and insights.
* **🔝Insight Generation:** Insights are derived from Airbnb data, and key findings are presented on the dashboard through Streamlit.

### 💻 Import Packages
```python
import streamlit as st
from streamlit_option_menu import option_menu
import mysql.connector
import pandas as pd
import plotly_express as px
import plotly.graph_objects as go
from wordcloud import WordCloud
import matplotlib.pyplot as plt
