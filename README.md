Module 11 - Challenge 11 : MercadoLibre Growth Analysis
==========================================

## Purpose

 The purpose of this notebook is to analyze MercadoLibre's financial and user data in clever ways to make the company grow. By utilizing fbprophet to create analysis and visualizations we will be able to better understand the company's financial outlook. 

---

## Technologies

Jupyter notebooks and the Pandas data analysis library were used in the creation of this project. Additionaly the project was created on Google Colab, a cloud based notebook generation IDE. 

---

## Installation Guide

First, install the jupyter and pandas libraries. In your terminal or command shell install the following packages: 

```python
pip install jupyter
```

```python
pip install pandas
```

```python
pip install pystan
```

```python
pip install fbprophet
```

```python
pip install hvplot
```

```python
pip install holoviews
```

Additionally hvplot was used to create a interactive visualization for the project. In one case the ```groupby``` function was used to create a widget so one can select certain years of larger data sets. 

This notebook was created using python 3.7.10. There were a number of issues with the packages within this specific conda environment, and I definitely recommend taking time to troubleshoot any package discrepencies that may arise. 

---
## Usage

First, head on over to [Colaboratory](https://colab.research.google.com/). You can then upload this notebook into the online IDE. Under the Runtime tab you can select "Run All" - this will then prompt you to open the various CSV files found in the "Resources" folder found within this repo. 

---
## Conclusion

Contained within the notebook are the results of the analysis. If I were to improve on this project, I would try to further implement some type of Fire CLI that would open VSCode directly in to the Colab runtime. 

---

## Contributors

Created by: Christopher Henderson

cdhendy@gmail.com

[LinkedIn](https://www.linkedin.com/in/chris-henderson123/)

---

## License

(c) Copyright 2021 Chris Henderson

Licensed under the MIT license:

    http://www.opensource.org/licenses/mit-license.php

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.