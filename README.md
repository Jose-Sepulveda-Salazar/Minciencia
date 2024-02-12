# Minciencia
Para una correcta ejecución del programa se utilizan las siguientes funcionalidades
Python version 3.9
Librerías:
from selenium import webdriver
from selenium.webdriver.chrome.service import Service
from selenium.webdriver.common.by import By
from selenium.webdriver.support.ui import WebDriverWait
from selenium.webdriver.support import expected_conditions as EC
from webdriver_manager.chrome import ChromeDriverManager
import openpyxl
import time
import os
import pandas as pd

import psycopg2
import configparser