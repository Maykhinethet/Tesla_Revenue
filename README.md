# Tesla_Revenue
Analyzing Historical Stock/Revenue Data and Building a Dashboard
!pip install yfinance==0.1.67
!mamba install bs4==4.10.0 -y
!pip install nbformat==5.2.0
import yfinance as yf
import pandas as pd
import yfinance as yf

msft = yf.Ticker("MSFT")
msft_data = msft.history(period="max")

msft_data.head()
