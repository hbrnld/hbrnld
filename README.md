# Hello! 🔥

Welcome to my GitHub profile. 

I'm currently pursuing full-time double-degree studies towards an **M.Sc. in Financial Mathematics** at KTH and a **B.Sc. in Business and Economics** at SSE, on track to graduate in June 2025. Moreover, I'm also working part-time as a **Junior Quantitative Analyst** at Söderberg & Partners. 

Looking for all opportunities to meet new people, continue developing my skills and making an impact.

### Main areas of interest
While my interests are multifaceted, the main ones can be summarized as: 

* Mathematics
* Quantitative Finance
* Machine Learning & Deep Learning
* Stochastic Calculus
* Financial Derivatives

### Languages
Here's a collection of the programming languages and software I have experience in.

[<img align="left" alt="Python" width="26px" src="https://github.com/hbrnld/hbrnld/blob/main/images/pythonicon.png" />]()
[<img align="left" alt="PyTorch" width="26px" src="https://github.com/hbrnld/hbrnld/blob/main/images/pytorchicon.png" />]()
[<img align="left" alt="NumPy" width="40px" src="https://github.com/hbrnld/hbrnld/blob/main/images/numpyicon.png" />]()
[<img align="left" alt="Pandas" width="26px" src="https://github.com/hbrnld/hbrnld/blob/main/images/pandasicon.png" />]()
[<img align="left" alt="Matplotlib" width="26px" src="https://github.com/hbrnld/hbrnld/blob/main/images/matplotlibicon.png" />]()
[<img align="left" alt="SQL" width="40px" src="https://github.com/hbrnld/hbrnld/blob/main/images/azure-sql-icon.png" />]()
[<img align="left" alt="R" width="26px" src="https://github.com/hbrnld/hbrnld/blob/main/images/Ricon.png" />]()
[<img align="left" alt="MATLAB" width="26px" src="https://github.com/hbrnld/hbrnld/blob/main/images/matlabicon.png" />]()
[<img align="left" alt="VBA" width="26px" src="https://github.com/hbrnld/hbrnld/blob/main/images/vbaicon.png" />]()
[<img align="left" alt="VSCode" width="26px" src="https://github.com/hbrnld/hbrnld/blob/main/images/vscodeicon.png" />]()
[<img align="left" alt="Excel" width="26px" src="https://github.com/hbrnld/hbrnld/blob/main/images/excelicon.png" />]()
[<img align="left" alt="PowerPoint" width="26px" src="https://github.com/hbrnld/hbrnld/blob/main/images/powerpointicon.png" />]()
[<img align="left" alt="PowerBI" width="26px" src="https://github.com/hbrnld/hbrnld/blob/main/images/powerbicon.png" />]()
[<img align="left" alt="LaTeX" width="40px" src="https://github.com/hbrnld/hbrnld/blob/main/images/latexicon.png" />]()

<!--
This is a comment
-->

<br><br>

## 🚀 Optiver Trading at the Close: Deep Learning Models

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=hbrnld&repo=Optiver-Trading-at-the-Close&title_color=000000)](https://github.com/hbrnld/Optiver-Trading-at-the-Close)

In this project, we implement a number of deep learning models for the competition *Trading at the Close* by Optiver. We merely aim to explore the intersection of financial markets and machine learning as predicting financial markets is a challenging and intriguing task due to their complex and dynamic nature. While the Efficient Market Hypothesis assets that asset prices fully reflect all available information, there might still be a presence of market inefficiencies to exploit.

Initially, feature engineering was conducted to select the most significant features for the analysis. A total of five deep learning models were implemented using the PyTorch library in Python. These models include a Neural Network (NN), Recurrent Neural Network (RNN), Convolutional Neural Network (CNN), Long Short-Term Memory (LSTM), and a Transformer model. An ensemble model is developed to leverage the strengths of each individual model.

**Note**: This code was developed post-competition, and inspiration for feature engineering and model selection is taked from top leaderboard submissions, including user **[nimashahbazi](https://github.com/nimashahbazi/optiver-trading-close/tree/master)**. 

The following figure depicts feature importance from a selection of 159 total features, using CatBoost feature selection. 

<p align="center">
  <img src="/images/feature_importance.png" alt="Feature Importance" width="400"/>
</p>

<br><br>

## 📈 Predicting Equity Fund Returns: Impact of Momentum on Performance

In collaboration with Söderberg & Partners, the bachelor thesis in Applied Mathematics and Industrial Economics was developed together with my co-author Pontus Hovberger. In the thesis, the impact of the momentum factor on equity fund returns is evaluated over the period 2000-2023. A multifactor model is developed, using factor attribution to explain the impact on fund performance over time by factors such as risk, size, value-growth orientation and momentum. Conclusions are made that while momentum have previously been successful in predicting future returns, particularly for growth-oriented funds, recent market situations have lead to underperformance.

Here is an illustration of factor coefficients over time, illustrating the premium generated by risk exposure to each factor. Note the significant momentum crashes following the financial crisis in 2008 and during the Covid-19 pandemic. 

<p align="center">
  <img src="/images/MultifactorModel_fullPeriod.png" alt="Multifactor Coefficients" width="500"/>
</p>

<br>

For a more in-depth look at the results, have a look at the **[thesis](https://kth.diva-portal.org/smash/record.jsf?pid=diva2%3A1827858&dswid=-3917)**.

<br><br>

## 🕸️ Implementing a Neural Network from Scratch in Python

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=hbrnld&repo=NN-from-scratch&title_color=000000)](https://github.com/hbrnld/NN-from-scratch)

In this project, a feed-forward neural network is implemented from scratch using the Numpy library in Python. The architecture contains a forward pass, a backward pass with mini-batch efficient gradient computations using analytical solutions of the gradients. Furthermore, the network implements batch normalization and performs a search for the optimal regularization parameter lambda. In the bonus assignment, the Adam optimizer is implemented from scratch and some data augmentation is performed. CIFAR-10 is used as the underlying data set, containing batches of labelled images to be categorized. Even though a simple neural network is far from the optimal architecture for image classification, the implementation demonstrates understanding of the underlying aspects of a neural network. 

<p align="center">
  <img src="/images/nn.png" alt="Network Architecture" width="400"/>
</p>

<br>
