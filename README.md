# :comet: NebulaNet:
> - NebulaNet is a cutting-edge data science hackathon organized by the physics department of IIT BHU for Jigyasa. Participants were provided with a Dataset containing astrophysical data. They had to train a Machine Learning Model which optimizes the given dataset, focusing on how ml techniques can be applied to physics research.

## :bar_chart: Dataset:
| Column ID |   Column Name  | Data type | Values type |          Description         |
|:---------:|:--------------:|:---------:|:-----------:|:----------------------------:|
|     0     |       Temperature (K)      |   int64   |  Continous  |         Temperature of stars        |
|     1     |    Luminosity(L/Lo)  |  float64  |   Continous  |      Luminosity of stars     |
|     2     |     Radius(R/Ro)|   float64   |  Continous  |         Radius of stars         |
|     3     |    Absolute magnitude(Mv)   |   float64  |   continous  |  Magnitude of stars  |
|     4     |  Star type |   object   |  Discrete  | Types of stars |
|     5     | Star color |   object  |   Discrete  |   Colours of stars   |
|     6     |   Spectral Class|   object  |   Discrete  |     Spectral class of stars     |

## :chart_with_upwards_trend: Data Analysis:
### :books: Dataset:

> - It contains categorical and numerical variables.
> - It is skewed and contains outliers.
> - It is not normally distributed.

### :handshake: Relationships:
> - Relationships between various variables has been analysed and significant points have been highlighted.

## :memo: Motivation:
> - While working on the project, I discovered various physics terms & formulaes which have impact on star type.

## :scroll: Conclusion:
> - Random Forest Classifier , Decision Tree Classifier & Xgboost get 1.00 as accuracy score. We select Random Forest Classifier.The reason for the same is that using bagging algorithms is much better than using boosting algorithms for a small dataset.

# I secured the first position in this hackathon.
