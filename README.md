# Tailored Fertilizer Advisor Tool
tailored fertilizer advisor tool


# Please  install all Python dependences of these libraries
import numpy as np
import pandas as pd
from sklearn.preprocessing import LabelEncoder
import matplotlib.pyplot as plt
import descartes
import geopandas as gpd
from shapely.geometry import Point, Polygon
from latlon_utils import get_country, get_climate
import tensorflow as tf
from tensorflow import keras
from tensorflow.keras import layers
from keras.callbacks import ModelCheckpoint, EarlyStopping
from keras.layers import Dense, Input, Dropout, MaxPooling1D
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt 
from sklearn.metrics import mean_squared_error
from keras.models import Sequential
from keras.optimizers import Nadam
import geopandas as gpd
import plotly.express as px
from folium import plugins
import folium


## And install all R langauge dependeces of:
library(ggplot2)
library(randomForest)
library(caTools)
library(randomForest)
library(e1071) #SVR
library(caret)
library(rpart)
library(corrplot)
