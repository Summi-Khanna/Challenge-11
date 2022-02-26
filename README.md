# MercadoLibre Growth and TimeSeries Analysis

This is analysis looks a trends and forecasts searches, stock price, and revenue to help company's growth we predict company's searh traffic and see if it can be translated into the ability to sccessfully translate the stock.
Our Analysis consist of following:

1. Finding unusual patterns in hourly Google search traffic
2. Mining the search traffic data for seasonality
3. Relating the search traffic to stock price patterns
4. Creating a time series model with Prophet
5. Forecasting revenue by using time series models


---

## Technologies

It supports Python 3.7 and above and has been constructed in the jupyter lab notebook named ```forecasting_net_prophet.ipynb```
Additionally, the following packages/libraries are used to run the analysis:

- [pandas](https://pypi.org/project/pandas/) - for analyzing data
- [jupyter](https://pypi.org/project/jupyter/) - for an IDE
- [hvplot](https://pypi.org/project/hvplot/) - for creating interactive Visualizations of data
- [holoviews](https://pypi.org/project/holoviews/) - for creating interactive plots
- [colab]() - For running a jupyter server remotely
- [numpy]() - For numerical operations
- [pystan]() - For statistical modeling and high-performance statistical computation
- [fbprophet]() -For forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects.

---

## Installation Guide

Before running the application first install the following dependencies:

```python
  pip install pystan
  pip install fbprophet
  pip install pandas 
  pip install hvplot
  pip install holoviews

```
---

## Usage

Upload the ```forecasting_net_prophet.ipynb``` file in [colab](https://colab.research.google.com/) and start running the code. Upload the mentioned data files in the comment section of that code line located in Resources folder as and when it is executed.
You can clone the repository using "git clone <link>"  from the [repository directory](https://github.com/Summi-Khanna/Challenge-11).

---

## Analysis Overview:

Snapshots of the relevant graphs and information are given below for each step followed:

1. ### Finding unusual patterns in hourly Google search traffic 

![Step1](https://github.com/Summi-Khanna/Challenge-11/blob/main/Images/step1.png)


2. ### Mining the search traffic data for seasonality

![Step2](https://github.com/Summi-Khanna/Challenge-11/blob/main/Images/step2-1.png) 

![Step2-2](https://github.com/Summi-Khanna/Challenge-11/blob/main/Images/step2-2.png)

![Step2-3](https://github.com/Summi-Khanna/Challenge-11/blob/main/Images/Step2-3.png)


3. ### Relating the search traffic to stock price patterns

![Step3](https://github.com/Summi-Khanna/Challenge-11/blob/main/Images/Step3-1.png)

![Step3-2](https://github.com/Summi-Khanna/Challenge-11/blob/main/Images/Step3-2.png)

![Step3-3](https://github.com/Summi-Khanna/Challenge-11/blob/main/Images/Step3-3.png)

![Step3-4](https://github.com/Summi-Khanna/Challenge-11/blob/main/Images/step3-4.png)


4. ### Creating a time series model with Prophet

![Step4](https://github.com/Summi-Khanna/Challenge-11/blob/main/Images/Step4-1.png)

![Step4-2](https://github.com/Summi-Khanna/Challenge-11/blob/main/Images/step4-2.png)


5. ### Forecasting revenue by using time series models

![Step5](https://github.com/Summi-Khanna/Challenge-11/blob/main/Images/Step5-1.png)

![Step5](https://github.com/Summi-Khanna/Challenge-11/blob/main/Images/step5-2.png)

![Step5](https://github.com/Summi-Khanna/Challenge-11/blob/main/Images/Step5-3.png)


---

## Contributors
 
Summi Khanna  
Email : sam.summo2812@gmail.com <br>
LinkedIn : https://www.linkedin.com/in/summi-khanna-004a60187/

---

## License

MIT License

Copyright (c) 2021 Summi Khanna

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

---
