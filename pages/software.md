---
layout: page
title: Data Analytics Toolkit
date: 2020-11-17
description: Michael Salceda's DS Toolkit
---
<a name="top"></a>
<div class="navbar">
    <div class="navbar-inner">
        <ul class="nav">
            <ul class="dropdown">
                <li>
                    <a href="#python">Python Packages</a>
                    <ul class="dropdown-content">
                        <li>
                            <a href="#data_manipulation">Data Manipulation</a>
                            <ul class="dropdown-subcontent-level-1">
                                <li><a href="#dask">Dask</a></li>
                                <li><a href="#koalas">Koalas</a></li>
                                <li><a href="#pandas">pandas</a></li>
                                <li><a href="#pyspark">PySpark</a></li>
                            </ul>
                        </li>
                        <li>
                            <a href="#deep_learning">Deep Learning</a>
                            <ul class="dropdown-subcontent-level-1">
                                <li><a href="#fastai">fastai</a></li>
                                <li><a href="#keras">Keras</a></li>
                                <li><a href="#pytorch">PyTorch</a></li>
                                <li><a href="#tensorflow">TensorFlow</a></li>
                            </ul>
                        </li>
                        <li>
                            <a href="#ml">Machine Learning</a>
                            <ul class="dropdown-subcontent-level-1">
                                <li><a href="#mllib">MLlib</a></li>
                                <li><a href="#pyod">PyOD</a></li>
                                <li><a href="#scikit">scikit-learn</a></li>
                            </ul>
                        </li>
                        <li>
                            <a href="#nlp">Natural Language Processing</a>
                            <ul class="dropdown-subcontent-level-1">
                                <li><a href="#gensim">Gensim</a></li>
                                <li><a href="#nltk">Natural Language Toolkit</a></li>
                                <li><a href="#spacy">spaCy</a></li>
                                <li><a href="#transformers">Transformers</a></li>
                            </ul>
                        </li>
                        <li>
                            <a href="#network_analysis">Network Analysis</a>
                            <ul class="dropdown-subcontent-level-1">
                                <li><a href="#networkx">NetworkX</a></li>
                            </ul>
                        </li>
                        <li>
                            <a href="#scientific_computing">Scientific Computing</a>
                            <ul class="dropdown-subcontent-level-1">
                                <li><a href="#numpy">NumPy</a></li>
                                <li><a href="#scipy">SciPy</a></li>
                            </ul>
                        </li>
                        <li>
                            <a href="#statistical_analysis">Statistical Analysis</a>
                            <ul class="dropdown-subcontent-level-1">
                                <li><a href="#lifelines">Lifelines</a></li>
                                <li><a href="#lifetimes">Lifetimes</a></li>
                                <li><a href="#statsmodels">statsmodels</a></li>
                            </ul>
                        </li>
                        <li>
                            <a href="#viz">Visualization</a>
                            <ul class="dropdown-subcontent-level-1">
                                <li><a href="#bokeh">Bokeh</a></li>
                                <li><a href="#holoviews">HoloViews</a></li>
                                <li><a href="#matplotlib">Matplotlib</a></li>
                                <li><a href="#plotly">Plotly</a></li>
                                <li><a href="#seaborn">seaborn</a></li>
                            </ul>
                        </li>
                        <li>
                            <a href="#web_scraping">Web Scraping</a>
                            <ul class="dropdown-subcontent-level-1">
                                <li><a href="#beautiful_soup">Beautiful Soup</a></li>
                                <li><a href="#scrapy">Scrapy</a></li>
                            </ul>
                        </li>
                    </ul>
                </li>
            </ul>
        </ul>
    </div>
</div>

### <a name="python"></a>Python Packages
---
---
#### <a name="data_manipulation"></a>Data Manipulation
---
---
##### <a name="dask"></a>[Dask](https://docs.dask.org/en/latest/)
Dask is a library for data processing, loading, and manipulation in a distributed manner. It's similar to Spark in that it does processing in a parallel manner, but is written purely in Python and is more lightweight.

---

##### <a name="koalas"></a>[Koalas](https://koalas.readthedocs.io/en/latest/)
Koalas is built off of Apache Spark. It abstracts typical Spark operations into a pandas-like API so the barrier of entry is lower. This makes it easier to do transformations and data manipulation with Spark without having to use the Spark API.

---

##### <a name="pandas"></a>[pandas](https://pandas.pydata.org/)
pandas is the de-facto standard for machine learning data processing and munging. It offers an API to load in data from various file types (CSV, Excel, TXT, JSON, etc.). 

---

##### <a name="pyspark"></a>[PySpark](https://spark.apache.org/docs/latest/api/python/index.html)
PySpark is the Python API for Apache Spark. The PySpark API provides a way to work with big data without having to learn Scala. This does mean there are some tradeoffs as PySpark can run slower in some cases since there is some additional overhead. 

---

<center><a href="#top">Back to Top</a></center>

---
---
#### <a name="deep_learning"></a>Deep Learning
---
---

##### <a name="fastai"></a>[fastai](https://docs.fast.ai/)
fastai is a deep learning Python library meant to make it easy to get into coding neural networks with minimal lines of code. They have a free course which contains a lot of useful information on how to effectively use fastai and they also have released a book on the package. 

---

##### <a name="keras"></a>[Keras](https://keras.io/)
Keras is a deep learning API written on top of TensorFlow. It abstracts a lot of the TensorFlow neural network building code into a simpler API.

---

##### <a name="pytorch"></a>[PyTorch](https://pytorch.org/)
PyTorch is a deep learning framework that is an alternative to TensorFlow. [fastai](#fastai) is written on top of PyTorch and other libraries use PyTorch in the backend.

---

##### <a name="tensorflow"></a>[TensorFlow](https://www.tensorflow.org/)
TensorFlow is the deep learning framework maintained by Google. It is widely used like [PyTorch](#pytorch) and other libraries use TensorFlow in the backend (like [Keras](#keras)).

---

<center><a href="#top">Back to Top</a></center>

---
---
#### <a name="ml"></a>Machine Learning
---
---

##### <a name="mllib"></a>[MLlib](https://spark.apache.org/docs/latest/ml-guide.html)
MLlib is the machine learning library implemented within Apache Spark. There is a Python API (through PySpark) that allows the training of machine learning models in a distributed manner.

---

##### <a name="pyod"></a>[PyOD](https://pyod.readthedocs.io/en/latest/)
PyOD is a machine learning library for outlier detection. It contains many outlier detection algorithms and uses a [scikit-learn](#scikit)-like API so it's easy to use.

---

##### <a name="scikit"></a>[scikit-learn](https://scikit-learn.org/stable/)
The standard Python machine learning library to use. It contains many, many machine learning algorithms as well as preprocessing utilities like word vectorization and feature scaling.

---

<center><a href="#top">Back to Top</a></center>

---
---
#### <a name="nlp"></a>Natural Language Processing
---
---

##### <a name="gensim"></a>[Gensim](https://radimrehurek.com/gensim/)
Gensim is a Python library for text preprocessing and NLP-related machine learning algorithms (e.g., Word2Vec, Doc2Vec). It contains utilities to preprocess text to make it usable for ML algorithms.

---

##### <a name="nltk"></a>[Natural Language Toolkit](https://www.nltk.org/)
The Natural Language Toolkit (NLTK) is a library that has many functions to preprocess text like tokenization, stemming, and lemmatization.

---

##### <a name="spacy"></a>[spaCy](https://spacy.io/)
spaCy is a high-powered NLP library that contains many of the text preprocessing utilities as [NLTK](#nltk), but more advanced.

---

##### <a name="transformers"></a>[Transformers](https://huggingface.co/transformers/)
Transformers is a deep learning library specifically for NLP tasks. It contains many state-of-the-art NLP models like BERT, RoBERTa, and XLNet.

---

<center><a href="#top">Back to Top</a></center>

---
---
#### <a name="network_analysis"></a>Network Analysis
---
---

##### <a name="networkx"></a>[NetworkX](https://networkx.org/documentation/stable/index.html)
NetworkX is a library for working with network and graph-like structures. 

---

<center><a href="#top">Back to Top</a></center>

---
---
#### <a name="scientific_computing"></a>Scientific Computing
---
---

##### <a name="numpy"></a>[NumPy](https://numpy.org/)
NumPy is a Python library made for doing fast and efficient numerical computations. Many libraries are built on top of NumPy like [pandas](#pandas) and [scikit-learn](#scikit) to make them computationally efficient.

---

##### <a name="scipy"></a>[SciPy](https://docs.scipy.org/doc/scipy/reference/)
SciPy is built on top of [NumPy](#numpy) to do more mathematical-focused things such as fourier transforms and linear algebra operations. SciPy is more built out in terms of complex mathematical support versus NumPy.

---

<center><a href="#top">Back to Top</a></center>

---
---
#### <a name="statistical_analysis"></a>Statistical Analysis
---
---

##### <a name="lifelines"></a>[Lifelines](https://lifelines.readthedocs.io/en/latest/)
Lifelines is a library built primarily for survival analysis. This package contains models for doing survival analysis (e.g., Cox proportional hazard, Kaplan-Meier) and has a [scikit-learn](#scikit)-like API to ease of use.

---

##### <a name="lifetimes"></a>[Lifetimes](https://lifetimes.readthedocs.io/en/latest/)
Lifetimes is a library specifically for prediction customer lifetime value (CLV). CLV calculation is someting widely explored in industry as companies try to figure out how much value a customer is worth in order to optimize spending on tihngs like marketing. Note that this library is now in maintenance mode as of September 15, 2020. 

---

##### <a name="statsmodels"></a>[statsmodels](https://www.statsmodels.org/stable/index.html)
statsmodels contains a bunch of classes and functions for statistical models and tests. It has models like ARIMA for time series predictions, ordinary least squares functionality, etc. 

---

<center><a href="#top">Back to Top</a></center>

---
---
#### <a name="viz"></a>Visualization
---
---

##### <a name="bokeh"></a>[Bokeh](https://docs.bokeh.org/en/latest/index.html)
Bokeh is a library for creating cool and pretty interaction visualizations. This can be used to create portable graphics that can be exported as JavaScript or other formats so it can be used across many places.

---

##### <a name="holoviews"></a>[HoloViews](https://holoviews.org/)
HoloViews is a library for easy building of interactive visualizations. It can use libraries like [Bokeh](#bokeh) in the backend to generate the interactive visuals with fewer lines of code.

---

##### <a name="matplotlib"></a>[Matplotlib](https://matplotlib.org/)
Matplotlib is the standard visualization library in Python. It contains a lot of customization options for creating graphs, charts, etc. and is based off the plotting utilities found in Matlab.

---

##### <a name="plotly"></a>[Plotly](https://plotly.com/python/)
Plotly is a library for interactive graphing. It also has an interface called "Dash" for creating dashboards and deploying them easily. 

---

##### <a name="seaborn"></a>[seaborn](https://seaborn.pydata.org/)
seaborn is a visualization library built on top of [Matplotlib](#matplotlib). It offers more options on color palettes and makes statistical analysis graphs easier to create. 

---

<center><a href="#top">Back to Top</a></center>

---
---
#### <a name="web_scraping"></a>Web Scraping
---
---

##### <a name="beautiful_soup"></a>[Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
Beautiful Soup is a library for doing web scraping. It makes it easy to pull information out of HTML and XML files without having to work with the native Python HTML parser or XML parser.

---

##### <a name="scrapy"></a>[Scrapy](https://docs.scrapy.org/en/latest/)
Scrapy is a library for doing web crawling and scraping those websites. It is good for automating processes such as if you want to crawl through multiple websites at once and get their data.

---

<center><a href="#top">Back to Top</a></center>

---
---
