# **All-Russian Championship - Digital Breakthrough**

### *Development of a model for predicting the loss of mail*

The whole delivery process — from reception at the department to delivery to the recipient — consists of a large number of operations. The shipment is packed, transported to a warehouse and transported between sorting points. If the delivery is coming from abroad, then there are additional operations at foreign and Russian customs.

Large logistics hubs help to speed up and reduce the cost of delivery. There, small cargoes are sorted and sent to neighboring regions or collected in new containers for shipment to other macro-regions. Thus, mail travels through the network of sorting centers, like blood through capillaries, and eventually gets to any point in our country.

Despite the high level of the security system, there is still a risk of loss or damage of shipments: there are a lot of movements and operations with parcels, in addition, the human factor can play in the process.

Accurate prediction of missing items and their localization will improve the reliability of the system — guarantee the delivery of shipments on time and reduce transportation costs. The task is to develop a model for predicting the loss of mail.

***For predicting mail loss***:
- Produced by: EDA (Exploratory Data Analysis) and Data Preprocessing
- Trained CatBoost models
- Trained logistic regression (Increasing the stacking gradient)

***Technology Stack***:
Python, Jupiter Notebook, CatBoost, Sklearn, Logistic Regression, Imblearn, Google Disk and Google Collab

The Stacking Gradient Boosting is a powerful method for machine learning, since Bagging is aimed at reducing the spread (variance) in the data.
CatBoost is easy to use and works especially well with categorical variables (half of the features in the samples are categorical).
On many popular datasets, the Cut Boost quality is better compared to LightGBM, XGBoost and H2O.

Together, the use of two models gives a sufficiently high result for predicting the loss of mail.
