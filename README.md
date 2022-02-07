![header](https://capsule-render.vercel.app/api?type=waving&color=gradient&width=1000&height=200&section=header&text=Unsupervised%20Machine%20Learning%20&fontSize=30&fontColor=black)

<!-- header is made with: https://github.com/kyechan99/capsule-render -->

[John Sung](https://linkedin.com/in/john-sung-3675569) [<img src="https://cdn2.auth0.com/docs/media/connections/linkedin.png" alt="LinkedIn -  John Sung" width=15/>](https://linkedin.com/in/john-sung-3675569/)
                                 
---

### Table of Contents

* [Overview](#overview)
* [Technoligies](#technologies)
* [Usage](#usage)
* [Example Values](#example-values)
* [License](#license)  



## Overview
In this week’s challenge, I have created a machine learning model that groups cryptocurrencies to assemble investment portfolios that are based on the profitability of those cryptocurrencies. You'll be able evaluate and the contrast the best value of KMeans, explained variance ratios, elbow curves and clusters.

---

## Technologies

This project leverages python 3.7, scikit-lesarn and hvPlot.

Go to your terminal or git bash and run conda activate dev to activate your conda dev environment. 
You will then install the following librarie(s) and module(s) to run in Python codes created.
    pip install -U scikit-learn
    conda install -c pyviz hvplot
    
To ensure installation was complete, run the following...
    conda list scikit-learn
    conda list hvplot

---

## Usage

Go to the Anaconda Prompt to launch JupyterLab by typing Jupyter Lab. To use this application simply clone the repository and run the crypto_investments.ipynb in you Jupyter Lab Notebook.

---


## Visualization

![conda_list](Images/conda_list.PNG)
![df_market_data_hvplot](Images/df_market_data_hvplot.PNG)
![elbow_curve](Images/elbow_curve.PNG)
![scatter_plot](Images/scatter_plot.PNG)
![composite_elbow](Images/composite_elbow.PNG)
![composite_scatter](Images/composite_scatter.PNG)


---

## License

MIT License

Copyright (c) 2021 John Sung

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
