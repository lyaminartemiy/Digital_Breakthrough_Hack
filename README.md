# **Всероссийский чемпионат - Цифровой прорыв**

### *Разработка модели предсказания потери почтовых отправлений*

Весь процесс доставки — от приема в отделении до вручения получателю — состоит из большого числа операций. Отправление запаковывают, перевозят на склад и транспортируют между сортировочными пунктами. Если доставка едет из-за границы, то дополнительно появляются операции на зарубежной и российской таможне.

Ускорить и удешевить доставку помогают крупные логистические хабы. Там мелкие грузы сортируются и отправляются в соседние регионы или собираются в новые контейнеры для отправки в другие макрорегионы. Таким образом, почтовые отправления путешествуют по сети сортировочных центров, как кровь по капиллярам, и в конце концов добираются в любые точки нашей страны.

Несмотря на высокий уровень системы безопасности, по-прежнему остается риск пропаж или порчи отправлений: перемещений и операций с посылками очень много, кроме того, в процессе может сыграть человеческий фактор.

Точное предсказание пропаж и их локализация позволит повысить надежность системы — гарантировать доставку отправлений в срок и снизить расходы на транспортировку. Задача — разработать модель предсказания потери почтовых отправлений:

***Скачать данные:***
 - Датасеты: https://drive.google.com/drive/folders/1nLkxFfX4o9XPrmsk1T7p-QB9dVxdQTU3?usp=share_link
 - Презентация: https://drive.google.com/drive/folders/11XDeCViKFqm-LN8-1kidjV3G4b_-JT70?usp=share_link
 - Модели CatBoost: https://drive.google.com/drive/folders/1gQ4V8yhOz70Q3MmXFLbsfs03bsZUpcYs?usp=share_link
 - Предсказанные значения: https://drive.google.com/drive/folders/12ESjgTpr-hyg6yDUdbIXj2hCAZgZeK_n?usp=share_link
 
***Для предсказаний потерь почтовых отправлений***:
 - Произведены: EDA (exploratory data analysis) и Data Preprocessing
 - Обучены модели CatBoost
 - Обучена логистическая регрессия (Stacking Gradient Boosting)
 
***Стек технологий***:
Python, Jupyter Notebook, CatBoost, Sklearn, LogisticRegression, Imblearn, Google Disk & Google Colab

Mетод Stacking Gradient Boosting – мощный метод для машинного обучения, поскольку Bagging направлен на уменьшение разброса (дисперсии) в данных.
CatBoost - прост в использовании и особенно хорошо работает с категориальными переменными (в выборках половина признаков категориальные).
Hа многих популярных наборах данных качество CatBoost является лучшим по сравнению с LightGBM, XGBoost и H2O.

В совокупности использование двух моделей дает достаточно высокий результат для предсказаний потерь почтовых отправлений.

# **All-Russian Championship - Digital Breakthrough**

### *Development of a model for predicting the loss of mail*

The whole delivery process — from reception at the department to delivery to the recipient — consists of a large number of operations. The shipment is packed, transported to a warehouse and transported between sorting points. If the delivery is coming from abroad, then there are additional operations at foreign and Russian customs.

Large logistics hubs help to speed up and reduce the cost of delivery. There, small cargoes are sorted and sent to neighboring regions or collected in new containers for shipment to other macro-regions. Thus, mail travels through the network of sorting centers, like blood through capillaries, and eventually gets to any point in our country.

Despite the high level of the security system, there is still a risk of loss or damage of shipments: there are a lot of movements and operations with parcels, in addition, the human factor can play in the process.

Accurate prediction of missing items and their localization will improve the reliability of the system — guarantee the delivery of shipments on time and reduce transportation costs. The task is to develop a model for predicting the loss of mail.

***Download data:***
- Datasets: https://drive.google.com/drive/folders/1nLkxFfX4o9XPrmsk1T7p-QB9dVxdQTU3?usp=share_link
- Presentation: https://drive.google.com/drive/folders/11XDeCViKFqm-LN8-1kidjV3G4b_-JT70?usp=share_link
- CatBoost Models: https://drive.google.com/drive/folders/1gQ4V8yhOz70Q3MmXFLbsfs03bsZUpcYs?usp=share_link
- Predicted values: https://drive.google.com/drive/folders/12ESjgTpr-hyg6yDUdbIXj2hCAZgZeK_n?usp=share_link

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
