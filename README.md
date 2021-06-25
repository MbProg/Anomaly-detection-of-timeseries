# Anomaly-detection-of-timeseries
Anomaly detection of timeseries: A comparison of statistical vs classical machine learning vs deep learning approaches

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project
Due to many requests to share the code of my research, I have decided to upload the programming code and part of the results to help other students and researchers in implementing anamoly detection methods of time series data. The code in this repository helped me to write my master thesis ["Anomaly detection of timeseries: A comparison of statistical vs classical machine learning vs deep learning approaches"](https://www.researchgate.net/publication/342898903_Master_Thesis?_sg=KGr1GnYwxaPcc7rWkL4CrSpYe6oQfcM-Ke6KYArUMnCgoLDPHoJowOUI12rHI8Vc3Yo1FttEAOlEHfsjdC_VS_xk5PaA2tBfOpKIZbeu.qlBSptPjZ-l6EsE7bggcru4jnN6_2z95C-YRIeH0D-ZR6PRL_ZAJmnGF0A4GPHRz95wGxQ3av5tz_j3GqEEiYA) and to pushlish the paper ["Anomaly Detection in Univariate Time-series: A Survey on the State-of-the-Art"](https://www.researchgate.net/publication/340374826_Anomaly_Detection_in_Univariate_Time-series_A_Survey_on_the_State-of-the-Art).  
By reading the [thesis](https://www.researchgate.net/publication/342898903_Master_Thesis?_sg=KGr1GnYwxaPcc7rWkL4CrSpYe6oQfcM-Ke6KYArUMnCgoLDPHoJowOUI12rHI8Vc3Yo1FttEAOlEHfsjdC_VS_xk5PaA2tBfOpKIZbeu.qlBSptPjZ-l6EsE7bggcru4jnN6_2z95C-YRIeH0D-ZR6PRL_ZAJmnGF0A4GPHRz95wGxQ3av5tz_j3GqEEiYA), you will get a thorough understanding about the research and the implementation. Thus, please refer to the thesis for more information.  
The code in this repository has the following strcuture

```bash
├── Mutlivariate (multivariate time series algorithms)
│   ├── Euclidean vs. Mahalanobis (evaluate different distance measures for multivariate time series)
│   ├── ML (machine learning approaches for univariate time series)
│   │   ├── NASA (Evaluation of the ML algo on the NASA Shuttle dataset - refer to 4.2 in the thesis)
│   │   ├── SD (Evaluation of the ML algo on the synthetic data)
│   │   └── SMTP (Evaluation of the ML algo on the SMTP Dataset)
│   ├── Neural Networks (neural network approaches for univariate time series)
│   │   ├── NASA (Evaluation of the neural network approaches on the NASA Shuttle dataset - refer to 4.2 in the thesis)
│   │   ├── SD (Evaluation of the neural network approaches on the synthetic data)
│   │   └── SMTP (Evaluation of the neural network approaches on the SMTP Dataset)
│   └── Statistical   (statistical approaches for univariate time series)
│       ├── NASA (Evaluation of the statistical approaches on the NASA Shuttle dataset - refer to 4.2 in the thesis)
│       ├── SD (Evaluation of the statistical approaches on the synthetic data)
│       └── SMTP (Evaluation of the statistical approaches on the SMTP Dataset)
└── Univariate   (univariate time series algorithms)
    ├── ML (machine learning approaches for univariate time series)
    │   ├── NYCT (Evaluation of the ML algo on the NYCT Dataset)
    │   └── UD1_UD4 (Evaluation of the ML algo on the UD1-UD4 datasets - refer to 4.2 in the thesis)
    ├── Neural Networks (neural network approaches for univariate time series)
    │   ├── NYCT (Evaluation of the neural network approaches on the NYCT Dataset)
    │   └── UD1_UD4 (Evaluation of the neural network approaches on the UD1-UD4 datasets - refer to 4.2 in the thesis)
    └── Statistical   (statistical approaches for univariate time series)
        ├── NYCT (Evaluation of the statistical approaches on the NYCT Dataset)
        └── UD1_UD4 (Evaluation of the statistical approache on the UD1-UD4 datasets - refer to 4.2 in the thesis)

```
### Built With

The entire algorithms have been implemented in python 3.\* The major libraries which have been used are the following:
* Statsmodels
* Scikit-learn (Sklearn)
* tensorflow
* [keras](https://github.com/fchollet/keras)


## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Project Link: [https://github.com/MbProg/Anomaly-detection-of-timeseries](https://github.com/MbProg/Anomaly-detection-of-timeseries)
