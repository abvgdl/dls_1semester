# Machine Learning Homeworks — MIPT DLS 1st Semester (Classic ML & Computer Vision)

Репозиторий содержит домашние задания курса **Deep Learning School (МФТИ)** за 1 семестр: задачи по **классическому машинному обучению** и **нейронным сетям** (включая computer vision).

## Tech Stack

`PyTorch`, `torchvision`, `NumPy`, `Pandas`, `Scikit-learn`, `Matplotlib`, `Seaborn`, `CatBoost`, `OpenCV`, `SciPy`

## Содержание репозитория

| Файл/Папка | Описание задачи | Технологии и методы |
|---|---|---|
| `hw_2_linear_models.ipynb` | Линейные модели и оптимизация: регрессия/классификация, работа с признаками, валидация | Gradient Descent, Linear Regression, Lasso, Ridge, StandardScaler, Cross-Validation |
| `hw_GOTpredictions.ipynb` | Классификация табличных данных (Kaggle-задача по персонажам Game of Thrones) | IterativeImputer, OneHotEncoder, StandardScaler, Logistic Regression, SVC, KNN, Random Forest, Gradient Boosting, AdaBoost, VotingClassifier |
| `hw3_gradbost.ipynb` | Полный ML-пайплайн для соревнования: подготовка данных, обучение и отбор модели | CatBoostClassifier, Logistic Regression, ColumnTransformer, Pipeline, GridSearchCV, ROC-AUC |
| `hw4_conv_nets.ipynb` | Построение и обучение нейросетей для задач классификации, переход от MLP к CNN | PyTorch, MLP, LeNet, SGD, Adam, Batch training |
| `hw5_cnn_and_fine-tuning.ipynb` | Классификация изображений и transfer learning с дообучением предобученной сети | Custom CNN, ResNet (fine-tuning), Adam/AdamW, Data Augmentation, F1-score |
| `README.md` | Краткое описание репозитория и структуры домашних заданий | Markdown |

## Итоговые метрики экспериментов

| Ноутбук | Эксперимент | Итоговая метрика |
|---|---|---|
| `hw_2_linear_models.ipynb` | Линейные модели и оптимизация | — |
| `hw_GOTpredictions.ipynb` | Лучшая модель на тесте | Accuracy = **0.8301** (AdaBoost) |
| `hw_GOTpredictions.ipynb` | CV для Random Forest (5-fold) | Accuracy = **0.8297 ± 0.0131** |
| `hw3_gradbost.ipynb` | Logistic Regression (best CV / test) | Accuracy = **0.849 / 0.827** |
| `hw3_gradbost.ipynb` | CatBoostClassifier (train best) | AUC = **0.8951** |
| `hw4_conv_nets.ipynb` | LeNet на MNIST (test) | Accuracy = **0.9872** (~0.99) |
| `hw5_cnn_and_fine-tuning.ipynb` | Simple CNN (best val) | F1 = **0.8294**, Accuracy = **0.8294** |
| `hw5_cnn_and_fine-tuning.ipynb` | ResNet50 fine-tuning (best val) | F1 = **0.9727**, Accuracy = **0.9727** |
