### How to encode Time-Series into Images 
[Article](https://towardsdatascience.com/how-to-encode-time-series-into-images-for-financial-forecasting-using-convolutional-neural-networks-5683eb5c53d9)
* How do we visualize timeseries in a meaningful way such that we can train a Deep Learning model with it?
* Using Gramian Angular Fields (GAF) are images representing a timeseries in a non-Cartesian coordinates system (i.e. each point on the plane is referenced by a X and Y axis).

#### Encoding Time Series as Images for Visual Inspection and Classification Using Tiled Convolutional Neural Networks[pdf](https://www.aaai.org/ocs/index.php/WS/AAAIW15/paper/viewFile/10179/10251)

#### Deep Learning and Time Series-to-Image Encoding for Financial Forecasting [Download](https://www.researchgate.net/publication/341250503_Deep_Learning_and_Time_Series-to-Image_Encoding_for_Financial_Forecasting/link/60753f5e4585151ce17ee67c/download)

This paper exploits an ensemble of CNNs, trained over Gramian angular fields
(GAF) images, generated from time series related to the Standard & Poor’s 500 index future; the aim is the prediction of the future trend of the U.S. market. A multi-resolution imaging approach is used to feed each CNN, enabling the analysis of different time intervals for a single observation. A simple trading system based on the ensemble forecaster is used to evaluate the quality of the proposed approach. Our method outperforms the buyand-hold (B&H) strategy in a time frame where the latter
provides excellent returns. Both quantitative and qualitative results are provided.
Given the two factors
described above, our approach proposes a multi-resolution
imaging, which aggregates the data under K different intervals
of time, thus creating K different, but analogous, time series. Let D
be the original time series in which T
defines the moment in which the observations of a given event
are done, and with are the features describing
the event.


### Capsule Networks: Deep Learning Computer Vision for Stock Forecasting​ [site](https://lucenaresearch.com/2019/07/15/capsule-networks-deep-learning-for-stock-forecasting/)
Using recurrent plot (RP) or Gramien Angular Difference Field to transform time series image to richer uniform image representation. 


### Classification of Time-Series Images Using Deep Convolutional Neural Networks [github](https://github.com/Shuchismita-Biswas/AML_Project_Fall19)
* Gramian Angular Field (GAF)
* Recurrence Plots (RP)
* Code [notebook](https://github.com/Shuchismita-Biswas/AML_Project_Fall19/blob/master/ECG200_notebook.ipynb) 

    This notebook illustrates how time series data can be embedded into images using two different methods : (a) Recurrence Plots (RP) and (b) Gramian Angular Field (GAF).


### Using python to work with time series data: list source [Source](https://github.com/MaxBenChrist/awesome_time_series_in_python)

### pyts: a Python package for time series classification [github](https://github.com/johannfaouzi/pyts)
pyts is a Python package for time series classification. It aims to make time series classification easily accessible by providing preprocessing and utility tools, and implementations of state-of-the-art algorithms. Most of these algorithms transform time series, thus pyts provides several tools to perform these transformations.
[process image](https://pyts.readthedocs.io/en/stable/modules/image.html)
* MarkovTransitionField
* GramianAngularField
* RecurrencePlot

* Markov transition fields (MTF) [site](https://towardsdatascience.com/advanced-visualization-techniques-for-time-series-analysis-14eeb17ec4b0) 

    from pyts.image import RecurrencePlot, GramianAngularField
    transformer = RecurrencePlot()
    GAF= GramianAngularField()
    x_new = transformer.transform(X)
    gaf_data = GAF.transform(X)



