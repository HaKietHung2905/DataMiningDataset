# Mobile Price Data

## Description
The 'Mobile Price Data' dataset is designed for training classification models to predict mobile phone prices. The dataset contains various details about mobile phone hardware, specifications, and prices, which are crucial for understanding the factors that influence mobile phone pricing. The target variable, `price range`, categorizes the prices into four distinct classes: low cost, medium cost, high cost, and very high cost.

## Dataset Columns

| Column        | Meaning                                                                 |
|:-------------:|:-----------------------------------------------------------------------:|
| `battery_power` | Total energy a battery can store in one time measured in mAh          |
| `blue`         | Indicates if the mobile phone has Bluetooth (1: Yes, 0: No)            |
| `clock_speed`  | Speed at which the microprocessor executes instructions (GHz)          |
| `dual_sim`     | Indicates if the mobile phone has dual SIM support (1: Yes, 0: No)     |
| `fc`           | Front Camera resolution in megapixels                                  |
| `four_g`       | Indicates if the mobile phone has 4G support (1: Yes, 0: No)           |
| `int_memory`   | Internal memory in gigabytes                                           |
| `m_dep`        | Mobile depth in centimeters                                            |
| `mobile_wt`    | Weight of the mobile phone in grams                                    |
| `n_cores`      | Number of cores in the processor                                       |
| `pc`           | Primary Camera resolution in megapixels                                |
| `px_height`    | Pixel resolution height                                                |
| `px_width`     | Pixel resolution width                                                 |
| `ram`          | Random Access Memory in megabytes                                      |
| `sc_h`         | Screen height of the mobile phone in centimeters                       |
| `sc_w`         | Screen width of the mobile phone in centimeters                        |
| `talk_time`    | Maximum time that a single battery charge will last during talk time   |
| `three_g`      | Indicates if the mobile phone has 3G support (1: Yes, 0: No)           |
| `touch_screen` | Indicates if the mobile phone has a touch screen (1: Yes, 0: No)       |
| `wifi`         | Indicates if the mobile phone has WiFi support (1: Yes, 0: No)         |
| `price_range`  | Target variable with values: 0 (low cost), 1 (medium cost), 2 (high cost), and 3 (very high cost) |

## Usage
This dataset is ideal for building and evaluating classification models that predict the price range of mobile phones based on their specifications. It can be used for various machine learning tasks, including:

- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Training and Evaluation
- Hyperparameter Tuning

## Goals
- To understand the relationship between mobile phone specifications and their prices.
- To train classification models to accurately predict the price range of mobile phones.
- To evaluate the performance of different models and understand their strengths and weaknesses.

## Example Analyses
- **Feature Importance**: Identify which features (e.g., RAM, battery power) have the most significant impact on the price range.
- **Model Comparison**: Compare different classification algorithms (e.g., decision trees, random forests, logistic regression) to determine which model performs best in predicting mobile phone prices.
- **Visualization**: Use visualizations like box plots, scatter plots, and heatmaps to explore the data and identify patterns or trends.
