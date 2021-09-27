#This lesson is extracted from "https://towardsdatascience.com/web-scraping-crypto-prices-with-python-41072ea5b5bf"
#import libraries
import streamlit as st
import pandas as pd
import seaborn as sns
import numpy as pd
import matplotlib.pyplot as plt
import base64
import requests
import json
import time
from PIL import Image
from bs4 import BeautifulSoup

#Specific website to be scraped
cmc = requests.get("https://coinmarketcap.com")
soup = BeautifulSoup(cmc.content, "html.parser")
print(soup.prettify())
